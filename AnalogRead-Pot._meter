int potentiometr = A5;
int led_pin = A0;

void setup() {
 Serial.println("Starting the prog");
 pinMode(potentiometr, INPUT);
 pinMode(led_pin, OUTPUT);
}

void loop() {
  Serial.println("Start again");

  for(int i=0; i<4945; i+=10)
  {
    int value = analogRead(potentiometr);
    analogWrite(led_pin, i);
    Serial.println(i);
    delay(100);
  }
  Serial.println("Done");
}
