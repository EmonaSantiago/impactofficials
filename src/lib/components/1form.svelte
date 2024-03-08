<body>
    <div class="container">
       <form action="https://formspree.io/f/mpzvlaob" method="POST">
   
        <!-- Full name -->
        <div class="row">
          <div class="col-25">
            <label for="full-name">FULL NAME</label>
          </div>
          <div class="col-75">
            <input type="text" name="full-name" id="full-name" placeholder="" required="">
          </div>
        </div>

         <!-- Branch --> 
         <div class="row">
          <div class="col-25">
            <label for="branch">BRANCH</label>
          </div>
          <div class="col-75">
            <input type="text" name="branch" id="branch" placeholder="EX: fashion ,  visuals , music , art , beauty, lifestyle OR other" required="">
          </div>
        </div>

   
         <!-- Brand name -->
         <div class="row">
           <div class="col-25">
             <label for="brand-name">BRAND NAME</label>
           </div>
           <div class="col-75">
             <input type="text" name="brand-name" id="Brand name" placeholder="" required="">
           </div>
         </div>
   
   
       <!-- Link insta web -->
       <div class="row">
           <div class="col-25">
             <label for="link">LINK TO SOCIALS</label>
           </div>
           <div class="col-75">
             <input type="text" name="link" id="link" placeholder="EX: instagram , tiktok , website OR other" required="https:/">
           </div>
         </div>
   
  
   
            <!-- Email -->
            <div class="row">
               <div class="col-25">
                 <label for="email-address">EMAIL</label>
               </div>
               <div class="col-75">
                 <input type="text" name="email" id="email-address" placeholder="EX: myname@example.com" required="">
               </div>
             </div>
       
        
   
   
         <!-- Telefoon nummer -->
         <div class="row">
           <div class="col-25">
             <label for="phone-nummer">PHONE NUMBER</label>
           </div>
           <div class="col-75">
             <input type="text" name="phone-name" id="phone-number" placeholder="+31()" required="">
           </div>
         </div>
   
   
         <!-- Motivatie message -->
         <div class="row">
           <div class="col-25">
             <label for="motivation-message">MOTIVATION </label>
           </div>
           <div class="col-75">
             <textarea rows="3" name="message" id="message" required="" placeholder="The reason why i want to join as a creative..."></textarea>
         <input type="hidden" name="_subject" id="email-subject" value="Department Contact Form Submission">
           </div>
         </div>
   
         <!-- Bestand -->
         <div class="row">
           <div class="col-25">
             <label for="subject">MOTIVATION (FILE)</label>
           </div>
           <div class="col-75">
               <input id="file-button" type="file" name="attachment" accept="image/png, image/jpeg">
           </div>
         </div>
   
         <!-- How did you hear about this form? -->
         <div class="row">
           <div class="col-25">
             <label for="reclame">HOW DID YOU HEAR ABOUT THIS FORM?</label>
           </div>
           <div class="col-75">
             <select id="reclame" name="reclame">
               <option value="Instagram">Instagram</option>
               <option value="Tiktok">Tiktok</option>
               <option value="Sticker">Sticker</option>
               <option value="mutuals">Mutuals</option>
             </select>
           </div>
         </div>
   
   
         <div class="row">
           <input id="submit" type="submit" value="SUBMIT">
         </div>
       </form>
     </div>
   
   
   </body>
   
   
   <style>
   * {
   margin: 0;
   font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
   }
   
   :root {
   --main-yellow-: #F8F053;
   }
   
   h1 {
   font-size: 110px;
   color: #F8F053;
   text-align: center;
   }
   
   body {
   background-image: url(/src/darkimg.png);
   margin: 1em;
   /* height: 1000px; */
   background-position: center;
   background-repeat: no-repeat;
   background-size: cover;
   position: relative;
   }
   
   /* button */
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
   padding: 10px;
   /* background-color: #F8F053; */
   color: white;
   text-decoration: none;
   border: none;
   border: solid #F8F053 1px;
   /* border-radius: 5px; */
   transition: background-color 0.3s;
   }
   
   .button:hover {
   background-color: #F8F053;
   }
   
   @media (max-width: 600px) {
   /* Adjust for smaller screens */
   .button {
   max-width: 100%; /* Full width on smaller screens */
   }
   }
   
   .button1 {
   flex: 1; /* Each button takes equal space */
   max-width: 30%; /* Maximum width for each button */
   text-align: center;
   margin: 5px; /* Adjust margin as needed */
   padding: 10px;
   background-color: #F8F053;
   color: black;
   text-decoration: none;
   border: none;
   /* border-radius: 5px; */
   transition: background-color 0.3s;
   }
   
   .button1:hover {
   background-color: #F8F053;
   }
   
   @media (max-width: 600px) {
   /* Adjust for smaller screens */
   .button1 {
   max-width: 100%; /* Full width on smaller screens */
   }
   }
   
   
   /* form */
   * {
   box-sizing: border-box;
   }
   
   input[type=text], select, textarea {
   width: 100%;
   padding: 12px;
   border: 1px solid #ccc;
   resize: vertical;
   border-radius: 5px;
   }
   label {
   padding: 12px 12px 12px 0;
   display: inline-block;
   color: white;
   float: inline-start;
   }
   
   input[type=submit] {
   background-color: #F8F053;
   color: black;
   padding: 12px 20px;
   border: none;
   cursor: pointer;
   border-radius: 5px;
   width: 100%;
   }

   input[type="file" i] {
    color: white;
    /* padding: 12px 12px 12px 0; */
   }
   
   /* input[type=submit]:hover {
   background-color: #45a049;
   } */
   
   .container {
   border-radius: 5px;
   padding: 10px;
   }
   
   .col-25 {
   float: left;
   width: 25%;
   margin-top: 6px;
   }
   
   /* .col-75 {
   float: left;
   width: 75%;
   margin-top: 6px;
   } */
   
   /* Clear floats after the columns */
   .row:after {
   content: "";
   display: table;
   clear: both;
   }
   
   #file-button {
     color: greyc;
   }
   
   /* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
   @media screen and (min-width: 600px){
   .col-25, .col-75 {
   width: 100%;
   margin-top: 0;
   }
   
   input[type=submit] {
     margin-top: 1em;
     width: 100%;
   }
   }

   @media screen and (max-width: 600px){ 
    .col-25, .col-75 {
   width: 100%;
   margin-top: 0;
   }
   
   input[type=submit] {
     margin-top: 1em;
     width: 100%;
   }
   }

   
   
   </style>