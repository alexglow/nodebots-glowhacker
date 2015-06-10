# nodebots-glowhacker


/*
This sketch reads the acceleration from the Bean's on-board
accelerometer and displays it on the Bean's LED.

This example code is in the public domain.
*/

static int d2 = 2;
  
void setup() {
// Optional: Use Bean.setAccelerationRange() to set the sensitivity
// to something other than the default of ±2g.
    pinMode(d2, OUTPUT);
}


void loop() {
    digitalWrite(d2, HIGH);
    Bean.sleep(250);
    digitalWrite(d2, LOW);
    Bean.sleep(1000);
}



RED YELLOW GREEN!!!


/*
This sketch reads the acceleration from the Bean's on-board
accelerometer and displays it on the Bean's LED.

This example code is in the public domain.
*/

static int d2 = 2;
static int d3 = 3;
  
void setup() {
// Optional: Use Bean.setAccelerationRange() to set the sensitivity
// to something other than the default of ±2g.
    pinMode(d2, OUTPUT);
    pinMode(d3, OUTPUT);
}


void loop() {
    digitalWrite(d2, HIGH);
    Bean.sleep(250);
    digitalWrite(d3, HIGH);
    Bean.sleep(250);
    digitalWrite(d2, LOW);
    Bean.sleep(250);
    digitalWrite(d3, LOW);
    Bean.sleep(1000);
}
