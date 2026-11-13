
<!DOCTYPE html>
<html>
<head>
<title>Registration Form</title>
<style>
body {
    font-family: Arial;
    background: #f0f0f0;
}
table {
    margin: auto;
    padding: 20px;
    background: white;
}
td { padding: 8px; }
input, select, textarea {
    padding: 8px;
}
input[type="submit"] {
    background: green;
    color: white;
    padding: 10px;
}
</style>
</head>
<body>

<h2 align="center">Registration Form</h2>

<form>
<table>
<tr><td>Name:</td><td><input type="text" required></td></tr>
<tr><td>Email:</td><td><input type="email" required></td></tr>
<tr><td>Password:</td><td><input type="password" required></td></tr>
<tr><td>Confirm Password:</td><td><input type="password" required></td></tr>
<tr><td>Gender:</td><td>
<input type="radio" name="gender">Male
<input type="radio" name="gender">Female
</td></tr>
<tr><td>DOB:</td><td><input type="date"></td></tr>
<tr><td>Country:</td><td>
<select>
<option>India</option>
<option>UK</option>
<option>USA</option>
</select>
</td></tr>
<tr><td>Interests:</td><td>
<input type="checkbox">Sports
<input type="checkbox">Music
</td></tr>
<tr><td>Bio:</td><td><textarea></textarea></td></tr>
<tr><td colspan="2" align="center">
<input type="submit" value="Register">
</td></tr>
</table>
</form>

</body>
</html>
