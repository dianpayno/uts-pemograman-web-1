<script lang="ts">

</script>

<template>
  <NuxtLayout>
    <div class="w-full min-h-screen flex justify-start bg-black">
    <!-- SideBar Contetnt -->
    <div class="w-[370px] min-h-screen text-white py-10 px-5">
      <!-- Avatar Summary With Image -->
   
      <div class="flex justify-start items-center gap-3">
        <div
          class="flex justify-center items-center min-w-[70px] min-h-[70px] max-w-[70px] max-h-[70px] rounded-full p-2 border-[1px] border-white overflow-hidden"
        >
          <img
            src="./assets/image/fotoprofile.JPG"
            alt="Gambar"
            class="min-w-[70px] min-h-[70px] max-w-[70px] max-h-[70px] object-cover"
          />
        </div>
        <div class="flex flex-col">
          <p class="text-[20px]">Dian Herdiana</p>
          <p class="text-[15px] text-gray-500">Fronted Web Developer</p>
        </div>
      </div>

      <!-- List Of Menu with Ul Tag -->
      <div class="my-10 px-5">
        <div class="mb-3">
          <span class="text-[17px] font-bold ">Menu</span>
        </div>
        <ul class="flex flex-col gap-7 list-disc">
          <li class="hover:text-gray-500 cursor-pointer w-full p-2">Home</li>
          <li class="hover:text-gray-500 cursor-pointer w-full p-2">
            Projects
          </li>
          <li class="hover:text-gray-500 cursor-pointer w-full p-2">
            Contacts
          </li>
        </ul>
      </div>

      <!-- Navigate with a href to internal and external link -->

      <div class="my-10 px-5">
        <p class="font-bold">Social Media</p>
        <ul class="flex flex-col gap-7 list-disc">
          <div></div>
          <li class="hover:text-gray-500 cursor-pointer w-full p-2">
            <a href="https://www.instagram.com" target="_blank" > Instagram </a>
          </li>
          <li class="hover:text-gray-500 cursor-pointer w-full p-2">
            <a href="https://www.linkedin.com" target="_blank">Linkedin</a>
          </li>
          <li class="hover:text-gray-500 cursor-pointer w-full p-2">
            <a href="https://www.github.com" target="_blank">Github</a>
          </li>
        </ul>
      </div>
    </div>

    <!-- Main Content -->
    <div
      class="m-5 w-full min-h-[calc(70vh-40px)] bg-gray-900 p-10 text-white rounded-2xl shadow"
    >
      <!-- Heading Style & text formating -->
      <h1 class="text-5xl mt-20 mb-2"><b>Hello!, I'm Dian</b></h1>
      <div class="flex justify-start items-center gap-3">
        <h2 class="text-4xl font-bold text-purple-300">
          Fronted Web Developer
        </h2>
        <div
          class="text-[17px] bg-black/30 h-[40px] px-7 flex justify-center items-center rounded-2xl"
        >
          <span>📍 Jakarta, Indonesia</span>
        </div>
      </div>

      <!-- Paragraph and Text Formating -->
      <div class="max-w-[800px]">
        <p class="my-9">
          With 2 years of hands-on experience <i>building web </i> and
          <i>mobile apps</i> using Vue/Nuxt.js, React/Next.js, and React Native.
          I love crafting smooth, responsive user interfaces and bringing ideas
          to life with code. Whether it's building sleek dashboards, dynamic
          websites, or mobile apps, I enjoy turning complex problems into
          simple, beautiful solutions.
        </p>
        <p>
          Right now, I’m also a first-semester student at
          <strong>University Siber Asia</strong>, diving deeper into the world
          of tech while continuing to grow as a developer. I'm always up for
          learning new things, collaborating on cool projects, or just geeking
          out over clean UI and good code. Let’s build something awesome
          together!
        </p>
      </div>

      <!-- Tag Image Here -->
      <div class="my-10 flex justify-start gap-5">
        <div>
          <h3 class="text-2xl">Gallery</h3>
          <div class="flex justify-start items-center gap-3 my-5">
            <img
              src="./assets/image/foto1.JPG"
              alt="'image1'"
              class="w-[300px] h-[300px] object-cover"
            />
            <img
              src="./assets/image/foto2.JPG"
              alt="image2"
              class="w-[300px] h-[300px] object-cover"
            />
            <img
              src="./assets/image/fotoProfile.JPG"
              alt="image3"
              class="w-[300px] h-[300px] object-cover"
            />
          </div>
        </div>
        <!-- Table Section -->
        <div>
          <h3 class="text-2xl mb-5">Technical Skills</h3>
          <table>
            <thead>
              <tr>
                <th class="w-[200px] border-1">Tech Stack</th>
                <th class="w-[200px] border-1">Capability</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="w-[200px] border-1 text-[14px] text-center">
                  React/Next.js
                </td>
                <td class="w-[200px] border-1 text-center">
                  <input type="checkbox" checked disabled />
                  <span class="ml-2">Proficient</span>
                </td>
              </tr>
              <tr>
                <td class="w-[200px] border-1 text-[14px] text-center">
                  Vue/Nuxt.js
                </td>
                <td class="w-[200px] border-1 text-center">
                  <input type="checkbox" checked disabled />
                  <span class="ml-2">Proficient</span>
                </td>
              </tr>
            </tbody>
          </table>
          <h3 class="text-2xl my-5">Non-Technical Skills</h3>
          <table>
            <thead>
              <tr>
                <th class="w-[200px] border-1">Skill</th>
                <th class="w-[200px] border-1">Capability</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="w-[200px] border-1 text-[14px] text-center">
                  Communication
                </td>
                <td class="w-[200px] border-1 text-center">
                  <input type="checkbox" checked disabled />
                  <span class="ml-2">Excellent</span>
                </td>
              </tr>
              <tr>
                <td class="w-[200px] border-1 text-[14px] text-center">
                  Problem Solving
                </td>
                <td class="w-[200px] border-1 text-center">
                  <input type="checkbox" checked disabled />
                  <span class="ml-2">Excellent</span>
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
  </NuxtLayout>
</template>
