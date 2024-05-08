# HTML-TASK
<!DOCTYPE html>
<html>
<head>
      <title>registration form</title>
</head>
<body>
    <h1>Registration Form !</h1>
    <fieldset>
        <legend><h2>Personal Details</h2></legend>
<form>
  <div> 
    <label>First name:</label>
  <input type="text" > 
 </div>
  <div>
  <label for="lname">Last name:</label>
  <input type="text" >
</div>
   <div>
    <label for="Email">Email:</label>
    <input type="text" >
</div>

  <div>
<label>Gender:</label>
<input type="radio" id="male" >
<label>male</label>
<input type="radio" id="female" >
<label>female</label>
</div>

<div>
    <label for="City">City:</label>
    <select id="City" name="City">
        <option value="Zarqa">Zarqa</option>
        <option value="Amman">Amman</option>
        <option value="Irbid">Irbid</option>
      </select>
</div>

<button>Sign up</button> 
    </fieldset>
</form>
</body>

</html>

