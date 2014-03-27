# Project Title
Hologram

## Authors
- GXG Jičín:

Main author:
- Ing. arch. Radek Jiránek https://github.com/archikultura
 
Other authors:
- Bc. Martin Vancl https://github.com/tuxmartin
- Mgr. Jiří Komárek

## Description
Insert a description containing about 100 to 150 words, including your motivation and the meaning behind your idea and execution. The Judges will be keen to know how your idea pushes the boundaries of code and technology. 

## Example Code
NOTE: Wrap your code blocks or any code citation by using ``` like the example below.
```
byte ledPin = 7;
int interval = 500; // miliSeconds

void setup() {                
  Serial.begin(9600);
  pinMode(ledPin, OUTPUT);     
}

void loop() {  
  if (Serial.available() > 0) {
    interval = Serial.read();
  }
  blink(interval);
}

void blink(int miliSeconds) {
  digitalWrite(ledPin, HIGH);
  delay(miliSeconds * 1000);
  digitalWrite(ledPin, LOW);
  delay(miliSeconds * 1000);  
}

```
## Links to External Libraries
[APIs - google-api-java-client](https://code.google.com/p/google-api-java-client/wiki/APIs "APIs - google-api-java-client")

## Images & Videos

![Example Image](project_images/cover.jpg?raw=true "Example Image")
