<template>
  <div id="contact" class="py-20 px-4 max-w-6xl mx-auto">
    <h2 class="text-4xl font-bold text-center mb-12">Contact Me</h2>
    <div class="card bg-base-100 shadow-lg max-w-2xl mx-auto">
      <div class="card-body">
        <form class="space-y-4">
          <div class=" flex flex-col space-y-2">
            <label class="label">
              <span class="label-text">Your Name</span>
            </label>
            <input type="text" placeholder="Name" class="input w-full input-bordered" required />
          </div>
          <div class=" flex flex-col space-y-2">
            <label class="label">
              <span class="label-text">Your Email</span>
            </label>
            <input type="email" placeholder="Email" class="input w-full input-bordered" required />
          </div>
          <div class=" flex flex-col space-y-2">
            <label class="label">
              <span class="label-text">Message</span>
            </label>
            <textarea class="textarea w-full textarea-bordered h-24" placeholder="Your message"></textarea>
          </div>
          <div class=" flex flex-col space-y-2 mt-6">
            <button class="btn btn-primary">Send Message</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>