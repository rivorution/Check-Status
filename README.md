<FONT Color=green
  <FONT SIZE=20>กำลังพาท่านเข้าสู่หน้าหลัก</FONT>
 </font>


<script language="JavaScript">
	sec=5;
	function tplus() {
		sec-=1;
		document.getElementById("OutputText").innerHTML="<font color=\'red\'>" + sec + " </font> Sec.";
		if (sec==0) {
			document.getElementById("OutputText").innerHTML="Go!";
			document.getElementById("OutputText2").innerHTML="";
			window.location.replace("http://เว็บเป้าหมาย");
		}
		if (sec>0) {setTimeout("tplus()",1000);}
	}
	setTimeout("tplus()",1000);
</script>
		
<div align="center" id="OutputText"></div>
<div id="OutputText2">
	<div align="center">Please wait...</div>
</div>
