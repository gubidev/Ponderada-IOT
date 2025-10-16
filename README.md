# Ponderada IOT
### Parte 1 
Nessa parte tivemos que fazer o led "built-in" do arduino piscar. Para isso utilizei o seguinte codigo:
``` 
void setup() {
  // put your setup code here, to run once:
  pinMode(10, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(10, HIGH);  
  delay(500);                      
  digitalWrite(10, LOW);   
  delay(500);                      
}
```
Aqui esta a imagem do codigo no Arduino IDE e logo embaixo uma imagem do projeto com a luz no momento em que piscou: 

<img src="Screenshot 2025-10-16 085349.png" alt="Imagem do codigo" style="width: 500px;">
<img src="IMG_2198.jpg" alt="Imagem da parte 1" style="width: 500px;">

### Parte 2
A primeira etapa era fazer uma simulação no TinkerCad com uma montagem do pisca-pisca com Arduino Uno: 
[Link Para o TinkerCad](https://www.tinkercad.com/things/3zBGBH4CGx5/editel?sharecode=ddXuFrDDaOcI5fOJxKuq4ZYj2Wlr_dqNsPmPuoCqTLI)

O codigo utilizado foi:
```
void setup() {
  // put your setup code here, to run once:
  pinMode(10, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(10, HIGH);  
  delay(500);                      
  digitalWrite(10, LOW);   
  delay(500);                      
}
```
Também fiz esse projeto no protoboard físico está a imagem:
<img src="Screenshot 2025-10-16 134053.png" alt="Imagem da parte 2" style="width: 500px;">
