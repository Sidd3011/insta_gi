


<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Generate Link</title>
    <link rel="stylesheet" href="css/style.css">

<script type="text/javascript">
    function generateFullName()
    {
        document.getElementById('fullName').innerText = 'https://www.icicibank.com/Personal-Banking/insurance/motor-insurance.page?ID' +
            document.getElementById('fName').value + '/UID' + 
            document.getElementById('lName').value;
    }
</script>

 <B> <center><p style="font-family:verdana">Employee ID <input type="text" id="fName" onkeyup="generateFullName()" /></P><br/>
  <B><center><p style="font-family:verdana">USM Employee ID <input type="text" id="lName" onkeyup="generateFullName()" /></P><br/>
<br/>
  <B><U><center><p style="font-family:verdana;color:red;font-size:150%">COPY BELOW LINK & SEND TO CUSTOMER</P><br/>
<center>
<p style="font-family:verdana;font-size:100%;color:Blue"><span id="fullName" /></P>
</center>

</head>
<body>
 
</body>
</html>
