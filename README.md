
# how it works 

well, it is just written in plain easy vanilla javaScript. -should not be heard
to find out how it works, I just like to present the idea behind ... 

There are currently then different tiles 

 mType[0]="xxxxxxxxxxxxxxxx"; // code 0 , all wall 
 mType[1]="xxxx........xxxx"; // code 1 , large room 
 mType[2]="xxxx......xxxxxx"; // code 2 , medium sized room 
 mType[3]="xxxx....xxxxxxxx"; // code 3 , small room 
 mType[4]="xxxxx.xxxxxxxxxx"; // code 4 , path down 
 mType[5]="xxxx............"; // code 5 , right escape
 mType[6]="............xxxx"; // code 6 , large room left join 
 mType[7]="..........xxxxxx"; // code 7 , medium room left join 
 mType[8]="........xxxxxxxx"; // code 8 , small room left join 
 mType[9]="................"; // code 9 , walk through

...

There are four random values and according to the upper , the left neighbor and the right
border a fitting tile is chosen. 

I modified the code a little, just to make sure it's possible to walk through all the rooms. 

Try it out now ! (what are you waiting for btw)
