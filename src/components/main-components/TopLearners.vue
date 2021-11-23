<template>
  <section style="background-color: #f8f8f8">
    <!--Section title!-->
    <div class="top-learners-header text-center">
      <p>GREAT WORDS ABOUT MAXCOACH</p>
      <h2>Our <a href="#">top learners'</a> verbatim</h2>
    </div>

    <!--Reviews container!-->
    <div class="reviews-container">
      <!--Card description!-->
      <div class="review-card">
        <h5>It's a choice of quality for people with special needs</h5>
        <p>
          I'm a very strict person so I require everything to be organized and
          neat. Then, I'll be able to make things right and shine. MaxCoach guys
          just got me.
        </p>

        <!--Card author!-->
        <div class="review-author">
          <img src="../../assets/testimonial-avata-03.jpg" alt="mina-hollace" />
          <div class="author-info">
            <h6>FLORENCE THEMES</h6>
            <small>/ Multimedia Admin</small>
          </div>
        </div>
      </div>

      <div class="review-card active">
        <h5>High level of efficiency and scientific teaching methods</h5>
        <p>
          I am free to learn at my own pace, follow my own schedule and choose
          the subject I want to learn from the syllabus. Great study portal for
          people like me.
        </p>

        <div class="review-author">
          <img src="../../assets/testimonial-avata-02.jpg" alt="mina-hollace" />
          <div class="author-info">
            <h6>MINA HOLLACE</h6>
            <small>/ Freelancer</small>
          </div>
        </div>
      </div>

      <div class="review-card">
        <h5>
          Professional team of specialists and passionate mentors to reach
        </h5>
        <p>
          I need to get a certification for English proficiency and MaxCoach is
          my best choice. Their tutors are smart and professional when dealing
          with students.
        </p>

        <div class="review-author">
          <img src="../../assets/testimonial-avata-04.jpg" alt="mina-hollace" />
          <div class="author-info">
            <h6>MADLEY PONDOR</h6>
            <small>/ IT Specialist</small>
          </div>
        </div>
      </div>
    </div>

    <!--Cards navigation dots!-->
    <div class="reviews-nav-dots">
      <i class="fa fa-circle active"></i>
      <i class="fa fa-circle"></i>
      <i class="fa fa-circle"></i>
      <i class="fa fa-circle"></i>
    </div>

    <!--Get started sub-section!-->
    <div class="container">
      <div class="top-learners-footer">
        <h5>Start today for getting <a href="#">Online Certification</a></h5>
        <h2>You can be your own guiding star with our help!</h2>
        <a href="#" class="btn btn-primary">Get started now</a>

        <img src="../../assets/maxcoach-shape-01.png" alt="" class="fx7" />
        <img src="../../assets/maxcoach-shape-02.png" alt="" class="fx8" />
        <div class="empty-circle fx11"></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "TopLearners",
};
</script>

<style lang="scss">
@import "../../styles/toplearners.scss";
</style>