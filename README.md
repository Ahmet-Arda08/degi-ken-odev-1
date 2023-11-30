# degi-ken-odev-1
Değişkenler ve Veri Tiplerleri

 Console.WriteLine("");
        byte b =5;  //1 byte
        sbyte c =5; // 1 byte 

        short s =5; //2 byte
        ushort us =5; //2 byte

        Int16 i16 =2; //2 byte
        int i =2; //4 byte
        Int32 i32 =2; //4 byte
        Int64 i64 =2; //8 byte

        uint u1 =2; //4 byte
        long l =4; //8 byte
        ulong ul =4; //8 byte

        // reel sayılar
        float f =5;  //4 byte
        double d =5; //8 byte 
        decimal de =5; //16 byte

        char ch = '2'; //2 byte
        string str ="Arda"; //sınırsız

        bool b1 =true;
        bool b2=false;

        DateTime d1 =DateTime.Now;

        Console.WriteLine(d1);

        object o1 ="x";
        object o2 ='y';
        object o3 = 3;
        object o4 =4.3;

        //string ifadeler

        string str1 = string.Empty;
        str1 = "Arda Korkmaz";  
        string ad ="Arda";
        string soyad ="Korkmaz";
        string tümisim =ad + " " + soyad;

        Console.WriteLine(tümisim);

        //integer tamamlama şekilleri 
        int integer1 =5;
        int intger2 =3;
        int integer3 = integer1 + intger2;  

        //boolean
        bool bool3 = 10>2;

        //degişken Dönüşümleri 
        string str20 ="20";
        int integer20 =20;
        string yenideger =str20 +integer20.ToString();
        Console.WriteLine(yenideger); //çıktı 2020

        int int21 = integer20 + Convert.ToInt32(str20);
        Console.WriteLine(int21); //çıktı 40

        int int22 = integer20 + int.Parse(str20); //çıktı 40

        //datetime

        string datetime = DateTime.Now.ToString("dd.MM.yyyy");           
        Console.WriteLine(datetime);

        string datetime2 = DateTime.Now.ToString("dd/MM/yyyy"); 
        Console.WriteLine(datetime2);
         
         //saat
        string hour = DateTime.Now.ToString("HH:mm"); 
        Console.WriteLine(hour);
