<html>
	<head>
		<title>Admin-Authentication</title>
	</head>
	<body>
	<?php
 
			if(isset($_POST['login']))
			{
			 $uname = trim($_POST['uname']);
			 $upass = trim($_POST['pass']);
			 
			 if(empty($uname))
			 {
			  $error = "enter your name !";
			  $code = 1;
			 }
			 
			 else if(empty($upass))
			 {
			  $error = "enter password !";
			  $code = 4;
			 }
			 else if(strlen($upass) < 8 )
			 {
			  $error = "Minimum 8 characters !";
			  $code = 4;
			 }
			 else
			 {
					//details	for	connecting	to	database
				$dbhost = 'localhost';
				$dbuser = 'root';
				$dbpass = '';
				$database = 'users';
				$con=mysql_connect($dbhost, $dbuser, $dbpass,$database);
					// Check connection
					 if(!$con )
					  {
					  echo "Failed to connect to MySQL: " . mysql_error();
					  }
				mysql_select_db ($database,$con);
				//for	checking	the	database	from	database.	  
				$sql = 'SELECT * FROM user_detail WHERE user_name ="'.$uname.'" 
						AND password ="'.$upass.'"';
				$result = mysql_query($sql);
				//print_r	($result);
				$numrows = mysql_num_rows($result);
				if($numrows > 0)
				   {
						?>
					<script>
					alert('success	Login!!');
				document.location.href='../index.html';
					</script>
				<?php
				   }
				else
				   {?>
					   <script>
					alert('Error!');
					</script>
				 <?php  }
			  
			 }
			}
			?>
		<form method="post">
			<table align="center" width="50%" border="0">
				<tr><td><h3>Login Here</h3></td></tr>
				<?php
				if(isset($error))
				{
				?>
					<tr>
						<td id="error"><font color="#FF0000">
						<?php echo $error; ?></font></td>
					</tr>
				<?php
				}
				?>
				<tr>
					<td><input type="text" name="uname" 
					placeholder="User Name" value="<?php if(isset($uname)){echo $uname;} ?>"  
					<?php if(isset($code) && $code == 1){ echo "autofocus"; }  ?> /></td>
				</tr>
				
				<tr>
					<td><input type="password" name="pass" 
					placeholder="Your Password" 
					<?php if(isset($code) && $code == 4){ echo "autofocus"; }  ?> /></td>
				</tr>
				<tr>
					<td><button type="submit" name="login"	style="color:blue">Log Me In</button></td>
				</tr>
			</table>
		</form>	
	</body>
</html>	