# HTML-CSS
**HTML** - makes the structure of the webpage
**CS** - makes the page stylish
**JS** - Makes the page more interactive

#HTML

**HTML** consists of tags with which we can structure the web page
The structure of the tag is
![image](https://user-images.githubusercontent.com/48470508/182291650-8dca1421-35d0-4dbf-a84f-4873d2f39247.png)<br/>
There are some elements which doesnt have a closing tag known as empty elements becoz they dont wrap any content


**CS** - Casacde styel sheets

basic syntax


![image](https://user-images.githubusercontent.com/48470508/182335284-22e2364d-fd69-4050-af9c-21e3a232053e.png)<br/>

`````
*{
}
``````

Hastrick is used as universal selector

Type selector

``````````````
h1{
}
``````````````````
a type selector is selecting by using html elements<br/>


Class selector
```````````````````
.class{
}
```````````````````
```````````````````````
<h1 class="class"> done</h1>
````````````````````````````````````

we can use the class selector in multiple html elements by assigning it to a class

We can use multiple class for a sample element by providing a space

**id selector**

Id selector is sample as class selector but u can use an id for a single element only

`````````````````
#id{
}
````````````````````

>The major difference between classes and IDs is that an element can only have one ID. An ID cannot be repeated on a single page, and the ID attribute should not contain any whitespace at all.


**Grouping Selector**

````````````````````````````````````````````
.read {
  color: white;
  background-color: black;
  /* several unique declarations */
}

.unread {
  color: white;
  background-color: black;
  /* several unique declarations */
}
```````````````````````````````````````````````````



Both unread and red have same properties . So, we can group them as below

``````````````````````````````````````
.read,
.unread{
color:white;
background-color:black;
}
```````````````````````````````````````````


**Chain selector**

we can also do chaining of multiple class or classed with id without giving space

``````````````````````````
<div>
  <div class="subsection header">Latest Posts</div>
  <p class="subsection preview">This is where a preview for a post might go.</p>
</div>
``````````````````````````````````````
```````````````````````````````
.subsection.header {
  color: red;
}
`````````````````````````````

Descendent combinator

```````````````````````
<!-- index.html -->

<div class="ancestor"> <!-- A -->
  <div class="contents"> <!-- B -->
    <div class="contents"> <!-- C -->
    </div>
  </div>
</div>

<div class="contents"></div> <!-- D -->

/* styles.css */

.ancestor .contents {
  /* some declarations */
}
``````````````````````````````````
by using about css only B and C elements are selected<br/>
**CSS Box Model**

![image](https://user-images.githubusercontent.com/48470508/182448554-4c87654f-bd25-4aac-8f4a-5b77b1fad13e.png)




