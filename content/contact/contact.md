---
layout: layouts/base.njk
eleventyNavigation:
  key: Contact
  order: 3
---

<h2 class="text-center mt-5 fs-5 text-secondary">Thanks for taking the time to reach out. <br> How can I help you today?</h2>

  <main class="container mt-0">

    <form name="contact" method="POST" data-netlify="true" class="row g-1 mt-0 mb-md-5  d-flex justify-content-center shadow-sm p-3 mb-5 bg-light rounded">

        <div class="col-lg-7">
          <label for="name" class="form-label">Name</label>
          <input type="name" name="name" class="form-control bg-dark-subtle" id="inputName" >
        </div>

        <div class="col-lg-7">
            <label for="inputEmail" class="form-label">Email</label>
            <input type="email" name="email" class="form-control bg-dark-subtle" id="inputEmail" >
        </div>

        <div class="col-lg-7">
          <label for="PhoneNumber" class="form-label">Phone Number</label>
          <input type="tel" name="number" class="form-control bg-dark-subtle" id="PhoneNumber" >
        </div>

        <div class="mt-5 col-lg-7">
          <label for="message">Message</label>
          <textarea name="message" class="form-control  lead bg-dark-subtle" placeholder="" id="message" style="height: 300px"></textarea>
        </div>

        <div class="text-center">
        <input type="checkbox" required class="ms-3">
            "I agree to the terms and conditions as set out by the user agreement."
        </input>
        </div>

      <div class="field">
         <div data-netlify-recaptcha="true"></div>
      </div>

      <div class="col-12 text-center">
          <button type="submit" class="btn btn-lg btn-primary">Submit</button>
      </div>

  </form>

</main>

<div class=" d-flex justify-content-center">
<p class="mt-5">
<i class="bi bi-envelope-fill"> kalaya.grimshaw@gmail.com</i> <br>
<i class="bi bi-github"> https://github.com/KGrim23</i> <br>
<i class="bi bi-linkedin">  www.linkedin.com/in/kgrim23</i>
</pre>
</div>

<script>
  let inputName = document.getElementById("inputName")
  function justLetters (inputName) {
    let letters = /^[A-Za-z]+$/;
    if (inputName.value.match(letters)){
      return true;
    }
    else{
      return false;
    }
  }

</script>
