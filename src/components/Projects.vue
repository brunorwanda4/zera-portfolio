<template>
  <div id="projects" class="py-20 px-4 max-w-6xl mx-auto">
    <h2 class="text-4xl font-bold text-center mb-12">My Projects</h2>
    
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <!-- Hinga Agritech -->
      <div class="card bg-base-100 pt-4 shadow border border-base-content/20">
        <figure><img src="../assets/images/sprinkler.png"  class=" size-20" alt="Hinga Agritech" /></figure>
        <div class="card-body">
          <h3 class="card-title">Hinga Agritech Platform</h3>
          <p>A comprehensive platform helping farmers access weather updates, training materials, irrigation tools, and modern equipment.</p>
          <div class="card-actions justify-end">
            <div class="badge badge-outline">Vue.js</div>
            <div class="badge badge-outline">Flask</div>
            <div class="badge badge-outline">Agriculture</div>
          </div>
          <div class="mt-4">
            <button class="btn btn-primary btn-sm">View Project</button>
          </div>
        </div>
      </div>
      
      <!-- IT Institute Website -->
      <div class="card bg-base-100 pt-4 shadow border border-base-content/20">
        <figure><img src="../assets/images/university.png"  class=" size-20" alt="IT Institute" /></figure>
        <div class="card-body">
          <h3 class="card-title">Rural IT Institute Website</h3>
          <p>Platform for my IT institute offering courses and resources to students in rural communities.</p>
          <div class="card-actions justify-end">
            <div class="badge badge-outline">Vue.js</div>
            <div class="badge badge-outline">Node.js</div>
            <div class="badge badge-outline">Education</div>
          </div>
          <div class="mt-4">
            <button class="btn btn-primary btn-sm">View Project</button>
          </div>
        </div>
      </div>
      
      <!-- Face Recognition App -->
      <div class="card bg-base-100 pt-4 shadow border border-base-content/20">
        <figure><img src="../assets/images/face-scan.png"  class=" size-20" alt="Face Recognition" /></figure>
        <div class="card-body">
          <h3 class="card-title">Face Recognition System</h3>
          <p>An experimental project exploring facial recognition technology with Python and OpenCV.</p>
          <div class="card-actions justify-end">
            <div class="badge badge-outline">Python</div>
            <div class="badge badge-outline">OpenCV</div>
            <div class="badge badge-outline">Machine Learning</div>
          </div>
          <div class="mt-4">
            <button class="btn btn-primary btn-sm">View Project</button>
          </div>
        </div>
      </div>
      
      <!-- Weather App -->
      <div class="card bg-base-100 pt-4 shadow border border-base-content/20">
        <figure><img src="../assets/images/weather.png" class=" size-20" alt="Weather App" /></figure>
        <div class="card-body">
          <h3 class="card-title">Real-time Weather App</h3>
          <p>A weather application providing real-time updates and forecasts for rural farmers.</p>
          <div class="card-actions justify-end">
            <div class="badge badge-outline">Vue.js</div>
            <div class="badge badge-outline">API Integration</div>
            <div class="badge badge-outline">Real-time</div>
          </div>
          <div class="mt-4">
            <button class="btn btn-primary btn-sm">View Project</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>