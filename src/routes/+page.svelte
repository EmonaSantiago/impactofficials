<body>
    <div class="row">
        <div class="column">
            <h1>IMPACT</h1>
          <h3>WELCOME TO THE IMPACT</h3>
        <span>APPLICATION FORM</span>
        </div>
    
        <div class="column">
             <ul class="link-list">
                <a href="/creative">CREATIVE</a>
                <a href="/model">MODEL</a>
                <a href="/crew">CREW</a>
            </ul>
        </div>
</body>


<style>
* {
    margin: 0;
    box-sizing: border-box;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

:root {
        --impact-yellow: #F8F053;
}

img {
    width: 100%;
}

body {
    margin: 0;
    background-image: url("/images/homepage.png");
    height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    text-align: center;
    justify-content: center;
}

.column {
  float: left;
  padding: 10px;
  padding-top: 30px;
  height: 300px;
  width: 100%;
}


.row:after {
  content: "";
  display: table;
  clear: both;
}

h1 {
    color: var(--impact-yellow);
    font-size: 120px;
}

h3, span {
    /* font-family: MADE Future x; */
    font-size: 30px;
    /* -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: white; */
  color: white;
}
span { 
        color: var(--impact-yellow);
    }



.link-list a {
    font-size: 20px;
    background-color: var(--impact-yellow);
    color: black;
    width: 100%;
    display: block;
    text-decoration: none;
    padding: 1em; 
    border-radius: 5px; 
    margin-bottom: 2em;
}

.link-list a:hover {
    background-color: transparent; 
    color: var(--impact-yellow);
    border: solid 2px var(--impact-yellow);
}

ul {
    padding: 0;
}

/* @media screen and (max-width: 600px) {

  .column {
    width: 100%;
  }
} */


@media only screen and (min-width: 750px) {
    body {
        margin-top: 2em;
    }
    
    .column {
        width: 50%;
    }
    h1 {
        color: var(--impact-yellow);
        font-size: 15vw;
    }

    h3, span {
        font-size: 3vw;
    }

    .link-list a {
        font-size: 2vw;
    }

    /* .link-list {
        margin-top: 2em;
    } */
}
</style>