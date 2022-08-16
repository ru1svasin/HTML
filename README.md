<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML,CSS,XML,JavaScript">
  <meta name="author" content="John Doe">
  <link rel="stylesheet" href="style.css">
  <style>
    .background {
      background-color: black;
      color: white;
    }
  </style>
  <title>codeSTACKr</title>
</head>
<body>
  <!-- Headings -->
  <h1>Hello World</h1>
  <h2>Hello World</h2>
  <h3>Hello World</h3>
  <h4>Hello World</h4>
  <h5>Hello World</h5>
  <h6>Hello World</h6>

  <hr>
  
  <!-- Paragraphs -->
  <div>
    <p title="This is a tooltip">Lorem ipsum dolor sit, <strong>amet</strong> consectetur <em>adipisicing</em> elit. Adipisci necessitatibus consectetur debitis. Molestias dolore architecto asperiores facere, est sed adipisci quia dignissimos, aliquid eligendi sit eveniet. Sed perferendis excepturi minus!</p>
    <p>Lorem ipsum dolor sit, amet <mark>consectetur</mark> adipisicing elit. Adipisci necessitatibus consectetur debitis. Molestias dolore <small>architecto</small> asperiores facere, <span style="color:red">est sed adipisci quia dignissimos</span>, <del>aliquid</del> eligendi sit eveniet. Sed perferendis excepturi minus!</p>
    <p class="background">Lorem ipsum dolor sit, amet <ins>consectetur</ins> adipisicing elit. Adipisci necessitatibus consectetur debitis. Molestias dolore architecto <sub>asperiores</sub> facere, est sed adipisci quia dignissimos, aliquid <sup>eligendi</sup> sit eveniet. Sed perferendis excepturi minus!</p>
  </div>

  <!-- Image and Bookmark -->
  <a href="#bookmark">
    <img src="banner.png" alt="alternate description here" width="400">
  </a>

  <br><br>
  <a href="https://www.google.com">Google</a>
  
  <hr>

  <!-- List Examples -->
  <ol type="1" start="25">
    <li>List Item 1</li>
      <ul>
        <li>Sub Bullet 1</li>
        <li>Sub Bullet 2</li>
      </ul>
    <li>List Item 2</li>
    <li>List Item 3</li>
    <li>List Item 4</li>
    <li>List Item 5</li>
  </ol>

  <br><hr><br>

  <!-- Table Examples -->
  <table>
    <caption>This is a caption</caption>
    <thead>
      <tr>
        <th>First Name</th>
        <th>Last Name</th>
        <th>Age</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Jill</td>
        <td>Smith</td>
        <td>25</td>
      </tr>
      <tr>
        <td>Eve</td>
        <td>Jackson</td>
        <td>35</td>
      </tr>
    </tbody>
  </table>
  <br>
  <table>
    <thead>
      <tr>
        <th>Name</th>
        <th colspan="2">Telephone</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Jill Smith</td>
        <td>555-555-5555</td>
        <td>777-777-7777</td>
      </tr>
    </tbody>
  </table>
  <br>
  <table>
    <tr>
      <th>Name:</th>
      <td>Jill Smith</td>
    </tr>
    <tr>
      <th rowspan="2">Telephone:</th>
      <td>555-555-5555</td>
    </tr>
    <tr>
      <td>777-777-7777</td>
    </tr>
  </table>

  <br>
  <hr>
  <br>

  <!-- Form Example -->
  <form action="server.php">
    <fieldset>
      <legend>Personal information:</legend>
      First Name:<br>
      <input type="text" name="firstname" value="" placeholder="First Name Here"><br>
      Last Name:<br>
      <input type="text" name="lastname" value=""><br>
      <input type="radio" name="options"> Option 1
      <input type="radio" name="options"> Option 2<br>
      <input type="checkbox" name="checkboxes" checked> Checkbox 1
      <input type="checkbox" name="checkboxes"> Checkbox 2
      <input type="checkbox" name="checkboxes"> Checkbox 3<br>
      <label for="carSelect">Select:</label>
      <select name="cars" id="carSelect" multiple>
        <option value="BMW" selected>BMW</option>
        <option value="Volvo">Volvo</option>
        <option value="Audi">Audi</option>
      </select>
      <br><br>
      <input type="submit" value="Submit">
    </fieldset>
  </form>

  <hr>

  <!-- Button -->
  <button>Click Me</button>

  <hr>
  
  <!-- Bookmarked Paragraph -->
  <p id="bookmark">this is a paragraph</p>











  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
</body>
</html>
