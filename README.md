//  Assignment 1: FizzBuzzz
//  main.c
//  FizzBuzz
//
//  Created by Rosalyn Kingsmill on 2016-03-28.
//  Copyright © 2016 Rosalyn Kingsmill. All rights reserved.
//

#include <stdio.h>

int main(int argc, const char * argv[]) {
    
  
   
    
//Main loop
    
    for (int i = 1; i <101; i++) {
        
    
//If a multiple of 3
        
        if ((i % 3 == 0) && (i % 5 != 0)) {
            
            printf("Fizz ");
            
//If a multiple of 5
            
        } else {
            
            if ((i % 3 != 0) && (i % 5 == 0)) {
                
                printf("Buzz ");
                
            } else {
                
//If a multiple of 3 and 5
                    
            } if ((i % 3 == 0) && (i % 5 == 0)) {
                printf ("FizzBuzz ");
                
//If neither a multiple of 3 or 5
                
            } else {
                
            } if ((i % 3 != 0) && (i % 5 !=0)) {
                
                    printf("%d ", i);
                    
            }
        }
    }
    

    
    return 0;
}
