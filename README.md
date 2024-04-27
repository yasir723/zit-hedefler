# Zıt Hedefler (Opposing Goals)
Zaman zaman, faydalı düşüncelerimiz olabilir ancak aynı zamanda zararlı olma potansiyeline sahip olabilirler. Mike Andrews'ın `How To Break Web Software` adlı kitabında bu durum çok açık bir şekilde ele alınmıştır.

## Ortaya Konulan Temel Noktalar
- Güvenilirlik (Reliability): Sorunları çözmek veya hataları düzeltmek için yazılan kod satırları zaman zaman fazla karmaşık hale gelebilir. Bu durumda, bir testçinin sistemin tüm kodları test etmeye zamanı olmayabilir. Bu durum, hacker'lar için bir fırsat olabilir. Sistemlere veri göndererek, `sistemlerden hata mesajları alarak, hacker'lar sistemdeki hataları keşfedebilirler`. Bu durum, hacker'ların sistem hakkında daha fazla bilgi edinmelerine ve potansiyel olarak ciddi zararlara yol açmalarına neden olabilir.
- Performans: Genellikle bir web uygulaması veya başka herhangi bir uygulama geliştirdiğimizde onun çok hızlı olmasına çablıyoruz, Bir web sitesini hızlandıran en temel unsur, kodların sunucu tarafında çalışacak şekilde yazılması değil, istemci tarafında yazılmasıdır. `Bu kullanıcıya ne kadar bir avantaj sağlarsa, bir hacker'a o kadar avantaj sağlayabilir`. Çünkü JavaScript gibi istemci tarafı kodları, hacker'lar tarafından görülebilir. Kodlarımızı istemci tarafında yazdığımızda, hacker'ların sistemimiz hakkında bilgi edinmelerine yardımcı oluyoruz. Bu yüzden istemci tarafında yazacağımız her kodu bir hacker tarafından nasıl değerlendirebileceğini iyi hesaplamamız lazım ve ona göre önlemler almamız gerek.
- Kullanılabilirlik (Usability): Bir web uygulaması tasarlarken, kullanımı mümkün olduğunca kolay hale getirmeye çalışırız. Ancak, basit bir sistem kurmak, genellikle daha fazla detay gerektirir. `Daha fazla detay, hacker'ların daha fazla fırsata sahip olmasını sağlayabilir`. Bu nedenle, hangi bilgilerin kullanıcılara, hangi bilgilerin ise hacker'lara görüneceğini iyi hesaplamamız gerekmektedir.
