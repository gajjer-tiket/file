# Отчет №5
## Билик Михаил
### Группа 8310


[Ссылка на проект.](https://www.tinkercad.com/things/lQFXhApmgRb-neat-duup-albar/editel?sharecode=KEmOuWFmRSa9RF8dlvIPBPZ8co_H_y2M2J33ZksteYQ)

![1](https://user-images.githubusercontent.com/106704479/193897719-4c1dd533-2833-404c-ac8b-276448080759.jpg)
![2](https://user-images.githubusercontent.com/106704479/193897715-20efb36d-0d07-4f91-b536-fea0845b13d4.jpg)
![3](https://user-images.githubusercontent.com/106704479/193897710-2f79733f-9d65-4a3a-96aa-1c1a571e4f14.jpg)


//////1
```С++
int led1 = 2;
int led2 = 3;
int led3 = 4;
void setup()
{ 
pinMode(led1, OUTPUT); 
pinMode(led2, OUTPUT);
pinMode(led3, OUTPUT);
} 
void loop()
{ 
digitalWrite(led1, HIGH);
delay(9000);
digitalWrite(led2, HIGH);
delay(4000);
digitalWrite(led2, LOW);
digitalWrite(led1, LOW);
digitalWrite(led3, HIGH);
delay(4000);
digitalWrite(led3, LOW);
digitalWrite(led2, HIGH);
delay(4000);
digitalWrite(led2, LOW);
digitalWrite(led1, HIGH);
delay(9000);
digitalWrite(led2, HIGH);
delay(4000);
digitalWrite(led2, LOW);
digitalWrite(led1, LOW);
digitalWrite(led3, HIGH);
delay(4000);
digitalWrite(led3, LOW);
digitalWrite(led2, HIGH);
delay(4000);
}
```

## Блок-схема
![Диограмма](https://user-images.githubusercontent.com/106704479/193923224-e884a214-7436-4b28-a09f-7624275c065e.jpg)

//////2
```С++
int led1 = 2; 
int led2 = 3; 
void setup()
{ 
pinMode(led1, OUTPUT);
pinMode(led2, OUTPUT);
} 
void loop()
{ digitalWrite(led1, HIGH);
delay(4000);
digitalWrite(led1, LOW);
delay(1000); 
digitalWrite(led2, HIGH); delay(6000);
digitalWrite(led2, LOW);
delay(1000);
}
```

//////3
```С++
int led1 = 2;
int led2 = 3;
void setup() 
{ 
pinMode(led1, OUTPUT);
pinMode(led2, OUTPUT);
} 
void loop() 
{ 
digitalWrite(led2, HIGH);
digitalWrite(led1, HIGH);
delay(10000);
digitalWrite(led1, LOW);
delay(4000); 
}
```

## Пояснение
