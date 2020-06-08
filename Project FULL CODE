#include <FastLED.h>

#define NUM_LEDS 192
#define DATA_PIN 3 
#define COLOR_ORDER GRB              
CRGB leds[NUM_LEDS];

int P;


int r = 60; //DARK BLUE SUIT
int g = 50;
int b = 120;


int r1 =60; //brown part of suit
int g1 = 42;
int b1 = 5;

int d = 300;

//FRAME 1 .  21 , 7
//CAPTAIN AMERICA
int ma[] = {9,12,13,14,19,25,28,29,30,37,38,44,45,46,51,52,53,54,60,61};//blue
int mb[] = {4,6,10,18,20,22,26}; //red

//FRAME 3. 17, 7
int mc[] = {9,12,13,14,19,25,29,30,36,37,38,43,44,45,46,52,53}; //Blue suit
int md[] = {4,7,10,18,20,22,26}; //RED part suit


//Frame 4,, 4,5
int qq[] = {155,160,168,169};
int qw[] = {144,145,152,154,161};

//frame 6,, 10, 7
int qe[] = {144,152,156,157,160,162,168,169,170,171}; //RED
int qr[] = {145,146,147,154,156,161,163}; //YELLOW

//Frame7,, 11,7
int qt[] = {144,145,152,153,158,161,163,169,170,171,172}; //RED
int qy[] = {146,147,148,155,157,162,164}; //YELLOW

//FRAME 8---- 12,8
int qu[] = {145,146,152,153,154,159,162,164,170,171,172,173};
int qi[] = {144,147,148,149,156,158,163,165};

//frame 18 --------- The iron man made separately * now made it on array
int me[] = {88,140,144,145,146,147,152,153,154,155,159,163,171,172,173,174}; // 15
int mf[] = {139,148,149,150,157,164,165,166}; //yellow 8
int mg[] = {0,8,16,24,32,72,73,74,75,76,77,78,79,89,90,91,92,93,94,95,141,142,143}; //LASER 23

//FRAME 19
int mh[] = {6,8,11,12,13,18,24,28,29,35,36,37,42,43,44,45,51,52}; //Blue suit captain america 18
int mi[] = {3,9,17,19,21,25}; //red 6
//iron man
int qo[] = {88,89,141,144,145,146,147,148,152,153,154,155,156,164,172,173,174,175}; //REDE 18
int qp[] = {140,149,150,151,158,166,165,166,167}; //9 yellow
int qa[] = {71,75,76,77,78,79,87,91,92,93,94,95,103};// LASER DARK YELLOW 13
int qs[] = {66,72,73,74,82,90,98,142,143}; //purple laser evo 9

//frame 20
int qd[] = {67,68,75,76,83,84,91,92,99,100}; // LASER EVO purple 10

//Frame 21
int qf[] = {69,70,71,77,78,79,85,86,87,93,94,95,101,102,103}; //LASER EVO purple 15

//FRAME 23
int amg[] = {17,18,19,35,36,37,44,51}; //skin colo of captain america 8
int amh[] = {38,45,46,52,53,54,59,60,61,62}; //Hair color CP 10

int qz[] = {129,131,137,138,139,145,146,147,148,153,154,155}; //12  RED
int qx[] = {161,164,169,177,178,179,185,186,187,188}; // 10 BROWN color
int gauntlet[] = {141,142,143,149,151,157,158,159}; //8

//FRAM 24 power up
int power[] = {24,26,48,49,50,95,103,111,119}; //9 

//FRAME 25 SHOT
int storm[] = {110,117,108,115,106,113,104,183,174,181}; //mjlornir shot blue 10
int ystorm[] = {118,109,116,107,114,105,112,175,182,173};// 10 yellow

int inf[] = {73,74,75,76,77,78,79,8}; //8
int inf1[] = {81,82,83,84,85,86,87,16};
int inf2[] = {89,90,91,92,93,94,95,24};



void setup() {
  // put your setup code here, to run once:
  FastLED.addLeds<WS2811,DATA_PIN,COLOR_ORDER>(leds,NUM_LEDS);
  FastLED.setBrightness(15);
}

void loop() {
  
  //FRAME 1
  //iron man
  leds[152] = CRGB::DarkRed; //red arm
  

//captai america
  for(int i = 0; i < 20; i++) {
    leds[ma[i]] = CRGB(r,g,b);
  }
  for (int i = 0; i < 8; i++) {
    leds[mb[i]] = CRGB::Red;
  }
  leds[35] = CRGB::Peru; //skin color
  leds[36] = CRGB::Peru;
  leds[43] = CRGB::White; //eyes
  leds[21] = CRGB::White; //suit
  leds[17] = CRGB::White; // shield
    FastLED.show();
    FastLED.clear();
    delay(d);

    
    
  //FRAME 2-------------------------------
  leds[152] = CRGB::Yellow; //yellow arm
  leds[153] = CRGB::DarkRed;

//captai america
  for(int i = 0; i < 20; i++) {
    leds[ma[i]] = CRGB(r,g,b);
  }
  for (int i = 0; i < 8; i++) {
    leds[mb[i]] = CRGB::Red;
  }
  leds[35] = CRGB::Peru; //skin color
  leds[36] = CRGB::Peru;
  leds[43] = CRGB::White; //eyes
  leds[21] = CRGB::White; //suit
  leds[17] = CRGB::White; // shield
  
  FastLED.show();
  FastLED.clear();
   delay(d);



  //FRAME 3---------------------------------
  leds[152] = CRGB::Yellow; //arm
  leds[153] = CRGB::DarkRed; //arm
  leds[154] = CRGB::LightBlue; //LASER

  //CAPTAIamerica
  for (int i = 0; i < 21; i++) {
  leds[mc[i]] = CRGB(r,g,b);
 }

 for(int i = 0; i < 7; i++) {
  leds[md[i]] = CRGB::Red;
 }
 
  leds[28] = CRGB::Peru; //skin color
  leds[27] = CRGB::Peru;
  leds[35] = CRGB::White; //eyes
  leds[17] = CRGB::White; //Shield
  leds[21] = CRGB::White; //suit
  FastLED.show();
  FastLED.clear();
  delay(d);

  

  //FRAME4------------------------------------
  //iron man
  leds[168] = CRGB::DarkRed;
  leds[160] = CRGB::Yellow;
  leds[152] = CRGB::Blue;
  leds[144] = CRGB::Yellow;
  leds[153] = CRGB::Yellow;
  leds[154] = CRGB::DarkRed;
  leds[155] = CRGB::LightBlue;
  leds[156] = CRGB::LightBlue;

  //CAPTAIN AMERICA---------
  for (int i = 0; i < 21; i++) {
  leds[mc[i]] = CRGB(r,g,b);
 }

 for(int i = 0; i < 7; i++) {
  leds[md[i]] = CRGB::Red;
 }
 
  leds[28] = CRGB::Peru; //skin color
  leds[27] = CRGB::Peru;
  leds[35] = CRGB::White; //eyes
  leds[17] = CRGB::White; //Shield
  leds[21] = CRGB::White; //suit
 
  FastLED.show();
  fill_solid(leds,NUM_LEDS,CRGB::Black);
   delay(d);

   //FRAME5------------------------------------------
   for (int i = 0; i < 4; i++){
    leds[qq[i]] = CRGB::DarkRed;
   }
   for (int i = 0; i < 5; i++) {
    leds[qw[i]] = CRGB::Yellow;
   }

   leds[153] = CRGB::Blue;
   leds[157] = CRGB::LightBlue;
   leds[156] = CRGB::LightBlue;
   leds[158] = CRGB::LightBlue;
   leds[159] = CRGB::LightBlue;

   
  //captain america
  for (int i = 0; i < 21; i++) {
  leds[mc[i]] = CRGB(r,g,b);
 }

 for(int i = 0; i < 7; i++) {
  leds[md[i]] = CRGB::Red;
 }
 
  leds[28] = CRGB::Peru; //skin color
  leds[27] = CRGB::Peru;
  leds[35] = CRGB::White; //eyes
  leds[17] = CRGB::White; //Shield
  leds[21] = CRGB::White; //suit

   FastLED.show();
   fill_solid(leds,NUM_LEDS,CRGB::Black);
   delay(d);

   //FRAME 6----------------------------------------

    for (int i = 0; i < 10; i++){
    leds[qe[i]] = CRGB::DarkRed;
   }
   for (int i = 0; i < 7; i++) {
    leds[qr[i]] = CRGB::Gold;
   }

   leds[153] = CRGB::Blue; //eyes
   leds[155] = CRGB::Blue;//Eyes
   leds[158] = CRGB::LightBlue;
   leds[159] = CRGB::LightBlue;
   leds[88] = CRGB::LightBlue;
   leds[89] = CRGB::LightBlue;
   leds[90] = CRGB::LightBlue;

    //captain america----
  for (int i = 0; i < 21; i++) {
  leds[mc[i]] = CRGB(r,g,b);
 }

 for(int i = 0; i < 7; i++) {
  leds[md[i]] = CRGB::Red;
 }
 
  leds[28] = CRGB::Peru; //skin color
  leds[27] = CRGB::Peru;
  leds[35] = CRGB::White; //eyes
  leds[17] = CRGB::White; //Shield
  leds[21] = CRGB::White; //suit

  FastLED.show();
   fill_solid(leds,NUM_LEDS,CRGB::Black);
   delay(d);



 //FRAME 7------------------------------------------
 
    for (int i = 0; i < 11; i++){
    leds[qt[i]] = CRGB::DarkRed;
   }
   for (int i = 0; i < 7; i++) {
    leds[qy[i]] = CRGB::Gold;
   }

   leds[154] = CRGB::Blue; //eyes
   leds[156] = CRGB::Blue;
   leds[159] = CRGB::LightBlue;
   leds[88] = CRGB::LightBlue;
   leds[89] = CRGB::LightBlue;
   leds[90] = CRGB::LightBlue;
   leds[91] = CRGB::LightBlue;
   leds[92] = CRGB::LightBlue;
   leds[93] = CRGB::LightBlue;

    //captain america
  for (int i = 0; i < 21; i++) {
  leds[mc[i]] = CRGB(r,g,b);
 }

 for(int i = 0; i < 7; i++) {
  leds[md[i]] = CRGB::Red;
 }
 
  leds[28] = CRGB::Peru; //skin color
  leds[27] = CRGB::Peru;
  leds[35] = CRGB::White; //eyes
  leds[17] = CRGB::White; //Shield
  leds[21] = CRGB::White; //suit

  FastLED.show();
   fill_solid(leds,NUM_LEDS,CRGB::Black);
   delay(d);


   
 //FRAME 8------------------------------------------
 
    for (int i = 0; i < 12; i++){
    leds[qu[i]] = CRGB::DarkRed;
   }
   for (int i = 0; i < 8; i++) {
    leds[qi[i]] = CRGB::Gold;
   }

   leds[155] = CRGB::Blue; //eyes
   leds[157] = CRGB::Blue;
   leds[88] = CRGB::LightBlue;
   leds[89] = CRGB::LightBlue;
   leds[90] = CRGB::LightBlue;
   leds[91] = CRGB::LightBlue;
   leds[92] = CRGB::LightBlue;
   leds[93] = CRGB::LightBlue;
   leds[94] = CRGB::LightBlue;
   leds[95] = CRGB::LightBlue;
   leds[24] = CRGB::LightBlue;

    //captain america
  for (int i = 0; i < 21; i++) {
  leds[mc[i]] = CRGB(r,g,b);
 }

 for(int i = 0; i < 7; i++) {
  leds[md[i]] = CRGB::Red;
 }
 
  leds[28] = CRGB::Peru; //skin color
  leds[27] = CRGB::Peru;
  leds[35] = CRGB::White; //eyes
  leds[17] = CRGB::White; //Shield
  leds[21] = CRGB::White; //suit

  FastLED.show();
   delay(100);
   
   //FRAME 9---------------------------------
   leds[144] = CRGB::DarkRed;
   leds[136] = CRGB::Gold;
   leds[137] = CRGB::DarkRed;


delay(200);

//FTRAME 10----------------------
leds[138] = CRGB::LightBlue;
FastLED.show();
delay(200);

//FRAME 11-------------------
leds[136] = CRGB::Black;
leds[137] = CRGB::Gold;
leds[138] = CRGB::DarkRed;
leds[139] = CRGB::LightBlue;
leds[140] = CRGB::LightBlue;
leds[141] = CRGB::LightBlue;


FastLED.show();
delay(d);

//FRAME 12
leds[137] = CRGB::Black;
leds[138] = CRGB::Gold;
leds[139] = CRGB::DarkRed;
leds[142] = CRGB::LightBlue;
leds[143] = CRGB::LightBlue;
leds[72] = CRGB::LightBlue;

FastLED.show();
delay(100);

//frame13

leds[73] = CRGB::LightBlue;
leds[74] = CRGB::LightBlue;
leds[75] = CRGB::LightBlue;
leds[76] = CRGB::LightBlue;
FastLED.show();
delay(d);

leds[77] = CRGB::LightBlue;
leds[78] = CRGB::LightBlue;
leds[79] = CRGB::LightBlue;
leds[8] = CRGB::LightBlue;

FastLED.show();

delay(d);

//FRAME 14---------------
leds[88] = CRGB(51,51,00); //LASER EVOLUTION
leds[140] = CRGB(51,51,00);
FastLED.show();

delay(d);

//FRAME 15-----LASER EVOLUTION
leds[89] = CRGB(51,51,00);
leds[90] = CRGB(51,51,00);
leds[141] = CRGB(51,51,00);
leds[142] = CRGB(51,51,00);
leds[143]= CRGB(51,51,00);

FastLED.show();
delay(d);

//FRAME 16----------------------
leds[91] = CRGB(51,51,00);
leds[92]= CRGB(51,51,00);
leds[93]= CRGB(51,51,00);
leds[143]= CRGB(51,51,00);
leds[72]= CRGB(51,51,00);
leds[73] = CRGB(51,51,00);
leds[74] = CRGB(51,51,00);


FastLED.show();
delay(d);

//FRAME 17-------------------
leds[94] = CRGB(51,51,0);
leds[95] = CRGB(51,51,0);

for (int i = 75; i < 80; i++) {
  leds[i] = CRGB(51,51,0);
  
}


FastLED.show();
delay(d);

//FRAME18-------------------------------------F
leds[24] = CRGB(51,51,0);
leds[8] = CRGB(51,51,0);
leds[32] = CRGB(51,51,0);
leds[16] = CRGB(51,51,0);
leds[0]  = CRGB(51,51,0);
FastLED.show();
FastLED.clear();
delay(d);

//FRAME 19----------------------AFTER CLEAR
//iron man
for (int i = 0; i <16; i++) {
  leds[me[i]] = CRGB::DarkRed;
}
for ( int i = 0; i < 8; i++) {
  leds[mf[i]] = CRGB::Gold;
}
leds[156] = CRGB::Blue;
leds[158] = CRGB::Blue;

for (int i =0; i <23; i++) {
  leds[mg[i]] = CRGB(70,70,10);
  
}

leds[141] = CRGB::Purple; //laser evolution
leds[89] =  CRGB::Purple;


//captain america
  for(int i = 0; i < 20; i++) {
    leds[ma[i]] = CRGB(r,g,b);
  }
  for (int i = 0; i < 8; i++) {
    leds[mb[i]] = CRGB::Red;
  }
  leds[35] = CRGB::Peru; //skin color
  leds[36] = CRGB::Peru;
  leds[43] = CRGB::White; //eyes
  leds[21] = CRGB::White; //suit
  leds[17] = CRGB::White; // shield
    FastLED.show();
    FastLED.clear();
    delay(d);


//FRAME 19 -------------------------------------
//iron man
for(int i = 0; i < 18; i++) {
    leds[qo[i]] = CRGB::DarkRed;
  }
  for (int i = 0; i < 9; i++) {
    leds[qp[i]] = CRGB::Gold;
  }
leds[157] = CRGB::Blue;
leds[159] = CRGB::Blue;

 for (int i = 0; i < 13; i++) {
    leds[qa[i]] = CRGB(70,70,10); //yellow laser
  }
  for (int i = 0; i < 9; i++) {
    leds[qs[i]] = CRGB::Purple; //purple laser evo
  }


//captain america
 for(int i = 0; i < 18; i++) {
    leds[mh[i]] = CRGB(r,g,b);
  }
  for (int i = 0; i < 9; i++) {
    leds[mi[i]] = CRGB::Red;
  }
  leds[26] = CRGB::Peru; //skin color
  leds[27] = CRGB::Peru;
  leds[34] = CRGB::White; //eyes
  leds[20] = CRGB::White; //suit
  leds[16] = CRGB::White; //

    FastLED.show();
    delay(d);

//FRAME 20
    for (int i = 0; i < 10; i++) {
    leds[qd[i]] = CRGB::Purple;
  } 

  FastLED.show();
  delay(d);

//Frame 21-----------------------------------
     for (int i = 0; i < 15; i++) {
    leds[qf[i]] = CRGB::Purple;
  } 

  FastLED.show();
  FastLED.clear();
  delay(d*2); 

//FRAME 22------------------------------------------
fill_solid(leds,NUM_LEDS,CRGB::Purple);
FastLED.show();
delay(d*3);

//Frame 22.5---------------------------------------
FastLED.clear();
delay(d);


//FRAME 23
//iron man
for (int i = 0; i <12; i++) {
  leds[qz[i]] = CRGB::DarkRed;
}

for(int i =0; i < 10; i++) {
  leds[qx[i]] = CRGB(56,22,7); //brown hair
}
leds[162] = CRGB::Peru;
leds[163] = CRGB::Peru;
leds[170] = CRGB::Peru;
leds[171] = CRGB::Peru;
leds[180] = CRGB::Peru;
leds[172] = CRGB(25,25,25); //Eyes

//INFINITY GAUNTLET
leds[88] = CRGB(50,0,50); //inf stone
leds[80] = CRGB(0,0,50); //inf stone
leds[72] = CRGB(0,50,0); //inf stone
leds[150] = CRGB(102,102,0);
for (int i = 0; i <8; i++) {
  leds[gauntlet[i]] = CRGB(25,25,25);
}




//CAPTAIN AMERICA
//red suit part
leds[4] = CRGB::Red;
leds[20] = CRGB::Red;
leds[22] = CRGB::Red;

//Blue suit part
leds[6] = CRGB::Blue;
leds[12] = CRGB::Blue;
leds[13] = CRGB::Blue;
leds[14] = CRGB::Blue;
leds[28] = CRGB::Blue;
leds[29] = CRGB::Blue;
leds[30] = CRGB::Blue;
//EYES
leds[43] = CRGB(70,130,180);
//Suit
leds[21] = CRGB::White;

//skin color
for ( int i = 0; i< 8; i++) {
  leds[amg[i]] = CRGB::Peru;
}

for ( int i = 0; i< 10; i++) {
  leds[amh[i]] = CRGB(51,51,0);
}

//MJLORNIR
leds[9] = CRGB(139,65,19);
leds[25] = CRGB(139,65,19);
leds[33] = CRGB(25,25,25);
leds[41] = CRGB(25,25,25);
leds[32] = CRGB(25,25,25);
leds[34] = CRGB(25,25,25);
leds[40] = CRGB(25,25,25);
leds[42] = CRGB(25,25,25);

FastLED.show();
//FastLED.clear();
delay(d);

//Frame 23 POWERING UP
leds[88].maximizeBrightness(255);
leds[80].maximizeBrightness(255);
leds[72].maximizeBrightness(255);
leds[150].maximizeBrightness(255);
FastLED.show();
delay(d);

//FRAME 24---------------------------------
for (int i = 0; i < 9; i++) {
  leds[power[i]] = CRGB(0,191,255);
  
}

leds[147] = CRGB::Blue;

FastLED.show();
delay(d);
leds[138] = CRGB::Blue;
delay(d);
leds[145] = CRGB::Blue;
delay(d);
leds[131] = CRGB::Blue;
delay(d);

for(int x = 0; x < 10; x++) {
  
  leds[storm[x]] = CRGB(0,191,255);
  leds[ystorm[x]] = CRGB::Yellow;
  leds[inf[x]] = CRGB::White;
  leds[inf1[x]] = CRGB::White;
  leds[inf2[x]] = CRGB::White;
  
  FastLED.show();
  delay(100);
  
  

}

delay(d);
FastLED.clear();


//LAST FRAME
 fill_solid(leds,NUM_LEDS,CRGB(18,10+8,18));
FastLED.show();
delay(1000);
}

   
