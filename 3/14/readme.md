[v0.0.6](https://github.com/littleflute/a22/edit/master/3/14/readme.md)

[show this page](https://littleflute.github.io/a22/3/14)

[home](..)



<audio controls id="player"> 
  <source src="https://littleflute.github.io/a22/3/14/01 1 Formation of Latin American Civilization.mp3" type="audio/mpeg">
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
    var s = "https://littleflute.github.io/a22/3/14/";
    if(i==1)
    {
    	s +="01 1 Formation of Latin American Civilization.mp3";
    }  
    else if(i==7)
    {
    	s +="07 7 China and Japan - 19th C pressures.mp3";
    }
    else if(i==8)
    {
    	s +="08 Lecture 28.mp3";
    }
    else if(i==9)
    {
    	s +="09 Lecture 28.mp3";
    }
    else if(i==10)
    {
    	s +="10 Lecture 28.mp3";
    }
    else if(i==11)
    {
    	s +="11 Lecture 28.mp3";
    }
    else if(i==12)
    {
    	s +="12 Lecture 28.mp3";
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



