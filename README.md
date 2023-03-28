## Three.js with webpack

Install following

```
npm install three
npm install webpack
sudo npm -g install servez
```

run following when you change something in any file

```
npx webpack --config webpack.config.js

```
To start the server

```
servez .
```



## Student README
The following project is Assignment 2 of the Computer Graphics course in Spring 2023 in IIITH.
It is a Rudimentary car game, built using original models and ThreeJs.
The story is as follows :
McQueeb Is Late For his race as usual, only this time he's utterly screwed. With only half a tank of gas in his engine, he has no Chance of finishing the Race! Luckily for him, his crew had placed fuel cans across the track for him to use, but they're in very limited quantity, so he must be careful with the cans he's using!

Also, the opponents cars are Russian Panzer V ' s from the World war 2, and it is not fun to hit them, losing too much health means it's a game over!

It might also be important to mention that although it seems like Mcqueeb can escape this predicament by simply leaving the stadium, Dr. Nigaboo has installed invisible barriers which will continuously sting poor McQueeb to death, only way to win is to finish First!

## Controls
- W to go forward
- A to go left
- S to go back
- D to go right

## Features Implemented

- [x] 3D World 
With Racetrack and Stadium and audience 
- [x] Cars
Features to keep track of for each car
1. Moving car left and right (using left and right arrow keys or A and D keys)
2. Increasing speed of car (up arrow key or W key)
3. Applying Brakes. (down arrow key or S
key)
4. Keeping track of car’s
- Health
- Fuel
- Score
- time
5. Keep Mileage/liter value.

You should have a logic for Opponent cars motion in the race. It should not be
the same for all try to make it random.
- [x] Collisions
Collision between cars reduces health
- [x] Fuel Cans
Fuel cans are randomly spawned in the racetrack , increases fuel of car. When Fuel runs out, the game finishes with a game over screen
- [x] Different Camera Views
1. Top down minmap view
2. Third person view
3. Dashboard View.

Press C to toggle views
- [x] Display (HUD)

