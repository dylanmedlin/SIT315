void setup()
{
  Serial.begin(9600);
  pinMode(13, OUTPUT);
  pinMode(2, INPUT);
}

void loop()
{
  int val = (digitalRead(2));
  Serial.print("Motion: ");
  Serial.println(val);
  digitalWrite(13, val);
}
