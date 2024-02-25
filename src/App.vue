<!-- <script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
 -->

 <template>

    <!-- Main Content -->

      <div class="row">
        <div class="col-6 p-4">
          <!-- Left Column Content -->
          <h2>Main Section Left Column</h2>
          <!-- Add your content here -->
        </div>
        <div class="col-12 col-md-6 px-2">
          <!-- Right Column Content with Background Image -->
          <div class="dark-overlay"></div>
          <img class="col-11 image-fluid mt-5 p-5" src="./assets/spaceflow_office_orig.png" alt="" srcset="">
          <!-- <h2>Main Section Right Column</h2> -->
          <!-- Add your content here -->
        </div>
      </div>
   

</template>

<script setup>
// Your script setup here
</script>

<style scoped>
/* Your component-specific styles here */
/* You can include the Bootstrap styles here or in your global styles */
        /* Add your custom styles for the dark overlay */
        .dark-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(176, 219, 172, 0.4); /* Adjust the alpha value for transparency */
        }

        /* Add your custom styles for the right column with background image */
        .image-column {
            background: url('./assets/spaceflow_office_orig.png') center/cover no-repeat  ;
            background-size: cover; /* Replace 'your-image.jpg' with your image URL */
            /* height:100vh; */
            height:550px;
            width:auto;
            display: flex;
            position:relative;
            align-items: center;
            justify-content: center;
            color: #fff; /* Set text color for the overlay */
        }
</style>
