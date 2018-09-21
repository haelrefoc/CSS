# CSS
CSS Setup
<p>
  <strong>Inlay within HTML:</strong><br>
  p style="font-family: Arial; color: red; font-size: 20px;"> XXXXXXX /p><br>
  < !-- You can add CSS within HTML under a Style tag --><br>
    head><br>
    style><br>
    CSS CODE<br>
    /style><br>
    /head>
    <p>
    <i>Example of CSS Code</i><br>
     p {<br>
      color: red;<br>
      font-size: 20px;<br>
    }<br>
    < !--This adds characteristics to all p> paragaph content --><br>
      <p>
        <strong>Linking HTML and CSS Together:</strong><br>
        head><br>
        link href="PATH or URL" type="text/css" rel="stylesheet"><br>
        /head><br>
        < !--If CSS file is stored in the same directory as your HTML file, you can specify a relative path instead of a URL -->
          <p>
            <i>Example:</i><br>
            link href="./style.css" type="text/css" rel="stylesheet">
            <p>
              <strong>CSS Characteristics:</strong><br>
              Paragraph: p { xxx }<br>
              Heading 1: h1 { xxx }<br>
              <p>
                <strong>Curly Braces Content:</strong><br>
                font-family: Arial; (ex. cursive, "courier new")<br>
                font-size: 16px;<br>
                font-weight: normal; (ex. bold)<br>
                text-align: right; (ex. left, center)<br>
                color: maroon;<br>
                background-color: blue; (kind of like a text highlight)<br>
                opacity: 0.5; (50%)<br>
                text-transform: uppercase; (ex. capitalize)<br>
                background-image: url("PLACE URL HERE");<br>
                
                <p>
                  <strong>CSS Sector for HTML:</strong><br>
                  p class="brand">XXXXXXX /p><br>
                  h1 class="title">XXXX /h1><br>
                  < !--You can also make your own sectors in style.css and then reference them later all at once in one HTML element in index.html to attribute multiple characteristics to a section in your code --><br>
            <i>Example</i> .green { xxx }<br>
                    .bold { xxx }<br>
                    h1 class="green bold"> xxx /h1><br>
                    < !--If an HTML element needs to be styled uniquely (no matter what classes are applied to the element), we can add an ID to the element. Normally, this is only meant to be used once. --><br>
                      #large-title { xxx }<br>
                      h1 id="large-title"> XXX /h1><br>
                      <p>
                        <strong>Important:</strong><br>
                        < !--This overrides everything --><br>
                          <i>Example:</i> p {<br>
                          color: blue !important;<br>
                          }<br>
                          .main p {<br>
                          color: red;<br>
                          }<br>
                          < !--!Important will override all p elements and make them blue, even though there is a .main p below that says red. --><br>
                        <strong>CSS Chaining Selectors:</strong><br>
                        <i>Example:</i> p.special { xxx }<br>
                        h1.special { xxx }<br>
                        h1 class="special"> XXX /h1>
                        < !-- These two .special tags do not have the same characteristics and only affect the element to which it is attached --><br>
                          <p>
                            <strong>Nested Elements:</strong><br>
                            <i>Example:</i> .main-list li { xxx }<br>
                            ul class="main-list"><br>
                            li> xxx /li><br>
                            li> xxx /li><br>
                            /ul><br>
                          <p>
                            <strong>Multiple Selectors:</strong><br>
                            < !--If two elements have the same style attributes, you cna combine them to save you time and code --><br>
                              <i>Example:</i> h1 {<br>
                              font-family: Georgia;<br>
                              }<br>
                              .menu {<br>
                              font-family: Georgia;<br>
                              }<br>
                              < !--This can actually be written like the following... --><br>
                                h1,<br>
                                .menu {<br>
                                font-family: Georgia;<br>
                                }<br>
                                
                               
                                                      
                        
                      
                     
                
                    
                
            
