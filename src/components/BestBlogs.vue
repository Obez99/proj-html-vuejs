<template>
  <section>
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-4 most-viewed-list">
          <div>
            <p>Enjoyable Insights</p>
            <h2>Most Viewed Best Blogs</h2>
          </div>

          <ul>
            <li>
              <i class="fa fa-long-arrow-right"></i>Become a Better Blogger:
              Content Planning
            </li>
            <li>
              <i class="fa fa-long-arrow-right"></i>Promoting Your Online
              Business on Pinterest
            </li>
            <li>
              <i class="fa fa-long-arrow-right"></i>Gamification and Game-Based
              Learning
            </li>
            <li>
              <i class="fa fa-long-arrow-right"></i>Designing an Online Course
              from Expert's Perspective
            </li>
            <li>
              <i class="fa fa-long-arrow-right"
                >Why Online Courses Are the Future of Education</i
              >
            </li>
          </ul>
        </div>

        <div class="col-3 insight">
          <img src="../assets/artist-blog-03-480x352.jpeg" alt="" />
          <div class="insight-body">
            <p>ARTIST</p>
            <h5>Brush Strokes Energize Trees in Paintings</h5>
            <span><i class="fa fa-calendar-o"></i>May 15, 2020</span>
            <span><i class="fa fa-eye"></i>688 views</span>
          </div>
        </div>

        <div class="col-3 insight">
          <img src="../assets/artist-blog-01-480x352.jpg" alt="" />
          <div class="insight-body">
            <p>ARTIST</p>
            <h5>Pocket-Sized Notebooks Hold Miniature Paintings</h5>
            <span><i class="fa fa-calendar-o"></i>May 15, 2020</span>
            <span><i class="fa fa-eye"></i>603 views</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "BestBlogs",
};
</script>

<style lang="scss">
@import "../styles/bestblogs.scss";
</style>