Dekoratörler diğer fonksiyonların işlevselliğini(görevlerini) değiştiren, kodları kısaltan ve daha okunabilir hale getiren fonksiyonlardır. Önce kendi içindeki işlevleri yapar ve sonrasında kendinden sorna gelen fonksiyonu çağırarak onu execute eder. Kullanım şekilleri aşağıdadır.

* @pytest.fixture() : Testin çalışması için gereken koşulları önceden hazırlar.Testler arasında ortak bir durum veya kaynak paylaşmak için kullanılır.

* @pytest.mark.usefixtures() : Testlerde belirli bir fixture'u otomatik olarak ekler.

* @pytest.mark.parametrize() : Bir test fonksiyonunun farklı parametreler ile birden fazla çalışmasını sağlar.

* @pytest.mark.skip() : Belirlenen testlerin atlanmasını sağlar.

* @pytest.mark.xfail() : Testin başarısız olacağını düşünüyorsanız veya biliyorsanız bunu belirtmek ve sonucu etkilememesini sağlamak için kullanılır.

* @pytest.mark.timeout() : Testin belirtilen sürede tamamlanmasını sağlar.

* @pytest.mark.order() : Testleri sıralamak için kullanılır.

* @pytest.mark.slow() : Belirtilen testin yavaş çalıştığını ve geri kalan testlere etki edebileceğini belirtir.

* @pytest.mark.dependency() : Testler arasındaki bağlılığı belirlemek için kullanılır.
