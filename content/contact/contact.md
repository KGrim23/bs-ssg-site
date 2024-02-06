---
layout: layouts/base.njk
eleventyNavigation:
  key: Contact
  order: 3
---

<section><h2 class="text-center mt-5">Thanks for taking the time to reach out. <br> How can I help you today?</h2></section>

  <main class="container mt-0">
    <form name="contact" method="POST" data-netlify="true" action="/contact/success-msg.md" class="row g-1 mt-0 mb-md-5">
    
        <div class="col-lg-5">
          <label for="name" class="form-label">Name</label>
          <input type="name" name="name" class="form-control bg-dark-subtle" id="inputName" placeholder="">
        </div>

        <div class="col-lg-5">
            <label for="inputEmail" class="form-label">Email</label>
            <input type="email" name="email" class="form-control bg-dark-subtle" id="inputEmail" placeholder="">
        </div>

        <div class="col-lg-5">
          <label for="inputAddress2" class="form-label">Phone Number</label>
          <input type="tel" name="number" class="form-control bg-dark-subtle" id="inputPhoneNumber" placeholder="">
        </div>

          <div class="mt-5 col-lg-5">
          <label for="floatingTextarea2">Message</label>
          <textarea name="message" class="form-control  lead bg-dark-subtle" placeholder="" id="floatingTextarea2" style="height: 300px"></textarea>
        </div>

        <div class="field">
          <div data-netlify-recaptcha="true"></div>
        </div>

          <div class="col-12 text-center">
            <button type="submit" class="btn btn-lg btn-primary">Submit</button>
          </div>
      </form>
    </main>

  <input type="checkbox" required>
    "I agree to the terms and conditions as set out by the user agreement."
  </input>

<p class="mt-5">
<i class="bi bi-envelope-fill"> kalaya.grimshaw@gmail.com</i><br>
<i class="bi bi-github"> https://github.com/KGrim23</i><br>
<i class="bi bi-linkedin">  www.linkedin.com/in/kgrim23</i>
</p>
