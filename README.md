# SEMAFARO-C-PEDESTRES
tinkercad update
// C++ code<BR>
//<BR>
void setup()<BR>
{
  pinMode(12, OUTPUT);//pedestre verm<BR>
  pinMode(11, OUTPUT);//pedestre verde<BR>
  pinMode(10, OUTPUT);<BR>
  pinMode(9, OUTPUT);<BR>
  pinMode(8, OUTPUT);<BR>
  pinMode(7, OUTPUT);<BR>
  pinMode(6, OUTPUT);<BR>
  pinMode(5, OUTPUT);<BR>
  pinMode(4, OUTPUT);//pedestre verd<BR>
  pinMode(3, OUTPUT);//pedestre verm<BR>

}

void loop()<BR>
{
  digitalWrite(11,HIGH);//pedestre verde<BR>
  digitalWrite(12,LOW);//pedestre vermelho<BR>
  digitalWrite(10,HIGH);//VERM<BR>
  digitalWrite(9, LOW);//AMAR<BR>
  digitalWrite(8, LOW);//VERD<BR>
  digitalWrite(7, LOW);//VERM<BR>
  digitalWrite(6, LOW);//AMAR<BR>
  digitalWrite(5, HIGH);//VERD<BR>
  digitalWrite(4,LOW);//pedestre verd<BR>
  digitalWrite(3,HIGH);//pedestre verm<BR>
  delay(5000); // Wait for 1000 millisecond(s)<BR>
  
  digitalWrite(11,HIGH);//pedestre verde<BR>
  digitalWrite(12,LOW);//pedestre vermelho<BR>
  digitalWrite(10,HIGH);//VERM<BR>
  digitalWrite(9, LOW);//AMAR<BR>
  digitalWrite(8, LOW);//VERD<BR>
  digitalWrite(7, LOW);//VERM<BR>
  digitalWrite(6, HIGH);//AMAR<BR>
  digitalWrite(5, LOW);//VERD<BR>
  digitalWrite(4,LOW);//pedestre verd<BR>
  digitalWrite(3,HIGH);//pedestre verm<BR>
  delay(5000); // Wait for 1000 millisecond(s)<BR>
  
  digitalWrite(11,LOW);//pedestre verde<BR>
  digitalWrite(12,HIGH);//pedestre vermelho<BR>
  digitalWrite(10,LOW);//VERM<BR>
  digitalWrite(9, LOW);//AMAR<BR>
  digitalWrite(8, HIGH);//VERD<BR>
  digitalWrite(7, HIGH);//VERM<BR>
  digitalWrite(6, LOW);//AMAR<BR>
  digitalWrite(5, LOW);//VERD<BR>
  digitalWrite(4,HIGH);//pedestre verd<BR>
  digitalWrite(3,LOW);//pedestre verm<BR>
  delay(5000); // Wait for 1000 millisecond(s)<BR>
  
  digitalWrite(11,LOW);//pedestre verde<BR>
  digitalWrite(12,HIGH);//pedestre vermelho<BR>
  digitalWrite(10,LOW);//VERM<BR>
  digitalWrite(9, HIGH);//AMAR<BR>
  digitalWrite(8, LOW);//VERD<BR>
  digitalWrite(7, HIGH);//VERM<BR>
  digitalWrite(6, LOW);//AMAR<BR>
  digitalWrite(5, LOW);//VERD<BR>
  digitalWrite(4,HIGH);//pedestre verd<BR>
  digitalWrite(3,LOW);//pedestre verm<BR>
  delay(5000); // Wait for 1000 millisecond(s)<BR>
}
 
