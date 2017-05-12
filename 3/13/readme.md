[v0.0.6](https://github.com/littleflute/a22/edit/master/3/13/readme.md)

[show this page](https://littleflute.github.io/a22/3/13)

[home](..)



<audio controls id="player"> 
  <source src="https://littleflute.github.io/a22/3/13/01 1 Abolition of Slavery and Serfdom.mp3" type="audio/mpeg">
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
    var s = "https://littleflute.github.io/a22/3/13/";
    if(i==1)
    {
    	s +="01 1 Abolition of Slavery and Serfdom.mp3";
    }  
    else if(i==7)
    {
    	s +="07 7 Modernization and Nationalisms.mp3";
    }
    else if(i==8)
    {
    	s +="08 26-02.mp3";
    }
    else if(i==9)
    {
    	s +="09 26-03.mp3";
    }
    else if(i==10)
    {
    	s +="10 26-04.mp3";
    }
    else if(i==11)
    {
    	s +="11 26-05.mp3";
    }
    else if(i==12)
    {
    	s +="12 26-06.mp3";
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



