# BlinkName
Morse code spelling out my first name (Abdul)

//This program will blink an led on and off.
//It blinks the D7 LED on the Particle device. If you have an LED wired to D0, it will blink that LED as well.

int led2 = D7; // Instead of writing D7 over and over again, we'll write led2
// This one is the little blue LED on the board. On the Photon it is next to D7, and on the Core it is next to the USB jack.

// Setup function runs only once when the device boots up or is reset.

void setup() {
    
  pinMode(led2, OUTPUT);

}

// Next we have the loop function, the other essential part of a microcontroller program.
// This routine gets repeated over and over, as quickly as possible and as many times as possible, after the setup function is called.

void loop() {
  // To blink the LED, first we'll turn it on...
  
  //A
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(1500);
  
  digitalWrite(led2, LOW);
  delay(1500);
  
  //B
  digitalWrite(led2, HIGH);
  delay(1500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(1500);
  
  //D
  digitalWrite(led2, HIGH);
  delay(1500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(1500);
  
  //U
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(1500);
  
  digitalWrite(led2, LOW);
  delay(1500);
  
  //L
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(1500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(500);
  
  digitalWrite(led2, HIGH);
  delay(500);
  
  digitalWrite(led2, LOW);
  delay(1500);

  // And repeat!
}
