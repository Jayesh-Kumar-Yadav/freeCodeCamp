---
id: bad87fee1348cd8acdf08812
title: Create a Bootstrap Button
challengeType: 0
videoUrl: ''
localeTitle: إنشاء زر Bootstrap
---

## Description
<section id="description"> يحتوي Bootstrap على أنماطه الخاصة لعناصر <code>button</code> ، والتي تبدو أفضل بكثير من تلك الخاصة بتنسيق HTML العادي. أنشئ عنصرًا <code>button</code> جديدًا أسفل صورتك الكبيرة المضحكة. اعطها فئات <code>btn</code> و <code>btn-default</code> ، بالإضافة إلى نص &quot;Like&quot;. </section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: إنشاء عنصر <code>button</code> جديد مع النص &quot;أعجبني&quot;.
    testString: 'assert(new RegExp("like","gi").test($("button").text()) && ($("img.img-responsive + button.btn").length > 0), "Create a new <code>button</code> element with the text "Like".");'
  - text: 'يجب أن يحتوي الزر الجديد على فئتين: <code>btn</code> و <code>btn-default</code> .'
    testString: 'assert($("button").hasClass("btn") && $("button").hasClass("btn-default"), "Your new button should have two classes: <code>btn</code> and <code>btn-default</code>.");'
  - text: تأكد من أن جميع عناصر <code>button</code> لديك بها علامة إغلاق.
    testString: 'assert(code.match(/<\/button>/g) && code.match(/<button/g) && code.match(/<\/button>/g).length === code.match(/<button/g).length, "Make sure all your <code>button</code> elements have a closing tag.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
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

  <a href="#"><img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <img src="https://bit.ly/fcc-running-cats" class="img-responsive" alt="Three kittens running towards the camera.">

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
  <form action="https://freecatphotoapp.com/submit-cat-photo">
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

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
