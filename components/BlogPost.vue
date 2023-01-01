<template>
  <section>
    <div id="primary" class="content-area with-sidebar">
      <!-- site-content -->
      <div id="content" class="site-content" role="main">
        <!-- entry-header -->
        <!--<header class="entry-header">
                     <h1 class="entry-title">Latest Stories</h1>
                 </header>-->
        <!-- entry-header -->

        <!-- BLOG LIST -->
        <div class="blog-creative blog-stream">
          <!-- .hentry -->
          <article class="hentry post has-post-thumbnail" v-for="">
            <div
              class="post-thumbnail post-img"
              style="background-image: url(images/blog/07.jpg)"
            >
              <a href="blog-single.html">Gathering with old friends</a>

              <!-- .entry-header -->
              <header class="entry-header">
                <!-- .entry-meta -->
                <div class="entry-meta">
                  <span class="entry-date">
                    <time
                      class="entry-date"
                      datetime="2014-07-13T04:34:10+00:00"
                      >July 13, 2014</time
                    >
                  </span>
                  <span class="comment-link">
                    <a href="#comments">4 Comments</a>
                  </span>
                </div>
                <!-- .entry-meta -->
              </header>
              <!-- .entry-header -->
            </div>

            <div class="post-thumbnail post-desc">
              <!-- .entry-header -->
              <header class="entry-header">
                <!-- .entry-meta -->
                <div class="entry-meta">
                  <span class="cat-links">
                    <a
                      href="#"
                      title="View all posts in Life"
                      rel="category tag"
                      >Life</a
                    >
                  </span>
                </div>
                <!-- .entry-meta -->

                <!-- .entry-title -->
                <h2 class="entry-title">
                  <a href="blog-single.html">Gathering with old friends</a>
                </h2>

                <p>
                  <a href="blog-single.html" class="more-link">View Post</a>
                </p>
              </header>
              <!-- .entry-header -->
            </div>
          </article>
          <!-- .hentry -->

          </div>
        <!-- BLOG CREATIVE -->

        <!-- post pagination -->
        <nav class="post-pagination">
          <ul class="pagination">
            <li class="pagination-first"><a href="#"> First </a></li>
            <li class="pagination-prev"><a href="#" rel="prev"></a></li>
            <li class="pagination-num"><a href="#"> 1 </a></li>
            <li class="pagination-num current"><a href="#"> 2 </a></li>
            <li class="pagination-num"><a href="#"> 3 </a></li>
            <li class="pagination-next"><a href="#" rel="next"></a></li>
            <li class="pagination-last"><a href="#"> Last </a></li>
          </ul>
        </nav>
        <!-- post pagination -->
      </div>
      <!-- site-content -->
    </div>
    <!-- primary -->

    <!-- #secondary -->
    <div id="secondary" class="widget-area sidebar" role="complementary">
      <Sidebar />
    </div>
    <!-- #secondary -->
  </section>
</template>

<script>
import Sidebar from './Sidebar.vue';

export default {
    data() {
        return {};
    },
    components: { 
      Sidebar: () => import("@/components/Sidebar.vue"),
     }
};
</script>
