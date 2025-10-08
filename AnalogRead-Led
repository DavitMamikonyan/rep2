#define led_pin 25

void setup() {
 Serial.println("Starting the prog");
 pinMode(led_pin, OUTPUT);
}

void loop() {
  Serial.println("Start again");

  for(int i=0; i<4945; i+=10)
  {
    analogWrite(led_pin, i);
    Serial.println(i);
    delay(100);
  }

  Serial.println("Done");
}
