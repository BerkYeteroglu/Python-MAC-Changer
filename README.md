# Python-Mac-Changer

Bu Python kodu, kullanıcının belirtmiş olduğu ağ arayüzünde ve belirtmiş olduğu yeni MAC adresi ile arayüzün MAC adresini değiştirir. 
Kod, kullanıcının argümanlarını doğru şekilde kullanıp kullanmadığını kontrol etmek için optparse kütüphanesini kullanır. 
Bu kütüphane, kullanıcıya doğru kullanımı nasıl yapabileceği hakkında bilgi verir. 
Kod, ifconfig komutunu çalıştırmak için subprocess kütüphanesini kullanır. 
Subprocess kütüphanesi, komut satırı komutlarını kullanabilmemizi sağlar. 
Kod, MAC adresinin değiştirildiğini doğrulamak için ifconfig komutunun çıktısını alır ve re kütüphanesi ile aranır. 
Eğer yeni MAC adresi doğrulandıysa, kod "success" yazdırır, aksi halde "Error" yazdırır.
Bu kod sadece linux işletim sisteminde çalışır.
