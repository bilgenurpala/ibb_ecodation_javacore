# IBB Ecodation Java Core

## Git
```sh

git init
git add .
git commit -m "commit_message"
git push -u origin master
git clone "github links"
```
---

## 1. Hafta Öğrendiklerim

### Java Nedir?
```sh

Java, platform bağımsız, nesne yönelimli (OOP) ve genel amaçlı bir programlama dilidir. 
"Bir kere yaz, her yerde çalıştır" (Write Once, Run Anywhere - WORA) prensibiyle çalışır. 
Yani, yazdığın kodu farklı işletim sistemlerinde değiştirmeden çalıştırabilirsin.

```
---

### Java'nın Kullanıldığı Alanlar
```sh

1️⃣ Masaüstü Uygulamaları

Banka sistemleri, kurumsal yazılımlar, muhasebe programları gibi büyük ölçekli uygulamalar Java ile yazılabilir.
2️⃣ Web Geliştirme

Java, Spring, Hibernate gibi framework'ler sayesinde büyük ölçekli web siteleri ve API'ler geliştirmek için kullanılır.
Örneğin, büyük e-ticaret siteleri, finans platformları Java ile geliştirilir.
3️⃣ Mobil Uygulamalar (Android)

Android uygulamaları Java ile yazılabilir. Kotlin popüler olsa da Java hâlâ güçlü bir seçenek.
4️⃣ Oyun Geliştirme

Minecraft gibi popüler oyunlar Java ile yazılmıştır. LibGDX, jMonkeyEngine gibi oyun motorları Java destekler.
5️⃣ Veritabanı Yönetimi

Java, JDBC (Java Database Connectivity) ile MySQL, PostgreSQL gibi veritabanlarıyla çalışabilir.
6️⃣ Büyük Veri ve Yapay Zekâ

Java, Apache Hadoop, Spark gibi büyük veri işleme sistemlerinde kullanılır.
AI ve makine öğrenmesi uygulamalarında Java tercih edilen dillerden biridir.
7️⃣ Gömülü Sistemler ve IoT

Java, akıllı cihazlar, gömülü sistemler, ATM’ler gibi yerlerde de kullanılır.
8️⃣ Finans ve Bankacılık Uygulamaları

Java’nın güvenilir ve hata toleranslı olması nedeniyle bankalar ve borsa sistemlerinde yaygın olarak kullanılır.

```
---

### JDK (Java Development Kit) Nedir?
```sh

JDK, Java uygulamaları geliştirmek için gerekli olan araçları içeren bir yazılım paketidir. 
Java kodu yazmak, derlemek (compile etmek) ve çalıştırmak için JDK'ya ihtiyacın vardır.

✔️ JRE (Java Runtime Environment): Java programlarını çalıştırmak için gerekli olan ortam. 
(JVM + Kütüphaneler içerir.)
✔️ JVM (Java Virtual Machine): Java kodunu makine diline çevirip çalıştıran sanal makine.
✔️ Java Compiler (javac): Java kaynak kodunu (.java) derleyerek çalıştırılabilir bytecode (.class) dosyalarına çeviren araç.
✔️ Java Debugger (jdb): Hataları bulmak ve kodu debug etmek için kullanılır.
✔️ Java Kütüphaneleri: Java'nın temel fonksiyonlarını sağlayan sınıflar 
(String, Math, IO, Collections, vs.).
```
---

### JRE (Java Runtime Environment) Nedir?
```sh

JRE (Java Runtime Environment) Nedir?
JRE (Java Çalışma Ortamı), Java programlarını çalıştırmak için gerekli olan yazılımdır.
Java kodu yazmak veya derlemek için JDK gerekirken, sadece Java programlarını çalıştırmak için JRE yeterlidir.

JRE’nin İçindekiler:
✅ JVM (Java Virtual Machine): Java kodlarını çalıştıran sanal makine.
✅ Java Kütüphaneleri (Core Libraries): Java programlarının çalışması için gereken temel sınıflar.
✅ Destekleyici Dosyalar: Java uygulamalarının çalışmasını sağlayan sistem dosyaları.
```
---

### JVM (Java Virtual Machine) Nedir?
```sh

JRE (Java Çalışma Ortamı), Java programlarını çalıştırmak için gerekli olan yazılımdır.
Java kodu yazmak veya derlemek için JDK gerekirken, sadece Java programlarını çalıştırmak için JRE yeterlidir.

JRE’nin İçindekiler:
✅ JVM (Java Virtual Machine): Java kodlarını çalıştıran sanal makine.
✅ Java Kütüphaneleri (Core Libraries): Java programlarının çalışması için gereken temel sınıflar.
✅ Destekleyici Dosyalar: Java uygulamalarının çalışmasını sağlayan sistem dosyaları.

JVM'in Görevleri:
1️⃣ Java Bytecode'u Çalıştırır:

Java kodları önce derlenir ve bytecode (makine bağımsız bir ara dil) haline gelir.
JVM, bu bytecode’u işletim sisteminin anlayacağı makine diline çevirip çalıştırır.
2️⃣ Platform Bağımsızlık Sağlar:

"Bir kere yaz, her yerde çalıştır" (Write Once, Run Anywhere - WORA) ilkesini mümkün kılar.
Windows, Mac, Linux gibi farklı sistemlerde çalıştırılabilir.
3️⃣ Bellek Yönetimi ve Çöp Toplama (Garbage Collection):

JVM, bellek yönetimini otomatik yapar ve kullanılmayan nesneleri temizler.
4️⃣ Güvenlik Sağlar:

Java kodlarının tehlikeli işlemler yapmasını önlemek için bir güvenlik mekanizması içerir.
```
---
### Maven Nedir?
```sh
📌 Apache Maven, Java projelerini yönetmek, derlemek, bağımlılıkları yüklemek ve otomatikleştirmek için kullanılan bir build (derleme) aracıdır.

1️⃣ Maven’in Temel İşlevleri
✅ Bağımlılık Yönetimi (Dependency Management)

Projede kullanılan kütüphaneleri (JAR dosyaları) otomatik indirir ve günceller.
Örneğin, Spring, Hibernate gibi kütüphaneleri manuel eklemek yerine, pom.xml dosyasına yazarak otomatik yükleyebilirsin.
✅ Proje Otomasyonu

Kod derleme, test çalıştırma, paketleme ve dağıtım işlemlerini otomatik yapar.
Tek komutla tüm işlemleri gerçekleştirebilirsin.
✅ Standart Proje Yapısı Sağlar

Maven, projelerin belirli bir klasör yapısına sahip olmasını sağlar.
src/main/java, src/test/java, target/ gibi klasör yapıları oluşturur.
✅ Çok Modüllü Projeler İçin Uygundur

Büyük projelerde birden fazla modül içeren uygulamalar geliştirmeyi kolaylaştırır.
✅ Platformdan Bağımsız Çalışır

Maven projeleri Windows, Mac, Linux gibi tüm işletim sistemlerinde çalışabilir.

2️⃣ Maven Kurulumu
💡 Maven’i kurmak için:
1️⃣ Java JDK yüklü olmalı (java -version ile kontrol edebilirsin).
2️⃣ Maven’i Apache Maven Resmi Sitesi üzerinden indir.
3️⃣ Maven’i yükledikten sonra aşağıdaki komut ile doğrula:
mvn -version

ğer başarıyla yüklendiyse, aşağıdaki gibi bir çıktı görmelisin:
Apache Maven 3.x.x
Maven home: /usr/local/apache-maven
Java version: 11.0.10

3️⃣ Maven ile Yeni Proje Oluşturma
Yeni bir Maven projesi başlatmak için:
mvn archetype:generate -DgroupId=com.example -DartifactId=my-java-project -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
📌 Bu komut:

com.example → Proje grubu adı
my-java-project → Proje adı
maven-archetype-quickstart → Varsayılan Maven proje yapısını oluşturur.

Oluşturulan Maven projesi aşağıdaki gibi bir klasör yapısına sahip olur:
my-java-project
│── src
│   ├── main/java  (Ana kodlar buraya yazılır)
│   ├── test/java  (Testler buraya yazılır)
│── pom.xml        (Proje yapılandırma dosyası)

4️⃣ Maven’in En Önemli Dosyası: pom.xml
📌 pom.xml, Maven projelerinin yapılandırma dosyasıdır.
📌 İçinde bağımlılıklar (dependencies), build ayarları ve eklentiler (plugins) bulunur.

Örnek pom.xml:
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    
    <modelVersion>4.0.0</modelVersion>

    <groupId>com.example</groupId>
    <artifactId>my-java-project</artifactId>
    <version>1.0.0</version>
    <packaging>jar</packaging>

    <dependencies>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
            <version>2.7.0</version>
        </dependency>
    </dependencies>
</project>
📌 Bu dosya, projenin bağımlılıklarını yönetir ve Maven'in nasıl çalışacağını belirler.

5️⃣ Maven Komutları
  Komut	                    Açıklama
mvn compile	        Kaynak kodları derler.
mvn clean	        target/ klasörünü temizler (önceki build dosyalarını siler).
mvn test	        Testleri çalıştırır.
mvn package	        Projeyi JAR/WAR dosyası olarak paketler.
mvn install	        Projeyi yerel Maven deposuna yükler.
mvn dependency:tree	Proje bağımlılıklarını gösterir.

6️⃣ Maven Kullanarak Bağımlılık (Dependency) Yönetimi
Maven ile bir kütüphane (JAR dosyası) eklemek için pom.xml içine aşağıdaki gibi eklenir:

Spring Boot Bağımlılığı Ekleme

<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
    <version>2.7.0</version>
</dependency>
Daha sonra Maven bağımlılıkları güncellemek için şu komutu çalıştırabilirsin:

mvn clean install
Bu komut, bağımlılıkları indirir ve projeyi derler.

```
---

### pom.xml Nedir? (Project Object Model - POM)
```sh

📌 pom.xml, Maven projelerinde kullanılan bir yapılandırma dosyasıdır.
📌 Maven, Java projelerinde bağımlılık yönetimi ve derleme işlemlerini otomatikleştiren bir araçtır.
📌 pom.xml dosyası, projenin bağımlılıklarını, yapılandırmasını ve derleme ayarlarını içerir.

1️⃣ pom.xml Ne İşe Yarar?
✅ Bağımlılık Yönetimi (Dependency Management) → Projeye eklenmesi gereken kütüphaneleri (JAR dosyaları) otomatik olarak indirir.
✅ Proje Yapılandırması → Proje adı, versiyonu, geliştirici bilgileri gibi ayarları içerir.
✅ Build (Derleme) Yönetimi → Derleme, test ve dağıtım işlemlerini otomatize eder.
✅ Eklenti (Plugin) Yönetimi → Maven eklentileri ile test ve paketleme işlemlerini yönetir.

2️⃣ pom.xml İçeriği ve Yapısı
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    
    <modelVersion>4.0.0</modelVersion>

    <!-- Proje bilgileri -->
    <groupId>com.example</groupId>
    <artifactId>my-java-project</artifactId>
    <version>1.0.0</version>
    <packaging>jar</packaging>

    <!-- Proje bağımlılıkları (Dependencies) -->
    <dependencies>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
            <version>2.7.0</version>
        </dependency>

        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.13.2</version>
            <scope>test</scope>
        </dependency>
    </dependencies>

    <!-- Build eklentileri -->
    <build>
        <plugins>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-compiler-plugin</artifactId>
                <version>3.8.1</version>
                <configuration>
                    <source>11</source>
                    <target>11</target>
                </configuration>
            </plugin>
        </plugins>
    </build>
</project>

3️⃣ pom.xml'in Temel Bileşenleri
Etiket	           Açıklama
<groupId>	Proje grubu kimliği (com.example gibi)
<artifactId>	Proje adı (my-java-project gibi)
<version>	Projenin sürüm numarası (1.0.0 gibi)
<packaging>	Paket türü (jar veya war)
<dependencies>	Projeye eklenen kütüphaneler (Spring Boot, JUnit vb.)
<build>	        Derleme işlemleri (Java sürümü, eklentiler, vs.)
<plugins>	Maven eklentileri (maven-compiler-plugin gibi)

```
---

### Compiler (Derleyici) Nedir?
```sh

Compiler (Derleyici), yazdığın programlama dili kodunu makinenin anlayacağı dile çeviren bir araçtır.

Java'da kullanılan derleyici javac (Java Compiler) olarak adlandırılır.

Java Compiler (javac) Ne Yapar?
🔹 1. Java Kaynak Kodunu Okur → HelloWorld.java
🔹 2. Derleme İşlemi Yapar → Kaynak kodu bytecode’a çevirir (HelloWorld.class)
🔹 3. Bytecode JVM Tarafından Çalıştırılır

💡 Derleyici, hataları kontrol eder ve eğer sözdizimi hatası varsa programın derlenmesine izin vermez.
```
---

### Interpreter (Yorumlayıcı) Nedir?
```sh

Interpreter (Yorumlayıcı), programlama dilinde yazılmış kodları satır satır çalıştıran bir programdır.

Interpreter Nasıl Çalışır?
🔹 1. Kaynak kodu doğrudan okur ve analiz eder.
🔹 2. Kodu satır satır çalıştırır.
🔹 3. Hata varsa, anında bildirir ve çalışmayı durdurur.

💡 Interpreter, Compiler'dan farklı olarak tüm kodu bir kerede makine koduna çevirmek yerine satır satır çevirir ve çalıştırır.

Java’da Interpreter Kullanımı:
Java’da hem Compiler hem de Interpreter kullanılır!

✅ Java Compiler (javac) → Java kodunu bytecode'a çevirir.
✅ Java Interpreter (JVM içindeki Just-In-Time Compiler - JIT) → Bytecode'u satır satır makine koduna çevirip çalıştırır.
```
---

### Java'da Data Types (Veri Tipleri) Nedir?
```sh

Data types (veri tipleri), değişkenlerin hangi türde veri tutacağını belirler. 
Java'da veri tipleri ikiye ayrılır:

1️⃣ Primitive (İlkel) Veri Tipleri
Bunlar Java’nın hafızada doğrudan sakladığı basit veri tipleridir.

Veri Tipi		                                                     Örnek
byte:	 1 byte, -128 ile 127 arasında değer alır.	                 byte a = 100;
short:	 2 byte, -32,768 ile 32,767 arasında değer alır.	         short b = 30000;
int:	 4 byte, tam sayılar için kullanılır.	                         int c = 123456;
long:	 8 byte, büyük tam sayılar için kullanılır.	                 long d = 123456789L;
float:	 4 byte, ondalıklı sayılar için kullanılır.	                 float e = 12.34f;
double:	 8 byte, daha hassas ondalıklı sayılar için kullanılır.	         double f = 12.345678;
char:	 2 byte, tek bir karakter saklar.	                         char g = 'A';
boolean: 1 bit, true veya false değer alır.	                         boolean h = true;

📝 Not: Sayısal veri tiplerinde long, float gibi büyük olanlar daha fazla hafıza kaplar ama büyük değerleri saklayabilir.

2️⃣ Reference (Referans) Veri Tipleri
Bunlar nesne tabanlı (Object-Oriented) veri tipleridir. Java’da sınıflar, diziler (arrays) ve özel nesneler bu kategoriye girer.

  Veri Tipi	                                            	   Örnek
String:	 Metin ifadeleri için kullanılır.	                String name = "Java";
Arrays:	 Aynı veri tipinden birden fazla değer saklar.	        int[] numbers = {1, 2, 3};
Classes: Kendi nesnelerimizi oluşturmak için kullanılır.	Car myCar = new Car();

🔹 Primitive tipler doğrudan hafızada saklanır, referans tipler ise bellek adresi üzerinden erişilir.
```
---

### Wrapper Types Nedir?
```sh

Wrapper Class'lar (Sarmalayıcı Sınıflar), primitive (ilkel) veri tiplerini bir nesneye dönüştüren sınıflardır.
Java'da her primitive veri tipinin bir Wrapper Class'ı vardır ve bunlar java.lang paketinde bulunur.

Neden Wrapper Class Kullanılır?
✅ Primitive tipleri nesne olarak kullanabilmek için
✅ Collections (ArrayList, HashMap) gibi veri yapılarıyla çalışmak için
✅ Primitive veri tiplerinde ekstra metotlara erişmek için

Wrapper Class Kullanımı

1️⃣ Primitive'den Wrapper'a Dönüştürme (Boxing)
✅Örnek:
int number = 10;  
Integer wrappedNumber = Integer.valueOf(number); // Boxing (Otomatik olarak nesneye dönüştürme)

2️⃣ Wrapper’dan Primitive’e Dönüştürme (Unboxing)
✅Örnek:
Integer wrappedNumber = 20;  
int primitiveNumber = wrappedNumber.intValue(); // Unboxing (Primitive tipe çevirme)

3️⃣ Autoboxing ve Unboxing (Otomatik Dönüştürme)
Java 5 ve sonrası, Autoboxing ve Unboxing desteği sağlar. Yani valueOf() ve intValue() gibi metotları yazmana gerek kalmaz:
✅Örnek:
int num = 30;
Integer autoWrapped = num;  // Autoboxing
int autoUnwrapped = autoWrapped;  // Unboxing

4️⃣ Wrapper Class’ların Faydalı Metotları
✅Örnek:
String str = "123";
int converted = Integer.parseInt(str);  // String'i int'e çevirir

Integer max = Integer.max(10, 20);  // Büyük olanı döndürür (20)
Double piValue = Double.valueOf("3.14");  // String'den double'a çevirir.

👉Özet:
🔹Wrapper Class'lar, primitive tipleri nesneye dönüştürmek için kullanılır.
🔹Autoboxing ve Unboxing sayesinde otomatik dönüşümler yapılabilir.
🔹Wrapper Class’lar, ekstra metotlarla veri dönüşümü ve karşılaştırma işlemlerinde yardımcı olur.
```
---

### Scanner Class Nedir?
```sh

📌 Scanner Class, Java’da kullanıcıdan giriş almak (input almak) için kullanılan bir sınıftır.
📌 java.util.Scanner kütüphanesinde bulunur.

1️⃣ Scanner Nasıl Kullanılır?
📌 Kullanıcıdan veri almak için öncelikle bir Scanner nesnesi oluşturmalıyız.

import java.util.Scanner;  // Scanner sınıfını içe aktar

public class ScannerExample {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);  // Scanner nesnesi oluştur
        
        System.out.print("Adınızı girin: ");
        String name = input.nextLine();  // Kullanıcıdan String giriş al
        
        System.out.println("Merhaba, " + name + "!");
        
        input.close(); // Scanner'ı kapat
    }
}

💡 Çıktı:
Adınızı girin: Ahmet
Merhaba, Ahmet!

2️⃣ Scanner ile Farklı Veri Tipleri Alma
Kullanılabilecek Metotlar ve Veri Tipleri

Metot	Veri Tipi	                                         Örnek Kullanım
nextLine()	   String (Boşluk içeren metinler)	      String isim = input.nextLine();
next()	           String (Boşluk olmadan ilk kelime)	      String isim = input.next();
nextInt()	   int (Tam sayı)	                      int yas = input.nextInt();
nextDouble()	   double (Ondalıklı sayı)	              double maas = input.nextDouble();
nextBoolean()	   boolean (true/false)	                      boolean aktif = input.nextBoolean();

3️⃣ Scanner Kullanımı Örnekleri
👉 Tam Sayı Girişi (nextInt())
Scanner input = new Scanner(System.in);
System.out.print("Yaşınızı girin: ");
int age = input.nextInt();
System.out.println("Yaşınız: " + age);
input.close();

👉 Ondalıklı Sayı Girişi (nextDouble())
Scanner input = new Scanner(System.in);
System.out.print("Maaşınızı girin: ");
double salary = input.nextDouble();
System.out.println("Maaşınız: " + salary);
input.close();

👉 Boolean (true/false) Girişi (nextBoolean())
Scanner input = new Scanner(System.in);
System.out.print("Java öğreniyor musunuz? (true/false): ");
boolean learning = input.nextBoolean();
System.out.println("Cevabınız: " + learning);
input.close();

4️⃣ Scanner Kullanırken Dikkat Edilmesi Gerekenler
❗ nextInt(), nextDouble() gibi metotlar sonrası nextLine() çağrılırsa, satır atlama sorunu yaşanabilir.
 Çözüm: nextLine() öncesinde boş bir input.nextLine() ekle!
Scanner input = new Scanner(System.in);
System.out.print("Yaşınızı girin: ");
int age = input.nextInt();
input.nextLine();  // **Boş nextLine() ekleyerek satır atlamasını önlüyoruz**

System.out.print("Adınızı girin: ");
String name = input.nextLine();  // Kullanıcıdan String al
System.out.println("Merhaba " + name + ", yaşınız: " + age);
input.close();

Özet:
✅ Scanner Class, kullanıcıdan veri almak için kullanılır.
✅ nextInt(), nextDouble(), nextLine() gibi farklı veri alma metotları vardır.
✅ Giriş hatalarından kaçınmak için dikkatli kullanılmalıdır!

```
---

### Escape Character Nedir?
```sh
📌 Escape character (kaçış karakteri), özel karakterleri metin içinde kullanmamızı sağlayan bir işarettir.
📌 Java'da \ (ters eğik çizgi - backslash) escape karakter olarak kullanılır.

Java'da Kullanılan Escape Karakterler
Escape Karakter	Anlamı	                            Örnek
\n	Yeni satıra geçme	               "Merhaba\nDünya" → Merhaba (alt satır) Dünya
\t	Tab (4-8 boşluk bırakır)	       "Java\tProgramlama" → Java Programlama
\"	Çift tırnak kullanma	               "Ali dedi ki: \"Merhaba\"" → Ali dedi ki: "Merhaba"
\'	Tek tırnak kullanma	                char c = '\''; → ' karakteri atanır
\\	Ters eğik çizgi kullanma	        "C:\\Users\\Documents" → C:\Users\Documents
\r	Satır başına döner (Carriage Return)	"Merhaba\rDünya" → Dünyaaba
\b	Bir karakter siler (Backspace)	        "Merhaba\b!" → Merhab!
\f	Yeni sayfa (Form Feed)	                "Sayfa1\fSayfa2" → (Yeni sayfaya geçer)

Örnek Kullanımlar:
1️⃣ Yeni Satıra Geçme (\n)
public class EscapeExample {
    public static void main(String[] args) {
        System.out.println("Merhaba\nDünya");
    }
}
💡 Çıktı:
Merhaba
Dünya

2️⃣ Tab Boşluğu Bırakma (\t)
System.out.println("Java\tProgramlama");
💡 Çıktı:
Java    Programlama

3️⃣ Çift Tırnak Kullanma (\")
System.out.println("Ali dedi ki: \"Merhaba!\"");
💡 Çıktı:
Ali dedi ki: "Merhaba!"

4️⃣ Dosya Yolu Yazma (\\)
System.out.println("C:\\Users\\Documents\\file.txt");
💡 Çıktı:
C:\Users\Documents\file.txt

```
---

### Farklı Değişken ve Fonksiyon İsimlendirme Formatları
```sh

Programlamada değişken, fonksiyon ve sınıf isimlendirmesi için kullanılan 4 temel stil vardır:
1️⃣ Camel Case (Deve Notasyonu) 🐫
👉 İlk kelime küçük harfle başlar, sonraki kelimeler büyük harfle başlar.
🔹 Kullanım: Değişken ve metod isimleri

✅ Örnek:
int userAge = 25;
String firstName = "Ahmet";

👉 Kullanıldığı Yerler: Java, JavaScript, Python, C# gibi dillerde değişken ve metod isimlendirmesi.

2️⃣ Pascal Case (Büyük Camel Case) 🏛️
👉 Her kelime büyük harfle başlar.
🔹 Kullanım: Sınıf ve nesne isimleri

✅ Örnek:
class EmployeeData { }
String FullName = "John Doe";

👉 Kullanıldığı Yerler: Java, C#, Python gibi dillerde sınıf ve nesne isimlendirmesi.

3️⃣ Snake Case (Alt Çizgi Notasyonu) 🐍
👉 Tüm kelimeler küçük harfle yazılır ve _ (alt çizgi) ile ayrılır.
🔹 Kullanım: Veritabanı isimleri, sabit değişkenler

✅ Örnek:
int user_age = 25;
String first_name = "Ahmet";
final double PI_VALUE = 3.14;

👉 Kullanıldığı Yerler: Python, C, SQL veritabanları, sabit (constant) isimlendirmeleri.

4️⃣ Kebab Case (Tire Notasyonu) 🥖
👉 Kelimeler - (tire) ile ayrılır.
🔹 Kullanım: URL’lerde ve bazı frontend frameworklerinde

✅ Örnek:
<h1 class="main-title">Hello</h1>

👉 Kullanıldığı Yerler: CSS class isimleri, HTML ID’leri, bazı API endpoint isimlendirmeleri.

Özet:
İsimlendirme	     Örnek	        Kullanım Alanı
Camel Case	   firstName	   Değişken ve metodlar (Java, JS, Python)
Pascal Case	   EmployeeData	   Sınıf ve nesneler (Java, C#)
Snake Case	   user_age	   Veritabanı, sabitler (Python, SQL)
Kebab Case	   main-title	   CSS, HTML class ve id’ler
💡 Öneri:
Java’da genellikle camelCase (değişken/metot), PascalCase (sınıflar), UPPER_SNAKE_CASE (sabitler) kullanılır. 🚀
```
---

### Java'da Stack Memory ve Heap Memory Nedir?
```sh
Java'da bellek yönetimi iki ana bölgeye ayrılır:
📌 Stack Memory → Küçük ve hızlıdır, metod çağrıları ve yerel değişkenler burada saklanır.
📌 Heap Memory → Büyük ve esnektir, nesneler ve sınıflar burada saklanır.

1️⃣ Stack Memory (Yığın Bellek)
📌 Geçici veriler (method çağrıları, yerel değişkenler) için kullanılan küçük ve hızlı bir bellek alanıdır.

🔹 Özellikleri:
✅ Metod çağrıları ve yerel değişkenler burada saklanır.
✅ LIFO (Last In, First Out - Son Giren İlk Çıkar) prensibiyle çalışır.
✅ Her metod çağrıldığında yeni bir stack frame oluşturulur.
✅ Metod tamamlandığında ilgili bellek otomatik olarak temizlenir.

🔹 Örnek:
public class StackExample {
    public static void main(String[] args) {
        int a = 5;  // Stack Memory'de saklanır
        int b = 10; // Stack Memory'de saklanır
        sum(a, b);
    }

    public static int sum(int x, int y) {
        int result = x + y; // Stack Memory'de saklanır
        return result;
    }
}
📌 a, b, x, y ve result değişkenleri Stack Memory içinde tutulur ve metod bitince otomatik silinir.

2️⃣ Heap Memory (Yığın Bellek)
📌 Java'da nesnelerin ve sınıfların saklandığı büyük bir bellek alanıdır.

🔹 Özellikleri:
✅ new anahtar kelimesi ile oluşturulan nesneler burada saklanır.
✅ Heap bellekte saklanan nesnelere referans ile erişilir.
✅ Garbage Collector (Çöp Toplayıcı) kullanılmayan nesneleri temizler.

🔹 Örnek:
class Person {
    String name;

    Person(String name) {
        this.name = name;
    }
}

public class HeapExample {
    public static void main(String[] args) {
        Person p1 = new Person("Ali");  // Heap Memory'de saklanır
        Person p2 = new Person("Ayşe"); // Heap Memory'de saklanır
    }
}
📌 p1 ve p2 değişkenleri Stack'te tutulur, ancak new Person("Ali") ve new Person("Ayşe") nesneleri Heap Memory içinde saklanır.

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---
### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---

### Git
```sh

```
---