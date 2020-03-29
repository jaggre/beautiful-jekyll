---
layout: page
title: "Contact Us"
tags: contact
image: /img/hello_world.jpeg

---

## Contact Us

<div class="contact-form">
      <form netlify action="thank-you">
        <fieldset>
          <section>
            <label for="name">Name
              <input autofocus type="text" name="name" id="name">
            </label>
          </section>

          <section>
            <label for="email">Email
              <input required type="email" name="email" id="email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,3}$">
            </label>
          </section>

          <section>
            <label for="message">Message
              <textarea required name="message" id="message"></textarea>
            </label>
          </section>

          <section>
            <div data-netlify-recaptcha></div>
          </section>

          <input class="button-secondary" type="submit" value="Send Message">
        </fieldset>
      </form>
    </div>