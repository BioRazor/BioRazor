<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info" fixed="top">
      <b-img
        v-bind="mainProps"
        rounded="circle"
        alt="Profile Picture"
        src="https://media-exp2.licdn.com/dms/image/C4D03AQFdkIU8vUcQHA/profile-displayphoto-shrink_200_200/0?e=1585180800&v=beta&t=h6kBfX-qAD8O-zQnbeWRN9OQ8A8DL0waI68Hpii5ios"
      ></b-img>
      <b-navbar-brand href="#">David Abreu</b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="https://www.linkedin.com/in/biorazor/"
            >LinkedIn</b-nav-item
          >
          <b-nav-item href="#" disabled>Blog</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "BrandNav",
  data() {
    return {
      mainProps: {
        blank: false,
        blankColor: "#777",
        width: 55,
        height: 55,
        class: "m1"
      },
      navProps: {
        fixed: "bottom",
        sticky: true
      }
    };
  }
};
</script>
