1. For the given JSON iterate over all for loops(for,for in,for of,for Each):

        var ass = {
        
        "studentname" : "monika",
        "rollno"      : "1317121124",
        "email"       : "abc@gmail.com",
        
        };
        
        //For loop
        
        for(var i=0; i<ass.length; i++){
        
        console.log(ass[i].studentname+" "+ass[i].rollno+" "+ass[i].email);
        
        }
        
        //For in loop
        
        for (var x in ass) {
       
        console.log(x + ": "+ ass[x])
     
        }
        
        2.Create your own resume data in JSON format:
        
        var resume = {
        
        "name" : "monika",
        "age"  : "22",
        "degree" : "maths",
        "yearofpassing" : "2020",
        "school" : "milton",
        "college" : "msn",
        
        };
        console.log(resume);
        
        3.Read about the difference between window, screen and document in javascript:
        
        Window:
          
              The JavaScript window object sits at the top of the JavaScript Object hierarchy and represents the browser window. The window object is supported by all          browsers. All global JavaScript objects , functions, and variables automatically become members of the window object. The window is the first thing that gets          loaded into the browser . This window object has the majority of the properties like length, innerWidth, innerHeight, name, if it has been closed, its
         parents, and more.

              The window object represents the current browsing context . It holds things like window.location, window.history, window.screen, window.status, or the            window.document . Each browser tab has its own top-level window object. Each of these windows gets its own separate global object. window.window always refers          to window, but window.parent and window.top might refer to enclosing windows, giving access to other execution contexts. Moreover, the window property of a            window object points to the window object itself. So the following ststements all return the same window object.
              
         Screen:
         
              Screen is a small information object about physical screen dimensions . It can be used to display screen width, height, colorDepth, pixelDepth etc. It is          not mandatory to write window prefix with screen object. It can be written without window prefix.
              
         Document:
         
              The Document interface represents any web page loaded in the browser and serves as an entry point into the web page's content, which is the DOM tree.
         When an HTML document is loaded into a web browser , it becomes a document object. It is the root node of the HTML document. The document actually gets loaded          inside the window object and has properties available to it like title, URL, cookie, etc. HTML documents, served with the "text/html" content type, also
         implement the HTMLDocument interface, whereas XML and SVG documents implement the XMLDocument interface.
         
         Difference between window, screen and document:
         
               Well, the window is the first thing that gets loaded into the browser. This window object has the majority of the properties like length, innerWidth,            innerHeight, name, if it has been closed, its parents, and more.The document object is your html, aspx, php, or other document that will be loaded into the            browser. The document actually gets loaded inside the window object and has properties available to it like title, URL, cookie, etc. That means if you want to          access a property for the window it is window.property, if it is document it is window.document.property which is also available in short as
         document.property.
