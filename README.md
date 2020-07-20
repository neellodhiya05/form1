<html>
<form>
  <div class="row">
  
    <div class="col">
      First name<input type="text" class="form-control" placeholder="First name" required>
    </div>
	
    <div class="col">
      Last name<input type="text" class="form-control" placeholder="Last name" required>
    </div>
	
	<div class="col">
		
     Mobile number<input type="tel"
           name="phone_number"
           id="phone_number"
           pattern="[789][0-9]{9}"
           required="required"
          />
	 </div>
	
	<div class="col">
      E-mail<input type="text" class="form-control" placeholder="email address" >
    </div>

    <div class="col">
      Company name<input type="text" class="form-control" placeholder="Company name" required>
    </div>
	
	 <div class="col">
      Discription<input type="text" class="form-control" placeholder="Discription" required>
    </div>
	
	 <div class="form-row">
   <select class="custom-select custom-select-lg mb-3" >
  <option selected>Open this state list</option>
  <option value="1">Andhra Pradesh</option>
  <option value="2">Arunachal Pradesh</option>
  <option value="3"> Assam</option>
  <option value="4">Bihar</option>
  <option value="5">Chandigarh</option>
  <option value="6">Chhattisgarh</option>
  <option value="7">Dadra and Nagar Haveli</option>
  <option value="8">Daman and Diu</option>
  <option value="9">Delhi</option>
  <option value="10">Goa</option>
  <option value="11">Gujarat</option>
  <option value="12">Haryana</option>
  <option value="13">Himachal Pradesh</option>
  <option value="14">Jammu and Kashmir</option>
  <option value="15">Jharkhand</option>
  <option value="16">Karnataka</option>
  <option value="17">Kerala</option>
  <option value="18">Lakshadweep</option>
  <option value="19">Madhya Pradesh</option>
  <option value="20">Maharashtra</option>
  <option value="21">Manipur</option>
  <option value="22">Meghalaya</option>
  <option value="23">Mizoram</option>
  <option value="24">Nagaland</option>
  <option value="25">Odisha</option>
  <option value="26">Puducherry</option>
  <option value="27">Punjab</option>
  <option value="28">Rajasthan</option>
  <option value="29">Sikkim</option>
  <option value="30">Tamil Nadu</option>
  <option value="31">Telangana</option>
  <option value="32">Tripura</option>
  <option value="33">Uttar Pradesh</option>
  <option value="34">Uttarakhand</option>
  <option value="35">West Bengal</option>
 
 </select>  
    <div class="form-group col-md-6">
      <label for="inputCity">City</label>
      <input type="text" class="form-control" id="inputCity" required>
    </div>
	
	<div class="col">
      pin code<input type="number" class="form-control" placeholder="enter city pin-code" required>
	  </div>
	  
	<div class="form-group">
      <label for="inputAddress">Address</label>
      <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St" required>
    </div>
	
    <div class="form-group">
     <label for="inputAddress2">Address 2</label>
     <input type="text" class="form-control" id="inputAddress2" placeholder="Apartment">
    </div>
  
    <div class="form-group">
      <label for="inputAddress2">Address 3</label>
      <input type="text" class="form-control" id="inputAddress2" placeholder=" studio, or floor">
    </div>
  
    </div>
  
    <button type="submit" class="btn btn-primary">submit</button>
  
</form>
