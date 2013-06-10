slidercontroller
===
a controller to control slideshow slide among different device based on socket.io
---

### Controller
Control the slide

    - Login by string
    
Demo: http://localhost:3000


### WebSlide
Controlled slide

Demo: http://localhost:3000/impress.js/index.html

Prerequisites:

Your webslide include follow links:

    - open below slide and controller two links
    - Added user string param in your controller page (this demo used 331547274)
      - This string is used to controller login.

        <script type="text/javascript" src="/webslidecontrol.js?user=331547274"></script>
        


Current support slide framework:

    * reveal.js based slide
    * impress.js based slide
    * slide-presentation.js based slide
