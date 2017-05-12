[v0.0.6](https://github.com/littleflute/a22/edit/master/3/18/readme.md)

[show this page](https://littleflute.github.io/a22/3/18)

[home](..)

<audio controls id="player"> 
  <source src="https://littleflute.github.io/a22/3/18/01 1 Gender in contemporary Democracy.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 
 
for(var n=1; n<=12; n++)
{	
 	html += fNewBtn(n);

}  
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/a22/3/18/";
    if(i==1)
    {
    	s +="01 1 Gender in contemporary Democracy.mp3";
    }  
    else if(i==2)
    {
    	s +="02 Lecture 35.mp3";
    }
    else if(i==3)
    {
    	s +="03 Lecture 35.mp3";
    } 
    else if(i==4)
    {
    	s +="04 Lecture 35.mp3";
    } 
    else if(i==5)
    {
    	s +="05 Lecture 35.mp3";
    } 
    else if(i==6)
    {
    	s +="06 Lecture 35.mp3";
    } 
    else if(i==7)
    {
    	s +="07 Lecture 36 Contemporary cultural change.mp3";
    } 
    else if(i==8)
    {
    	s +="08 Lecture 36.mp3";
    } 
    else if(i==9)
    {
    	s +="09 Lecture 36.mp3";
    } 
    else if(i==10)
    {
    	s +="10 x.mp3";
    }
    else if(i==11)
    {
    	s +="11 xi.mp3";
    }
    else if(i==12)
    {
    	s +="12 xii.mp3";
    }
    else 
    {
    	if(i<10) 
    	{
    		s += "0";
    	} 
    	s += i;
    	s += " ";
    	s += i;
    	s += ".mp3";
    }
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
 
</script>
