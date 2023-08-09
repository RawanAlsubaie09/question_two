# question_two

<html>
<main>
<div class="pagewrap">
    <form class="form" id="form">
      <h2 class="form__title">Sing Up Form Example</h2>
      
      <div class="container">
      
            <label id="userLabel1" for="fname" class="container__label">First,Last Name*</label> 
             <input class="container__input" type="text" id="fname" name="fname" value="" required> 
           <input class="container__input" type="text" id="Lname" name="Lname" value="" required> 
   
      </div>
      
      <div class="container">
        <label id="userLabel3" for="org" class="container__label">Organization</label>
        <input class="container__input" type="text" id="org" name="org" value="" >
        
      </div>
      <div class="container">
        <label id="userLabel4" for="org" class="container__label">Email Address*</label>
        <input class="container__input" type="text" id="Email" name="Email" value="" required>
       
      </div>
       <div class="container">
        <label id="userLabel5" for="WorkPhone" class="container__label">Work Phone</label>
        <input class="container__input" type="text" id="WorkPhone" name="WorkPhone" value="" >
       
      </div>
  
      <div class="container">
        <label id="userLabel6" for="HPhone" class="container__label">Home Phone</label>
        <input class="container__input" type="text" id="HPhone" name="HPhone" value="" >
       
      </div>
  
       <div class="container">
        <label id="userLabel7" for="CPhone" class="container__label">Cell Phone</label>
        <input class="container__input" type="text" id="CPhone" name="CPhone" value="" >
        
      </div>
  
      <div class="container">
        <label id="userLabel8" for="fax" class="container__label">Fax</label>
        <input class="container__input" type="text" id="fax" name="fax" value="" >
       
      </div>
  
      <div class="container">
        <label id="userLabel9" for="add1" class="container__label">Address 1*</label>
        <input class="container__input" type="text" id="add1" name="add1" value="" required>
        
      </div>
  
      <div class="container">
        <label id="userLabel10" for="add2" class="container__label">Address 2</label>
        <input class="container__input" type="text" id="add2" name="add2" value="" >
       
      </div>
  
      <div class="container">
          <label id="userLabel11" for="city" class="container__label">City* </label>
          <input class="container__input" type="text" id="city" name="city" value="" >
          
        </div>
  
        <div class="container">
          <label id="userLabel12" for="SP" class="container__label">State Provioce </label>
          <input class="container__input" type="text" id="SP" name="SP" value="" >
         
        </div>
  
        <div class="container">
          <label id="userLabel13" for="zippstel" class="container__label">zip postal Code </label>
          <input class="container__input" type="text" id="SP" name="zippstel" value="" >
          
        </div>
  
        <div class="container">
          <label id="userLabel14" for="Country" class="container__label">Country* </label>
          <input class="container__input" type="text" id="Country" name="Country" value="" >
          
        </div>
  
        <div class="container">
            <label id="userLabel15" for="requiredlabel" class="container__label">*.required fields </label>
            <input  id="submit" type="submit" value="Submit" />           
          </div>
        </table>
    </form>
  </div>
</main>




  
  <script>
  function validate() {
  var fname = document.getElementById('fname').value;
  var Lname = document.getElementById('Lname').value;
  var adds1 = document.getElementById('add1').value;
  var ct = document.getElementById('city').value;
  var Coun = document.getElementById('Country').value;

      
    if (fname === "" || fname === null) {
      alert("First Name required");               
    }
    if (Lname === "" || Lname === null) {
        alert("Last Name required");  
    }
    if (adds1 === "" || adds1 === null) {
        alert("address1 required");  
    }
    if (Coun === "" || Coun === null) {
        alert("Country required");  
    }
    if (ct === "" || ct === null) {
        alert("city required");  
    }
  }
  var submit = document.getElementById('submit');
  submit.addEventListener('click', validate);
 
  
  
  </script>
