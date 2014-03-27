# Hologram

## Authors
- GXG Jičín:

Main author:
- Ing. arch. Radek Jiránek https://github.com/archikultura
 
Other authors:
- Bc. Martin Vancl https://github.com/tuxmartin
- Mgr. Jiří Komárek

## Description
Insert a description containing about 100 to 150 words, including your motivation and the meaning behind your idea and execution. The Judges will be keen to know how your idea pushes the boundaries of code and technology. 

Object of this project is vizualization of defined object and not just virtually but even in real world.The creators are suspicious that, thanks to LED technologie installed inside of a board glass without visible contacts will be illusion of virtual object almost perfect. The propossed way of this image “hologram” will be very close to naturale sence how we know it in the world surrouding us.

The impression of the hologram is created with help of lightning discharge on the display-glass desk.Illusion is created by one desk rottating around one axis.The assumption is, that this scheme will still be free in another two axisa so will be possible turn with the object and look at it from all the sides.

Doesnt need to be proved In pressent stage of the project, that hypothesis brought forward is working but to construct a simple  functional prototype and by a simple form to prove and develop an options of conception.The ideal way of istalation of object is like  interactive surrounding like in public galerie of arts.

The visitors could be taken onto interaction with hologram in form of mistaken attempt.For  this application could be possible to use two similar models in pressent time. The first one would be using  code of a standard software.For example:Google documents (painting),when the visitor of the gakleria would use a touchpad  and paint a random bitmap picture,which would with help of the code transform onto the displaying glass board“Hologram”. Subsequently the painting would be transformed into rotational illusion of 3D object.The secondary option is to generate a code with noncontact machine,for example Kinect.Visitor of the galeria could remove matterial using movements of hands from full body illusion,mould it,similar to for example in ceramic production on pottery ring.

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
