# MENGUBAH-BILANGAN-PECAHAN-BIASA-KE-CAMPURAN

## CODING PROGRAM LENGKAP

    #include<stdio.h>
    int pecahan();
    int main(){
    pecahan();


    } 
    int pecahan (){
    int a,b,l,t;
    printf("===========================DINDA PUSPITA DEWI============================");
    printf("==================================MENYEDERHANAKAN PECAHAN==============================");
    printf("Masukkan pembilang:");
    scanf("%d", &a);
    printf("Masukkan penyebut:");
    scanf("%d", &b);
    t=a/b;
    l=a%b;
    if(a%b==0)
    printf("Bilangan (%d/%d)\n di sederhanakan menjadi %d",a,b,t);
    else if(a%b !=0)
    printf("Bilangan (%d/%d)\n di sederhanakan menjadi(%d %d/%d) ",a,b,t,l,b);

    }


 ## HASIL PROGRAM

![img](https://github.com/dindapuspitadewi/MENGUBAH-BILANGAN-PECAHAN-BIASA-KE-CAMPURAN/blob/master/pecahan%20biasa%20ke%20campuran%202.png?raw=true)
