  to  Everyone
// 1. declare 5 sass variables and use them in rulesets


// 2. declare sass nested selectors that will generate this css
// .container .box {
//   background-color: yellow;
//   border: 1px solid black;
// }

// .container .box .button {
//   color: green;
// }

// .container .box.link {
//   color: blue;
// }

// .container .box.link:hover {
//   color: purple;
// }


// 3. declare and apply a mixin that will apply a ruleset to the hover, focus, and active state of a selector
// example css output
// }
// .class-example2 {
//     @include example;
// }
// .example1{
//   @include color-change;
// }

// .example2{
//   @include color-change;
// }


// .example1:hover {
//   color: red;
// }
// .example1:focus {
//   color: orange;
// }
// .example1:active {
//   color: blue;
// }

// .example2:hover {
//   color: red;
// }
// .example2:focus {
//   color: orange;
// }
// .example2:active {
//   color: blue;
// }


// 4. declare and apply a mixin that will apply a ruleset to the hover, focus, and active state of a selector with the values from a parameter
// example css output
// .example1 {
//   @include example(red)
// }

// .example1:hover {
//   color: red;
// }
// .example1:focus {
//   color: red;
// }
// .example1:active {
//   color: red;
// }


// 5. write a function that will return 50% if the parameter passed in is red and 100% if the parameter is blue, and 0% if anything else


// 6. write a loop that will generate .col-md-X selectors where X is a number from 1-12 and the ruleset of each selector is width: Y% where Y is 100/(12/X)

