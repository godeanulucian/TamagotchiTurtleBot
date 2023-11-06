# TamagotchiTurtleBot


// initial requirements, each action takes approx. 5 seconds, and after each action it returns to default()
Tamagotchi Requirements:

   0. default():
   - stay put
   - print "puppy awaits your attention"
   - //white LEDs are in fading mode
 
   1. eat():
   - detects the picture with yellow color
   - perform 2 360* rotations per place
   - print "happy puppy eats"
   - //performs 2 360* rotations on the spot and comes towards the picture
   - //make a happy eating puppy sound
   - //green leds are flashing
 
   2. poop(): // only after eat() is executed
   - after 5s after eating, poop() will be executed automatically
   - it will move 2 times front-back quickly
   - print "sad puppy wants to poop"
   - //it will move quickly 2 times front-back and look for the blue picture
   - //makes a sound of a sad puppy wanting to go to the bathroom
   - //yellow led blink
 
   3. play():
   - detects the blue picture
   - makes 2-3 turns (surrounds an object)
   - print "happy puppy running"
   - //sound of happy puppy running
   - //blue led blink
 
   4. sleep(): // only after play() is executed
   - after 5s after playing, sleep() will be executed automatically
   - print "shhh the puppy is sleeping"
   - //fade purple led
 
   5. love():
   - detects orange
   - it moves slowly towards orange
   - print "puppy loves you so much"
   - //sound of puppy licking
   - //fade orange led
 
   6. attack():
   - detects red
   - it follows us very quickly 5s
   - show "run, puppy is in attack mode"
   - //sound of dog barking aggressively
   - //red led blinks