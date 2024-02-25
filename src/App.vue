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
        <div class="col-12 col-md-6 p-4 leftCol">
          <!-- Left Column Content -->
          <h2 class="px-3">Main Section Left Column</h2>
          <div class="row">
            <div class="col-12 mx-3">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Id, accusamus.</div>
            <div class="col-12">
              <div class="mb-3">
                <form class="row g-3 mt-4 px-2 px-md-5">
                  <div class="col-12 col-md-6">
                    <label for="inputEmail4" class="form-label">Email</label>
                    <input type="email" class="form-control" id="inputEmail4">
                  </div>
                  <div class="col-12 col-md-6">
                    <label for="inputPassword4" class="form-label">Password</label>
                    <input type="password" class="form-control" id="inputPassword4">
                  </div>
                  <div class="col-12">
                    <label for="inputAddress" class="form-label">Address</label>
                    <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
                  </div>
                  <div class="col-12">
                    <label for="inputAddress2" class="form-label">Address 2</label>
                    <input type="text" class="form-control" id="inputAddress2" placeholder="Apartment, studio, or floor">
                  </div>
                  <div class="col-12 col-md-6">
                    <label for="inputCity" class="form-label">City</label>
                    <input type="text" class="form-control" id="inputCity">
                  </div>
                  <div class="col-md-4">
                    <label for="inputState" class="form-label">State</label>
                    <select id="inputState" class="form-select">
                      <option selected>Choose...</option>
                      <option>...</option>
                    </select>
                  </div>
                  <div class="col-md-2">
                    <label for="inputZip" class="form-label">Zip</label>
                    <input type="text" class="form-control" id="inputZip">
                  </div>
                  <div class="col-12">
                    <div class="form-check">
                      <input class="form-check-input" type="checkbox" id="gridCheck">
                      <label class="form-check-label" for="gridCheck">
                        Check me out
                      </label>
                    </div>
                  </div>
                  <div class="col-12">
                    <button type="submit" class="btn btn-primary">Sign in</button>
                  </div>
                </form>
              </div>
              
            </div>
          </div>
          <!-- Add your content here -->
        </div>
        <div class="col-12 col-md-6 mb-5 px-2">
          <!-- Right Column Content with Background Image -->
          <!-- <div class="dark-overlay"></div> -->
          <img class="col-12 image-fluid mb-4 p-0 p-md-5" src="./assets/spaceflow_office_orig.png" alt="" srcset="">
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
