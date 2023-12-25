<template>
  <div class="min-h-screen max-w-[100vw] mix-w-[100vw] bg-[#F9F8F8] text-black lg:px-28 xl:px-36 ">
    <div class="xl:max-w-[70vw] xl:mx-auto">
      <!-- <div class="flex justify-between bg-white h-[5vh] w-full px-10">
        <div class="">Home</div>
        <div class="flex">
          <div class="">About</div>
          <div class="">Project</div>
          <div class="">Content</div>
        </div>
      </div> -->
      <div class="text-2xl py-48 px-10 scroll-m-11 snap-start sm:px-20 lg:px-10">
        <p class="text-4xl font-sans font-extrabold lg:text-5xl">
          Full-Stack Python Developer
        </p>
        <!-- <div class="text-xl mt-2 mb-5 font-bold ">Expertise at Python, JS</div> -->
        <p class="text-xl font-light mt-2 pt-5 text-gray-800 lg:w-3/4 lg:mx-auto">
          Hi, I'm Prithak Lamsal, also known as Sasquatch Rex. A passionate Full-stack
          Developer based in Kathmandu,Nepal
        </p>
        <div class="text-xl font-bold pt-5 pb-3">Here are my Tech Stacks</div>
        <div class="">
          <div class="items-center justify-between flex px-10 sm:px-20 md:px-36 lg:text-2xl lg:px-56 xl:px-80">
            <div class="hover:cursor-pointer text-orange-600">
              <i class="fa-brands fa-html5 fa-xl"></i>
            </div>
            <div class="cursor pointer text-blue-600">
              <i class="fa-brands fa-css3-alt fa-xl"></i>
            </div>

            <div class="text-yellow-500">
              <i class="fa-brands fa-js fa-xl"></i>
            </div>
            <div class="text-green-600">
              <i class="fa-brands fa-vuejs fa-xl"></i>
            </div>

            <div class="text-blue-700">
              <i class="fa-brands fa-python fa-xl"></i>
            </div>
            <div class="text-green-600">
              <i class="fa-brands fa-android fa-xl"></i>
            </div>
          </div>
        </div>
        <button
          class="px-5 py-2 text-center my-6 rounded-3xl bg-gray-300 font-serif font-semiboldshadow-2xl shadow-neutral-600 hover:shadow-neutral-400 hover:bg-gray-500 transition-all"
        >
          <a href="../assets/Resume.pdf" download class=""
            >Download My CV <i class="fa-solid fa-download" style="color: #000000"></i
          ></a>
        </button>
      </div>
    </div>
    <div class="xl:max-w-[70vw] xl:mx-auto">
    <div class="-mt-4 md:mx-16">
      <div
        class="text-4xl font-bold font-serif text-blue-600 border-gray-500 border-b-2 text-center pt-2 w-36 mx-auto"
      >
        Portfolio
      </div>
      <div
        class="mt-8 mb-10 h-full px-6 py-6 mx-4 rounded-2xl shadow-xl shadow-gray-300 text-2xl  bg-gray-100 sm:flex"
      >
        <div class="sm:w-[30%] md:w-1/3 sm:border-r-2 sm:px-2 sm:my-auto">
          <div class="font-mono text-3xl mb-2 font-bold">Ecommerce</div>

          <div class="text-xl mb-1 font-extralight font-serif text-neutral-500">
            Python · Html · TailwindCSS
          </div>
          <div class="text-base text-neutral-400 text-center mt-0 mb-2">
            Feburary, 2022
          </div>
        </div>
        <div class="sm:px-5 sm:text-left sm:my-auto">
          <p class="text-xl">
            A fully functioning Ecommerce website made using Django (Python). This project
            was made while learning Django itself.
          </p>

          <div class="my-5 mt-10 flex">
            <div class="mr-5 text-neutral-500 text-xl">Source Code :</div>
            <a href="https://github.com/SasquatchRex/E-commerce-Django" target="_blank"
              ><i
                class="fa-brands fa-github fa-xl hover:text-slate-500 hover:scale-105 transition-all"
              ></i
            ></a>
          </div>
        </div>
      </div>
      <div
        class="mt-8 mb-10 h-full px-6 py-6 mx-4 rounded-2xl shadow-xl shadow-gray-300 text-2xl  bg-gray-100 sm:flex"
      >
        <div class="sm:w-[30%] md:w-1/3 sm:border-r-2 sm:px-2 sm:my-auto">
          <div class="font-mono text-3xl mb-2 font-bold">Discourse GPT</div>

          <div class="text-xl mb-1 font-extralight font-serif text-neutral-500">
            Vue Js · Django · TailwindCSS
          </div>
          <div class="text-base text-neutral-400 text-center mt-0 mb-2">
            November, 2023
          </div>
        </div>
        <div class="sm:px-5 sm:text-left sm:my-auto">
          <p class="text-xl">
            An AI Chatbot which is trained upon custom data made using Django as backend and
          Vue Js as Frontend
          </p>

          <div class="my-5 mt-10 flex">
            <div class="mr-5 text-neutral-500 text-xl">Source Code :</div>
            <a href="#" target="_blank" class="text-gray-500"
              ><i
                class="fa-brands fa-github fa-xl hover:text-slate-500 hover:scale-105 transition-all"
              ></i
            ></a>
          </div>
        </div>
      </div>
      <div
        class="mt-8 mb-10 h-full px-6 py-6 mx-4 rounded-2xl shadow-xl shadow-gray-300 text-2xl  bg-gray-100 sm:flex"
      >
        <div class="sm:w-[30%] md:w-1/3 sm:border-r-2 sm:px-2 sm:my-auto">
          <div class="font-mono text-3xl mb-2 font-bold">Cubics</div>

          <div class="text-xl mb-1 font-extralight font-serif text-neutral-500">
            Unity · C#
          </div>
          <div class="text-base text-neutral-400 text-center mt-0 mb-2">
            Feburary, 2022
          </div>
        </div>
        <div class="sm:px-5 sm:text-left sm:my-auto">
          <p class="text-xl">
            A simple game made with the help of Unity as the engine and Unity as the
          programming language. This was the first project i ever did in unity and C#.
          </p>

          <div class="my-5 mt-10 flex">
            <div class="mr-5 text-neutral-500 text-xl">Source Code :</div>
            <a href="https://github.com/SasquatchRex/CUBICS/releases/tag/Game" target="_blank"
              ><i
                class="fa-brands fa-github fa-xl hover:text-slate-500 hover:scale-105 transition-all"
              ></i
            ></a>
          </div>
        </div>
      </div>
      <div
        class="mt-8 mb-10 h-full px-6 py-6 mx-4 rounded-2xl shadow-xl shadow-gray-300 text-2xl  bg-gray-100 sm:flex"
      >
        <div class="sm:w-[30%] md:w-1/3 sm:border-r-2 sm:px-2 sm:my-auto">
          <div class="font-mono text-3xl mb-2 font-bold">Messegex</div>

          <div class="text-xl mb-1 font-extralight font-serif text-neutral-500">
            Vue Js · Firebase · TailwindCSS
          </div>
          <div class="text-base text-neutral-400 text-center mt-0 mb-2">
            October, 2023
          </div>
        </div>
        <div class="sm:px-5 sm:text-left sm:my-auto">
          <p class="text-xl">
            A chat application I made while learning firebase and Vue Js. I learned things
          like User-Authentication, User-Creation, Message-Storage and many more while
          doing this project.
          </p>

          <div class="my-5 mt-10 flex">
            <div class="mr-5 text-neutral-500 text-xl">Source Code :</div>
            <a href="#" class="text-gray-500" target="_blank"
              ><i
                class="fa-brands fa-github fa-xl hover:text-slate-500 hover:scale-105 transition-all"
              ></i
            ></a>
          </div>
        </div>
      </div>
      <div
        class="mt-8 mb-10 h-full px-6 py-6 mx-4 rounded-2xl shadow-xl shadow-gray-300 text-2xl  bg-gray-100 sm:flex"
      >
        <div class="sm:w-[30%] md:w-1/3 sm:border-r-2 sm:px-2 sm:my-auto">
          <div class="font-mono text-3xl mb-2 font-bold">Market Portfolio</div>

          <div class="text-xl mb-1 font-extralight font-serif text-neutral-500">
            Flutter · Django
          </div>
          <div class="text-base text-neutral-400 text-center mt-0 mb-2">
            December, 2023
          </div>
        </div>
        <div class="sm:px-5 sm:text-left sm:my-auto">
          <p class="text-xl">
            A share Market Portfolio App that i made while learning Flutter. It also includes features like live data, News and many more. This was the first time I created a native Mobile App.
          </p>

          <div class="my-5 mt-10 flex">
            <div class="mr-5 text-neutral-500 text-xl">Source Code :</div>
            <a href="#" class="text-gray-500" target="_blank"
              ><i
                class="fa-brands fa-github fa-xl hover:text-slate-500 hover:scale-105 transition-all"
              ></i
            ></a>
          </div>
        </div>
      </div>
      
    </div>
    <div class="">
      <div
        class="mt-24 mb-0 bg-gray-200 px-4 py-12 mx-4 rounded-2xl shadow-xl shadow-neutral-300 "
      >
        <div class="text-4xl text-center font-serif font-bold mb-5 text-blue-600">
          Contact Me
        </div>
        <div class="flex justify-between mt-10 md:px-20">
          <a href="https://www.facebook.com/SasquatchRex/" target="_blank"
            ><i
              class="fa-brands fa-facebook fa-2xl hover:text-slate-500 hover:scale-105 transition-all"
            ></i>
          </a>
          <a href="https://www.instagram.com/saasquatch_rex/" target="_blank"
            ><i
              class="fa-brands fa-instagram fa-2xl hover:text-slate-500 hover:scale-105 transition-all"
            ></i
          ></a>
          <a href="https://github.com/sasquatchrex" target="_blank"
            ><i
              class="fa-brands fa-github fa-2xl hover:text-slate-500 hover:scale-105 transition-all"
            ></i
          ></a>
          <a href="https://www.reddit.com/user/Sasquatch_Rex" target="_blank"
            ><i
              class="fa-brands fa-reddit fa-2xl hover:text-slate-500 hover:scale-105 transition-all"
            ></i
          ></a>
          <a href="#" target="_blank"
            ><i
              class="fa-brands fa-linkedin fa-2xl hover:text-slate-500 hover:scale-105 transition-all"
            ></i
          ></a>
          <a href="https://twitter.com/RexSasquatch" target="_blank"
            ><i
              class="fa-brands fa-twitter fa-2xl hover:text-slate-500 hover:scale-105 transition-all"
            ></i
          ></a>
          <a href="mailto:contact@prithaklamsal.com.np"
            ><i class="fa-solid fa-envelope fa-2xl"></i
          ></a>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "HomeView",
};
</script>
