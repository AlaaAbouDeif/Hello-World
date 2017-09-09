# Hello-World
//Example_12_LCD_16x2 
#include <LiquidCrystal.h> 
LiquidCrystal lcd(0x27,16,2); 
const byte dataPin  = 2;    // SR Data from Arduino pin 10
const byte clockPin = 3;    // SR Clock from Arduino pin 11 
void setup() 
 { 

  lcd.begin(16, 2); 
  lcd.print(a" ^_^ Welcome ^_^");
  delay(3000);
  
   
lcd.begin(16, 2); 
  lcd.print("!#$%()+,-.;=[]^");
  delay(3000);
   
lcd.begin(16, 2); 
  lcd.print("     01159707095");
  delay(3000);
    
lcd.begin(16, 2); 
  lcd.print("    01159707095");
  delay(200);
    
lcd.begin(16, 2); 
  lcd.print("   01159707095");
  delay(200);
    
lcd.begin(16, 2); 
  lcd.print("  01159707095");
  delay(200);
  

lcd.begin(16, 2); 
  lcd.print(" 01159707095");
  delay(200);
 
 
lcd.begin(16, 2); 
  lcd.print("9707095");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print("707095");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print("07095");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print("7095");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print("095");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print("095");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print(" 95");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print("5");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print("    ");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print(" 01159707095");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print("             ");
  delay(200);
  
lcd.begin(16, 2); 
  lcd.print(" 01159707095");
  delay(200);
   
}

void loop() 
{
  lcd.setCursor(0, 1); 
  lcd.print(millis()/1000); 
} 
