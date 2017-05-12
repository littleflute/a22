[v0.0.5](https://github.com/littleflute/a22/edit/master/2/9/readme.md)

[show this page](https://littleflute.github.io/a22/2/9)

[home](..)



<audio controls id="player"> 
  <source src="https://littleflute.github.io/a22/2/9/01 1 Civilization in the Americas and in Africa.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 

html += fNewBtn1();
  
for(var n=2; n<=4; n++)
{	
 	html += fNewBtn(n);

} 
html += fNewBtn5();
html += fNewBtn6();
html += fNewBtn7();
html += fNewBtn8();
html += fNewBtn9();
html += fNewBtn10();
html += fNewBtn11();
html += fNewBtn12();
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/a22/2/9/";
    if(i<10) 
    {
    	s += "0";
    } 
    s += i;
    s += " Track ";
    s += i;
    s += ".mp3";
    
	p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}

function fNewBtn1()
{
	var rHTML = "";
    rHTML = "<button onclick='https://littleflute.github.io/a22/2/9/01 1 Civilization in the Americas and in Africa.mp3'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
function fNewBtn5()
{
	var rHTML = "";
    rHTML = "<button onclick='https://littleflute.github.io/a22/2/9/05 Lecture 17.mp3'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
function fNewBtn6()
{
	var rHTML = "";
    rHTML = "<button onclick='https://littleflute.github.io/a22/2/9/06 Lecture 17.mp3'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
function fNewBtn7()
{
	var rHTML = "";
    rHTML = "<button onclick='https://littleflute.github.io/a22/2/9/07 7 The World in 1450.mp3'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}

function fNewBtn8()
{
	var rHTML = "";
    rHTML = "<button onclick='https://littleflute.github.io/a22/2/9/08 Lecture 18.mp3'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
function fNewBtn9()
{
	var rHTML = "";
    rHTML = "<button onclick='https://littleflute.github.io/a22/2/9/09 Lecture 18.mp3'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
function fNewBtn10()
{
	var rHTML = "";
    rHTML = "<button onclick='https://littleflute.github.io/a22/2/9/10 Lecture 18.mp3'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}

function fNewBtn11()
{
	var rHTML = "";
    rHTML = "<button onclick='https://littleflute.github.io/a22/2/9/11 Lecture 18.mp3'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
function fNewBtn12()
{
	var rHTML = "";
    rHTML = "<button onclick='https://littleflute.github.io/a22/2/9/12 Lecture 18.mp3'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>



