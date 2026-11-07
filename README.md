# Buggy-Code-Tristan-and-Daire-
// The greatest invention that mankind has ever lied its eyes upon


int IrSensor = 4;
int motorEnableA = 0;
int mototAIN1 = 2;
int motorAIN2 = 3;

bool IRSenosorValue;

void setup() {
  pinMode(IRSensor, INPUT);
  pinMode(motorAIN1, OUTPUT);
  pinMode(motorAIN2, OUTPUT);
}

void loop() {
  IRSensorValue - digitalRead(IRSensor);

  if(IRSensorvalue == LOW) {
    digitalWrite(motorAIN1, HIGH);
    digitalWrite(motorAIN2, LOW);
   }else {
    digitalWrite(motorAIN, LOW) ;
    digitalWrite(motorAIN2, HIGH)
   }
}
