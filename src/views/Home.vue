<template>
  <!-- HERO -->
  <section
    id="home"
    class="min-h-screen flex items-center bg-gradient-to-br from-indigo-600 via-purple-600 to-pink-500 text-white"
  >
    <div class="max-w-7xl mx-auto px-6 grid lg:grid-cols-2 gap-16 items-center">
      <div>
        <p class="text-indigo-200 mb-4 tracking-widest uppercase text-sm">Hello, I’m</p>

        <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-6">
          Dileep
          <br />
          <span class="text-yellow-300">Frontend Developer</span>
        </h1>

        <p class="text-lg text-indigo-100 mb-10 max-w-xl">
          I create modern, fast, and scalable web applications using Vue, TypeScript, and Tailwind
          CSS.
        </p>

        <div class="flex flex-wrap gap-5">
          <a
            href="#projects"
            class="bg-white text-indigo-700 px-8 py-3 rounded-xl font-semibold shadow-lg hover:shadow-xl hover:-translate-y-1 transition-all"
          >
            View Projects
          </a>

          <a
            href="#contact"
            class="bg-white/10 backdrop-blur px-8 py-3 rounded-xl shadow-lg hover:bg-white hover:text-indigo-700 transition-all"
          >
            Contact Me
          </a>
        </div>
      </div>

      <div class="hidden lg:flex justify-center">
        <img
          src="https://illustrations.popsy.co/gray/web-design.svg"
          alt="Developer illustration"
          class="max-w-md drop-shadow-[0_35px_70px_rgba(0,0,0,0.35)]"
        />
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section
    id="about"
    class="py-28 bg-gray-50"
  >
    <div class="max-w-4xl mx-auto px-6 text-center">
      <div class="bg-white rounded-2xl p-12 shadow-xl">
        <h2 class="text-3xl md:text-4xl font-bold mb-6">About Me</h2>

        <p class="text-gray-600 text-lg leading-relaxed">
          I’m a frontend developer focused on building clean, performant, and user-friendly
          interfaces using Vue 3, Vite, and Tailwind CSS. I enjoy turning complex problems into
          simple, beautiful solutions.
        </p>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section
    id="projects"
    class="py-28 bg-white"
  >
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-20">Projects</h2>

      <div class="grid gap-12 sm:grid-cols-2 lg:grid-cols-3">
        <div
          v-for="i in 3"
          :key="i"
          class="group rounded-2xl bg-gray-50 overflow-hidden shadow-lg hover:shadow-2xl hover:-translate-y-2 transition-all duration-300"
        >
          <div class="h-44 bg-gradient-to-br from-indigo-500 to-purple-500"></div>

          <div class="p-7">
            <h3 class="text-xl font-semibold mb-3">Project {{ i }}</h3>

            <p class="text-gray-600 mb-6">
              Brief description of the project, tools used, and the problem it solves.
            </p>

            <a
              href="#"
              class="inline-flex items-center text-indigo-600 font-medium group-hover:underline"
            >
              View Project →
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section
    id="contact"
    class="py-28 bg-gray-900 text-white"
  >
    <div class="max-w-4xl mx-auto px-6 text-center">
      <div class="bg-gray-800 rounded-2xl p-14 shadow-2xl">
        <h2 class="text-3xl md:text-4xl font-bold mb-6">Let’s Work Together</h2>

        <p class="text-gray-300 text-lg mb-10">
          Have an idea or project in mind? Let’s build something amazing.
        </p>

        <a
          href="mailto:dileepkushwaha8090@gmail.com"
          class="inline-block bg-indigo-600 px-12 py-4 rounded-xl font-semibold text-lg shadow-lg hover:shadow-xl hover:bg-indigo-700 transition-all"
        >
          Contact Me
        </a>
      </div>
    </div>
  </section>
</template>
