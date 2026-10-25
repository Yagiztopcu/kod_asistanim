# kod_asistanim yağız topçu
## projenin amacı:kullanıcılara günlük işlerinde  hesaplama selamlama yardımcı olacak bir dijital asistan tasarlamak 
## projenin hedefleri:bir asistanın ilerleyen zamanlarda hangi özellikleri kazanacağını  
veri saklama 
BAŞLA

    // 1. VERİ SAKLAMA KONTROLÜ
    EGER Hafizada_Kullanici_Adi_Var_Mi() ISE
        Kullanici_Adi = Hafizadan_Oku("Kullanici_Adi")
        Yazdir("Tekrar hoş geldin, " + Kullanici_Adi)
    DEGILSE
        Kullanici_Adi = Kullanicidan_Al("Adın nedir?")
        Hafiyaya_Kaydet("Kullanici_Adi", Kullanici_Adi)
        Yazdir("Tanıştığımıza memnun oldum, " + Kullanici_Adi)
        BİTİR
