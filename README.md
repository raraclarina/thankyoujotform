<div style="text-align:center;">
<img src="https://sig.id//wp-content/uploads/logo/SIG-LightLogo.png" width="200" height="110">

<div style="text-align:center;">
<h1>Thank you!</h1>
<p>Your submission has been received.</p>
<p>This page will redirect in <span id="timer"></span>s.</p>
</div>
<script type="text/javascript">
var count = 10;
var redirect = "https://www.jotform.com";
function countDown() {
if(count >= 0){
document.getElementById("timer").innerHTML = count--;
setTimeout("countDown()", 1000);
}else{
window.location.href = redirect;
}
}
countDown();
</script>
