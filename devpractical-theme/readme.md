keyword: 
---
10K – 100K
css box shadow
border shadow css
css drop shadow
---
1K – 10K
background shadow css
box bottom shadow css
box shadow inner
shadow html
box shadow bootstrap
css box shadow examples
button shadow css
css inner shadow
background shadow css
---
100-1k
div shadow in css
inner box shadow css
hover shadow css
css box shadow blur
nice box shadow css
css outer shadow
rounded box shadow css
---
10-100
box shadow bottom in css
---
10 – 100
how to remove box shadow
how to add border shadow in css
how to make border shadow in css
---
0 – 10
how do you shadow a border in css
how to shadow a border in css
how do you put a shadow on an image in css
0 – 10
how to put a shadow on an image in css
0 – 10
how do you get rid of shadow on one side
0 – 10
how to get rid of shadow on one side
0 – 10
how to get a box shadow on all sides
0 – 10
how do you get a box shadow on all sides
0 – 10

## How to make box bottom shadow in HTML & CSS
url: /bottom-shadow-in-css/
keyword: box bottom shadow css 1k-10k
other: box shadow border bottom, border shadow css bottom only

You can by create a box shadow border bottom only by 
Giving the spread radius a negative value of the same size as the blur radius.


Create a playit demo on this post like the w3schools( use inline css)

box-shadow: none|h-offset v-offset blur spread color |inset|initial|inherit;
h-offset	Required. The horizontal offset of the shadow. A positive value puts the shadow on the right side of the box, a negative value puts the shadow on the left side of the box	
v-offset	Required. The vertical offset of the shadow. A positive value puts the shadow below the box, a negative value puts the shadow above the box
blur	Optional. The blur radius. The higher the number, the more blurred the shadow will be	
spread	Optional. The spread radius. A positive value increases the size of the shadow, a negative value decreases the size of the shadow

Sources: 
https://css-tricks.com/snippets/css/css-box-shadow/



## How do you get a box shadow on all sides?

## How do you make an inner box shadow?

## How do you get rid of shadow on one side?
https://stackoverflow.com/questions/5460129/how-to-create-a-drop-shadow-only-on-one-side-of-an-element

.shadow {
  box-shadow: 0 4px 4px black;
  clip-path: polygon(0 0, 100% 0, 100% 200%, 0 200%);
}


Copied code snippet:
.shadow {
  box-shadow: 0 0 8px 5px rgba(200, 0, 0, 0.5);
}
.shadow-top {
  clip-path: polygon(0% -20%, 100% -20%, 100% 100%, 0% 100%);
}
.shadow-right {
  clip-path: polygon(0% 0%, 120% 0%, 120% 100%, 0% 100%);
}
.shadow-bottom {
  clip-path: polygon(0% 0%, 100% 0%, 100% 120%, 0% 120%);
}
.shadow-left {
  clip-path: polygon(-20% 0%, 100% 0%, 100% 100%, -20% 100%);
}

.shadow-bottom-right {
  clip-path: polygon(0% 0%, 120% 0%, 120% 120%, 0% 120%);
}

/* layout for example */
.box {
  display: inline-block;
  vertical-align: top;
  background: #338484;
  color: #fff;
  width: 4em;
  height: 2em;
  margin: 1em;
  padding: 1em;
}
<div class="box">none</div>
<div class="box shadow shadow-all">all</div>
<div class="box shadow shadow-top">top</div>
<div class="box shadow shadow-right">right</div>
<div class="box shadow shadow-bottom">bottom</div>
<div class="box shadow shadow-left">left</div>
<div class="box shadow shadow-bottom-right">bottom right</div>

https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path

## How do you shadow a border in CSS?

## How do you put a shadow on an image in CSS?
- How do you add a shadow to an image in HTML?

