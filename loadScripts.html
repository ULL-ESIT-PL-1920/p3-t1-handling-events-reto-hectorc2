<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
  <body>
    <p id="out"></p>
    <script>
      'use strict';
      let out = document.querySelector('p');
      function loadScript(src, callback) {
          let script = document.createElement('script');
          script.src = src;
          
          script.onload = () => callback(null, script);
          script.onerror = () => callback(new Error(`Script load error for ${src}`));
          
          document.head.append(script);
      }
      
      function loadScripts (scriptArray, cb){
          loadScripts2(scriptArray, cb, 0, []);
      }
      
      function loadScripts2 (scriptArray, cb, current, scripts){
          if (current < scriptArray.length){
              loadScript(scriptArray [current], (error, script) => {
                  if (error) {
                      cb (error);
                  } else {
                      scripts.push (script);
                      loadScripts2 (scriptArray, cb, current + 1, scripts);
                  }
              });
          } else {
              cb (null, scripts);
          }
      }
      
      loadScripts(['script-1.js', 'script-2.js', 'script-3.js'], (err, results) => out.innerHTML = results.map(s => s.src).join("<br/>"));
      </script>      
  </body>  
</html>







