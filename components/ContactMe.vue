<template>
  <section>
    <div id="content" class="site-content" role="main">
      <!-- .hentry -->
      <article class="hentry page">
        <header class="entry-header">
          <h1 class="entry-title">İLETİŞİM</h1>
        </header>

        <!-- .entry-content -->
        <div class="entry-content">
          <p>Her Konuda Fikirlerinizi Önemsiyorum</p>

          <!-- .contact-form -->
          <div class="contact-form">
            <form
              id="contact-form"
              class="validate-form"
              method="post"
              action="send-mail.php"
            >
              <!-- enter mail subject here -->
              <input
                type="hidden"
                name="subject"
                id="subject"
                value="You have a new message!"
              />

              <p>
                <label for="name">İSİM</label>
                <input type="text" name="name" id="name" class="required" />
              </p>

              <p>
                <label for="email">E-POSTA</label>
                <input
                  type="text"
                  name="email"
                  id="email"
                  class="required email"
                />
              </p>

              <p class="antispam">
                Leave this empty if you are a human : <br /><input name="url" />
              </p>

              <p>
                <label for="message">MESAJINIZ</label>
                <textarea
                  name="message"
                  id="message"
                  class="required"
                ></textarea>
              </p>

              <p>
                <button class="submit button">
                  <span class="submit-label">ROKETLE :)</span
                  ><span class="submit-status"></span>
                </button>
              </p>
            </form>
          </div>
          <!-- .contact-form -->
        </div>
        <!-- .entry-content -->
      </article>
      <!-- .hentry -->
    </div>
  </section>
</template>
