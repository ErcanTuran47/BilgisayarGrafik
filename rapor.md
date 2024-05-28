1306220105-Ercan Turan- Bilgisayar Grafikleri- Ebu Yusuf Güven 

# Bilgisayar Grafikler, Ders - WebGL Dönem  Ödevi Kod Dosyalarının Dökümantasyon Raporu 

## Giriş 

Bu proje, WebGL kullanarak "Ercan Turan" metnini çizen basit bir 3D grafik 
uygulamasıdır. Proje, HTML, JavaScript ve WebGL ile oluşturulmuştur ve her bir harf 
farklı renklere sahip olacak şekilde çizilmiştir. 
## Kod Yapısı ve Açıklamalar 
Kod yapısında tek HTML projesi olarak yazdım GitHub’a ama yaptığım tüm projeleri 
yükleyeceğim js kodunu yarı koymadım projenin son hali son.html’dir. Aşağıda Kod 
yapılarını ekran fotosu olarak ekledim şimdi html yapısını da ekleyeceğim buraya.  
Bu HTML yapısı, projenin temelini oluşturur. Bir canvas elementi ve harici bir 
JavaScript dosyası (script.js) içerir. 


## JavaScript (script.js) 

## Açıklamalar Açıklamalar 
Ana Fonksiyon (main): Canvas ve WebGL bağlamını başlatır, shader programını 
oluşturur ve sahneyi çizer. 
Shader Programı Başlatma (initShaderProgram): Vertex ve fragment shader'larını 
oluşturur ve bağlar. 
Shader Yükleme (loadShader): Shader kaynak kodunu yükler ve derler. 
Tamponları Başlatma (initBuffers): Pozisyon ve renk verilerini tanımlar ve WebGL 
tamponlarına yükler. 
Sahneyi Çizme (drawScene): Sahneyi temizler, dönüşüm matrislerini hesaplar ve 
çizim işlemini gerçekleştirir. 
## Sonuç 
Bu proje, WebGL kullanarak basit bir metin çizimi örneğidir. Daha karmaşık şekiller 
ve animasyonlar için temel bir yapı sağlar. 

## Kaynakça
MDN Web Docs - Using WebGL: WebGL bağlamı oluşturma, shader programlarını başlatma ve temel WebGL işlemleri hakkında bilgi almak için bu kılavuzdan faydalandım.

URL: MDN Web Docs - Using WebGL

MDN Web Docs - WebGLRenderingContext: WebGLRenderingContext nesnesi ve metodları hakkında ayrıntılı bilgi edinmek için kullandım.

URL: MDN Web Docs - WebGLRenderingContext

glMatrix Documentation: glMatrix kütüphanesi kullanılarak matris işlemleri nasıl yapılır konusunda bilgi sağladı.

URL: glMatrix Documentation
WebGL Fundamentals: Shader'lar ve temel WebGL programlaması hakkında kapsamlı bilgi sunan bir kaynak.

URL: WebGL Fundamentals
Interactive Computer Graphics: A Top-Down Approach with WebGL: Özellikle shader'lar ve 3D grafikleri oluşturma konularında rehberlik eden bu kitap temel bir referans olarak kullanıldı.

Yazar: Edward Angel, Dave Shreiner