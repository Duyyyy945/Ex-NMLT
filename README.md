#include<stdio.h>
int main()
 {
    /*int n, tuoi;
    printf("Nhap nam sinh: ");
    scanf("%d", &n);
    tuoi = 2024-n;
    printf("tuoi : %d",tuoi);
    return 0;*/
    /*int a,b, tong, hieu, tich;
    float thuong;
    printf("Nhap so a: ");
    scanf("%d", &a);
    printf("Nhap so b: ");
    scanf("%d", &b);
    tong=a+b;
    hieu=a-b;
    tich=a*b;
    thuong=a/b;
    printf("Tong: %d\n", tong);
    printf("Hieu: %d\n", hieu);
    printf("Tich: %d\n", tich);
    printf("Thuong: %.2f\n", thuong);
    return 0;*/
    /*int  sl, dg, t;
    char sp[30];
    float vat;
    printf("Nhap ten san pham:");
    scanf("%s", sp);
    printf("Nhap so luong:");
    scanf("%d", &sl);
    printf("Nhap don gia:");
    scanf("%d", &dg);
    t=sl*dg;
    vat=0.1*t;
    printf("%s\n", sp);
    printf("Tien: %d\n", t);
    printf("Thue gia tri gia tang: %.1f\n", vat);
    return 0;*/
    /* HsT, HsL, HsH;
    float T, L, H, DTB;
    printf("Nhap diem Toan:");
    scanf("%f", &T);
    printf("Nhap he so Toan:");
    scanf("%d", &HsT);
    printf("Nhap diem Ly:");
    scanf("%f", &L);
    printf("Nhap he so Ly:");
    scanf("%d", &HsL);
    printf("Nhap diem Hoa:");
    scanf("%f", &H);
    printf("Nhap he so Hoa:");
    scanf("%d", &HsH);
    DTB=((T*HsT)+(L*HsL)+(H*HsH))/(HsT+HsL+HsH);
    printf("Diem trung binh: %.1f", DTB);
    return 0;*/
    /*float r, s, p;
    float pi=3.1415;
    printf("Nhap ban kinh:");
    scanf("%f", &r);
    s=pi*r*r;
    p=pi*2*r;
    printf("Dien tich: %.2f\n", s);
    printf("Chu vi:%.2f\n", p);
    return 0;*/
    int a, b, c, d, tong;
    printf("Nhap so thu nhat:");
    scanf("%d", &a);
    printf("Nhap so thu hai:");
    scanf("%d", &b);
    printf("Nhap so thu ba:");
    scanf("%d", &c);
    printf("Nhap so thu tu:");
    scanf("%d", &d);
    tong=a+b+c+d;
    if(tong<10){
        printf("So nut:%d\n",tong);
    }
    else{
        int t1=tong%10;
        int t2=tong/10;
        int t=t1+t2;
        printf("So nut:%d\n",t);
    }
    return 0;
    /*int a, b;
    printf("Nhap so a:");
    scanf("%d", &a);
    printf("Nhap so b:");
    scanf("%d", &b);
    if(a>b){
        printf("so lon nhat la: %d\n", a);
    }
    else{
        printf("so lon nhat la: %d\n", b);
    }
    return 0;*/
 }

 //Chap3.1
 #include<stdio.h>
int main()
{
	int a;
	printf("Nhap so a:");
	scanf("%d",&a);
	switch(a){
		case 1: printf("Mot"); break;
		case 2: printf("Hai"); break;
		case 3: printf("Ba"); break;
		case 4: printf("Bon"); break;
		case 5: printf("Nam"); break;
		case 6: printf("Sau"); break;
		case 7: printf("Bay"); break;
		case 8: printf("Tam"); break;
		case 9: printf("Chin"); break;
	}
	if(a>9){
		printf("Khong doc duoc");
	}
	return 0;
}

//Chap3.2

