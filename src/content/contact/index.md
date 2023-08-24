 # Contact PEPTI
 
 <form name="contact" method="POST" data-netlify="true">
    <p>
        <label>Your Name: <input type="text" name="name" required/></label>
    </p>
    <p>
        <label>Your Email: <input type="email" name="email" required/></label>
    </p>                
    <p>
        <label>Message: <textarea name="message"></textarea></label>
    </p>
    <fieldset>
    <legend>I'd like to receive emails from PEPTI with the latest resources, upcoming events,  and career opportunities.</legend>
    <p>
      <label>
        <input type="radio" name="receiveEmails" value="Yes"> Yes
      </label>
    </p>
    
  </fieldset>
    <p>
        <button type="submit">Send</button>
    </p>
</form>

<style>
input[type=text],input[type='email'], textarea {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

form input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: var(--SteelBlue);
}

.contact-form {
    width:50%;
  border-radius: 5px;
  background-color:var(--SteelBlue);
  padding: 20px;
}
</style>