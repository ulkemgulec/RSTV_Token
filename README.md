# RSTV_Token
RSTT token bir rüşvet tokenidir. Rüşveti artık gizli kapaklı işler arkasından yapmaya gerek kalmaksızın apaçık uygulanabilmektedir. Bu da aslında bir nevi rüşvet rekabet ortamı doğurmaktadır. Ekonomiye katkısı vardır(?). Total supply ı tam olarak 0.01 tane olduğu için çok değerlidir.

# ERC20 token nedir?
ETH aksine ERC20 tokenları hesaplar tarafından tutulmaz. Onun yerine bir kontratın içinde var olurlar. Bu kontrata da kendi kendine yeten bir veri taban şeklinde tanımlayabiliriz. Kullanıcuların bakiyeleri Ethereum adreslerine bağlayan bir listede tutulur. Bu contratlarda tokenlar için kurallar belirlenir.

# RSTV_Token Oluştururken Kullandığım Fonksiyonlar

## 1) totalSupply ##
Bu fonksiyonun özelliği kullanıcı çağırdığında contratta bulunan tokenların toplam arzını gösterir.

## 2) balanceOf ##
Bu fonksiyon içine bir adres parametresi alır ve adresini yazdığınız kişinin kalan bakiyesini gösterir.

## 3) transfer ##
Transfer, tokenları bir kullanıcıdan diğerine uygun bir şekilde transfer eder. Burada, gönderim yapmak istediğiniz adresi ve gönderilecek tutarı belirtmeniz gerekir. Event Transfer adı altında bir eventi  de çağırmaktadır.

## 4) transferFrom ##
Bu da transfer fonksionu gibidir ama başka bir kontratını sizin adınaza çalışmasını token transfer etmesini sağlayabilirsiniz.

## 5) approve ##
Approve (onay), programlanabilirlik açısından bir diğer kullanışlı fonksiyondur. Bu fonksiyonla, bir akıllı kontratın bakiyenizden çekebileceği token sayısını sınırlayabilirsiniz. 

## 6) allowance ##
Allowance, (kalan bakiye) approve ile birlikte kullanılabilir. Bir kontrata tokenlarınızı yönetmesi için izin verdiğinizde, kontratın çekebileceği ne kadar tokenın kaldığını kontrol edebilirsiniz.

