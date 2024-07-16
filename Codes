//Codes of Uno Arduino control of 6 servo motors

// Step 1 (include Arduino Servo library)
#include <Servo.h>   

//step 2 ( servo 1 settings)
Servo servo1;
const int servo1PotPin = A0;
const int servo1Pin = 9; // Must use PWM enabled pin
int servo1_test;

//Step 3 ( servo 2 settings)
Servo servo2;
const int servo2PotPin = A1;
const int servo2Pin = 8; // Must use PWM enabled pin
int servo2_test;

//Step 4 ( servo 3 settings)
Servo servo3;
const int servo3PotPin = A2;
const int servo3Pin = 10; // Must use PWM enabled pin
int servo3_test;

//Step 5 ( servo 4 settings)
Servo servo4;
const int servo4PotPin = A3;
const int servo4Pin = 11; // Must use PWM enabled pin
int servo4_test;





//Step 6 ( servo 5 settings)
Servo servo5;
const int servo5PotPin = A4;
const int servo5Pin = 12; // Must use PWM enabled pin
int servo5_test;

//Step 7 ( servo 6 settings)
Servo servo6;
const int servo6PotPin = A5;
const int servo6Pin = 13; // Must use PWM enabled pin
int servo6_test;

//Step 8 (settings the digital pins of servo motors)
void setup() {

servo1.attach(servo1Pin);

servo2.attach(servo2Pin);
  
servo3.attach(servo3Pin);  

servo4.attach(servo4Pin);

servo5.attach(servo5Pin);
  
servo6.attach(servo6Pin);


}


//Step 9 (settings the Analog pins of servo motors and its angle movement)

void loop() {

servo1_test = analogRead(servo1PotPin);

servo1_test = map(servo1_test, 0, 1023, 180, 0); //servo rotation is only 180 degrees. currently translating potentiometer values to degrees of rotation for servo, currently in reverse

servo1.write(servo1_test);
  

servo2_test = analogRead(servo2PotPin);

servo2_test = map(servo2_test, 0, 1023, 180 , 0); //servo rotation is only 180 degrees. currently translating potentiometer values to degrees of rotation for servo, currently in reverse

servo2.write(servo2_test);
  
  
servo3_test = analogRead(servo3PotPin);

servo3_test = map(servo3_test, 0, 1023, 180 , 0); //servo rotation is only 180 degrees. currently translating potentiometer values to degrees of rotation for servo, currently in reverse

servo3.write(servo3_test);
  
  
servo4_test = analogRead(servo4PotPin);

servo4_test = map(servo4_test, 0, 1023, 180 , 0); //servo rotation is only 180 degrees. currently translating potentiometer values to degrees of rotation for servo, currently in reverse

servo4.write(servo4_test);
  
  
servo5_test = analogRead(servo5PotPin);

servo5_test = map(servo5_test, 0, 1023, 180 , 0); //servo rotation is only 180 degrees. currently translating potentiometer values to degrees of rotation for servo, currently in reverse

servo5.write(servo5_test);
  
  
servo6_test = analogRead(servo6PotPin);

servo6_test = map(servo6_test, 0, 1023, 180 , 0); //servo rotation is only 180 degrees. currently translating potentiometer values to degrees of rotation for servo, currently in reverse

servo6.write(servo6_test);

delay(5);

}
