# anagram
```
#include <stdio.h>
#include <string.h>
int main(){
        int i,j,count;
        count=0;
        char str[10];
        char rev[10];
        strcpy(str, "racecar");
        printf("%s\n",str);
        for (i=strlen(str)-1;i>=0;i--){
                rev[count]= str[i];
                printf("%c",rev[count]);
                count=count+1;
        }
printf("\n");
        if (strcmp ( rev, str )== 0) {
                printf("The word is an anagram\n");
        }
        else{
                printf("The words is not an anagram\n");
        }
printf("%d\n",count);
return 0;
}
```
