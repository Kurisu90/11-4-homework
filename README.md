# 11-4-homework
代码：
//第一题

#include<stdio.h>
int main(void) {
double k1,k2,k3;
double sum = 0;
for (k1 = 1; k1< 101; k1++) {
sum += k1;
}

for (k2 = 1; k1 < 50; k2++) {
sum += k2 * k2;
}

for (k3 = 1; k3 < 10; k3++) {
sum += (1 / k3);
}

printf("result:%lf", sum);
}

运行结果：

result:5052.828968

C:\Users\86188\source\repos\Project2\x64\Debug\Project2.exe (进程 11964)已退出，代码为 0。

按任意键关闭此窗口. . .













//第二题

#include<stdio.h>

int main(void) {

int M;

int a, b, c;

for (M = 100; M< 1000; M++) {

a = M /100;

b = (M/10)-a*10;

c = M % 10;

if (M == a * a * a + b * b * b + c * c * c) {

printf("%d \t", M);

}

}

}

运行结果：

153     370     371     407

C:\Users\86188\source\repos\Project1\x64\Debug\Project1.exe (进程 9324)已退出，代码为 0。

按任意键关闭此窗口. . .



//第4题

#include<stdio.h>

int main() {

int n;

printf("Enter a number.");

scanf_s("%d", &n);

int n1 = n;

int op_n = 0;

int gw;

while (n != 0) {

gw = n % 10;

op_n = op_n * 10 + gw;

n = n / 10;

}

if (n1 == op_n) {

printf("Yes.");

}

else {

printf("No.");

}

}



运行结果：

Enter a number.12321

Yes.

C:\Users\86188\source\repos\Project1\x64\Debug\Project1.exe (进程 14924)已退出，代码为 0。

按任意键关闭此窗口. . .



//第四题

#include<stdio.h>

int main(void) {

int n = 20;

unsigned long long int result=1;

for (; n>1; n--) {

result =result*n;



}

printf("result=%llu", result);

}



运行结果：

result=2432902008176640000

C:\Users\86188\source\repos\Project1\x64\Debug\Project1.exe (进程 1184)已退出，代码为 0。

按任意键关闭此窗口. . .



