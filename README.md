# My_life_in_weeks_JS

function lifeInWeeks(age) {
var yearsRemaining = 90 - age;
var days =  yearsRemaining *365;
var weeks = yearsRemaining * 52;
var month = yearsRemaining * 12;

Console.log(«You have «+days+» days, «+weeks+» weeks, and «+months+» months left.»); 
}

lifeInWeeks(30);
