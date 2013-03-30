16
==

16


/*
  aprilFools.css
  Written by Wes Bos
  I assume no responsibility for angry co-workers or lost productivity 

  Put these CSS definitons into your co-workers Custom.css file.
  They will be applied to every website they visit as well as their developer tools.

  Mac: ~/Library/Application Support/Google/Chrome/Default/User StyleSheets/Custom.css

  PC: C:/Users/YourUsername/AppData/Local/Google/Chrome/User Data/Default/User StyleSheets/Custom.css

  Ubuntu (Chromium): ~/.config/chromium/Default/User StyleSheets/Custom.css
  
*/


/*
  Turn every website upside down
*/
body {
  /*-webkit-transform: rotate(180deg);*/
}

/*
  blur every website for a split second every 30 seconds
*/
body {
  /*-webkit-animation: blur 30s infinite;*/
}

/*
  Spin every Website
*/ 
body {
  /*-webkit-animation: spin 5s linear infinite;*/
}

/*
  Flip all images upside down
*/
img {
  /*-webkit-transform: rotate(180deg);*/
}

/*
  COMIC SANS EVERYTHING
*/

body, p, body p, body div p {
  /*font-family: 'Comic Sans MS', cursive !important;*/
}

/*
  Spin all images
*/ 
img {
  /*-webkit-animation: spin 1s linear infinite;*/
}

/*
  Hide every 2nd paragraph element on a page
*/
p:nth-child(2) {
  /*display:none !important;*/
}

/*
  Spin dev tools round and round
*/
#-webkit-web-inspector {
 /*-webkit-animation: spin 1s linear infinite; */
}

/*
  Flip dev tools upside down
*/ 
#-webkit-web-inspector {
 /*-webkit-transform:rotate(180deg);*/
}

/* Hide the close button */
#-webkit-web-inspector .toolbar-item.close-left {
  /*display:none !important;*/
}

/* Make console text all blurry */
#-webkit-web-inspector .console-group-messages {
  /*text-shadow: 0 0 3px rgba(0,0,0,.5) !important;*/
}

#-webkit-web-inspector .console-error-level .console-message-text,
#-webkit-web-inspector .console-error-level .section .header .title {
  /*text-shadow: 0 0 3px rgba(255,0,0,.5) !important;*/
}

#-webkit-web-inspector .console-user-command > .console-message-text {
  /*text-shadow: 0 0 3px rgba(0,128,255,.5) !important;*/
}

#-webkit-web-inspector .console-group-messages,
#-webkit-web-inspector .console-user-command > .console-message-text,
#-webkit-web-inspector .console-formatted-null,
#-webkit-web-inspector .console-formatted-undefined,
#-webkit-web-inspector .console-debug-level .console-message-text,
#-webkit-web-inspector .console-error-level .console-message-text,
#-webkit-web-inspector .console-error-level .section .header .title,
#-webkit-web-inspector .console-group-messages .section .header .title,
#-webkit-web-inspector .console-formatted-object,
#-webkit-web-inspector .console-formatted-node,
#-webkit-web-inspector .console-formatted-array,
#-webkit-web-inspector .section .properties .name,
#-webkit-web-inspector .event-properties .name,
#-webkit-web-inspector .console-formatted-object .name,
#-webkit-web-inspector .console-formatted-number,
#-webkit-web-inspector .console-formatted-string,
#-webkit-web-inspector #console-messages a {
  /*color: transparent !important;*/
}

/* HTML PRIDE! */
html {
  /*-webkit-animation: rainbow 8s infinite;*/
}

/*
  Make every website fall over!
*/
/*
html, body {
  height: 100%;
}

html {
  -webkit-perspective: 1000;
}

body {
  -webkit-transform-origin: bottom center;
  -webkit-transform: rotateX(-90deg);
  -webkit-animation: fall 1.5s ease-in;
}
*/

/*
  Insert a phrase every paragraph
*/
/*
p:before {
   content: "YOLO ";
}
*/

/* Animations */

@-webkit-keyframes blur {
  0%   { -webkit-filter: blur(0px); }
  49%   { -webkit-filter: blur(0px); }
  50%   { -webkit-filter: blur(1px); }
  51%   { -webkit-filter: blur(0px); }
  100%   { -webkit-filter: blur(0px); }
}

@-webkit-keyframes spin {
  0%   { -webkit-transform: rotate(0deg); }
  100%   { -webkit-transform: rotate(360deg); }
}

@-webkit-keyframes rainbow {
  100% { -webkit-filter: hue-rotate(360deg); }
}

@-webkit-keyframes fall {
  0%   { -webkit-transform: none; }
  100%   { -webkit-transform: rotateX(-90deg); }
}
