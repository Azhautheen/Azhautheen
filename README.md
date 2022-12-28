<!DOCTYPE html>
<html lang="en">
<head>
				<meta charset="UTF-8">
				<title>login </title>
			<style>
							input{border-style:insed;
							border-color:black;
							boder-style:solid;
						border-radius: 10px 5px 2em / 20px 25px 30%;}
							*{background-color: orange;
						}
						button{
										background-color:white;
										font-size: 18px;
										border-style:double;
										border-bottom-color: white;
										border-radius:15px;
						}
						
							#topbar{
											height: 30px;
											width: 100%;
							}
			</style>
</head>
<body><div id="topbar">
				
</div>	<h2>Form</h2>
	<form><center>
	<label>User Nam	</label><br>
	<input type="name"placeholder="enter your name"><br><br>

         <label>Email</label>
	<br>
        <input type="email"placeholder="@gmail.com">
	<br><br>
	<label>Mobile Number</label><br>
	<input type="number"/><br><br>
	<label> Enter password</label><br>
	<input type="password" ><br><br>
	<label>Gender</label><br>
	<label>Male</label>
	<input type="radio" name="Gender" >
	<label>Female</label>
	<input type="radio" name="Gender" ><br><br>
	<label>Passout Year</label>
	<select>
					
	<option>2019</option
        <option>2020</option>
	<option>2021</option>
	<option>2022</option>
	</select>
        <br><br>
	<label>Description</label><br>
         <textarea cols="40"rows="10"></textarea>
         <br>
        <button class="button"type="button"> Sign In</button>
        </form>
</body>
</html>
