#include <stdio.h>
//세균 수 구하기 문제
int main()
{
    // 초기 세균 수
    int bacteria = 10;

    // 1시간에 4배씩 증가
    for (int i = 0; i < 7; i++) {
        bacteria *= 4;
    }

    // 결과 출력
    printf("7시간 후 세균의 수: %d\n", bacteria);

    return 0;
    }
    
    
    #include <stdio.h>
//종이 접는 문제
int main()
{
    // 초기값 설정
    double area = 1.0;
    int count = 0;

    // 종이를 계속해서 반으로 접음
    while (area > 0.01) {
        area /= 2.0;
        count++;
    }

    // 결과 출력
    printf("%d번 접으면 종이의 면적이 원래의 1/100이 됩니다.\n", count);

    return 0;
}
