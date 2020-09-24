# malloc-for-3D-array

purpose of this code: 삼차원 배열을 동적할당해주고, 두개의 삼차원 배열을 더해 그 값을 출력한뒤, 할당되었던 삼차원 배열을 다시 해제해준다. 

사용된 함수:
double ***mem_alloc_3D_double(int width,int length,int height) // 삼차원 배열(삼중포인터)을 동적할당해주는 함수 
parameters: 할당할 삼차원 배열의 넓이, 높이, 너비를 각각 int형으로 받아온다. 
변수: double ***data; // 메모리가 동적할당될 삼중 포인터 변수 data
        int i,j; //for문을 위한 변수 
return값: 할당된 삼중포인터 data를 return한다.

int memoryRelease(double*** data,int width,int length,int height) // 동적할당된 메모리를 해제해주는 함수
parameters: 해제할 삼차원 배열의 넓이, 높이, 너비를 각각 int형으로 받아온다. 
변수: int i,j; //for문을 위한 변수

void addition_3D(double*** a, double*** b) // 2개의 삼차원 배열 덧셈을 해주는 함수
parameter: 덧셈을 할 두개의 삼중 포인터를 받아온다. 
변수: double data; //a,b배열의 값을 더해서 저장할 변수 
        int i,j,k; //for loop를 돌리는데 필요한 정수변수 




