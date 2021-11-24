<template>
  <section style="background-color: #f5f7fa">
    <!--Section header!-->
    <div class="text-center">
      <p>STIMULATED TO LEARN?</p>
      <h2>Featured Online Courses</h2>
    </div>

    <!--Courses container!-->
    <div class="container">
      <div class="row">
        <Course
          v-for="(course, i) in coursesList"
          :key="i"
          :course="coursesList[i]"
        ></Course>
      </div>
    </div>

    <!--All courses button!-->
    <div class="container text-center all-courses-btn">
      <a class="btn btn-primary" href="#"
        >View all courses <i class="fa fa-long-arrow-right"></i
      ></a>
    </div>
  </section>
</template>

<script>
import Course from "./main-sub-components/Course.vue";
export default {
  name: "Courses",
  components: { Course },
  data() {
    return {
      coursesList: [
        {
          name: "Learning to Write as a Professional Author",
          image: require("../../assets/course-02-480x298.jpg"),
          price: "$40.00",
          lessons: 20,
          students: 50,
        },
        {
          name: "Customer-centric Info-Tech Strategies",
          image: require("../../assets/stock-full-hd-03-480x298.jpg"),
          price: null,
          lessons: 24,
          students: 769,
        },
        {
          name: "Open Programming Courses for Everyone: Python",
          image: require("../../assets/stock-full-hd-04-480x298.jpg"),
          price: "$19.00",
          lessons: 17,
          students: 62,
        },
        {
          name: "Academic Listening and Note-taking",
          image: require("../../assets/stock-full-hd-06-480x298.jpg"),
          price: "$26.00",
          lessons: 14,
          students: 67,
        },
        {
          name: "Master jQuery in a Short Period of Time",
          image: require("../../assets/course-featured-image-01-480x298.jpg"),
          price: "$39.00",
          lessons: 6,
          students: 51,
        },
        {
          name: "Introduction to Javascript for Beginners",
          image: require("../../assets/stock-full-hd-05-480x298.jpg"),
          price: "$59.00",
          lessons: 14,
          students: 76,
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "../../styles/courses.scss";
</style>