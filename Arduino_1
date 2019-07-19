void setup() {
  pinMode(13, OUTPUT);
  Serial.begin(9600);
  
                // put your setup code here, to run once:
}

void loop() {
  if(Serial.available()){   // 입력된 데이터가 있으면
    char a;                 // a
    a = Serial.read();
    if(a=='1')
    {
      digitalWrite(13,HIGH);      // turn on LED
      Serial.println("led ON!");  // led ON print
    }
    else
    {
      digitalWrite(13,LOW);       // led를 끈다
      Serial.print(Input data : ");
      Serial.println(a);          // print 
      Serial.println("led OFF!"); // led OFF print
    }
  }
                // put your main code here, to run repeatedly:
}
