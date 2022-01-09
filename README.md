<h2>🔎 Konu: Lojistik Regresyon</h2><hr>
<h3>📜 Açıklama: Lojistik regresyon ile tahmin</h3><hr>
<h3>🐱 Katkı Sağlayanlar: </h3>
<ul>
  <li><a href="https://github.com/eyllcyldrm" title="Go to Github Profile Of Eylul Ece Yildirim"> Eylül Ece Yıldırım </a></li>
  <li><a href="https://github.com/eyllcyldrm" title="Go to Github Profile Of Feyza Sahin"> Feyza Şahin </a></li>
  <li><a href="https://github.com/semihgencturk" title="Go to Github Profile Of Semih Gencturk"> Semih Gençtürk </a></li>
</ul>
<hr>
<hr>
<h4><i> Lojistik Regresyon Nedir? </i></h4>
<p> lineer reg ten farklı olarak y değişkeni kategoriktir. Kategorik bir yanıt değişkeninin tahmin edilmesine sınıflandırma denmiş olur. Amacımız henüz gözlenmemiş bir x değşkeni için sınıfını yani y değerini tahmin etmektir. Genellikle x in her bir kategoriye ait olma olasılıkları ile ilgilenilir. Sınıf tahminlerinin iyiliği yanlış sınıflandırma oranı ya da doğru sınıflandırma oranı ile ölçülür. </p>
<hr>
<h4><i> Neden loj reg sınıflandırıcısı? </i></h4>
<p> Yanıt değişkeni 0 veya 1 olduğu zaman da daha çok yanıt olduğunda da kullanılabilir. Lineer de yanıt değişkeni 0 ya da 1 olabilir. Peki hangi durumlarda lineer reg kullanmayıp lojistik reg kullanalım? Tahmin edilecek olan değerler yine 0 – 1 değerlerinden oluşsun ancak bu değerler karşımıza 1 den büyük ya da 0 den küçük şeklinde çıkarsa (yuvarlama da yapılabilir ancak her zaman sağlıklı bir işlem değildir.) lineer reg yerine lojistik reg kullanılır çünkü lojistik reg in fonksiyonu y değerlerinin 0 ile 1 arasında olmasını garanti altına alır. </p>
<hr>
<h4><i> Lojistik dağılım hakkında: </i></h4>
<ul> 
  <li> ilgilendiğimiz sınıfın = 1 olması olasılığı ilgili hesaplamalar yapılarak olasılık değerleri elde edilir. </li>
  <li> logistik dağılım bir sürekli olasılık dağılımdır. </li>
  <li> Şekil bakımından çan şeklinde olan [normal dağılıma](https://tr.wikipedia.org/wiki/Normal_da%C4%9F%C4%B1l%C4%B1m) çok benzer; fakat kuyrukları daha ağır olduğu için daha basık bir şekil gösterir. </li> 
</ul>
