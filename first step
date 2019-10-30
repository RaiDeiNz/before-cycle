#include <stdio.h>
#include <time.h>
#include <stdlib.h>

int main(int argc, char const *argv[])
{   
	int cinsiyet,secenek,yas,islem,sayi1,sayi2,cekilis,cevap;
	char hitap,isim,sehir,soyisim;

    printf("====================================================================\n");
    printf("\tHosgeldiniz. Size nasil hitap edilmesini istersiniz ?  :  ");
    printf("====================================================================\n");
    scanf("%s",&hitap);
    donus:
    printf(" Cinsiyetiniz [1]Erkek\n[2]Kadin:  \n\n");
    scanf("%d",&cinsiyet);
    if (cinsiyet==1)
    {
        printf("=========================================================\n");    
        printf("\tO halde sansli cekilisimize hosgeldiniz %s bey.\n\n",hitap);
        printf("=========================================================\n");                
    }
    else if (cinsiyet==2)
    {
        printf("=========================================================\n");    
        printf("\tO halde sansli cekilisimize hosgeldiniz %s hanim.\n\n",hitap);
        printf("=========================================================\n");        
    }
    else
    {
        printf("=========================================================\n");
        printf("\tHatali bir giris yaptiniz. Lutfen cinsiyetinizi parantez icinde yer aldigi numara ile yaziniz..\n\n");
        printf("=========================================================\n");
        goto donus;
    }
    geri:
    printf("=================================\n");
    printf("\t[1]Kimlik Belgesi Hazirla.\n\n");
    printf("=================================\n");
    printf("\t[2]Hesap Makinesine Git\n\n");
    printf("=================================\n");
    printf("\t[3]Sansli Cekilis Oyna\n\n");
    printf("=================================\n");
    printf("\t[0]Programı Kapat\n\n");
    printf("=================================\n");


    printf("Lutfen yapmak istediginiz islemi, islem numarasini girerek belirtiniz :  \n\n");
    scanf("%d",secenek);
    switch (secenek)
    {
    case 1:
        printf("Lutfen isim belirtiniz  : \n");
        scanf("%s",&isim);
        printf("Lutfen soyisim belirtiniz  : \n");
        scanf("%s",&soyisim);
        printf("Lutfen yasinizi belirtiniz : \n");
        scanf("%d",&yas);
        printf("Lutfen dogdugunuz sehri belirtiniz : \n");
        scanf("%s",&sehir);
        printf("Sizin icin hazirliyoruz..\n\n\n\n\n\n\n");
        printf("=====*=====*=====*=====*=====*=====*=====\n");
        printf("Kisinin ismi       :  %s\n",isim);
        printf("Kisinin Soyismi    :  %s\n",soyisim);
        printf("Kisinin yasi       :  %d\n",yas);
        printf("Kisinin dogum yeri :  %s\n",sehir);
        printf("=====*=====*=====*=====*=====*=====*=====\n");
        break;
    case 2:
	bas:
	    printf("========================\n");
	    printf("\t[0]:Onceki Menüye Cikis\n");
	    printf("========================\n");
	    printf("\t[1]:Toplama\n");
	    printf("========================\n");
	    printf("\t[2]:Cikarma\n");
	    printf("========================\n");
	    printf("\t[3]:Carpma\n");
        printf("========================\n");
        printf("\t[4]:Bolme\n");
        printf("========================\n");
	    printf("\nLutfen yapmak istediginiz islemi, islemin numarasini yazarak belirtiniz... :  ");
	    scanf("%d",&islem);
	    switch(islem)
	    {
		    case 0:
			    break;
			    goto geri;
		    case 1:
			    printf("\n\nLutfen toplanmasini istediginiz ilk sayiyi giriniz  :  ");
			    scanf("%d",&sayi1);
			    printf("\nLutfen ikinci sayiyi giriniz :  ");
			    scanf("%d",&sayi2);
			    printf("=============================================\n");
			    printf("-----------> Islem sonucunuz :  > %d <\n",sayi1+sayi2);
			    printf("=============================================\n");			
			    break;
		    case 2:
			    printf("\n\nLutfen cikartilmasini istediginiz ilk sayiyi giriniz  :  ");
			    scanf("%d",&sayi1);
			    printf("\nLutfen ikinci sayiyi giriniz :  ");
			    scanf("%d",&sayi2);
			    printf("=============================================\n");
			    printf("-----------> Islem sonucunuz :  > %d <\n",sayi1-sayi2);
			    printf("=============================================\n");
			    break;
		    case 3:
			    printf("\n\nLutfen carpilmasini istediginiz ilk sayiyi giriniz  :  ");
			    scanf("%d",&sayi1);
			    printf("Lutfen ikinci sayiyi giriniz :  ");
			    scanf("%d",&sayi2);
			    printf("=============================================\n");
			    printf("-----------> Islem sonucunuz :  > %d <\n",sayi1*sayi2);
			    printf("=============================================\n");
			    break;
		    case 4:
			    printf("\n\nLutfen bolunmesini istediginiz ilk sayiyi giriniz  :  ");
			    scanf("%d",&sayi1);
			    printf("\nLutfen ikinci sayiyi giriniz :  ");
			    scanf("%d",&sayi2);
			    printf("=============================================\n");
			    printf("-----------> Islem sonucunuz :  > %d <\n",sayi1/sayi2);
			    printf("=============================================\n");
			    break;
		    default:
			    printf("=============================================\n");
			    printf("-----Hatali bir giris yaptiniz.       ||\n-----Sisteme yonlendiriliyorsunuz...  \\/\n");
			    printf("=============================================\n");
			    goto bas;
        }
	case 3:
        tekrar:
        printf("=========================================================\n");    
        printf("\tSansli cekilisimize hosgeldiniz %s %s. \n\n",hitap,cinsiyet);
        printf("=========================================================\n");
        printf("\n\tLutfen 1~10 arasinda bir sayi giriniz.Sansli cekilis bu sayilardan birinde : \n");
        scanf("%d",&cekilis);
        srand(time(NULL));
        int random=1+rand()%10;    
        if (cekilis=random)
        {
            printf("Sansinizi %d sayisi ile denediniz.. \n\n\tSansli cekilisimizin sayisi da %d.\n",cekilis,random);
            printf("Tebrikler, kazandiniz !!\n");
            printf("\nYeniden oynamak ister misiniz ?\n\n\t E veya H seklinde cevaplayiniz  :  \n[1]Evet :\n[2]Hayir :\n");
            scanf("%d",&cevap);
                if (cevap=1)
                {
                    goto tekrar;
                }
                else if (cevap=2)
                {
                    goto bitir;
                }
                else
                {
                    printf("=============================================================\n");
                    printf("Hatali bir giris yaptiniz.. Ana menuye yonlendiriliyorsunuz..\n");
                    printf("=============================================================\n");
                    goto geri;
                }    
        }
        else
        {
            printf("Sansinizi %d sayisi ile denediniz.. \n\n\tSansli cekilisimizin sayisi da %d.\n",cekilis,random);
            printf("\nYeniden oynamak ister misiniz ?\n\n\t E veya H seklinde cevaplayiniz  :  \n[1]Evet :\n[2]Hayir :\n");
            scanf("%d",&cevap);
                if (cevap=1)
                {
                    goto tekrar;
                }
                else if (cevap=2)
                {
                    goto bitir;
                }
                else
                {
                    printf("=============================================================\n");
                    printf("Hatali bir giris yaptiniz.. Ana menuye yonlendiriliyorsunuz..\n");
                    printf("=============================================================\n");
                    goto geri;
                }    
        }
                
	     
    default:
        printf("Burayi kodlarken kafam karistigi icin sizi %s, cikisa kadar goturmeme izin verin..\n",hitap);
        goto bitir;
    }
    bitir:
return 0;
}
