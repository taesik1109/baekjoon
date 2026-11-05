# baekjoon
This is an auto push repository for Baekjoon Online Judge created with [BaekjoonHub](https://github.com/BaekjoonHub/BaekjoonHub).
# 20261105

#include <stdio.h>
#include <stdbool.h>
#include <stdlib.h>
#include <string.h> 


char* solution(const char* my_string, int k) {
    
    int len = strlen(my_string); 
    char* answer = (char*)malloc((len * k + 1) * sizeof(char));
    
    for(int i = 0; i < k; i++){
        for (int j = 0; j < len; j++) {
        answer[len * i + j] = my_string[j];
    }
    }
    answer[len * k] = '\0';
    return answer;
   
}
