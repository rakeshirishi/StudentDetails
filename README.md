<html>
<head>
	Student Login
</head>
<body>
	<form>
		<fieldset >
		 	<legend>Student Login Form</legend>
			
		<	label> First Name :</label>
		 		<input type="text" size="20"/> <br><br>
			<label> Middle Name :</label>
		 		<input type="text" size="20"/> <br><br>
			<label> Last Name :</label>
		 		<input type="text" size="20"/> <br><br>
				
			<label> Course :</label>
			<select>
				<option value="Course">Select</option>
				<option value="BCA">BCA</option>
				<option value="BBA">BBA</option>
				<option value="B.sc">B.sc</option>
				<option value="MCA">MCA</option>
				<option value="MBA">MBA</option>
			</select><br><br>
			
			<label> Gender :</label>
		 		<input type="radio" value="m" name="Gender"/>Male
		 		<input type="radio" value="f" name="Gender"/>Female
		 		<input type="radio" value="o" name="Gender"/>other <br><br>
			
			<label> Phone no :</label>
		 		<input type="text" value="+91" size="2"/>
		 		<input type="text" size="10"/> <br><br>
			
			<label> Address : </label><br>
		 		<textarea col="100" rows="100"></textarea><br><br>
			
			<label> Pin code :</label>
		 		<input type="text" size="6"/> <br><br>
			
			<label> Email :</label>
		 		<input type="text" id="email"/> <br><br>
			
			<button type="Submit">Submit </button>
		</fieldset>
	</form>
</body>
</html>
