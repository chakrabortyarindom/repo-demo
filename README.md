
//"piramid left half structer"//
#include<stdio.h>
int main(){
    int i,j,k,n;
    printf("enter the numbers of rowa");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=n-i;j++){
            printf(" ");
        }
        for(k=1;k<=i;k++){
            printf("* ");
        }
        printf("\n");
    }
    return 0;
}

//"piramid structer "//
#include<stdio.h>
int main(){
    int i,j,k,n;
    printf("enter the numbers of rowa");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=n-i;j++){
            printf(" ");
        }
        for(k=1;k<=2*i-1;k++){
            printf("*");
        }
        printf("\n");
    }
    return 0;
}
//"diamond structer "//
#include<stdio.h>
int main(){
    int i,j,k,n;
    printf("enter the numbers you want");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=n-i;j++){
            printf(" ");
        }
        for(k=1;k<=2*i-1;k++){
            printf("*");
        }

        printf("\n");
    }
    for(i=1;i<n;i++){
        for(j=1;j<=i;j++){
            printf(" ");
        }
        for(k=1; k<=2*(n-i)-1;k++){
            printf("*");
    }
    printf("\n");
}
}
 
//"sum using for loop"//
#include<stdio.h>
int main(){
    int i,n,sum;
    sum=0;
    printf("enter the numbers you want");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        sum +=i*i;
        printf("%d",sum);


    }
    
}

//"fibonacci 0 1 1"//
#include<stdio.h>
int main(){
    int i,a,b,c,n;
    a=0;
    b=1;
    printf("enter the numbers you want");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        printf("%d ",a);
        c=a+b;
        a=b;
        b=c;
  }
}
//"fibonacci series 2 3 6"//
#include<stdio.h>
int main(){
    int a,b,c,n,i;
    a=2;b=3;
    printf("enter the numbers you want");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        printf("%d",a);
        c=a*b;
        a=b;
        b=c;
    }
}


//"ct 02 question 2"//
#include<stdio.h>
    int main(){
        int num,b;
        num=23,b=0;
        while(num!=0){
            b+=num%10;
            num=num/10;
        }
        printf("result=%d",b);
    }



//"hollow diamond  "//
#include<stdio.h>
int main(){
    int i,j,k,n;
    printf("enter the numbers you want");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=n-i;j++){
            printf(" ");
        }
        for(k=1;k<=2*i-1;k++){
            if(k==1||k==2*i-1){
                printf("*");
            }
            else{
                printf(" ");
            }
        }
        printf("\n");
    }
    for(i=1;i<n;i++){
        for(k=1;k<=i;k++){
            printf(" ");
        }
        for(j=1;j<=2*(n-i)-1;j++){
             if(j==1||j==2*(n-i)-1){
                printf("*");
            }
            else{
                printf(" ");
            }
        }
        printf("\n");
}
    }
//" hour glass "//
    #include<stdio.h>
    int main(){
        int i,j,k,n;
        printf(" enter the number of rows");
        scanf("%d",&n);
        for(i=1;i<=n;i++){
            for(k=1;k<i;k++){
                printf(" ");
            }
            for(j=i;j<=n;j++){
                printf("* ");
            }
            printf("\n");
        }
        for(i=1;i<=n;i++){
            for(j=1;j<=n-i;j++){
                printf(" ");
            }
            for(k=1;k<=i;k++){
                printf("* ");
            }
            printf("\n");
        }
    }


//" downward piramid structer "//
     #include<stdio.h>
    int main(){
        int i,j,k,n;
        printf("enter the numbers you want");
        scanf("%d",&n);
        for(i=1;i<=n;i++){
            for(j=1;j<i;j++){
                printf(" ");
            }
            for(k=i;k<=n;k++){
                printf("* ");
            }
            printf("\n");
        }
    }
    

//"heart shape structer"//
    #include<stdio.h>
    int main(){
        int i,j,k,n;
        printf("enter the number of rows");
        scanf("%d",&n);
        for(i=1;i<=n;i++){
            for(j=1;j<=n-i;j++){
                printf(" ");
            }
            for(k=1;k<=i;k++){
                printf("* ");
            }
            for(j=1;j<=(n-i);j++){
                printf("  ");
            }
            for(k=1;k<=i;k++){
                printf("* ");
            }
            printf("\n");
        }
        for(i=1;i<=2*n-1;i++){
                for(j=1;j<=i;j++){
                    printf(" ");
                }
                for(k=1;k<=2*n-i;k++){
                    printf("* ");
                }
                printf("\n");
            }
        
            
    }
//"fibonacci series + swap"//
    #include<stdio.h>
    int main(){
        int i,n,a,b,c;
        printf("enter the numbers you want");
        scanf("%d",&n);
        a=0;b=1;
        for(i=1;i<=n;i++){
             printf("%d" ,a);
            c=a+b;
            a=b;
            b=c;
           

        }
    }



   



#include<stdio.h>
int main(){
    int a[10],i;
    for(i=0;i<10;i++){
        printf("enetr the number of index %d",i);
        scanf("%d",&a[i]);
    }
    printf("array elements are as follows");
    for(i=0;i<10;i++){
        printf("%d",a[i]);
    }
}

//" array reverse"//
#include<stdio.h>
int main(){
    int i;
     int a[10] = {20 , 19 , 18 , 17 , 16 , 15 , 14 , 13 , 12 , 11};
     for(i=0;i<9;i++){
        printf("%d",a[i]);
     }
     printf("\n");
     for(i=9;i>=0;i--){
        printf("%d",a[i]);
        }
    }
//"armstrong number"//
#include <stdio.h>
int main()
{
    int num, a[1], result = 0, rem, enterednumber;
    printf("enter a three digit number");
    scanf("%d", &a[0]);
    enterednumber = a[0];
    while (a[0] > 0)
    {
        rem = a[0] % 10;
        num = rem * rem * rem;
        a[0] = a[0] / 10;
        result = result + num;
    }
    if (result == enterednumber)
    {
        printf("the entered number is an armstrong number");
    }
    else
    {
        printf("the entered number is not an armstrong number");
    }
}

//" array multiplication"//
#include<stdio.h>
int main(){
    int  a[3][3],b[3][2],i,j,r[3][2],k;
    for(i=0;i<3;i++){
        for(j=0;j<3;j++){
            scanf("%d",&a[i][j]);
            printf("%d\t",a[i][j]);
        }
        printf("\n");
    }
    printf("\n");
     for(i=0;i<3;i++){
        for(j=0;j<2;j++){
            scanf("%d",&b[i][j]);
            printf("%d\t",b[i][j]);
        }
        printf("\n");
    }
    printf("\n");
    
    for(i=0;i<3;i++){
        for(j=0;j<2;j++){
             r[i][j]=0;
            for(k=0;k<3;k++){ 
                r[i][j] += a[i][k] * b[k][j];
           
            }
            printf("%d\t",r[i][j]);
        }
        printf("\n");
}

printf("\n");
     
}

//"palindrome number"//
#include<stdio.h>
int main(){
    int i,n,pelindrome;
    char a[10];
    printf("enter the numbers you want");
    scanf("%d",&n);
    printf("enter %d charecters",n);
    for(i=0;i<n;i++){
        scanf(" %c",&a[i]);
    }  
    for(i=0;i<n/2;i++){
        if(a[i] == a[n-1-i]){
            pelindrome =1;
            break;
        }
        else{
            pelindrome=0;
        }
    
    }
    if(pelindrome == 1){
        printf("the entered charecters form a pelindrome");
    }
    else{
        printf("the entered charecters dont form a pelindrome");
    
}
}

#include<stdio.h>
int main(){
    int i,n,sum=0,result;
     int a[10];
    scanf("%d",&n);
    for(i=0;i<n;i++){
        scanf("%d",&a[i]);
        sum=sum+a[i];
    }
    result= abs(sum);
    printf("%d",result);

}


//" cgpa calculation program"//
#include <stdio.h>

int main(){
    int marks[8], creditsum = 0, i, sum_total = 0;
    float credit[8], cgpa;
    
    for(i = 0; i < 8; i++) {
        int sum = 0;
        printf("Enter all subjects marks : \n");
        scanf("%d", &marks[i]);
        printf("Enter credit hours of all subjects : \n");
        scanf("%f", &credit[i]);
        creditsum += credit[i];
        if(marks[i] >= 80) {
            sum = sum + 4;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } else if (marks[i] >= 75 && marks[i] <= 79) {
            sum = sum + 3.75;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } else if (marks[i] >= 70 && marks[i] <= 74) {
            sum = sum + 3.5;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } else if (marks[i] >= 65 && marks[i] <= 69) {
            sum = sum + 3.25;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } else if (marks[i] >= 60 && marks[i] <= 64) {
            sum = sum + 3.0;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } else if (marks[i] >= 55 && marks[i] <= 59) {
            sum = sum + 2.75;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } else if (marks[i] >= 50 && marks[i] <= 54) {
            sum = sum + 2.5;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } else if (marks[i] >= 45 && marks[i] <= 49) {
            sum = sum + 2.25;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } else if (marks[i] >= 40 && marks[i] <= 45) {
            sum = sum + 2;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } else {
            sum = sum + 0;
            sum = sum *credit[i];
            sum_total = sum_total + sum;
        } 
    }
    cgpa = sum_total / creditsum;
    printf("%f is your cgpa", cgpa);
    
    return 0;
}

//" prime number using isprime function"//
#include<stdio.h>
#include<stdbool.h>
bool isprime(int num){
    int count=0,i;
    for(i=2;i<num;i++){
        if(num%i==0){
            count++;
            break;
        }
    }
    if(count==0){
        return 1;
    }
    else{
        return 0;
    }

}
int main(){
    int num;
    printf("enter a positive number");
    scanf("%d",&num);
    if(isprime(num)){
        printf("boolean number");
    }
    else{
        printf("not a boolean number");
    }
   
}

//"pascals triangle"//
#include<stdio.h>
int main(){
    int i,j,n,k,value;
    printf("enter the number of rows");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        value=1;
        for(j=1;j<=n-i;j++){
            printf(" ");
        }
        for(k=1;k<=i;k++){
            if(k==1||k==i){
                printf("1 ");
            }
            else{
                
                 value=value*(i-k+1)/(k-1);
                printf("%d ",value);
                
            }
        }
        printf("\n");
       
        
    }
}


//" gcd using function"//
#include<stdio.h>
int gcd(int a,int b){
    int i,gcd;
    for(i=1;i<=a && i<=b;i++){
        if(a%i==0 && b%i==0){
            gcd=i;

        }
    }
    return gcd;
}
int main(){
    int a,b;
    printf("enter two numbers");
    scanf("%d %d",&a,&b);
    printf( "%d" ,gcd(a,b));


}

//" transpose"//
#include<stdio.h>
int main(){
    int a[3][2],i,j;
    for(i=0;i<3;i++){
        for(j=0;j<2;j++){
            scanf("%d",&a[i][j]);
            printf("%d\t",a[i][j]);
        }
        printf("\n");
    }    
    for(j=0;j<2;j++){
        for(i=0;i<3;i++){
            printf("%d\t",a[i][j]);
        }
        printf("\n");
    }
    
}
