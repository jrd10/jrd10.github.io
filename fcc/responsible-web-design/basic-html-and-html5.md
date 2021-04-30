>https://freecodecamp.org/learn/responsive-web-design  
> Elements: h1, ... ; Attributes: title, ... ; Attribute value: "_blank"  
> Always minimalize

# Basic HTML and HTML5.
> HTML is a markup language that uses a special syntax or notation to describe the structure of a webpage to the browser.  
> HTML elements usually have opening and closing tags that surround and give meaning to content.  

## Les principaux éléments en html :)

- Head elements
  -`<h1>Hello >orld</h1>`
  - From h1 (bigger) up to h6 (smallest)

- Paragraphe element
  - `<p>I'm a paragraph!</p>`  

- Comment a program
  - `<!-- Ceci est un commentaire qui ne sera pas exécuter (sauf cas spécifique) -->`
  - In order to comment your code or to isolate some lignes of code

- Add an image (`img`)
  - `<img src="link to your image with .xxx" alt="text description" title="text when mouse over image"> - 

- Link to external page with anchor (<a>) element
  - `<a href="Lien vers la page" title="Text when mouse over link text">Link text</a>`

- Link to internal section of your page with anchor (<a>) element
  - First, create an `id` attribute : `<h2 id="link_here">My text</h2>`
  - Secondly, create un link to this 'id' : `<a href="#link_here" title="">to id attribute</a>`

- Nest an Anchor Element within a Paragraph
- `target` attribute to open the link in a new tab
  - `< ... target="_blank" ... >`

- Dead link with hash (#) symbol (for test or maintenance)
  - `< ... href="#" ... >`

- Turn an image into a link
  - `<a ..><img ... ></a>`
  - Insert the image as link text

- Bulleted Unordered list
```
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>

```

- Ordered list
```
<ol>
  <li>milk</li>
  <li>cheese</li>
</ol>

```

## Introduction of HTML5 elements
- `main`, `header`, `footer`, `nav`, `video`, `article`, `section`
- Allow to structure all the code

## Web forms with `input` and `form` attributs
- Several attributes has to be known
- Text input
  - `<input type="text">`: <input type="text">
  - Add a `placeorder` in the text field
  - `<input type="text" placeholder="Ceci est mon placehorder."`
- web form general code
```
<form action="url-where-you-want-to-submit-form-data">
  <inut>
</form>
```
- Add a 'submit' button
  - Inside and often at the end of the form code
```
<form action="link">
  ...
  <button type="submit">Button text</button>
</form>
```

- Make text required
`<input type="text" required>`

- Set of radio buttons
- Be attentive to `name` and `label`
```
<form action="link">
  ...
  <input type="radio" name="radio button group name">Radio button text 
  ...
</form>
```
 - It is a good practice to use `id` and `label for="id name"` for each radio button
  - Each radio button wrapped in its own label. `for` is for each radio button `input` `id`
  - Same `name` for radio buttons of the same group 
```
<form action="https://#">
    <label for="indoor"><input id="indoor" type="radio" name="indoor-outdoor"> Indoor</label>
    <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor"> Outdoor</label><br>
    ...
    <button type="submit">Submit</button>
  </form>
  ```
- `for` is for "input" id and `name` to group radio button
```
<form>
  <label for="this-id"><input type="radio" id="this-id" name="the-group">Indoor</label>  
  <label for="other-id"><input type="radio" id="other-id" name="the-group">Outdoor</label>    
  ...
  <button type="submit">Test it!</button>
<form>
```


