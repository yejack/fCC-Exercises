#Waypoint: Use the Bootstrap Grid to Put Elements Side By Side
<a href="http://freecodecamp.com/challenges/Waypoint:%20Use%20the%20Bootstrap%20Grid%20to%20Put%20Elements%20Side%20By%20Side?solution=%3Clink%20href%3D%22http%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DLobster%22%20rel%3D%22stylesheet%22%20type%3D%22text%2Fcss%22%3E%0A%3Cstyle%3E%0A%20%20.red-text%20%7B%0A%20%20%20%20color%3A%20red%3B%0A%20%20%7D%0A%0A%20%20h2%20%7B%0A%20%20%20%20font-family%3A%20Lobster%2C%20Monospace%3B%0A%20%20%7D%0A%0A%20%20p%20%7B%0A%20%20%20%20font-size%3A%2016px%3B%0A%20%20%20%20font-family%3A%20Monospace%3B%0A%20%20%7D%0A%0A%20%20.thick-green-border%20%7B%0A%20%20%20%20border-color%3A%20green%3B%0A%20%20%20%20border-width%3A%2010px%3B%0A%20%20%20%20border-style%3A%20solid%3B%0A%20%20%20%20border-radius%3A%2050%25%3B%0A%20%20%7D%0A%0A%20%20.smaller-image%20%7B%0A%20%20%20%20width%3A%20100px%3B%0A%20%20%7D%0A%3C%2Fstyle%3E%0A%0A%3Cdiv%20class%3D%22container-fluid%22%3E%0A%20%20%3Ch2%20class%3D%22red-text%20text-center%22%3ECatPhotoApp%3C%2Fh2%3E%0A%0A%20%20%3Cp%3EClick%20here%20for%20%3Ca%20href%3D%22%23%22%3Ecat%20photos%3C%2Fa%3E.%3C%2Fp%3E%0A%0A%20%20%3Ca%20href%3D%22%23%22%3E%3Cimg%20class%3D%22smaller-image%20thick-green-border%22%20src%3D%22https%3A%2F%2Fbit.ly%2Ffcc-relaxing-cat%22%3E%3C%2Fa%3E%0A%0A%20%20%3Cimg%20src%3D%22http%3A%2F%2Fbit.ly%2Ffcc-running-cats%22%20class%3D%22img-responsive%22%3E%0A%20%20%3Cdiv%20class%3D%22row%22%3E%0A%20%20%20%20%3Cdiv%20class%3D%22col-xs-4%22%3E%3Cbutton%20class%3D%22btn%20btn-block%20btn-primary%22%3ELike%3C%2Fbutton%3E%3C%2Fdiv%3E%0A%20%20%20%20%3Cdiv%20class%3D%22col-xs-4%22%3E%3Cbutton%20class%3D%22btn%20btn-block%20btn-info%22%3EInfo%3C%2Fbutton%3E%3C%2Fdiv%3E%0A%20%20%20%20%3Cdiv%20class%3D%22col-xs-4%22%3E%3Cbutton%20class%3D%22btn%20btn-block%20btn-danger%22%3EDelete%3C%2Fbutton%3E%3C%2Fdiv%3E%0A%20%20%3C%2Fdiv%3E%0A%20%20%3Cp%3EThings%20cats%20love%3A%3C%2Fp%3E%0A%20%20%3Cul%3E%0A%20%20%20%20%3Cli%3Ecat%20nip%3C%2Fli%3E%0A%20%20%20%20%3Cli%3Elaser%20pointers%3C%2Fli%3E%0A%20%20%20%20%3Cli%3Elasagna%3C%2Fli%3E%0A%20%20%3C%2Ful%3E%0A%20%20%3Cp%3ETop%203%20things%20cats%20hate%3A%3C%2Fp%3E%0A%20%20%3Col%3E%0A%20%20%20%20%3Cli%3Eflea%20treatment%3C%2Fli%3E%0A%20%20%20%20%3Cli%3Ethunder%3C%2Fli%3E%0A%20%20%20%20%3Cli%3Eother%20cats%3C%2Fli%3E%0A%20%20%3C%2Fol%3E%0A%20%20%3Cform%20action%3D%22%2Fsubmit-cat-photo%22%3E%0A%20%20%20%20%3Clabel%3E%3Cinput%20type%3D%22radio%22%20name%3D%22indoor-outdoor%22%3E%20Indoor%3C%2Flabel%3E%0A%20%20%20%20%3Clabel%3E%3Cinput%20type%3D%22radio%22%20name%3D%22indoor-outdoor%22%3E%20Outdoor%3C%2Flabel%3E%0A%20%20%20%20%3Clabel%3E%3Cinput%20type%3D%22checkbox%22%20name%3D%22personality%22%3E%20Loving%3C%2Flabel%3E%0A%20%20%20%20%3Clabel%3E%3Cinput%20type%3D%22checkbox%22%20name%3D%22personality%22%3E%20Lazy%3C%2Flabel%3E%0A%20%20%20%20%3Clabel%3E%3Cinput%20type%3D%22checkbox%22%20name%3D%22personality%22%3E%20Crazy%3C%2Flabel%3E%0A%20%20%20%20%3Cinput%20type%3D%22text%22%20placeholder%3D%22cat%20photo%20URL%22%20required%3E%0A%20%20%20%20%3Cbutton%20type%3D%22submit%22%3ESubmit%3C%2Fbutton%3E%0A%20%20%3C%2Fform%3E%0A%3C%2Fdiv%3E%0A" target="_blank">Click here</a> to see the solution on the freeCodeCamp website.


####Instructions:
<p class="wrappable negative-10">Bootstrap uses a responsive grid system, which makes it easy to put elements into rows and specify each element&apos;s relative width. Most of Bootstrap&apos;s classes can be applied to a <code>div</code> element.</p><p class="wrappable negative-10">Here&apos;s a diagram of how Bootstrap&apos;s 12-column grid layout works:</p><p class="wrappable negative-10"><a href="http://i.imgur.com/FaYuui8.png" data-lightbox="img-enlarge"><img class="img-responsive" src="http://i.imgur.com/FaYuui8.png" title="Click to enlarge" alt="an image illustrating Bootstrap&apos;s grid system"></a></p><p class="wrappable negative-10">Note that in this illustration, the <code>col-md-*</code> class is being used. Here, <code>md</code> means medium, and <code>*</code> is a number specifying how many columns wide the element should be. In this case, the column width of an element on a medium-sized screen, such as a laptop, is being specified.</p><p class="wrappable negative-10">In the Cat Photo App that we&apos;re building, we&apos;ll use <code>col-xs-*</code>, where <code>xs</code> means extra small (like an extra-small mobile phone screen), and <code>*</code> is the number of columns specifying how many columns wide the element should be.</p><p class="wrappable negative-10">Put the <code>Like</code>, <code>Info</code> and <code>Delete</code> buttons side-by-side by nesting all three of them within one <code>&lt;div class=&quot;row&quot;&gt;</code> element, then each of them within a <code>&lt;div class=&quot;col-xs-4&quot;&gt;</code> element.</p><p class="wrappable negative-10">The <code>row</code> class is applied to a <code>div</code>, and the buttons themselves can be nested within it.</p><div class="negative-bottom-margin-30"></div>


####Answer:
```javascript
<link href="http://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }
</style>

<div class="container-fluid">
  <h2 class="red-text text-center">CatPhotoApp</h2>

  <p>Click here for <a href="#">cat photos</a>.</p>

  <a href="#"><img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat"></a>

  <img src="http://bit.ly/fcc-running-cats" class="img-responsive">
  <div class="row">
    <div class="col-xs-4"><button class="btn btn-block btn-primary">Like</button></div>
    <div class="col-xs-4"><button class="btn btn-block btn-info">Info</button></div>
    <div class="col-xs-4"><button class="btn btn-block btn-danger">Delete</button></div>
  </div>
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <label><input type="radio" name="indoor-outdoor"> Indoor</label>
    <label><input type="radio" name="indoor-outdoor"> Outdoor</label>
    <label><input type="checkbox" name="personality"> Loving</label>
    <label><input type="checkbox" name="personality"> Lazy</label>
    <label><input type="checkbox" name="personality"> Crazy</label>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</div>

```