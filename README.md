# Average-marks-of-three-subjects-
#include <stdio.h>

int main(){
    float physics,chemistry,maths,average;
   printf("enter marks in physics : ");
   scanf("%f",&physics);
    printf("enter marks in chemistry : ");
   scanf("%f",&chemistry);
    printf("enter marks in maths : ");
   scanf("%f",&maths);
   printf("average : %f", average=(physics+chemistry+maths)/3);
   return 0;
}
