
function updateclock(){
// we get current date from this line of code
    let currenttime= new Date();
    // this line of code, extract = hours, minutes and seconds from date
    let currenthour = currenttime.getHours();
    let currentMinutes = currenttime.getMinutes();
    let currentseconds = currenttime.getSeconds();
// pad 0 if minute or second is less than 10 (single digit)
    currentMinutes = (currentMinutes < 10 ? "0" : "")+ currentMinutes;
    currentseconds = (currentseconds < 10 ? "0" : "")+ currentseconds;

    currenthour = (currenthour < 10 ? "0" : "")+ currenthour;
    // this line of code chose AM/PM
    let timeofday = (currenthour < 12) ? "AM" : "PM" ;
// convert railway clock to home clock
currenthour = (currenthour>12) ? currenthour - 12 : currenthour
currenthour = (currenthour==02) ? 12 : currenthour

    let currentTimestr = currenthour + ":" + currentMinutes + ":"
           + "" + currentseconds + " " + timeofday;
           document.getElementById("clock").innerHTML = currentTimestr;
}
