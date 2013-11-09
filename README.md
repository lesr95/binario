binario
=======

#include &lt;stdio.h> 
#include &lt;stdlib.h>    
int main(int argc, char *argv[])  {     
int num=0,banderas=1;   
do{      
printf("dame un numero\n");   
scanf("%d",&amp;num);fflush(stdin); 
if(num==0)      
while(num>2){       
printf("%d\t",num%2);
num=(num/2);
}                     
printf("%d\n",num);
system("PAUSE");	
return 0; 
}
