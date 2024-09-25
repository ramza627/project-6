<template>
  <div class="min-h-screen bg-gradient-to-r from-gray-100 to-blue-100 flex items-center justify-center">
    <div class="max-w-3xl bg-white shadow-lg rounded-lg overflow-hidden">
      <div class="flex items-center justify-between p-8 bg-gradient-to-r from-primary to-blue-500 text-white">

        <!-- Profile -->
        <img src="@/assets/foto_rama.jpg" alt="Profile Picture" 
    class="rounded-full border-4 border-white shadow-md" 
    style="width: 100px; height: 100px;">

        <div class="ml-8">
          <h1 class="text-4xl font-semibold">Ramadasita</h1>
          <p class="text-lg text-secondary">Mahasiswa Vokasi Universitas Brawijaya</p>
          <div class="flex space-x-4 mt-4">
            <a href="https://www.linkedin.com/in/rama-dasita-349a50288/" target="_blank" class="text-white hover:text-secondary transition-colors">
              <i class="fab fa-linkedin-in fa-lg"></i>
            </a>
            <a href="https://www.instagram.com/ramadasita/" target="_blank" class="text-white hover:text-secondary transition-colors">
              <i class="fab fa-facebook-f fa-lg"></i>
            </a>
          </div>
        </div>
      </div>
      <div class="p-8">

        <!-- About Me Section -->
        <section class="mb-8">
          <h2 class="text-2xl font-bold text-primary">About Me</h2>
          <p class="mt-4 text-gray-700 leading-relaxed">
            Saya Ramadasita mahasiswa universitas brawijaya. Saya mampu bekerja secara tim maupun individu, memiliki motivasi tinggi dalam bekerja, memiliki komunikasi yang baik, dan mampu belajar hal-hal baru.
            Saya memiliki kemampuan fisik yang optimal serta senantiasa cekatan dan disiplin waktu. 
          </p>
        </section>

        <!-- Skills Section -->
        <section class="mb-8">
          <h2 class="text-2xl font-bold text-primary">Skills</h2>
          <ul class="mt-4 grid grid-cols-2 gap-4">
            <li class="bg-blue-50 p-4 rounded-lg shadow hover:shadow-md transition-shadow duration-300">
              <span class="font-medium text-primary">JavaScript, Vue.js, Nuxt.js</span>
            </li>
            <li class="bg-blue-50 p-4 rounded-lg shadow hover:shadow-md transition-shadow duration-300">
              <span class="font-medium text-primary">Tailwind CSS, Bootstrap</span>
            </li>
            <li class="bg-blue-50 p-4 rounded-lg shadow hover:shadow-md transition-shadow duration-300">
              <span class="font-medium text-primary">UI/UX</span>
            </li>
          </ul>
        </section>

        <!-- Education Section -->
        <section class="mb-8">
          <h2 class="text-2xl font-bold text-primary">Education</h2>
          <ul class="mt-4 space-y-4">
            <li class="bg-gray-100 p-6 rounded-lg shadow">
              <div class="font-semibold text-primary"> Teknologi Informasi</div>
              <div class="text-sm text-gray-500">Universitas Brawijaya, 2023-Sekarang</div>
            </li>
          </ul>
        </section>
      </div>
    </div>
  </div>
</template>



