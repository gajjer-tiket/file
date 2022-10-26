
# Отчет №5
## Билик Михаил
### Группа 8310


[Ссылка на проект.](https://www.tinkercad.com/things/lQFXhApmgRb-neat-duup-albar/editel?sharecode=KEmOuWFmRSa9RF8dlvIPBPZ8co_H_y2M2J33ZksteYQ)

![изображение](https://user-images.githubusercontent.com/115870792/198043119-b4389a1c-d22d-4036-a82a-ea96a987b528.png)


```
С++
//////1

#include<LiquidCrystal.h> 
#include<Keypad.h>  
 
int a; 
LiquidCrystal lcd(12, 11, 5, 4, 3, 2); 
 
const byte ROWS = 3;  
const byte COLS = 3;  
char hexaKeys[ROWS][COLS] =  
{ 
{'1','4','7',},  
{'2','5','8',}, 
{'3','6','9',}, 
 
}; 
byte rowPins[ROWS] = {8, 7, 6 };  
byte colPins[COLS] = {13, 10, 9 };  
 
Keypad customKeypad = Keypad( makeKeymap(hexaKeys), rowPins, colPins, ROWS, COLS);  
 
void setup() { 
   
  lcd.begin(16, 23); 
 
 // lcd.print("hello, world!"); 
} 
 
void loop() { 
  char customKey = customKeypad.getKey();  
   
  switch (customKey){ 
case '1': 
    lcd.clear(); 
    lcd.setCursor(0, 0); 
  lcd.print('1');  
    a=1; 
  break;  
case '2': 
    lcd.clear(); 
    lcd.setCursor(0, 0); 
  lcd.print('2'); 
    a=2; 
  break;  
case '3':  
    lcd.clear(); 
    lcd.setCursor(0, 0); 
  lcd.print('3'); 
    a=3; 
  break;  
case '4':  
    lcd.clear(); 
    lcd.setCursor(0, 0); 
  lcd.print('4'); 
    a=4; 
  break;  
case '5':  
    lcd.clear(); 
    lcd.setCursor(0, 0); 
  lcd.print('5');  
    a=5; 
  break;  
case '6':  
    lcd.clear(); 
    lcd.setCursor(0, 0); 
  lcd.print('6'); 
    a=6; 
  break;  
case '7':  
    lcd.clear(); 
    lcd.setCursor(0, 0); 
  lcd.print('7'); 
    a=7; 
  break;  
case '8':  
    lcd.clear(); 
    lcd.setCursor(0, 0); 
  lcd.print('8');  
    a=8; 
  break;  
case '9':  
    lcd.clear(); 
    lcd.setCursor(0, 0); 
  lcd.print('9');  
    a=9; 
 break; 
  } 
  if ( a%2==0) 
  { 
  lcd.setCursor(0, 1); 
     lcd.print("Chetnoe"); 
  } 
  else 
  { 
  lcd.setCursor(0, 1); 
    lcd.print("Ne Chetnoe");    
  } 
}

```

## Пояснение
