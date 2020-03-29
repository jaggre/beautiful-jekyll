---
layout: page3
title: "Contact Us"
tags: contact
image: /img/hello_world.jpeg

---

## Contact Us
<div class="jumbotron">
<div class="contact-form">
      <div class="input-group">
      <form netlify action="thank-you">
        <fieldset>
          <section>
            <label for="name">Name</label>
              <input autofocus type="text" placeholder="name" class="form-control">
          </section>
          <section>
            <label for="email">Email </label>
              <input required type="email" placeholder="email" class="form-control" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,4}$">
          </section>
          <section>
            <label for="message">Message</label>
              <input required type="text" placeholder="message" class="form-control">
          </section>
          <li class="spacer"></li>
          <section>
            <div data-netlify-recaptcha></div>
          </section>
          <input class="btn btn-default" type="submit" value="Send Message">
        </fieldset>
      </form>
    </div>
    </div>
    </div>