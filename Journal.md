# Binary Counter

I'm building a binary counter that uses LEDs to show 1s and 0s.

## 4/17/2026 - Brainstorming and Schematic

I brainstormed stuff on what to make. Was originally going to make a comparison system between decimal and binary counting but then I realized that it was going to QUICKLY get very packed. For just simply 4 bits and the decimal max of LEDs I would need about 19 LEDs, 2 CD4017s, and a CD4040 which was not going to fit on a 10x10cm board. I instead decided to only count the binary values with a button for incrementing and resetting the LEDs. I plan to make it count up to 255 with 8 bits. I also shoved the parts onto the schematic for now. Will connect them together when I return home.

![[Image1.png|261]]

### Time Spent: 0.7 Hours

## 4/17/2026 - Finished Schematic
I put together all of the parts. Turns out I had to put resistors in between the buttons and the clock and reset ports cause of something known as pull-up resistors because too much high of a current may cause the IC to skip numbers. I don't fully understand it so I'll study it more in-depth later.

![[Image2.png]]

### Time Spent: 0.5 Hours

## 4/17/2026 - Back Circuits

I put all the parts on the board and complete the circuits for the back. The switches were a bit annoying however I managed to make it so none of them were blocking out words on the silkscreen.

![[Image3.png]]

### Time Spent: 0.5 Hours

## 4/17/2026 - Finished

I added on the front circuits, fixed the silk screens, and added the values. Took me a while to complete. The front circuits were a pain because I needed to make sure they wouldn't block out the silkscreens.
![[Image4.png]]
### Time Spent: 0.8 Hours
