#include <stdio.h>
#include <string.h>
#include <ctype.h>
#define MAX_LENGTH 13


void password(char str[]) {
    int upper=0,lower=0,digit=0,special = 0;
    int len = strlen(str);


    for(int i=0;str[i]!='\0';i++) {
        if(isupper(str[i])) {
              upper = 1;
              }
          else if(islower(str[i])) {
              lower = 1;
              }
          else if(isdigit(str[i])) {
              digit = 1;
              }
          else {
              special = 1;
            }

        }

    if( len < MAX_LENGTH ) {
        printf("Weak passwword");
        }
        else if (len >= MAX_LENGTH && upper && lower && digit && special ) {
                printf("Your Password is strong...");
              }
                    else {
                          printf("Need to add some digits,special character,upper & lower case letters too...");
}
}

  

int main() {
  char str[101];
  fgets(str,sizeof(str),stdin);
  str[strcspn(str,"\n")]='\0';
  password(str);
  return 0;
}
