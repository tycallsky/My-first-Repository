# My-first-Repository
My very first repository on Github

/*MAKE THE USER PICK A NUMBER AND LOG TO THE CONSOLE THE NUMBER OF TIMES*/

var number=prompt("pick a number.");
var counter = 1;

for (i=0;i<number;i++) {
    console.log("I'm looping until you tell me to quit. I've looped " + counter + " times.");
    counter++;
};


    





/*Practicing data arrays in JavaScript*/
var userFaction = prompt("fire, water, earth, or air");


if (userFaction === "fire") {
    var junkData = [100, 5, 15]
}
else if (userFaction === "water") {
    var junkData = [200, 6, 10]
}
else if (userFaction === "earth") {
    var junkData = [300, 7, 5]
}
else if (userFaction === "air") {
    var junkData = [400, 8, 3]
}


if (junkData[0] <= 200) {
    console.log ("You don't have enough health. A meteor crashes into you and you die!")
}
else {
    console.log ("you are a strong and heatlhy person. Keep on fightin'")
}
