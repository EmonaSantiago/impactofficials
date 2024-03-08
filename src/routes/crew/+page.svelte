<script>
    import Form from "../../lib/components/3form.svelte";
      import Navigation from "../../lib/components/3navigation.svelte";
  </script>
  
  <body>
  <Navigation></Navigation>
  <div class="row">
      <div class="column">
        <img src="/images/logo.png" alt="Italian Trulli" >
          <h3>"Looking to be part of a great team? Join us as a crew member and help us make our events even more impactfull! Whether you're experienced or just starting out, there's a place for you. Let's work together, have fun, and create memorable experiences. Apply now and be part of something special!"</h3>
      </div>
      <div class="column">
        <Form></Form>
      </div>
    </div>
  </body>

  <style>
    * {
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    }

    :root {
        --impact-yellow: #F8F053;
    }

    body {
    margin: 0;
    background-image: url("/images/crew.png");
    min-height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    text-align: center;
    }

    * {
  box-sizing: border-box;
  margin: 0;
}

h1 {
    color: var(--impact-yellow);
    font-size: 120px;
}

h2 {
  color: white;
}
h3 {
font-family: MADE Future x;
font-size: 12px;
color: rgba(121, 120, 120, 0.643);
padding: 1em;
padding-top: 0;
}


/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 720px) {
  .column {
    width: 100%;
  }
}

@media only screen and (min-width: 750px) {
    h1 {
        color: var(--impact-yellow);
    font-size: 15vw;
}
}
</style>