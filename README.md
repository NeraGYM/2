//led에 연결된 핀을 정의한다. 저항은 접근성이 편한 220옴 사용

int red_1=13;
int orange_1=12;
int green_1=11;
int red_2=10;
int orange_2=9;
int green_2=8;
int red_3=7;
int orange_3=6;
int green_3=5;
int red_4=4;
int orange_4=3;
int green_4=2;


void direction_1_green(void)//1번의 녹색 led가 켜질경우
{ 
  digitalWrite(red_1,LOW); 
  digitalWrite(orange_1,LOW); 
  digitalWrite(green_1,HIGH); 
  digitalWrite(red_2,HIGH); 
  digitalWrite(orange_2,LOW); 
  digitalWrite(green_2,LOW); 
  digitalWrite(red_3,HIGH); 
  digitalWrite(orange_3,LOW); 
  digitalWrite(green_3,LOW); 
  digitalWrite(red_4,HIGH); 
  digitalWrite(orange_4,LOW); 
  digitalWrite(green_4,LOW); 
}


void direction_2_orange(void)//orange LED of direction 2 will turn ON 
{
  digitalWrite(red_1,HIGH); 
  digitalWrite(orange_1,LOW); 
  digitalWrite(green_1,LOW); 
  digitalWrite(red_2,LOW); 
  digitalWrite(orange_2,HIGH); 
  digitalWrite(green_2,LOW); 
  digitalWrite(red_3,HIGH); 
  digitalWrite(orange_3,LOW); 
  digitalWrite(green_3,LOW); 
  digitalWrite(red_4,HIGH); 
  digitalWrite(orange_4,LOW); 
  digitalWrite(green_4,LOW); 
}


void direction_2_green(void)//green LED of direction 2 will turn ON 
{ 
  digitalWrite(red_1,HIGH); 
  digitalWrite(orange_1,LOW); 
  digitalWrite(green_1,LOW); 
  digitalWrite(red_2,LOW); 
  digitalWrite(orange_2,LOW); 
  digitalWrite(green_2,HIGH); 
  digitalWrite(red_3,HIGH); 
  digitalWrite(orange_3,LOW); 
  digitalWrite(green_3,LOW); 
  digitalWrite(red_4,HIGH); 
  digitalWrite(orange_4,LOW); 
  digitalWrite(green_4,LOW); 
}



void direction_3_orange(void)//orange LED of direction 3 will turn ON 
{ 
  digitalWrite(red_1,HIGH); 
  digitalWrite(orange_1,LOW); 
  digitalWrite(green_1,LOW); 
  digitalWrite(red_2,HIGH); 
  digitalWrite(orange_2,LOW); 
  digitalWrite(green_2,LOW); 
  digitalWrite(red_3,LOW); 
  digitalWrite(orange_3,HIGH); 
  digitalWrite(green_3,LOW); 
  digitalWrite(red_4,HIGH); 
  digitalWrite(orange_4,LOW); 
  digitalWrite(green_4,LOW); 
}



