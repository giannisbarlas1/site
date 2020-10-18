---
layout: single
title: Form validation 
header: no
categories:
  - synthesis
tags:
  - video
  - HCI
---

Το παράδειγμα αυτό βασίζεται σε regular expression για να εντοπίσει σφάλματα στην είσοδου του χρήστη.

<iframe height="265" style="width: 100%;" scrolling="no" title="Form Validation" src="https://codepen.io/mibook/embed/XWdwJxX?height=265&theme-id=light&default-tab=html,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/mibook/pen/XWdwJxX'>Form Validation</a> by mibook
  (<a href='https://codepen.io/mibook'>@mibook</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Άσκηση: Προσθέστε έλεγχο για email, credit card, ελληνικό τηλεφωνικό νούμερο. 

//////////////////////////////////////////////
<form>
  <h2>Phone Number Validation</h2>
  <label for="phonenum">Phone Number (format: xxxx-xxx-xxxx):</label><br/>
  <input id="phonenum" type="tel" pattern="^\d{4}-\d{3}-\d{4}$" required >
    <input type="submit" value="Submit">
<br>
  
  
 <h2>Email Validation</h2>
       <label for="phoenenum">Email
       (format:xxxxxxxx@xxxxx.xxx):</label><br>
       <input id="phoenenum" type"tel"
       pattern="^\d{4}-\d{3}-\d{4}$" required >
       <input type="submit" value="Submit">
 
  
  <h3>Credit Card Validation</h3>
       <label for="phoenenum">credit card
       (format:xxxx-xxxx-xxxx-xxxx):</label>
       <br> <input id="phoenenum" type"tel"
       pattern="^\d{4}-\d{3}-\d{4}$" required >
       <input type="submit" value="Submit">
  <br>
  
  <h2>Ελληνικό Τηλεφωνικό Νούμερο</h2>
       <label for="phoenenum">ελληνικο τηλεφωνικο νουμερο
       (format:+30xxxxxxxx):</label><br>
       <input id="phoenenum" type"tel"
       pattern="^\d{4}-\d{3}-\d{4}$" required >
       <input type="submit" value="Submit">
  <form>
  
  
  

  
  
  
  
  input[type="tel"] {
  border: 1px solid #ddd;
  padding: 4px 8px;
}
input[type="tel"]:focus {
  border: 1px solid #000;
}

input[type="submit"] {
  font-weight: bold;
  padding: 4px 8px;
  border:1px solid #000;
  background: #3b5998;
  color:#fff;
}

form {
  width: 50%;
  margin: 0 auto;
}

.p {
  padding-top: 30px;
}
  
  
  
