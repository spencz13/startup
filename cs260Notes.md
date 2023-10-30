# Here we will store lecture notes and other info to use on Midterm!

## To make a website run: Enter console home on AWS website. 
## Route 53 allows you to configure the name of the server
## Domain name system (DNS) is a system that will look up a name of a site to a server.
## Each server has a unique IP adresss for a site. 
### If you set up DNS correctly in git bash for byu, you can use the "dig" command to lookup DNS info. 
### TLD (Top level domain) examples: .com .gov .gov .mil etc.

## 10/1/23: 
### Notes on startup HTML: I guess it was just edit the simon code and then put it in the workspace. Cool. HTML is easy enough and embedding content is pretty easy, so it would be simple enough to put a video or photo in.

## 10/2/23: 
### CSS: allows your webpage to adapt to the various devices that could access your site (phones, computers, etc)
### Media queries: you want your page to have a generic adaption to multiple devices (avoid setting a preset based on specific devices). You can specify orientation of the devices (portrait or horizontal) and other things.
### floats: allows text to adjust to the size of the screen and adjust the location and size of images in the page. Can determine max adjusting size and if the image will increase or decrease.
### 

## Midterm Study Guide: example questions: 

### In the following code, what does the link element do?
#### <link rel="stylesheet" href="styles.css"> The <link> tag defines the relationship between the current document and an external resource. The <link> tag is most often used to link to external style sheets or to add a favicon to your website. The <link> element is an empty element, it contains attributes only.

### In the following code,  what does a div tag do?: 
#### The <div> tag defines a division or a section in an HTML document. The <div> tag is used as a container for HTML elements - which is then styled with CSS or manipulated with JavaScript. The <div> tag is easily styled by using the class or id attribute. Any sort of content can be put inside the <div> tag! 

### In the following code, what is the difference between the #title and .grid selector? 
#### <p><abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p> <p title="Free Web tutorials">W3Schools.com</p> title example. The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element. The title attribute can be used on any HTML element (it will validate on any HTML element. However, it is not necessarily useful). Grid selector is a CSS element. 

### In the following code, what is the difference between padding and margin?
#### Padding represents the amount of inner space an element has, while the margin is whitespace available surrounding an element. It’s not possible to set padding to auto padding. However, you can use automatic settings for margins. It’s not possible to use negative values when defining padding, but you can with margins. Padding can be impacted by the styling of other elements on a website. Margin won’t be impacted by the stylization of other elements on a website. Padding: Change the size of an element, Add space between borders and content. Margin: Adjust an element's positioning, Overlap elements, Setting distance.

### Given this HTML and this CSS how will the images be displayed using flex?
#### Flexbox: the css: .flex-container {
####   display: flex; 
####   flex-direction: column; //This makes the direction of the flexbox a column from top to bottom. 
#### }

#### HTML: <div class="flex-container">
####  <div>1</div>
####  <div>2</div>
####  <div>3</div>
#### </div>

### What does the following padding CSS do?
#### If the padding property has two values:

#### padding: 25px 50px;
#### top and bottom paddings are 25px
#### right and left paddings are 50px

#### If the padding property has one value:

#### padding: 25px;
#### all four paddings are 25px

#### If the padding property has three values:

#### padding: 25px 50px 75px;
#### top padding is 25px
#### right and left paddings are 50px
#### bottom padding is 75px

#### If the padding property has four values:

#### padding: 25px 50px 75px 100px;
#### top padding is 25px
#### right padding is 50px
#### bottom padding is 75px
#### left padding is 100px

### What does the following code using arrow syntax function declaration do?
#### example const myFunc = () => {
####   // do something
#### };

#### other example: const materials = ['Hydrogen', 'Helium', 'Lithium', 'Beryllium'];
#### console.log(materials.map((material) => material.length));
#### // Expected output: Array [8, 6, 7, 9]

### What does the following code using map with an array output?
#### example of an array: const cars = ["Saab", "Volvo", "BMW"];
#### example of map with array: const array1 = [1, 4, 9, 16];
#### // Pass a function to map
#### const map1 = array1.map((x) => x * 2);
#### console.log(map1);
#### // Expected output: Array [2, 8, 18, 32]

### What does the following code output using getElementByID and addEventListener?
#### The getElementById() method returns an element with a specified value.
#### The getElementById() method returns null if the element does not exist.
#### The getElementById() method is one of the most common methods in the HTML DOM. It is used almost every time you want to read or edit an HTML element.
#### example: document.getElementById("demo");
#### example: const myElement = document.getElementById("demo");
#### example: myElement.style.color = "red";
#### example: document.getElementById("demo").style.color = "red";

### What does the following line of Javascript do using a # selector?


### Which of the following are true? (mark all that are true about the DOM)
#### The HTML DOM is a standard object model and programming interface for HTML. It defines:
#### The HTML elements as objects
#### The properties of all HTML elements
#### The methods to access all HTML elements
#### The events for all HTML elements
#### In other words: The HTML DOM is a standard for how to get, change, add, or delete HTML elements.

### By default, the HTML span element has a default CSS display property value of: 
#### The <span> HTML element is a generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element is appropriate. <span> is very much like a <div> element, but <div> is a block-level element whereas a <span> is an inline-level element.
#### The CSS display property value none will result in the HTML element not being displayed in the page in the browser. Also, it will not take up any visible space in the HTML page. Here is an example of an HTML element with its CSS display property set to none :
#### The block value for the display CSS property makes an HTML element display as a separate block. A block starts on a new line, and content after the block starts on a new line too. Look at this HTML example:
#### The inline value displays an HTML element as part of the normal text flow. Look at this HTML example:
#### The inline-block value for the display CSS property makes an HTML element display like a block, but rendered as part of the normal text flow. What does that mean?
#### When you use the inline value you cannot control the width and height of the HTML elements. The browser determines that based on the content of the elements.
#### With the inline-block you get control of the width and height of the HTML elements again, even if they are rendered as part of the normal text flow.

### How would you use CSS to change all the div elements to have a background color of red?


### How would you display an image with a hyperlink in HTML?
#### example: <a href="https://www.Youtube.com/"><img src="https://www.tutorialspoint.com/assets/questions/media/426142-1668760872.png" style="width:50px;height:50px;"></a>
#### <a href="link address"><img src="image destination"></a>

### In the CSS box model, what is the ordering of the box layers starting at the inside and working out?


### Given the following HTML, what CSS would you use to set the text "troubl" to green and leave the "double" text unaffected?


### What will the following code output when executed using a for loop and console.log?


### How would you use JavaScript to select an element with the id of “byu” and change the text color of that element to green?


### What is the opening HTML tag for a paragraph, ordered list, unordered list, second level heading, first level heading, third level heading?


### How do you declare the document type to be html?
#### <! DOCTYPE html>

### What is valid javascript syntax for if, else, for, while, switch statements?
#### if (condition1) {
####  // do something
#### } else if (condition2) {
####  // do something else
#### } else {
####  // do something if neither condition is true
#### }

#### for (let i = 0; i < 10; i++) {
####  // do something
#### }

#### while (condition) {
####  // do something
#### }

#### switch (expression) {
####  case value1:
####    // do something
####    break;
####  case value2:
####    // do something else
####    break;
####  default:
####    // do something if none of the cases match
####    break;
#### }

### What is the correct syntax for creating a javascript object?
#### const myObject = {
####  name: "John Doe",
####  age: 30
#### };
#### or
#### console.log(myObject.name); // "John Doe"

### Is is possible to add new properties to javascript objects?
#### yes: 
#### // Dot notation
#### var obj = {
####  name: "John Doe"
#### };
#### obj.age = 30;
#### console.log(obj.age); // 30
#### // Bracket notation
#### var obj = {
####  name: "John Doe"
#### };
#### obj["age"] = 30;
#### console.log(obj.age); // 30

### If you want to include JavaScript on an HTML page, which tag do you use?
#### <script></script>

### Given the following HTML, what JavaScript could you use to set the text "animal" to "crow" and leave the "fish" text unaffected?


### Which of the following correctly describes JSON?
#### JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax. It is commonly used for transmitting data in web applications (e.g., sending some data from the server to the client, so it can be displayed on a web page, or vice versa)

### What does the console command chmod, pwd, cd, ls, vim, nano, mkdir, mv, rm, man, ssh, ps, wget, sudo  do?
#### sudo: The sudo command is used to run a command as root.
#### wget: download files online
#### ps: The ps command line command is used to list processes.
#### rm: The rm command is a command-line utility for removing files and directories.
#### move/rename file locations
#### vim: edit a file
#### nano: open a file
#### ls: list the contents of a directory
#### cd: change directory
#### pwd: print working directory
#### mkdir: create a directory
#### rmdir: remove a directory
#### touch: create a file
#### cat: view the contents of a file
#### grep: search for a pattern in a file
#### sort: sort the lines of a file
#### uniq: remove duplicate lines from a file
#### wc: count the number of lines, words, and characters in a file
#### more: view a file one screen at a time
#### less: view a file one page at a time
#### head: view the first few lines of a file
#### tail: view the last few lines of a file
#### man: view the manual page for a command
#### help: get help for a command

### Which of the following console command creates a remote shell session?
#### ssh <user>@<host> <command>

### Which of the following is true when the -la parameter is specified for the ls console command?
#### Options can be combined (this is a general principle of Unix commands) - for example "ls -la" gives a long listing of all files. ls -a will list all files including hidden files (files with names beginning with a dot)

### Which of the following is true for the domain name banana.fruit.bozo.click, which is the top level domain, which is a subdomain, which is a root domain?
#### http://animals.example.com/dogs/poodle?thing=thingymajigy
#### http:// <-protocol 
#### animals <-sub-domain
#### example <-domain
#### .com <- top level domain
#### /dog <-path
#### /thing... <-parameters

### Is a web certificate is necessary to use HTTPS.
#### Yes

### Can a DNS A record can point to an IP address or another A record.
#### yes

### Port 443, 80, 22 is reserved for which protocol?

### What will the following code using Promises output when executed?
