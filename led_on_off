const int buttonPin = 2;     // push button pin number
const int ledPin =  13;      // LED pin number

int buttonState = 0;         // pushbutton status

void setup() {
  pinMode(ledPin, OUTPUT);
  pinMode(buttonPin, INPUT);
}

void loop() {
  buttonState = digitalRead(buttonPin);

  // if the pushbutton pressed
  if (buttonState == HIGH) {
    // LED on:
    digitalWrite(ledPin, HIGH);
  } else {
    // LED off:
    digitalWrite(ledPin, LOW);
  }
}
