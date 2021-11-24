<template>
  <section style="background-color: #f8f8f8">
    <!--Section title!-->
    <div class="top-learners-header text-center">
      <p>GREAT WORDS ABOUT MAXCOACH</p>
      <h2>Our <a href="#">top learners'</a> verbatim</h2>
    </div>

    <!--Reviews container!-->
    <div class="reviews-container">
      <Review
        v-for="(review, i) in reviewsList"
        :key="i"
        :review="reviewsList[i]"
      ></Review>
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
import Review from "./main-sub-components/Review.vue";
export default {
  name: "TopLearners",
  components: { Review },
  data() {
    return {
      reviewsList: [
        {
          title: "It's a choice of quality for people with special needs",
          description:
            "I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just go me.",
          active: false,
          author: {
            name: "Florence Themes",
            photo: require("../../assets/testimonial-avata-03.jpg"),
            role: "Multimedia Admin",
          },
        },
        {
          title: "High level of efficiency and scientific teaching methods",
          description:
            "I am free to learn at my own pace, follow my own schedule and choose the subject I want to learn from the syllabus. Great study portal for people like me.",
          active: true,
          author: {
            name: "Mina Hollace",
            photo: require("../../assets/testimonial-avata-02.jpg"),
            role: "Freelancer",
          },
        },
        {
          title:
            "Professional team of specialists and passionate mentors at reach",
          description:
            "I need to get a certification for English proficiency and MaxCoach is my best choice. Their tutors are smart and professional when dealing with students.",
          active: false,
          author: {
            name: "Madley Pondor",
            photo: require("../../assets/testimonial-avata-04.jpg"),
            role: "IT Specialist",
          },
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "../../styles/toplearners.scss";
</style>