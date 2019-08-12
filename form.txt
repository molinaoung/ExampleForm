
/*Validation for firstname*/
function validateForm() {
  var x = document.forms["myForm"]["fname"].value;
  if (x == "") {
    alert("Name must be filled out");
    return false;
  }
}
/*Validation for lastname*/
function validateForm() {
  var x = document.forms["myForm"]["lname"].value;
  if (x == "") {
    alert("Last Name must be filled out");
    return false;
  }
}
/*Validation for phone number*/
function validateForm() {
  var x = document.forms["myForm"]["pnumber"].value;
  if (x == "") {
    alert("Number must be filled out");
    return false;
  }
}
/*Validation for promo code*/
function validateForm(inputtxt) {
  var x = document.forms["myForm"]["promo"].value;
  var letterNumber = /^[0-9a-zA-Z]+$/;
  if ((inputtxt.value.match(letterNumber)) {
    return true;
  }
  else
  {
	alert("Please enter a valid promo code"); 
   return false; 
  }
  
}
/*Validation for email*/
function validateForm() {
  var x = document.forms["myForm"]["email"].value;
  if (x == "") {
    alert("Email must be filled out");
    return false;
  }
}
/*Validation for how did you hear about us*/
function validateForm() {
  var x = document.forms["myForm"]["options"].value;
  if (x == "") {
    alert("Name must be filled out");
    return false;
  }
}
/*Validation for other box. although does not work with code
function showfield(name){
  if(name=='Other')document.getElementById('div1').innerHTML='Other: <input type="text" name="other" />';
  else document.getElementById('div1').innerHTML='';
}
*/
