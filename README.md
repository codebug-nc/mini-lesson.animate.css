# How to animate HTML elements using Animate.css

1. Checkout the different animations here: [https://daneden.github.io/animate.css/](https://daneden.github.io/animate.css/)
1. Add this to the `<head>` tag inside your `index.html`
        
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">
 1. Go to the project's [GitHub](https://github.com/daneden/animate.css) and look through all the possible class names
 1. Pick an HTML element and add the class `animated` and any animation name you would like. For example:
              
              <h1 class="animated bounce">Example</h1>
              
 1. You can even made the animation infinite like this:
                            
              <h1 class="animated bounce infinite">Example</h1>
 
 1. You could also add animations on click using the `addClass()` function:
      1. Add something like this to your `index.html`.
              
              <h1 id="test" >Testing on click animation</h1>
              
      1. Now add something like this to your `script.js`
      
                $("#test").click(function(){
                  $("#test").addClass("animated zoomOutRight")
                })
      
