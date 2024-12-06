# ceren
murat yücedap CSHARP eğitim videosu ders1-2 
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

