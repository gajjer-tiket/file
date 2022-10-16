# Отчет №5
## Билик Михаил
### Группа 8310


[Ссылка на проект.](https://www.tinkercad.com/things/lQFXhApmgRb-neat-duup-albar/editel?sharecode=KEmOuWFmRSa9RF8dlvIPBPZ8co_H_y2M2J33ZksteYQ)

![1practic](https://user-images.githubusercontent.com/106704479/195206070-5ec7d0fe-2cd0-4ea4-bda7-e6b46f97fade.jpg)
![2practic](https://user-images.githubusercontent.com/106704479/195206064-ce495b57-23ee-4264-9df5-e69bdd5a3b57.jpg)


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
