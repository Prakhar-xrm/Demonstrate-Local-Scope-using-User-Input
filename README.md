#include<stdio.h>
int main()
{
  int num;
  scanf("%d",&num);
  printf("Main value: %d\n",num);
  void dummy()
  {
    int num= 100;
    printf("Function value: %d", num);
  }
  dummy();
  return 0;
}
