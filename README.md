


<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Generate Link</title>
    <link rel="stylesheet" href="css/style.css">

<script type="text/javascript">
    function generateFullName()
    {
        document.getElementById('fullName').innerText = 'https://www.icicibank.com/Personal-Banking/insurance/motor-insurance.page?empref=' +
            document.getElementById('fName').value + '&solid=' + 
            document.getElementById('lName').value + '&channelid=' + document.getElementById('mName').value ;
    }
</script>

 <p style="font-family:verdana">Enter Employee ID <input type="text" id="fName" onkeyup="generateFullName()" /></P><br/>
  <p style="font-family:verdana">Enter Sol ID <input type="text" id="lName" onkeyup="generateFullName()" /></P><br/>
  <p style="font-family:verdana">Enter Channel Name <input type="text" id="mName" onkeyup="generateFullName()" /></P><br/>
 <br/>
  <p style="font-family:verdana;color:red;font-size:150%">COPY BELOW LINK & SEND TO CUSTOMER</P><br/>

<p style="font-family:verdana;font-size:100%;color:Blue"><span id="fullName" /></P>


</head>
<body>
 
</body>
</html>
