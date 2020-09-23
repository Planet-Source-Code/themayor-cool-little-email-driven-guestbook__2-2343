<div align="center">

## Cool little Email Driven GuestBook


</div>

### Description

This is a guestbook that lets you get user feedback right through your email! It comes complete with a preview function. Pretty neat little guestbook made by a beginner :) Any vote is appreciated!!

~kc~

Give me some feedback please :)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[theMayor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/themayor.md)
**Level**          |Beginner
**User Rating**    |4.5 (63 globes from 14 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/themayor-cool-little-email-driven-guestbook__2-2343/archive/master.zip)





### Source Code

```
<html>
<head>
<SCRIPT LANGUAGE="javascript">
function prev()
{
var kc=window.open('','joe',config='height=300,width=300')
kc.document.write("<html><head><title>Preview</title></head><body><center>")
kc.document.write("<font face='tahoma' color='blue' size='7'><u>")
kc.document.write("Preview</u></center><font size='2'>")
kc.document.write("</center>Name: "+document.gbook.Name.value+"<br>")
kc.document.write("Email: "+document.gbook.Email.value+"<br>")
kc.document.write("Website: <a href='"+document.gbook.Web.value+"' target='_new'>")
kc.document.write(""+document.gbook.WebName.value+"</a><br>")
kc.document.write("Location: "+document.gbook.Location.value+"<br>")
kc.document.write("Comments:<br>"+document.gbook.Comments.value+"<br>")
}
</SCRIPT>
<title>
Thank you for Signing the Guestbook!!
</title>
</head>
<body bgcolor="white" vlink="red" alink="green" link="blue">
<font face="tahoma" size="7" color="blue">
<center>
<u>
My Guestbook
</u>
</center>
<font color="red" size="3">
<FORM NAME="gbook" METHOD='post' ACTION='mailto:kcmerrill@hotmail.com?Subject=Signed Your GuestBook!!' ENCTYPE='text/plain'>
<center>
[<input type="submit" style="font-family:tahoma" style="border style:none" style="background:white" style="color:red" style="cursor:hand"value="Submit">
]
[
<input type="button" style="font-family:tahoma" style="border style:none" style="background:white" style="color:red" style="cursor:hand"value="Preview" onClick='prev()'>
]
[
<input type="reset" style="font-family:tahoma" style="border style:none" style="background:white" style="color:red" style="cursor:hand"value="Clear Fields">
]
</center>
<br>
Name: <input type="text" size="10" name="Name"><br>
Email: <input type="text" size="15" name="Email"><br>
Website Url: <input type="text" size="15" name="Web" value="http://"><br>
Website's Name: <input type="text" size="15" name="WebName"><br>
Location: <input type="text" size="15" name="Location"><br>
How Did you Find Me? <input type="text" size="15" name="Found By: "><br>
Comments:<br>
<TEXTAREA COLS="40" ROWS="10" NAME="Comments"></TEXTAREA>
<br>
</form>
</body>
</html>
```

