#include <FastLED.h>

#define NUM_LEDS 64
#define DATA_PIN 3 
#define COLOR_ORDER GRB              
CRGB leds[NUM_LEDS];
int d = 400;

int r = 179; //YELLOW
int g = 119;
int b = 0;

int r1=120; //RED
int g1= 10;
int b1 = 0;

//HULK dark green
int r2 = 0;
int g2= 117;
int b2= 20;

//FRAME 1 . 24, 9
int m[] = {2,5,8,11,12,15,18,19,20,21,25,26,27,28,29,30,34,42,50,52,58,59,60,61};
int n[] = {16,23,35,36,37,44,51,53};

//FRAME 2. 24,9
int qm[] = {2,5,9,11,12,14,18,19,20,21,25,26,27,28,29,30,34,42,50,52,58,59,60,61};
int wn[] = {17,22,35,36,37,44,51,53};

//FRAME 3 ironman  size 21,10
int mx[] = {2,4,10,11,12,17,19,20,25,26,27,28,33,41,42,49,51,57,58,59,60};
int mc[] = {18,34,35,36,42,50,52};

//FRAME 4 ,,22 6
int mq[] = {2,4,10,11,17,18,20,21,25,26,27,28,33,34,41,42,49,50,51,57,58,59,60};
int mw[] = {19,35,36,43,52};

//FRAME 5,, 23 6
int me[] {2,4,9,10,11,12,17,18,19,25,26,27,29,33,34,41,42,49,50,51,59,57,58,59,60};
int mr[] {28,35,36,43,52};

//frame 6,, 21,6
int mt[] = {1,4,8,10,11,17,18,24,25,26,28,32,33,40,41,48,49,50,56,57,58,59};
int my[] = {27,34,35,42,51};

//frame 9,, 18 6
int mu[]= {10,12,16,18,19,25,26,29,32,33,34,36,40,41,48,49,56,57,58};
int mi[] = {35,42,43,50,59};

//Frame 10,, 11 4
int mo[] = {17,25,26,32,33,36,40,41,43,48,56};
int mp[] = {42,50,49,57};

//Frame 11,, 9,3
int ma[] = {24,26,32,33,40,41,43,48,50};
int ms[] = {49,56,57};

//frame h2,, 6
int md[] = {50,53,58,59,60,61};

//Frameh3,, 4, 6
int mf[] = {58,59,60,61};
int mg[] = {42,45,50,51,52,53};

//Frame H4,, 11,6
int mh[] = {50,51,52,53,56,58,59,60,61,62,63};
int mj[] = {34,37,42,43,44,45};

//FRAME H5,, 14,6
int mk[] = {42,43,44,45,48,49,50,51,52,53,54,55,59,61};
int ml[] = {25,30,34,35,36,37};

//Frame H6,, 15,6
int mz[] = {34,35,36,37,40,41,42,43,44,45,46,47,51,53,60};
int mv[] = {18,21,26,27,28,29};



void setup() {
  // put your setup code here, to run once:
  FastLED.addLeds<WS2811,DATA_PIN,COLOR_ORDER>(leds,NUM_LEDS);
  FastLED.setBrightness(15);
 
}
void loop() {
  // put your main code here, to run repeatedly:
  //FRAME 1
  for (int dot = 0; dot < 24; dot++) {
    leds[m[dot]] = CRGB(r1,g1,b1);
  }
  for(int i = 0; i <  10; i++) {
    leds[n[i]] = CRGB(r,g,b);
  }
  leds[43] = CRGB::Blue;
  leds[45] = CRGB::Blue;
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);

//FRAME 2
  for(int i = 0; i < 24; i++) {
    leds[qm[i]] = CRGB(r1,g1,b1);
  }
  for(int i = 0; i < 10; i++){
    leds[wn[i]] = CRGB(r,g,b);
  }
  leds[43] = CRGB::Blue;
  leds[45] = CRGB::Blue;

  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);

//frame 3
  for(int i = 0; i < 22; i++) {
    leds[mx[i]] = CRGB(r1,g1,0);
  }
  for(int i = 0; i < 8; i++) {
    leds[mc[i]] = CRGB(r,g,b);
  }
  leds[43] = CRGB::Blue;
  leds[44] = CRGB::Blue;
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);

//FRAME 4
  for(int i = 0; i < 23; i++) {
    leds[mq[i]] = CRGB(r1,g1,0);
  }
  for(int i = 0; i < 6; i++) {
    leds[mw[i]] = CRGB(r,g,b);
  }
  leds[44] = CRGB::Blue;
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);

//FRAME 5
  for(int i = 0; i < 25; i++) {
    leds[me[i]] = CRGB(r1,g1,0);
  }
  for(int i = 0; i < 6; i++) {
    leds[mr[i]] = CRGB(r,g,b);
  }
  leds[44] = CRGB::Blue;
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);

//FRAME 6
  for(int i = 0; i < 25; i++) {
    leds[me[i]] = CRGB(r1,g1,0);
  }
  for(int i = 0; i < 6; i++) {
    leds[mr[i]] = CRGB(r,g,b);
  }
  leds[44] = CRGB::Blue;
  leds[30] = CRGB(143,180,200);
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);

//frame 7
for(int i = 0; i < 24; i++) {
    leds[mt[i]] = CRGB(r1,g1,0);
  }
  for(int i = 0; i < 6; i++) {
    leds[my[i]] = CRGB(r,g,b);
  }
  leds[43] = CRGB::Blue;
  leds[31] = CRGB(143,180,200);
  leds[29] = CRGB(r1,g1,0);
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);

//frame 8 same array as FRAME 7
for(int i = 0; i < 22; i++) {
    leds[mt[i]] = CRGB(r1,g1,0);
  }
  for(int i = 0; i < 6; i++) {
    leds[my[i]] = CRGB(r,g,b);
  }
  leds[43] = CRGB::Blue;
  leds[21] = CRGB(r1,g1,0);
  
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);

  //frame 9
for(int i = 0; i < 20; i++) {
    leds[mu[i]] = CRGB(r1,g1,0);
  }
  for(int i = 0; i < 6; i++) {
    leds[mi[i]] = CRGB(r,g,b);
  }
  leds[51] = CRGB::Blue;
  leds[3] = CRGB::LightBlue;
  leds[5] = CRGB::LightBlue;
  leds[22] = CRGB::LightBlue;
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);


 //frame 10
for(int i = 0; i < 11; i++) {
    leds[mo[i]] = CRGB(r1,g1,0);
  }
  for(int i = 0; i < 4; i++) {
    leds[mp[i]] = CRGB(r,g,b);
  }
  leds[58] = CRGB::Blue;
  leds[10] = CRGB::LightBlue;
  leds[19] = CRGB::LightBlue;
  leds[29] = CRGB::LightBlue;
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);

 //frame 11
for(int i = 0; i < 9; i++) {
    leds[ma[i]] = CRGB(r1,g1,0);
  }
  for(int i = 0; i < 3; i++) {
    leds[ms[i]] = CRGB(r,g,b);
  }
  leds[17] = CRGB::LightBlue;
  leds[19] = CRGB::LightBlue;
  leds[36] = CRGB::LightBlue;
  FastLED.show();
  fill_solid(leds, NUM_LEDS, CRGB::Black);
  delay(d);


//frame 12
leds[32] = CRGB(r1,g1,0);
leds[33] = CRGB(r1,g1,0);
leds[40] = CRGB(r1,g1,0);
leds[48] = CRGB(r1,g1,0);
leds[50] = CRGB(r1,g1,0);
leds[57] = CRGB(r1,g1,0);
leds[56] = CRGB::Yellow;
leds[24] = CRGB::LightBlue;
leds[26] = CRGB::LightBlue;
leds[43] = CRGB::LightBlue;


FastLED.show();
fill_solid(leds, NUM_LEDS, CRGB::Black);
delay(d);

//Frame 13
leds[40] = CRGB(r1,g1,0);
leds[57] = CRGB(r1,g1,0);
leds[33] = CRGB::LightBlue;
leds[50] = CRGB::LightBlue;


FastLED.show();
fill_solid(leds, NUM_LEDS, CRGB::Black);
 delay(d);

 
 }
