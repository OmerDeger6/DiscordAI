# Discord Bot - Bilgisayarlı Görü ile Bitki ve Hayvan Tanıma

Bu proje, bilgisayarlı görü kullanarak bitki ve hayvanları tanıyan bir Discord botunu içermektedir. Model, Google Teachable Machine kullanılarak eğitilmiş ve Discord botu ile entegre edilmiştir.

## Özellikler
- Görselleri analiz ederek bitki ve hayvanları tanıyabilir.
- Tanıdığı bitki veya hayvan hakkında bilgi verebilir.
- Tahmin doğruluk yüzdesini gösterir.
- Gelecekte Google API ile canlı bitki tanıma özelliği eklenmesi planlanmaktadır.

## Gereksinimler
Bu projeyi çalıştırmak için aşağıdaki bağımlılıkları yüklemeniz gerekmektedir:
```sh
pip install discord.py tensorflow numpy opencv-python requests
```

## Kurulum ve Kullanım
1. **Depoyu Klonlayın:**
```sh
git clone https://github.com/kullaniciadi/proje-adi.git
cd proje-adi
```

2. **Discord Bot Token'ınızı Ayarlayın:**
   - `config.json` dosyasını oluşturun ve içine aşağıdaki gibi bilgileri ekleyin:
   ```json
   {
       "TOKEN": "DISCORD_BOT_TOKEN",
       "MODEL_PATH": "model/model.tflite"
   }
   ```

3. **Botu Çalıştırın:**
```sh
python bot.py
```

## Kullanım
Bot çalıştırıldıktan sonra Discord sunucunuzda belirlenen komutları kullanabilirsiniz:
- `!tanı [resim]` - Yüklenen görseldeki bitki veya hayvanı tanır ve sonuçları gösterir.
- `!bilgi [tür_adı]` - Tanınan tür hakkında detaylı bilgi verir.

## Katkıda Bulunma
Katkıda bulunmak isterseniz, lütfen bir **fork** oluşturup değişikliklerinizi **pull request** olarak gönderin.

## Lisans
Bu proje MIT lisansı altındadır. Daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.

---
Eğer bu projeyi beğendiyseniz, yıldız vermeyi unutmayın ⭐


