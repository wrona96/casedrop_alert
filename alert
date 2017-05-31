var lel = (String($('.button-main-reversed').html()));
var hours = parseInt(String(/[0-9]{2}:/.exec(lel)));
var minutes = parseInt(String(/[0-9]{2}/.exec(String(/:[0-9]{2}:/.exec(lel)))));
var seconds = parseInt(String(/[0-9]{2}/.exec(String(/:[0-9]{2}</.exec(lel)))));
var x = setInterval(function() {

   seconds = seconds - 1;
   if (seconds == -1)
   {
		minutes = minutes - 1;
		seconds = 59;
	}
	if (minutes == -1)
	{
		hours = hours - 1;
		minutes = 59;
	}
	if ((hours == 0 && minutes == 0 && seconds == 0) || hours < 0)
	{
		alert("Hello! I am an alert box!!");
		clearInterval(x);
	}
  document.getElementsByClassName("free-case-box")[0].innerHTML = hours + "h "
  + minutes + "m " + seconds + "s ";
}, 1000);
