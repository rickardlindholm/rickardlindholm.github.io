## Welcome to GitHub Pages

Nu la jag till lite extra och nu vill jag ladda ner.

Och nu tog jag bort

********************
<!-- Include the dependencies -->
<link rel="stylesheet" id="font-awesome"  href="libs/font-awesome.min.css" type="text/css" />
<script type="text/javascript" src="libs/jquery-2.1.4.min.js"></script>	
<script type="text/javascript" src="libs/ace/ace.js"></script>
<script type="text/javascript" src="libs/FileSaver.js"></script>

<!-- Include the script and css for the online php editor -->	
<link rel="stylesheet" href="css/php-einfach-online-php-editor.css" type="text/css" />
<script type="text/javascript" src="js/php-einfach-online-php-editor.js"></script>


<!-- Include this code snippet where ever you like to have it in your site -->
<div  class="code" id="code_1" data-ace-editor-id="1"
	data-ace-editor-allow-execution="true" data-ace-editor-hide-vars="false" 
	data-ace-editor-script-name="page.php" data-ace-editor-default-get="" data-ace-editor-default-post="">
<pre class="editor" id="code_editor_1" > &lt;?php
echo "Hi and welcome for our Online PHP Editor. The current time is: ".date("H:i:s")." <br />";
echo "Press the button below to execute the code";
?&gt; </pre></div>

<!-- Call this script to transform your HTML code to actual editors -->
<script>
jQuery('div[data-ace-editor-id]').each(function() {
	var url='http://execute.php-einfach.de/execute.php';
	var language = 'en'; //Choose 'de' for German
	new OnlinePHPEditor(this, language, url);
});
</script>

You can use the [editor on GitHub](https://github.com/rickardlindholm/rickardlindholm.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rickardlindholm/rickardlindholm.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
