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

this angle still looks wrong, should we restart?

please recreate crossy road without looking at any other files, only use index.html.

## Attempt 2
in index.html, recreate crossy road as best you can. focus first on mirroring this visual, and then we can change any functional parts later. any questions?

looks like the orientation of the chicken is wrong and the score seems buggy ( has a lot of decimal points). the chicken si very cute though! also the roads are cutoff, can you either make them extend to the edge of the page or zoom in so we can not see the end of them?

nice! there is no log on the first river though so its impossibleto pass. also the screen shaking is a bit naseous, can you remove or tone it down?

it looks like the score has some bugs, for some reason it has a lot of decimals at the end. please fix this. 

can you makethe logs a bit more frequent and add some trees/color/decorative items!

can you make it so theres a bit less trees, diff colored cars, make the logs more sporadic and less no logs then 5 logs then no logs. and if you hvae time implement the coins?

the coins look good! how much are they worth?

can you make it so there arent long spaces of no logs? and then can you make it so we cant walk through cars?

less logs and more random space between them. and make it so we cant go thru trees. sure match the og crossy road dififculty

could you make the logs a bit more sporadic. also try and extend the plane to the edges especially after we start getting good and hitting the end? and sometimes multiple cars are overlapping and we fall off logs while standing on them

perfect! could you also make the tree hitbox maybe only 1x1, and then the logs still need to be a bit more sporadic. the coins and movement all look great. also try and extend the plane to the edges

it looks like some of the cars are still merging together, could you fix this bug?

can you extend the canvas so that we aren't jumping in blue sky space forever at the end? and extend the lines to the rest of the page since you can see where it is cutoff still. 

perfect! Now could you also make it so the logs aren't 20 logs in a row then a lot of blank space for a long time

were changes saved for the extended canvas and infinite canvas tweaks?

please re-add them