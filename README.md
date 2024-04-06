# COSPro2---3-4


## 3일차

#include <stdio.h>

int main(void) {
    // 정수형 변수들을 선언하고 초기화합니다.
    int num1 = 0xA7, num2 = 0x43;
    int num3 = 032, num4 = 24;
    
    // 각 변수들의 값을 출력합니다.
    printf("0xA7의 10진 정수값: %d\n", num1);
    printf("0x%X의 10진 정수값: %d\n", num1, num1);
    printf("0x43의 10진 정수값: %d\n", num2);
    printf("0x%X의 10진 정수값: %d\n", num2, num2);
    printf("032의 10진 정수값: %d\n", num3);
    printf("0%o의 10진 정수값: %d\n", num3, num3);
    printf("24의 10진 정수값: %d\n", num4);
    printf("0%o의 10진 정수값: %d\n", num4, num4);
    
    return 0;
}
/*
#include <stdio.h>

int main(void) {
    int num1, num2, result = 0;
    
    // 사용자로부터 두 개의 정수를 입력 받습니다.
    printf("두 개의 정수를 입력해 주세요: ");
    scanf("%d", &num1);
    scanf("%d", &num2);
    
    // 두 정수의 합을 계산합니다.
    result = num1 + num2;
    printf("두 수의 합은 %d입니다.\n", result);
    
    // 두 정수의 차를 계산하고 출력합니다.
    result = num1 - num2;
    printf("%d - %d = %d\n", num1, num2, result);
    
    // 두 정수의 곱을 계산하고 출력합니다.
    result = num1 * num2;
    printf("%d * %d = %d\n", num1, num2, result);
    
    // 두 정수의 나눗셈을 계산하고 출력합니다. (정수 나눗셈)
    result = num1 / num2;
    printf("%d / %d = %d\n", num1, num2, result);
    
    return 0;
}
*/


## 4일차


#include <stdio.h>

int main(void) {
    int num1 = 3;
    int num2 = 4;
    double divResult; // 변수 선언에 콜론(:) 대신 세미콜론(;) 사용

    // 변수 num1과 num2를 double로 캐스트하여 나눗셈을 진행
    divResult = (double)num1 / num2;

    printf("나눗셈 결과: %f\n", divResult); // printf 문자열에서 Wn -> \n으로 수정

    return 0;
}
/*
int main(void) {
    char ch1 = 'A', ch2 = 'A'; // ch2를 'A'로 수정
    char ch3 = 'Z', ch4 = 'Z'; // 등호 추가 및 ch4를 'Z'로 수정
    
    // 각 변수의 값과 문자를 출력합니다.
    printf("%c %d \n", ch1, ch1);
    printf("%c %d \n", ch2, ch2);
    printf("%c %d \n", ch3, ch3);
    printf("%c %d \n", ch4, ch4);
    
    return 0;
}
/*
