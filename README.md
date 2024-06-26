<html>
	<head></head>
<style>
sos{
    border: none;
    outline: none;
	left: -5px;
	top: 2px;
    color: #00d1fd;
    background: #00d1fd;
    cursor: pointer;
    position: relative;
    z-index: 0;
    border-radius: 10px;
    font-size: 20px;
    padding: 1px 30px;
    transition: background-color 0.3s;
 }
sos:before {
    content: '';
    background: linear-gradient(45deg, #00d1fd, #0097b8, #006479, #00252c);
    position: absolute;
    top: -5px;
    right: -5px;
    background-size: 400%;
    z-index: -1;
    filter: blur(5px);
    width: calc(100% + 4px);
    height: calc(100% + 4px);
    animation: glowing 20s linear infinite;
    opacity: 0;
    transition: opacity 0.3s ease-in-out;
    border-radius: 10px;
}
sos a{
	float: left; 
    display: block;
    color: black; 
    text-align: center;
    padding: 14px 20px; 
    text-decoration: none;
 }
sos:hover:before {
    opacity: 1;
}
sos:active {
    background: white;
}
@keyframes glowing {
    0% { background-position: 0 0; }
    50% { background-position: 400% 0; }
    100% { background-position: 0 0; }
}
.ogo{
	width: 30;
	border-size: cover;
	border-radius: 50px;
	background-image: url('437243.jpg');
}
ogo a{
    float: left;
	left: -5px;
	top: -14px;
    display: block;
    color: black; 
    text-align: center; 
    text-decoration: none;
}
</style>

<style>
.navbar {
        display: flex;
        justify-content: space-between;
        background-color: #333;
        padding: 10px;
		border-radius: 10px;
    }
    .nav-links {
        display: flex;
        gap: 20px;
    }

    .nav-links a {
        color: white;
        text-decoration: none;
    }
</style>
<style>
mnu{
    border: none;
    outline: none;
	left: -5px;
	top: 2px;
    color: black;
    background: black;
    cursor: pointer;
    position: relative;
    z-index: 0;
    border-radius: 10px;
    font-size: 20px;
    padding: 1px 30px;
    transition: background-color 0.3s;
 }
mnu:before {
    content: '';
    background: linear-gradient(45deg, #00d1fd, #0097b8, #006479, #00252c);
    position: absolute;
    top: -5px;
    right: -5px;
    background-size: 400%;
    z-index: -1;
    filter: blur(5px);
    width: calc(100% + 4px);
    height: calc(100% + 4px);
    animation: glowing 20s linear infinite;
    opacity: 0;
    transition: opacity 0.3s ease-in-out;
}
.ogo{
	width: 50px;
	border-size: cover;
	border-radius: 5000px;
	background-image: url('437243.jpg');
}
ogo a{
    float: left;
	left: -5px;
	top: -14px;
    display: block;
    color: black; 
    text-align: center; 
    text-decoration: none;
}
</style>
<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}
li {
    display: inline; 
    margin-right: 20px; 
}
li a:hover {
    color: #0074D9; 
}
<body background="Screenshot 2024-06-26 165849.png">
<div class="navbar">
    <div class="ogo">
			<a href="#" class="ogo"><img src="C:\Users\Acer\Downloads\R.jpeg" class="ogo" border size="cover"></a><font color="white">DORAX</font>	
    </div>
    <div class="nav-links">
        <sos><a href="file:///C:/Users/Acer/Desktop/1245.html">Home</a></sos>
        <mnu><a href="#">About</a></mnu>
		<mnu><a href="file:///C:/Users/Acer/Desktop/er.html">SingIn</a></mnu>
    </div>
</div>
</body>
</html>

