
//IR sensor using Arduino uno 
int LED = 13; // Onboard LED for Detection Indication  
void setup() { 
pinMode(LED, OUTPUT); 
Serial.begin(9600); 
} 

void loop() { 
int sensorValue = analogRead(A0); // Analog A0 Pin as Input pin (Connect IRmodule Out - A0)  
Serial.println(sensorValue); 
delay(100); 
if (sensorValue>200) 
  { 
  Serial.print("OBJECT DETECTED...!"); 
  digitalWrite(LED, HIGH); 
  } 

  else 
  { 
  Serial.print("NO OBJECT"); 
  digitalWrite(LED, LOW); 
  } 
delay(200); 
} 
