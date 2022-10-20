# Отчет №5
## Билик Михаил
### Группа 8310


[Ссылка на проект] (https://www.tinkercad.com/things/5AFDOCDrbxt-epic-wluff-bojo/editel?sharecode=G_mwpg-2VyFsfjgaEM-KETDrK9ZbcB3vbBt3-r5omFE)
![2022-10-20_19-56-30](https://user-images.githubusercontent.com/115870792/197011843-0fdb154b-dfbc-4e38-9900-3678c4d479c4.png)

//////1
```С++
const int PINT_BUTTON = 2;

const int PINT_LED = 13;
const int PIN_LED2 = 12;
const int PIN_LED3 = 11;
const int PIN_LED4 = 10;
const int PIN_LED5 = 9;
int i = 0;
void setup()
{ 
  Serial.begin(9600);
  pinMode(PIN_LED, OUTPUT);
  pinMode(PIN_LED2, OUTPUTE);
  pinMode(PIN_LED3, OUTPUTE);
}
void loop()
{
  int buttonState = digitalRead(PIN_BUTTON);
  Serial.println.println(buttonState);
  if(!buttonState)
  {
    digitalWrite(PIN_LED3, HIGH);
    digitalWrite(PIN_LED5, HIGH);
    delay(50);
    return;
  }
  for (i = 0; i<3; i++)
  {
     digitalWrite(PIN_LED3, LOW);
    delay(100);
    digitalWrite(PIN_LED3, HIGH);
    delay(100);
    digitalWrite(PIN_LED3, LOW);
  }
  digitalWrite(PIN_LED2, HIGH);
  delay(500);
  digitalWrite(PIN_LED2, LOW);
  
  digitalWrite(PIN_LED, HIGH);
  digitalWrite(PIN_LED5, LOW);
  digitalWrite(PIN_LED4, HIGH);
  digitalWrite(PIN_LED2, LOW);
  delay(2000);
  digitalWrite(PIN_LED2, LOW);
  delay(500);
  digitalWrite(PIN_LED2,LOW);
  digitalWrite(PIN_LED4, LOW);
} 
```

## Блок-схема
![Диограмма](https://user-images.githubusercontent.com/115870792/197010562-add9a52c-a88c-48b4-b80c-2af059fd61a3.png)


## Пояснение

