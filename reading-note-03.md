# Read: 03 - HTML Lists, CSS Boxes, JS Control Flow

### html lists :

***there are three types of lists in html :
1.order list : use the(<-ol-></-ol>) element to create the list and write a text between(<-li-><-/li>) and each line will be numbered.***

***-unordered list : use the (<-ul-></-ul>) element to create an unordered list and write a text between
(<-li-><-/li>) and in each line it will be renderd with bullets.***

***3.the definitions list : this list is created using <-dl><-/dl> element
and inside it there is <-dt><-/dt> and this contain the term inside it
and <-dd><-/dd> this conatin the definition of the tag inside it***

# boxes :
### dimention box :
***from the start the box is by default big enough to hold it content, using <-div><-/div>
it forms a box and you can manipulate with the size and the height of the box,
using css you write the following---- div.box {
                                           height:300px;
                                           width:300px; }
and also you can put a limitation on the how much a box can expand or shrink{
                                                                             min-width:300px;
                                                                             max-width:400px;}
the same goes for the height of the box too and lastly there is every box have
1.border 
2.margin
3.padding***

# javascript read
***java is a series of intructions that a computer can follow each intruction is called a statement***

### Decisions and Loops :
***if statements :checks a condition if the condition is true any statement in after it is executed
and if it is false then it jumps to else if and execute it based on it being true ot false***

***switch statements :it starts with a variable called switch value and each case indicates a possible value for the variable
it goes like this :
let myname
switch(myname){
case 1:
myname='mohammad';
break;
case 2:
myname='ahmad';}
console.log();***

### loops :
***1.for loop :to run a code mulitiple times :
2.example
for(var i=0;i>=10;i++){
console.log(i);}***

***2.while loop:if you dont know how many times you need to run a code it keeps running until the condition is true
while(i>10){}
console.log();***

***3.do while :it is similar to the while loop but the diffirence is that it will run the statements
 inside the curly braces at least once even if the condition is met.
 do { 
msg += i + ' x 5 = ' + (i * 5) + '<-br I>' ;s 
i++; 
} while ( i < 1) ;
console.log();***
