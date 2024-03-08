
<div class="button-container">
    <a href="/" class="button1">CREATIVE</a>
    <a href="/model" class="button">MODEL</a>
    <a href="/crew" class="button">CREW</a>
  </div>
  
  <style>
    :root {
        --impact-yellow: #F8F053;
    }


    .button-container {
      display: flex;
      justify-content: space-between; /* Distribute buttons evenly */
      flex-wrap: wrap; /* Wrap buttons to next line if necessary */
      margin: 0 auto;
      max-width: 600px; /* Adjust max-width as needed */
    }
  
    .button {
      flex: 1; /* Each button takes equal space */
      max-width: 30%; /* Maximum width for each button */
      text-align: center;
      margin: 5px; /* Adjust margin as needed */
      margin-top: 1em;
      padding: 10px;
      /* background-color: #F8F053; */
      color: white;
      text-decoration: none;
      border: none;
      border: solid white 1px;
      transition: background-color 0.3s;
    }
  
    .button:hover {
      background-color: #F8F053;
      color: black;
    }

    .button1 {
      flex: 1; /* Each button takes equal space */
      max-width: 30%; /* Maximum width for each button */
      text-align: center;
      margin: 5px; /* Adjust margin as needed */
      margin-top: 1em;
      padding: 10px;
      background-color: #F8F053;
      color: black;
      text-decoration: none;
      border: none;
      border: solid white 1px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
  
    .button1:hover {
      color: #F8F053;
      background: none;
    }
  
    @media (max-width: 600px) {
      /* Adjust for smaller screens */
      .button {
        max-width: 100%; /* Full width on smaller screens */
      }

      .button1 {
        max-width: 100%; /* Full width on smaller screens */
      }
    }
  </style>
  