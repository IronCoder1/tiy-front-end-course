##Problems 12 and 13

<cite> http://www.sitepoint.com/html5-form-validation/</cite>

example of HTML5 form validation using the 
1. required attribute and 
2. pattern attribute, pattern can be defined explicitly or using a Regular Expression

+ Date input with RegEx
<label for="date">Choose Date</label>
<input type="date" id="date" name="date" pattern="(0[1-9]|1[0-9]|2[0-9]|3[01]).(0[1-9]|1[012]).[0-9]{4}
 value="" required/>

+ email input
<label for="email">Personal eMail:</label>
<input type="email" id="email" name="email" required>

+ url input
<label for="webSite">Your website :</label>
<input type="url" id="website" name="website" required>

+ search input will support any character
<input type="search" name="search">