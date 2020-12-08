---
title: "Contact"
menu: "main"
---

<div class="col-lg-6 offset-lg-3 text-center">
<img src="/images/logo.about.png" class="img-fluid mx-auto d-block" width="75%" alt="">
</div>

<br>

### Please enter your e-mail below to register for PPP.

<form id="reg_form" name="contact" method="POST" data-netlify="true">

<p>
<label>Your Email:</label>
<input type="email" name="email" id="inputemail" class="form-control">
</p>

<p>
<button type="submit" class="btn btn-primary">Register</button>
</p>

</form>
<script>
document.querySelector("form").addEventListener("submit", handleSubmit);
const handleSubmit = (e) => {
  e.preventDefault();
  let myForm = document.getElementById("reg_form");
  let formData = new FormData(myForm);
  alert('here);
  fetch('https://portal.aws.biochemistry.gwu.edu/consortium_register', {
    method: 'GET',
    headers: { "Content-Type": "application/x-www-form-urlencoded" },
    body: new URLSearchParams(formData).toString()
  }).then(() => navigate("/thank-you/")).catch(error => alert(error))
}
</script>