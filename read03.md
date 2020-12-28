
Lists:
There is three types of lists orederd lists which will be numbered,unordered list which will begin with bullet points,
and definition list which are made up of a set of terms along with thedefinitions for each of those terms.

1. orederd lists <ol> uses this element and each item in the list is placedbetween an opening <li> tagand a closing </li> tag.
 (The li stands for list item.) 



2. unordered lists <ul> uses this element <li> Each item in the list is placed between an opening <li> tag and a closing </li> tag.
 (The li stands for list item.)


3. Definition Lists <dl> uses thid element and inside there is pairs <dt> to contain the term being defined and  <dd> to contain the
 definition.




4. Nested lists You can put a second list insidean <li> element to create a sublist.



 
Boxes:

You can set several properties that affect the appearance of these boxes like Boxes dimensions width, height. on the units used 
to make the dimensions are pixels, percentages, or ems. Now when using percentages,the size of the box is relative tothe size of the browser window.when using ems the sizeof the box is based on the sizeof text within it.


 
 **limiting width min and max width
 min-width property specifiesthe smallest size a box can be displayed at when the browser window is narrow.
 max-width property indicates the maximum width a box can stretch to when the browser window is wide.

 **limiting heights min-height, max-height
 min-height by using the min-height the same as min-width
 max-heigh  by using the max-heigh  the same as max-width

 Borders :

 border-width  is used to control the width of a border.value of this property can either be given
in pixels or thin ,medium ,thick. or you can use the percentage. 


border-style to control the style of a border and the values as follow :

solid a single solid line.
dotted a series of square dots
(if your border is 2px wide, then
the dots are 2px squared with a
2px gap between each dot)
dashed a series of short lines.
double two solid lines (the
value of the border-width
property creates the sum of the
two lines).
groove appears to be carved
into the page.
ridge appears to stick out from
the page.
inset appears embedded into
the page.
outset looks like it is coming
out of the screen.

margin : to control the gap between boxes. Its value is commonly given in pixels, although you may also use percentages or ems.
 
 for specifications :
 margin-top
margin-right
margin-bottom
margin-left

Variables :

n the basic javascript instructios.at first there is variables stores the bits temporarily.variable is a good name for thisconcept because the data storedin a variable can change (or vary)each time a script runs. for example var age = 25; and so on. or store a string var name = "Ahmad"; .or to store a boolean. 
for example var number = true or var number = fals . Also there is math operation in javascript like sum
suntract.division,multiplications,incerment and decrement.

USING LOGICAL AND:
true & true = true
true & false = false
false & true = false
false & false = false

USING LOGICAL OR:
true || true = true
true || false = true 
false || true = true
false || false = false


if and if else  statments:

Using for loops needs to have at first a condition apply then applying the condition if it was correct. and if it was not correct you use the  the else statment for example if ({)condition ) then aplly if its correct. if its not you write else  statment. operators equal == != not equal === srtict equal  !== strict not equal > greater than < less that =>greater tghan or equal.

switch :
As shown in the example below when using the switch you need at first to call the function then you the case then
you can alert what do you want then the break it means that the cas is ended. Also,you can add multipile casses
inside one case.



switch (level) {
case 1:
msg = 'Good luck on the first test ' ;
break;
case 2:
msg = 'Second of three - keep going!';
break;
case 3:
msg = ' Final round, almost there!';
break;
default :
msg = 'Good l uck!';
break;
}

For loops :

As shown in the example below you need to initialize the foor loop in this case it is var a = 10.Then the condition
a<10. Then the update which we choose to increment the value by 1  a++.

for (var a = 10; a<10; a++>){

    document.write(a);
}
