<template>
  <!-- HERO -->
  <section
    id="home"
    class="min-h-screen flex items-center bg-gradient-to-br from-indigo-600 via-purple-600 to-pink-500 text-white"
  >
    <div class="max-w-7xl mx-auto px-6 grid lg:grid-cols-2 gap-14 items-center">
      <div>
        <p class="text-indigo-200 mb-4 tracking-wide">Hello, I’m</p>

        <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-6">
          Dileep <br />
          <span class="text-yellow-300">Frontend Developer</span>
        </h1>

        <p class="text-lg text-indigo-100 mb-10 max-w-xl">
          I create modern, fast, and scalable web applications using
          Vue, TypeScript, and Tailwind CSS.
        </p>

        <div class="flex flex-wrap gap-4">
          <a
            href="#projects"
            class="bg-white text-indigo-700 px-7 py-3 rounded-lg font-semibold hover:bg-gray-100 transition"
          >
            View Projects
          </a>

          <a
            href="#contact"
            class="border border-white/70 px-7 py-3 rounded-lg hover:bg-white hover:text-indigo-700 transition"
          >
            Contact Me
          </a>
        </div>
      </div>

      <div class="hidden lg:flex justify-center">
        <img
          src="https://illustrations.popsy.co/gray/web-design.svg"
          alt="Developer illustration"
          class="max-w-md drop-shadow-2xl"
        />
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="py-24 bg-gray-50">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-6">
        About Me
      </h2>

      <p class="text-gray-600 text-lg leading-relaxed">
        I’m a frontend developer focused on building clean, performant,
        and user-friendly interfaces using Vue 3, Vite, and Tailwind CSS.
        I enjoy turning complex problems into simple, beautiful solutions.
      </p>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-16">
        Projects
      </h2>

      <div class="grid gap-8 sm:grid-cols-2 lg:grid-cols-3">
        <div
          v-for="i in 3"
          :key="i"
          class="group rounded-xl border bg-gray-50 overflow-hidden hover:shadow-xl transition"
        >
          <div class="h-44 bg-gradient-to-br from-indigo-500 to-purple-500"></div>

          <div class="p-6">
            <h3 class="text-xl font-semibold mb-3">
              Project {{ i }}
            </h3>

            <p class="text-gray-600 mb-5">
              Brief description of the project, tools used,
              and the problem it solves.
            </p>

            <a
              href="#"
              class="inline-flex items-center text-indigo-600 font-medium hover:underline"
            >
              View Project →
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-24 bg-gray-900 text-white">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-6">
        Let’s Work Together
      </h2>

      <p class="text-gray-300 text-lg mb-10">
        Have an idea or project in mind? Let’s build something amazing.
      </p>

      <a
        href="mailto:dileepkushwaha8090@gmail.com"
        class="inline-block bg-indigo-600 px-10 py-4 rounded-lg font-semibold text-lg hover:bg-indigo-700 transition"
      >
        Contact Me
      </a>
    </div>
  </section>
</template>
