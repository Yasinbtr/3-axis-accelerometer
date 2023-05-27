# 3-axis-accelerometer
MSP430G2553 &amp; MMA8452-GY45
MSP430G2553 işlemcisi ve MMA8452-GY45 sensörü kullanılmıştır.
Bu sensörün seçilme nedeni benzer işlevli sensörlere göre daha az güç tüketmesi ve daha hassas ölçümler yapabilmesidir.
Ancak, unutmamak gerekir ki MMA8452-GY45 sensörü yalnızca I2C protokolüyle çalışabilmektedir.
Dolayısıyla I2C protokolüne uygun olmayan işlemcilerle kullanılamaz, protokol donüşümü yapan bir entegreye ihtiyaç vardır(mcp_2221).
Bu projede 6 adet led kullanılarak X,Y ve Z eksenlerindeki pozitif veya negatif yöndeki değişimleri göstermektir. 
Bu 6 adet led işlemcinin 6 adet I/O pinine bağlanmıştır bu sayede sensörden aldığı bilgiye göre hangi led(ler)in yanacağına karar verecektir.
NOT: Sensör G kuvvetini de ölçebilmektadir yani bu karta LCD veya Display bağlanarak G kuvvetini göstermesini sağlamak projenin işlevselliğini artırıp amacına daha uyhun hale getirecektir.
Muhammed Yasin BEKTAŞ / Kocaeli Üniversitesi- Elektronik ve Haberleşme Mühendisliği / bektasyasin707@gmail.com / (May,2023)

