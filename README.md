#include<stdio.h>
void main(){
    int total1,total2;
    printf("Enter first array size  ");
    scanf("%d",&total1);
    printf("Enter second array size");
    scanf("%d",&total2);
    int number1[total1],number2[total2];
    if(total1==total2){
        printf("Enter first array values\n");
        for(int i =0;i<total1;i++){
            printf("Enter %d  value ",i+1);
            scanf("%d",&number1[i]);
        }printf("Enter second array values\n");
        for(int i=0;i<total2;i++){
            printf("Enter %d value ",i+1);
            scanf("%d",&number2[i]);
        }for(int i = 0;i<total1;i++){
            if(number1[i]!=number2[i]){
               printf("both array is not same value consider");
                break;
              
            }else if (total2==(i+1)) {
                printf("both array is same");
            }}
       
    }else {
        printf("array size is not same so array is also not same ");
    }
    
    
}  
              
            
      
        
       
            
             
            
            
