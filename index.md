---
layout: default
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<!-- ## Welcome! -->

<!-- <img class="profile-picture" src="sherlock.jpg"> -->

<div class="body">My name is Vijay Jain. I am a 
	<span id="changer">quantum engineer.</span></div>

I work at the <a href="https://quantuminstitute.yale.edu">Yale Quantum Institute</a> and am from New York and Zürich.
<!-- Currently, I am connecting superconducting circuits to sound waves in crystals as a memory for quantum information as a Postdoctoral Associate at the <a href="https://quantuminstitute.yale.edu">Yale Quantum Institute</a>.  -->

My portfolio is coming online soon. Let's chat!


<script>    var words = ["quantum engineer.", "laser scientist.", "collaborator.", "public speaker.", "German speaker.", "Pahari painting enthusiast.", "rower and cyclist."];
    var i = 0;
    var text = "quantum engineer.";
    function _getChangedText() {
      i = (i + 1) % words.length;
      return text.replace(/quantum engineer./, words[i]);
    }
    function _changeText() {
      var txt = _getChangedText();
        var d = document.getElementById("changer")
        d.className = "fadeOut";
        setTimeout(function(){
         d.className = "";
        document.getElementById("changer").innerHTML = txt;
    }, 1000);
    }
    setInterval("_changeText()", 2500);</script>

<a href="https://scholar.google.com/citations?user=XjmA_Q4AAAAJ&hl=en&oi=ao" target="_blank"><i class="fa fa-google"></i></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/vjain89" target="_blank"><i class="fa fa-linkedin"></i></a>&nbsp;&nbsp;
<a href="https://twitter.com/89Vjain" target="_blank"><i class="fa fa-twitter"></i></a>&nbsp;&nbsp;

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-SP8N9PDJP6"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-SP8N9PDJP6');
</script>