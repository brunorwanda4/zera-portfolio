<template>
  <div id="skills" class="py-20 px-4 max-w-6xl mx-auto">
    <h2 class="text-4xl font-bold text-center mb-12">My Skills</h2>
    
    <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
      <!-- Frontend Skills -->
      <div class="card bg-base-100 shadow">
        <div class="card-body items-center text-center">
          <div class="text-5xl text-primary mb-2">
            <i class="fab fa-vuejs"></i>
          </div>
          <h3 class="card-title">Vue.js</h3>
          <p>Frontend development with interactive UIs</p>
          <div class="rating rating-sm">
            <input type="radio" name="rating-1" class="mask mask-star" checked />
            <input type="radio" name="rating-1" class="mask mask-star" checked />
            <input type="radio" name="rating-1" class="mask mask-star" checked />
            <input type="radio" name="rating-1" class="mask mask-star" checked />
            <input type="radio" name="rating-1" class="mask mask-star" checked />
          </div>
        </div>
      </div>
      
      <!-- Backend Skills -->
      <div class="card bg-base-100 shadow">
        <div class="card-body items-center text-center">
          <div class="text-5xl text-secondary mb-2">
            <i class="fab fa-node-js"></i>
          </div>
          <h3 class="card-title">Node.js/Express</h3>
          <p>Backend API development</p>
          <div class="rating rating-sm">
            <input type="radio" name="rating-2" class="mask mask-star" checked />
            <input type="radio" name="rating-2" class="mask mask-star" checked />
            <input type="radio" name="rating-2" class="mask mask-star" checked />
            <input type="radio" name="rating-2" class="mask mask-star" checked />
            <input type="radio" name="rating-2" class="mask mask-star" />
          </div>
        </div>
      </div>
      
      <!-- Python -->
      <div class="card bg-base-100 shadow">
        <div class="card-body items-center text-center">
          <div class="text-5xl text-accent mb-2">
            <i class="fab fa-python"></i>
          </div>
          <h3 class="card-title">Python</h3>
          <p>Scripting, automation, and Flask</p>
          <div class="rating rating-sm">
            <input type="radio" name="rating-3" class="mask mask-star" checked />
            <input type="radio" name="rating-3" class="mask mask-star" checked />
            <input type="radio" name="rating-3" class="mask mask-star" checked />
            <input type="radio" name="rating-3" class="mask mask-star" checked />
            <input type="radio" name="rating-3" class="mask mask-star" checked />
          </div>
        </div>
      </div>
      
      <!-- UI/UX -->
      <div class="card bg-base-100 shadow">
        <div class="card-body items-center text-center">
          <div class="text-5xl text-primary mb-2">
            <i class="fas fa-paint-brush"></i>
          </div>
          <h3 class="card-title">UI/UX Design</h3>
          <p>User-friendly interfaces</p>
          <div class="rating rating-sm">
            <input type="radio" name="rating-4" class="mask mask-star" checked />
            <input type="radio" name="rating-4" class="mask mask-star" checked />
            <input type="radio" name="rating-4" class="mask mask-star" checked />
            <input type="radio" name="rating-4" class="mask mask-star" checked />
            <input type="radio" name="rating-4" class="mask mask-star" />
          </div>
        </div>
      </div>
      
      <!-- Add more skills as needed -->
    </div>
  </div>
</template>

<script setup>
// You might want to import Font Awesome icons properly in your project
</script>