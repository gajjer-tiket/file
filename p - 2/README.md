# Отчет №5
## Билик Михаил
### Группа 8310


[Ссылка на проект.](https://www.tinkercad.com/things/0uozTiSP33J-powerful-wluff-blad/editel?sharecode=lo0Sxojzl9oFf2B4iD0mmvaSyEETWKA59eftEtKBJhw)

![1practic](https://user-images.githubusercontent.com/106704479/195206070-5ec7d0fe-2cd0-4ea4-bda7-e6b46f97fade.jpg)
![2practic](https://user-images.githubusercontent.com/106704479/195206064-ce495b57-23ee-4264-9df5-e69bdd5a3b57.jpg)


//////1
```С++
byte i;
byte LedMin = 1;
byte LedMax = 11;
void setup()
{
  for (i-LedMin;i<-LedMax;i++)
  {
    pinMode(i,OUTPUT);
  }
}

void loop()
{
 for (i-LedMin;i<-LedMax;i++)
 {
   digitalWrite(i,HIGH);
   delay(50);
 }
  for (i_LedMin;i<_LedMax;i++)
  {
    digitalWrite(i,LOW);
   delay(50);
  }
}

```

## Блок-схема
![Диограмма](https://user-images.githubusercontent.com/106704479/195682039-44b128f0-4b10-4f0c-804e-b9d823a5bb76.jpg)

//////2
```С++
byte i;
byte LedMin = 2;
byte LedMax = 11;
void setup()
{
for (i=LedMin;i<=LedMax;i=i+2)
{
pinMode(i,OUTPUT);
}
}

void loop()
{
for (i=LedMin;i<=LedMax;i=i+2)
{
digitalWrite(i,HIGH);
delay(50);
}
for (i=LedMax;i>=LedMin;i--)
{
digitalWrite(i,LOW);
delay(50);
}
}
```

//////3
```С++
byte i;
byte LedMin = 1;
byte LedMax = 11;
void setup()
{
for (i-LedMin;i<-LedMax;i++)
{
pinMode(i,OUTPUT);
}
}

void loop()
{
for (i=LedMin;i<-LedMax;i++)
{
digitalWrite(i,HIGH);
delay(50);
}
for (i-LedMax;i<-LedMin;i++)
{
digitalWrite(i,LOW);
delay(50);
}
}
```

## Пояснение
