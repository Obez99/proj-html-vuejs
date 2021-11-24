<template>
  <div class="col-6 course-container d-flex align-items-center">
    <!--Course image!-->
    <div class="course-image">
      <img :src="course.image" :alt="course.name" />
    </div>

    <!--Course description!-->
    <div class="course-description ms-3">
      <h4 v-if="course.price">{{ course.price }}</h4>
      <h4 v-else>Free</h4>
      <h5>{{ course.name }}</h5>
      <small
        ><i class="fa fa-file-text-o"></i>{{ course.lessons }} Lessons</small
      >
      <small class="ms-5"
        ><i class="fa fa-user-o"></i>{{ course.students }} Students</small
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "Course",
  props: { course: Object },
};
</script>

<style>
</style>