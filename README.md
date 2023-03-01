# Centering-Content-Vertically-and-Horizontally
Centering Content Vertically and Horizontally



/* Center content vertically and horizontally */


.centeredContent_Container {
    width: 100%;
    height: 600px;
    padding: 100px;
}


.centeredContent {
    width: 100%;
    margin: auto auto;
    position: relative;
    left: 50%;
    top: 50%;
    -webkit-transform: translate(-50%, -50%);
    -moz-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
}


/* Notes */

/*
    * Container within a container
    * Text alignment unaffected - default left aligned
*/


