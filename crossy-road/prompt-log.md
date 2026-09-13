# Crossy Road Prompt Log
### AI Model: Kiro and ChatGPT Codex

## Attempt 1
For context: https://www.cs.cmu.edu/~113/hw2.html please read all of this. We will adhere to these guidelines.
So, we are creating crossy road. Let's just start with the fundamentals of crossy road - functionality first, and then we can fix the graphics later. The important thing to note is the 2.5D visuals. We will start from scratch and I will copy paste into my VSCode. Also, is there anyway to directly add codex to vscode? 
Ask any clarifying questions necessary before beginning.

Looks good! Let's do perspective and movement now!

ok now moving on, could you recreate the crossy road visual 1to1? And maybe tokens if htey will help you? I think the angle is off on what weve created and it makes it hard to see where the chicken is.

we need less cars and the angle is still incorrect, but the function looks good. could we also add smoother jump to the chicken like in the real game

ok some small fixes:
1. make roads extend to the side of the screen
2. make chicken turn when we go left right or backwards
3. also the angle is still a bit wrong, should be like a top left view. see photo
4. correct the textures to the logs, maybe water textures if you want to

ok next:
1. for some reason everything is all blue water now?
1. shouldnt be able to jump over the trees right? not sure though because i don't play crossy road

Inspect `index.html`, find why the canvas is one solid color, and fix it. Make the edits directly.

the angle is extremely incorrect. please take a look and reset yourself to adjust it to the correct angle. 2.5 dimensions. 

1. extend the grass to the sides. it is incomplete. 
2. no spawning on trees
3. the water animatino looks like its glitching?
4. now the chicken and trees seem to be transparent? please fix this because of the 2.5D projection. it still looks incorrect, ive attached a photo. please recreate the photo exactly. 

## Attempt 2
in index.html, recreate crossy road as best you can. focus first on mirroring this visual, and then we can change any functional parts later. any questions?

looks like the orientation of the chicken is wrong and the score seems buggy ( has a lot of decimal points). the chicken si very cute though! also the roads are cutoff, can you either make them extend to the edge of the page or zoom in so we can not see the end of them?

nice! there is no log on the first river though so its impossibleto pass. also the screen shaking is a bit naseous, can you remove or tone it down?

less logs and more random space between them. and make it so we cant go thru trees. sure match the og crossy road dififculty

could you make the logs a bit more sporadic. also try and extend the plane to the edges especially after we start getting good and hitting the end? and sometimes multiple cars are overlapping and we fall off logs while standing on them