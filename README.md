[v0.1.7](https://github.com/littleflute/a22/edit/master/README.md)

[show this page](https://littleflute.github.io/a22/)

[II](2) -> 
<button><a href="2/7">cd07</a></button>
<button><a href="2/8">cd08</a></button>
<button><a href="2/9">cd09</a></button>
<button><a href="2/10">cd10</a></button>
<button><a href="2/12">cd12</a></button> 

[III](3)-> 
<button><a href="3/13">cd13</a></button>
<button><a href="3/14">cd14</a></button>
<button><a href="3/15">cd15</a></button>
<button><a href="3/16">cd16</a></button>
<button><a href="3/17">cd17</a></button> 
<button><a href="3/18">cd18</a></button> 

<audio controls id="player"> 
  <source src="https://littleflute.github.io/a22/2/7/01 Track 1.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 

html += fNewBtn(1);
html += fNewBtn(2);
html += fNewBtn(3);
html += fNewBtn(4);
html += fNewBtn(5);
html += fNewBtn(6);
html += fNewBtn(7);
 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/a22/2/7/0";
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
</script>












## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/littleflute/a22/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/littleflute/a22/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
