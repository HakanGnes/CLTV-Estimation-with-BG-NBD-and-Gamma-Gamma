# OnlineRetail-Cltv
BG-NBD ve Gamma-Gamma ile CLTV Tahmini

# İş Problemi
İngiltere merkezli perakende şirketi müşterilerini segmentlere ayırıp bu segmentlere göre pazarlama stratejileri belirlemek istemektedir. Ortak davranışlar sergileyen müşteri segmentleri özelinde pazarlama çalışmaları yapmanın gelir artışı sağlayacağını düşünmektedir. Segmentlere ayırmak için RFM analizi kullanılacaktır.

# Veri Seti Hikayesi
Online Retail II isimli veri seti İngiltere merkezli bir perakende şirketinin 01/12/2009 - 09/12/2011 tarihleri arasındaki online satış işlemlerini içeriyor. Şirketin ürün kataloğunda hediyelik eşyalar yer almaktadır ve çoğu müşterisinin toptancı olduğu bilgisi mevcuttur.

# Degiskenler

  ## InvoiceNo = Fatura Numarası ( Eğer bu kod C ile başlıyorsa işlemin iptal edildiğini ifade eder )
  ## StockCode = Ürün kodu ( Her bir ürün için eşsiz )
  ## Description = Ürün ismi
  ## Quantity = Ürün adedi  ( Faturalardaki ürünlerden kaçar tane satıldığı)
  ## InvoiceDate = Fatura tarihi
  ## UnitPrice = Fatura fiyatı ( Sterlin )
  ## CustomerID = Eşsiz müşteri numarası
  ## Country = Ülke ismi
