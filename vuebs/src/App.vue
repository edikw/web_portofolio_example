<template>
    <div id="app">
    <router-view/>
  </div>
</template>

<script>
    

</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-family: 'Montserrat', sans-serif;

}
 .header-text h1 {
  color: #fff;
  font-family: monospace;
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: .15em solid orange; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: .15em; /* Adjust as needed */
  animation: 
    typing 3s steps(30, end),
    blink-caret .5s step-end infinite;
}
 .header-text h1 span{
    padding-top: 15px;
    padding-bottom: 5px;
    font-size: 25px;
    border-bottom: 2px solid #ddd;
    text-transform: uppercase;
    font-weight: 100;
    color: #dadada;

    /*font-family: '', sans-serif;*/

}

/* The typing effect */
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: 1px orange }
}


 #app {
      display: inline-block;
    }
    .nav {
      position: static;
      height: 0;
      width: 0;
      display: inline;
    }

    #menuToggle {
      display: block;
      position: relative;
      top: 30px;
      left: 30px;
      z-index: 1;
      -webkit-user-select: none;
      user-select: none;
      width: 0;
    }
    #menuToggle input:checked ~ ul {
      transform: none;
      padding-top: 65px;
    }

    #menuToggle input {
      display: block;
      width: 40px;
      height: 32px;
      position: absolute;
      top: 30px;
      left: 20px; 
      cursor: pointer;
      opacity: 0;
      position: fixed;
      z-index: 2;
      -webkit-touch-callout: none;
    }

    .burger {
      position: fixed;
      /*left: -1px;*/
      /*position: absolute;*/
      top: 30px;
    }

    .burger span {
      display: block;
      width: 25px;
      height: 4px;
      margin-bottom: 5px;
      position: relative;
      background: #cdcdcd;
      border-radius: 3px;
      z-index: 1;
      background-color: #c59a6d;
      transform-origin: 4px 0px;
      transition: transform 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
                  background 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
                  opacity 0.55s ease;
    }

    .burger span:first-child {
      transform-origin: 0% 0%;
    }

    .burger span:nth-last-child(2) {
      transform-origin: 0% 100%;
    }

    #menuToggle input:checked ~ .burger span {
      opacity: 1;
      transform: rotate(45deg) translate(-20px, -20px);
      background: #fff;
      z-index: 1;
    }

    #menuToggle input:checked ~ .burger span:nth-last-child(3) {
      opacity: 0;
      transform: rotate(0deg) scale(0.2, 0.2);
    }

    #menuToggle input:checked ~ .burger span:nth-last-child(2) {
      transform: rotate(-45deg) translate(5px, -3px);
    }

    #menuToggle input:checked ~ #menu {
      left: 0;
    }

    #menu {
      position: fixed;
      padding: 0;
      left: -50%;
      top: 0;
      height: 100%;
      text-align: center;
      background: rgba(34, 34, 34, 0.8);
      list-style-type: none;
      -webkit-font-smoothing: antialiased;      
      padding-top: 65px;
      transition: 0.5s cubic-bezier(0.77,0.2,0.05,1.0);
    }

    #menu a {
      text-align: center;
      /*padding: 10px;*/
      padding: 30px 0;
      font-size: 0.8em;
      display: inline-flex;
      width: 70%;
      justify-content: center;
      text-decoration: none;
    }
    #menu a li{
      color: #fff;
      text-transform: uppercase;
      font-family: 'Montserrat', sans-serif;

    }
    #menuToggle input:checked ~ ul {
      transform: none;
    }
    #menu a li:hover {
      border-right: none;
      color: #c59a6d;
    }
    @media all and (min-width: 768px) and (max-width: 1024px){

      
    }
    @media all and (min-width: 481px) and (max-width: 767px){

    }
    @media all and (max-width: 480px){
      #menuToggle input:checked ~ #menu {
        left: 0px;
      }
      #menu {
        width: 25%;
        position: fixed;
      }
      #menu a {
        padding: 20px 0;
        font-size: 0.7em;

      }
    }
</style>
