
            Console.WriteLine("-----------------------------------");
            Console.WriteLine("*İlkerCoach Hareket Eğitim Merkezi*");
            Console.WriteLine("-----------------------------------");

            Console.WriteLine("Öğrenci işlemleri için (0) tuşuna basınız ");
            Console.WriteLine("Öğretmen işlemleri için (1) tuşuna basınız ");
            Console.Write("Yapmak istediğiniz işlem: ");
            byte veri = Convert.ToByte(Console.ReadLine());
            Console.Clear();

            if (veri == 0)
            {
                Console.WriteLine("**************************************************");
                Console.WriteLine("Öğrenci İşlemine Başladınız");
                Console.WriteLine("**************************************************");
                Console.WriteLine("Öğrencileri Görüntülemek için (0) Tuşuna basınız");
                Console.WriteLine("Öğrenci Eklemek için (1) Tuşuna basınız ");
                Console.WriteLine("öğrenci Silmek için (2) Tuşuna basınız ");
                Console.WriteLine("**************************************************");
                Console.Write("Hangi işlemi yapmak istiyorsunuz: ");
                byte veri1= Convert.ToByte(Console.ReadLine());
                Console.Clear();

                //öğrenci gösterme mevcut
                if (veri1 == 0)
                {
                    Console.WriteLine("Öğrenciler görüntüleniyor");
                    //öğrencileri görüntüler
                    // öğrencileri yazdır

                }
                //Öğrenci ekleme 
                else if(veri1 == 1)
                {
                    Console.WriteLine("****************************************");
                    Console.WriteLine("Öğrenci Kayıt Sistemi Başlatıldı.");
                    Console.WriteLine("****************************************");
                    Console.Write("Kaç Öğrenci Kaydı Girmek İstersiniz: ");
                    byte OgrenciSayı = Convert.ToByte(Console.ReadLine());
                    
                    for (int i = 0; i <OgrenciSayı ; i++)
                    {
                        Console.WriteLine("Öğrenci İD :" + OgrenciSayı--);
                        Console.Write("Öğrenci İsmi giriniz: ");
                        string Ogrenciİsmi = Console.ReadLine();
                        Console.Write("Öğrenci SoyAd giriniz: ");
                        string OgrenciSoyad = Console.ReadLine();
                        Console.Write("Öğrenci Yaş(AY): ");
                        byte OgrenciYas = Convert.ToByte(Console.ReadLine());
                        Console.WriteLine("****************************************");

                    }
                    Console.Clear();
                    Console.WriteLine("****************************************");
                    Console.WriteLine("Öğrenci Kayıt işleminiz başarı ile tamamlanmıştır.");
                    Console.WriteLine("****************************************");
                    Console.ReadLine();
                    Console.Clear();
                    Console.WriteLine("Yazdırmak İsterseniz (0) Tuşuna basın ");
                    Console.WriteLine("Geriye dönmek için (1) Tuşuna basın ");
                    Console.Write("değer: ");
                    byte deger= Convert.ToByte(Console.ReadLine());

                    if (deger==0)
                    {
                        Console.WriteLine("Öğrenci İsmi:{0}");
                    }




                }
                // Öğrenci silme
                else if(veri1 == 2)
                {
                    Console.WriteLine("****************************************");
                    Console.WriteLine("Öğrenci silme işlemine geldiniz: ");
                    Console.WriteLine("****************************************");






                }


            }
           

            Console.ReadLine();
