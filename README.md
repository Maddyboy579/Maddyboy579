- š Hi, Iām @Maddyboy579
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Maddyboy579/Maddyboy579 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>;
#include<math.h>;
float main()
{
    float a,b,c;
    printf("Enter first number\n");
    scanf("%f",&a);
    printf("Enter second number\n");
    scanf("%f",&b);
    printf("press 1 for addition\n press 2 for subtraction\n press 3 for multiplication\n press 4 for division\n");
    scanf("%f",&c);
    if (c==1){
    printf("%0.2f",a+b); }
    if(c==2){
        printf("%0.2f",a-b);}
    if(c==3){
        printf("%0.2f",a*b);} 
    if(c==4){
        printf("%0.2f",a/b);}
}
