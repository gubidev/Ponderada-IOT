# Ponderada IOT
### Parte 1 
Nessa parte tivemos que fazer o led "built-in" do arduino, e fazer-lo piscar. Para isso utilizei o seguinte codigo:
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
