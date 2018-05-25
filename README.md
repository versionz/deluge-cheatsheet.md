# Deluge Cheat Sheet

#### Kit Tracks

| Function  |  Shortcut |
| :------------ |:---------------|
| Change colour of a specific kit row 	| Shift + Audition pad + turn ▼▲ knob |
| Create new kit 			| Shift + Kit |
| Slice sample				| Shift + Kit, turn Select knob to find sample, Shift + push Select knob |
| Record sample from input		| Audition pad + Record to start, Record to end |
| CV trig kit row 			| Audition pad + push and turn Select knob |
| Move row      			| Audition pad + hold down & turn ▼▲ knob |
| Delete row				| Hold Grid pad on row to delete + press Save/Delete |


references

v 2
https://horche.demkontinuum.de/Deluge%20Cheat%20Sheet.pdf

v1
https://synthstrom.com/app/uploads/2018/03/Deluge-Popular_Commands.pdf


---

### a larger view of the shift menu functions

![alt text](http://forums.synthstrom.com/uploads/editor/2y/z0lpcbgyol4g.png "Logo Title Text 1")

#### Markdown format examples
---
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### sHeading 6	

---

Paragraph
text `Inline Code` text		
~~Mistaken text.~~	
*Italics*	
**Bold**	

---

Tasks
- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**
- [ ] incomplete
- [x] completed

---

Code Blocks

    4 space indention
    makes full-width
    standard code blocks

```js
var now = new Date();

var days = new Array('Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday');

var months = new Array('January','February','March','April','May','June','July','August','September','October','November','December');

var date = ((now.getDate()<10) ? "0" : "")+ now.getDate();

function fourdigits(number)	{
	return (number < 1000) ? number + 1900 : number;
								}
today =  days[now.getDay()] + ", " +
         months[now.getMonth()] + " " +
         date + ", " +
         (fourdigits(now.getYear())) ;

document.write(today);
```

```css
#sc_drag_area {
  height:100px;
  left:150px;
  position: absolute;
  top:100px;
  width:250px;
  z-index: 9999;
}
```

---

* List item one
* List item two
    * A nested item

---

1. Number list item one		
	1.1. A nested item
2. Number list item two
3. Number list item three

---

> Quote
> 
> Second line Quote

---

Standard link =  http://ghost.org	
[Custom Text Link](http://ghost.org)



---


