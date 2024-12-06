# ceren
murat yücedağ CSHARP eğitim videosu ders1-2 
// = açıklama satırı
komutlar main methodunun içine yazılır.

#region yazdırma komutları 

//Console.write("");  =konsola metin ve veri yazdırmak 

//Console.WriteLine("");  = konsola metin veya veri yazdırdıktan sonra alt satıra geçer.

//Console.Read("");   = tek karakter okur

//Console.ReadLine("");  = tam satır oluşturur

  #endregion


#region string değişkeni

STRİNG KULLANIMI

//string name;

//name = "ceren";

//Console.Write(name);

//Console.ReadLine();


string ad;

string soyad;

string telefonnumarası;

string email, şehir, ilçe;

ad = "ceren";

soyad = "tekin";

telefonnumarası = "0554 217 88 53";

email = "ders@gmail.com";

şehir = "ankara";

ilçe = "keçiören";

Console.WriteLine("**** Rezervasyon Kartı ****");

Console.WriteLine();

Console.WriteLine("----------------------------");

Console.WriteLine("Müşteri: " + ad + " " + soyad);

Console.WriteLine("iletişim: " + telefonnumarası);

Console.WriteLine("email: " + email);

Console.WriteLine("Adres: " + ilçe + "/" + şehir);

Console.WriteLine("----------------------------");

Console.ReadLine();

#endregion

#region Int Değişkenleri

//int number = 35;

//Console.WriteLine(number);

//int hamburger = 250;

//int kola = 50;

//int patateskızartması = 80;

//int nugget = 65;

//int sos = 10;

//int pizza = 110;

//Console.WriteLine("#### RESTORANT MENÜ FİYATI ####");

//Console.WriteLine();

//Console.WriteLine("---hamburger: " + hamburger + "TL");

//Console.WriteLine("---kola: " + kola + "TL");

//Console.WriteLine("---pataes kızartması: " + patateskızartması + "TL");

//Console.WriteLine("---nugget: " + nugget + "TL");

//Console.WriteLine("---sos: " + sos + "TL");

//Console.WriteLine("---pizza: " + pizza + "TL");

//Console.WriteLine();

//// müşterinin ne kadar ödeyeceğini hesaplayacağız

//int hamburgerfiyatı= 0;

//int kolafiyatı = 0;

//int nuggetfiyatı = 0;

//int sosfiyatı = 0;

//int pizzafiyatı = 0;

//int hamburgersayısı = 3;

//int kolasayısı= 4;

//int nuggetsayısı = 5;

//int sossayısı = 6;

//int pizzasayısı = 2;

//hamburgerfiyatı = hamburger * hamburgersayısı;

//kolafiyatı = kola * kolasayısı;

//nuggetfiyatı = nugget * nuggetsayısı;

//sosfiyatı = sos * sosfiyatı;

//pizzafiyatı = pizza * pizzafiyatı;

//Console.WriteLine( );

//Console.WriteLine("Hamburger Tutarı = " + hamburgerfiyatı + "TL");

//Console.WriteLine("Kola Tutarı = " + kolafiyatı + "TL");

//Console.WriteLine("Nugget Tutarı = " + nuggetfiyatı + "TL");

//Console.WriteLine("Pizza Tutarı = " + pizzafiyatı + "TL");

//Console.WriteLine();

//int ÖdenecekTutar = hamburgerfiyatı + kolafiyatı + nuggetfiyatı + sosfiyatı + pizzafiyatı;

//Console.WriteLine(" Toplam Ödecek Tutar = " + ÖdenecekTutar + "TL");

//Console.ReadLine();

#endregion

#region double değişkeni

//double number;
//number = 6.89;
//Console.WriteLine(number);

//Console.WriteLine("**** FİYAT LİSTESİ****");
//Console.WriteLine();


//double elmakilosu, muzkilosu, erikkilosu, salatalıkkilosu, kivikilosu;

//elmakilosu = 32.90;
//muzkilosu = 55.80;
//erikkilosu = 79.90;
//salatalıkkilosu = 25.25;
//kivikilosu = 45.99;

//Console.WriteLine("---Elma Birim Fiyatı:" + elmakilosu + "TL");
//Console.WriteLine("---Muz Birim Fiyatı:" + muzkilosu + "TL");
//Console.WriteLine("---Erik Birim Fiyatı:" + erikkilosu + "TL");
//Console.WriteLine("---Salatalık Birim Fiyatı:" + salatalıkkilosu + "TL");
//Console.WriteLine("---Elma Birim Fiyatı:" + kivikilosu + "TL");

//Console.WriteLine();
//Console.WriteLine();


//double elmagram, muzgram, erikgram, salatalıkgram, kivigram;

//elmagram = 2.750;
//muzgram = 3.150;
//erikgram = 0.750;
//salatalıkgram = 4.200;
//kivigram = 0.550;

//double elmanıntoplamfiyatı = elmakilosu * elmagram;
//double muzuntoplamfiyatı = muzkilosu * muzgram;
//double eriktoplamfiyat = erikkilosu * erikgram;
//double salatalıktoplamfiyat = salatalıkkilosu * salatalıkgram;
//double kivitoplamfiyat = kivikilosu * kivigram;


//Console.WriteLine(" Elmanın Toplam Fiyatı: " + elmanıntoplamfiyatı);
//Console.WriteLine("Muzun Toplam Fiyatı: " + muzuntoplamfiyatı);
//Console.WriteLine("Eriğin Toplam Fiyatı: " + eriktoplamfiyat);
//Console.WriteLine("Salatalık Toplam Fiyat: " + salatalıktoplamfiyat);
//Console.WriteLine("Kivi Toplam Fiyat: " + kivitoplamfiyat);

//Double alışveriştoplamtutar = elmanıntoplamfiyatı + muzuntoplamfiyatı + eriktoplamfiyat + salatalıktoplamfiyat + kivitoplamfiyat;

//Console.WriteLine();
//Console.WriteLine();

//Console.WriteLine("Alışveriş Toplam Tutar: " + alışveriştoplamtutar + " TL ");


//Console.ReadLine();
#endregion


#region Char Değişkenler

//char symbol;
//symbol = 'a';

//Console.WriteLine(symbol);


//Console.ReadLine();
#endregion


#region Klavyede Veri Girişleri-String Değişkenler

//Console.WriteLine("*** CSHARP HAVA YOLLARI ***");
//Console.WriteLine();

//String yolcuadı, yolcusoyadı, yolcuadresi, yolcuyaşı, yolcutckimliknumarası;

//Console.Write("Yolcu Adı: ");
//yolcuadı = Console.ReadLine();

//Console.Write("Yolcu Soyadı: ");
//yolcusoyadı = Console.ReadLine();

//Console.Write("Yolcu Adresi: ");
//yolcuadresi = Console.ReadLine();

//Console.Write("Yolcu Yaşı: ");
//yolcuyaşı = Console.ReadLine();

//Console.Write("Yolcu Tc Kimlik Numarası: ");
//yolcutckimliknumarası = Console.ReadLine();

//Console.WriteLine();

//Console.WriteLine("----------------------------------");

//Console.WriteLine("Yolcu: " + yolcuadı + yolcusoyadı);
//Console.WriteLine("Adresi: "+ yolcuadresi);
//Console.WriteLine("Yaşı: " + yolcuyaşı);
//Console.WriteLine("TC Kimlik Numarası: "+ yolcutckimliknumarası);





//Console.ReadLine();
#endregion


#region Klavyeden Tam Sayı Girişleri ve Dönüşümler

//int ayakkabıfiyatı, çorapfiyatı, şortfiyatı, şapkafiyatı;

//ayakkabıfiyatı = 1000;
//çorapfiyatı = 40;
//şortfiyatı = 150;
//şapkafiyatı = 300;

//int ayakkabısayısı, çorapsayısı, şortsayısı, şapkasayısı;

//Console.Write("Lütfen Aldığınız Ayakkanı Sayısını Giriniz: ");
//ayakkabısayısı = int.Parse(Console.ReadLine());

//Console.Write("Lütfen Aldığınız Çorap Sayısını Giriniz: ");
//çorapsayısı = int.Parse(Console.ReadLine());

//Console.Write("Lüfen Aldığınız Şort Sayısını Giriniz: ");
//şortsayısı = int.Parse(Console.ReadLine());

//Console.Write("Lütfen Aldığınız Şapka Sayısını Giriniz: ");
//şapkasayısı = int.Parse(Console.ReadLine());


//int ToplamFiyat = ayakkabıfiyatı * ayakkabısayısı + çorapfiyatı * çorapsayısı + şortfiyatı * şortsayısı + şapkafiyatı * şapkasayısı;

//Console.WriteLine();
//Console.WriteLine("Toplam Ödemeniz Gereken Tutar: " + ToplamFiyat);







//Console.ReadLine();
#endregion


#region Klavyeden Ondalıklı Sayı İşlemleri

//double sınav1, sınav2, sınav3, sonuç;

//Console.Write("Lütfen 1. Sınav Notunu Giriniz: ");
//sınav1 = Double.Parse(Console.ReadLine());

//Console.Write("Lütfen 2. Sınav Notunu Giriniz: ");
//sınav2 = double.Parse(Console.ReadLine());

//Console.Write("Lütfen 3. Sınav Notunu Giriniz: ");
//sınav3 = double.Parse(Console.ReadLine());

//sonuç = (sınav1 + sınav2 + sınav3) / 3;

//Console.WriteLine();
//Console.WriteLine("Sınav Ortalamanız: " + sonuç);


//Console.ReadLine();
#endregion


#region Klavyeden Karakter Girişleri

//char gender;
//Console.Write("Lütfen Cinsiyet Seçiniz: ");
//gender = char.Parse(Console.ReadLine());

//Console.WriteLine("Seçtiğiniz Cinsiyet: " + gender);


//    Console.ReadLine();
#endregion



