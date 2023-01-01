<template>
    <section>
        <!-- widget : text -->
      <aside class="widget widget_text">
        <h3 class="widget-title">About Me</h3>
        <div class="textwidget">
          <p><img src="images/site/about-me.png" alt="avatar" /></p>
          <p>
            Merhaba. Ben Yusuf :) Freelancer bir geliştiriciyim. Tekirdağda
            yaşıyorum. yazılım ve spor hakkında blog yazıyorum.
          </p>
        </div>
      </aside>
      <!-- widget : text -->

      <!-- widget : text -->
      <aside class="widget widget_text">
        <h3 class="widget-title">Follow Me</h3>
        <div class="textwidget">
          <p>
            <a
              class="social-link github"
              href="https://github.com/yusuftangal"
            ></a>
            <a class="social-link twitter" href="#"></a>
            <a
              class="social-link spotify"
              href="https://open.spotify.com/user/mx9jjgacfaus629lcad97htrw"
            ></a>
            <a
              class="social-link linkedin"
              href="https://www.linkedin.com/in/yusuf-tangalo%C4%9Flu-1887ba23b/"
            ></a>
            <a
              class="social-link instagram"
              href="https://www.instagram.com/kodlojii/"
            ></a>
          </p>
        </div>
      </aside>
      <!-- widget : text -->

      <!-- widget :  MailChimp for WordPress Plugin -->
      <aside class="widget widget_mc4wp_widget">
        <h3 class="widget-title">Subscribe To Newsletter</h3>
        <div class="form mc4wp-form">
          <form method="post">
            <p>
              <label>Email address: </label>
              <input
                type="email"
                name="EMAIL"
                placeholder="Your email address"
                required=""
              />
            </p>
            <p>
              <input type="submit" value="Sign up" />
            </p>
          </form>
        </div>
      </aside>
      <!-- widget :  MailChimp for WordPress Plugin -->

      <!-- widget : popular-posts -->
      <!-- styles for plugin : https://wordpress.org/plugins/top-10 -->
      <aside class="widget widget_widget_tptn_pop">
        <h3 class="widget-title">Trending Posts</h3>
        <div class="tptn_posts tptn_posts_widget">
          <ul>
            <li>
              <a href="#" class="tptn_link">
                <img
                  src="images/blog/p2.jpg"
                  alt="post-image"
                  class="tptn_thumb"
                />
              </a>
              <span class="tptn_after_thumb">
                <a href="#" class="tptn_link"
                  ><span class="tptn_title">Feel The Wind</span></a
                >
                <!--<span class="tptn_author"> by <a href="#">Johnny Doe</a></span>-->
                <span class="tptn_date"> September 3, 2014</span>
              </span>
            </li>

                        <!--<li>
                             <span class="tptn_after_thumb">
                                 <a href="#" class="tptn_link"><span class="tptn_title">Keep it Simple Dummy!</span></a>
                                 <span class="tptn_author"> by <a href="#">Johnny Doe</a></span>
                                 <span class="tptn_date"> September 3, 2014</span> 
                             </span>
                         </li>-->
          </ul>
        </div>
      </aside>
      <!-- widget : popular-posts -->

      <!-- widget : categories -->
      <aside class="widget widget_categories">
        <h3 class="widget-title">Categories</h3>
        <ul>
          <li class="cat-item">
            <a href="/" title="View all posts filed under Nature">HAKKIMDA</a>
          </li>
          <li class="cat-item">
            <a href="#" title="View all posts filed under Life">İLETİŞİM</a>
          </li>
          <li class="cat-item">
            <a href="#" title="View all posts filed under Adventure"
              >GYM</a
            >
          </li>
          <li class="cat-item">
            <a href="#" title="View all posts filed under Freebies">TRAVEL</a>
          </li>
        </ul>
      </aside>
      <!-- widget : categories -->

      <!-- widget : text -->
      <aside class="widget widget_text">
        <!--<h3 class="widget-title">BANNER</h3>-->
        <div class="textwidget">
          <a href="#"><img src="images/blog/banner.jpg" alt="banner" /></a>
        </div>
      </aside>
      <!-- widget : text -->
    </section>
</template>