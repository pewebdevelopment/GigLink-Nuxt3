<template>
  <!-- Start Hero -->
  <div
    class="
      relative
      table
      w-full
      py-36
      bg-[url('../../assets/images/bg/bg1.jpg')] bg-bottom bg-no-repeat
    "
  >
    <div
      class="absolute inset-0 bg-gradient-to-b from-transparent to-slate-900"
    ></div>
    <div class="container">
      <div class="grid grid-cols-1 pb-8 text-center mt-10">
        <h3
          class="
            md:text-3xl
            text-2xl
            md:leading-snug
            tracking-wide
            leading-snug
            font-medium
            text-white
          "
        >
          About Us
        </h3>
      </div>
      <!--end grid-->
    </div>
    <!--end container-->

    <div class="absolute text-center z-10 bottom-5 right-0 left-0 mx-3">
      <ul
        class="breadcrumb tracking-[0.5px] breadcrumb-light mb-0 inline-block"
      >
        <li
          class="
            inline
            breadcrumb-item
            text-[15px]
            font-semibold
            duration-500
            ease-in-out
            text-white/50
            hover:text-white
          "
        >
          <a href="index.html">Giglink</a>
        </li>
        <li
          class="
            inline
            breadcrumb-item
            text-[15px]
            font-semibold
            duration-500
            ease-in-out
            text-white
          "
          aria-current="page"
        >
          About Us
        </li>
      </ul>
    </div>
  </div>
  <!--end section-->

  <!-- Start -->
  <section class="relative md:py-24 py-16">
    <div class="container">
      <div class="grid lg:grid-cols-12 grid-cols-2 items-center gap-[30px]">
        <div class="lg:col-span-5">
          <div class="relative">
            <div
              class="
                absolute
                inset-0
                bg-gradient-to-r
                from-red-600
                to-violet-600
                rounded-lg
                -mt-[15px]
                -ml-[15px]
                h-[98%]
                w-[98%]
                -z-1
              "
            ></div>
            <img
              src="assets/images/about.jpg"
              class="rounded-lg shadow-md dark:shadow-gray-800"
              alt=""
            />
            <div
              class="
                absolute
                bottom-2/4
                translate-y-2/4
                right-0
                left-0
                text-center
              "
            >
              <a
                href="#!"
                data-type="youtube"
                data-id="yba7hPeTSjk"
                class="
                  lightbox
                  h-20
                  w-20
                  rounded-full
                  shadow-lg
                  dark:shadow-gray-800
                  inline-flex
                  items-center
                  justify-center
                  bg-white
                  dark:bg-slate-900
                  text-violet-600
                "
              >
                <i
                  class="
                    mdi mdi-play
                    inline-flex
                    items-center
                    justify-center
                    text-2xl
                  "
                ></i>
              </a>
            </div>
          </div>
        </div>

        <div class="lg:col-span-7">
          <div class="lg:ml-5">
            <span class="text-violet-600 font-medium"
              >Creative Vision & Mission</span
            >
            <h3
              class="
                mb-4
                md:text-3xl
                text-2xl
                md:leading-snug
                leading-snug
                font-semibold
              "
            >
              We develop & create <br />
              digital art.
            </h3>

            <p class="text-slate-400 max-w-xl">
              We are a huge marketplace dedicated to connecting great artists of
              all Giglink with their fans and unique token collectors!
            </p>
            <p class="text-slate-400 max-w-xl mt-4">
              It seems that only fragments of the original text remain in the
              Lorem Ipsum texts used today. One may speculate that over the
              course of time certain letters were added or deleted at various
              positions within the text. This might also explain why one can now
              find slightly different versions.
            </p>

            <div class="mt-6">
              <a
                href="contact.html"
                class="
                  btn
                  bg-violet-600
                  hover:bg-violet-700
                  border-violet-600
                  hover:border-violet-700
                  text-white
                  rounded-full
                  mr-2
                  mt-2
                "
                ><i class="uil uil-envelope"></i> Contact us</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--end container-->

    <div class="container lg:mt-24 mt-16 lg:pt-24 pt-16">
      <div
        class="
          absolute
          inset-0
          opacity-25
          dark:opacity-50
          bg-[url('../../assets/images/map.png')] bg-no-repeat bg-center
        "
      ></div>
      <div class="relative grid grid-cols-1 pb-8 text-center z-1">
        <h3
          class="
            mb-4
            md:text-3xl
            text-2xl
            md:leading-snug
            leading-snug
            font-semibold
            text-black
            dark:text-white
          "
        >
          Trusted by more than 20K users
        </h3>

        <p class="text-slate-400 max-w-xl mx-auto">
          We are a huge marketplace dedicated to connecting great artists of all
          Giglink with their fans and unique token collectors!
        </p>
      </div>
      <!--end grid-->

      <div
        class="
          relative
          grid
          md:grid-cols-3
          grid-cols-1
          items-center
          mt-8
          gap-[30px]
          z-1
        "
      >
        <div class="counter-box text-center">
          <h1 class="lg:text-5xl text-4xl font-semibold mb-2">
            $<span class="counter-value" data-target="40">3</span>M
          </h1>
          <h5 class="counter-head text-lg font-medium text-slate-400">
            Trading volume
          </h5>
        </div>
        <!--end counter box-->

        <div class="counter-box text-center">
          <h1 class="lg:text-5xl text-4xl font-semibold mb-2">
            <span class="counter-value" data-target="200">2</span>+
          </h1>
          <h5 class="counter-head text-lg font-medium text-slate-400">
            NFTs created
          </h5>
        </div>
        <!--end counter box-->

        <div class="counter-box text-center">
          <h1 class="lg:text-5xl text-4xl font-semibold mb-2">
            <span class="counter-value" data-target="235">0</span>K
          </h1>
          <h5 class="counter-head text-lg font-medium text-slate-400">
            Total users
          </h5>
        </div>
        <!--end counter box-->
      </div>
    </div>
    <!--end container-->

    <div class="container lg:mt-24 mt-16">
      <div class="grid grid-cols-1 pb-8 text-center">
        <h6 class="text-violet-600 font-medium mb-2">Our Minds</h6>
        <h3
          class="
            mb-4
            md:text-3xl
            text-2xl
            md:leading-snug
            leading-snug
            font-semibold
          "
        >
          Management Team
        </h3>

        <p class="text-slate-400 max-w-xl mx-auto">
          We are a huge marketplace dedicated to connecting great artists of all
          Giglink with their fans and unique token collectors!
        </p>
      </div>
      <!--end grid-->

      <div class="grid md:grid-cols-12 grid-cols-1 mt-8 gap-[30px]">
        <div class="lg:col-span-3 md:col-span-6">
          <div class="group text-center">
            <div
              class="
                relative
                inline-block
                mx-auto
                h-52
                w-52
                rounded-full
                overflow-hidden
              "
            >
              <img src="assets/images/client/04.jpg" class="" alt="" />
              <div
                class="
                  absolute
                  inset-0
                  bg-gradient-to-b
                  from-transparent
                  to-black
                  h-52
                  w-52
                  rounded-full
                  opacity-0
                  group-hover:opacity-100
                  transition-all
                  duration-500
                  ease-in-out
                "
              ></div>

              <ul
                class="
                  list-none
                  absolute
                  right-0
                  left-0
                  -bottom-20
                  group-hover:bottom-5
                  transition-all
                  duration-500
                  ease-in-out
                "
              >
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="facebook" class="h-4 w-4"></i
                  ></a>
                </li>
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="instagram" class="h-4 w-4"></i
                  ></a>
                </li>
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="linkedin" class="h-4 w-4"></i
                  ></a>
                </li>
              </ul>
              <!--end icon-->
            </div>

            <div class="content mt-3">
              <a
                href=""
                class="
                  text-lg
                  font-semibold
                  hover:text-violet-600
                  transition-all
                  duration-500
                  ease-in-out
                "
                >Jack John</a
              >
              <p class="text-slate-400">Designer</p>
            </div>
          </div>
        </div>

        <div class="lg:col-span-3 md:col-span-6">
          <div class="group text-center">
            <div
              class="
                relative
                inline-block
                mx-auto
                h-52
                w-52
                rounded-full
                overflow-hidden
              "
            >
              <img src="assets/images/client/05.jpg" class="" alt="" />
              <div
                class="
                  absolute
                  inset-0
                  bg-gradient-to-b
                  from-transparent
                  to-black
                  h-52
                  w-52
                  rounded-full
                  opacity-0
                  group-hover:opacity-100
                  transition-all
                  duration-500
                  ease-in-out
                "
              ></div>

              <ul
                class="
                  list-none
                  absolute
                  right-0
                  left-0
                  -bottom-20
                  group-hover:bottom-5
                  transition-all
                  duration-500
                  ease-in-out
                "
              >
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="facebook" class="h-4 w-4"></i
                  ></a>
                </li>
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="instagram" class="h-4 w-4"></i
                  ></a>
                </li>
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="linkedin" class="h-4 w-4"></i
                  ></a>
                </li>
              </ul>
              <!--end icon-->
            </div>

            <div class="content mt-3">
              <a
                href=""
                class="
                  text-lg
                  font-semibold
                  hover:text-violet-600
                  transition-all
                  duration-500
                  ease-in-out
                "
                >Krista John</a
              >
              <p class="text-slate-400">Designer</p>
            </div>
          </div>
        </div>

        <div class="lg:col-span-3 md:col-span-6">
          <div class="group text-center">
            <div
              class="
                relative
                inline-block
                mx-auto
                h-52
                w-52
                rounded-full
                overflow-hidden
              "
            >
              <img src="assets/images/client/06.jpg" class="" alt="" />
              <div
                class="
                  absolute
                  inset-0
                  bg-gradient-to-b
                  from-transparent
                  to-black
                  h-52
                  w-52
                  rounded-full
                  opacity-0
                  group-hover:opacity-100
                  transition-all
                  duration-500
                  ease-in-out
                "
              ></div>

              <ul
                class="
                  list-none
                  absolute
                  right-0
                  left-0
                  -bottom-20
                  group-hover:bottom-5
                  transition-all
                  duration-500
                  ease-in-out
                "
              >
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="facebook" class="h-4 w-4"></i
                  ></a>
                </li>
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="instagram" class="h-4 w-4"></i
                  ></a>
                </li>
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="linkedin" class="h-4 w-4"></i
                  ></a>
                </li>
              </ul>
              <!--end icon-->
            </div>

            <div class="content mt-3">
              <a
                href=""
                class="
                  text-lg
                  font-semibold
                  hover:text-violet-600
                  transition-all
                  duration-500
                  ease-in-out
                "
                >Roger Jackson</a
              >
              <p class="text-slate-400">Designer</p>
            </div>
          </div>
        </div>

        <div class="lg:col-span-3 md:col-span-6">
          <div class="group text-center">
            <div
              class="
                relative
                inline-block
                mx-auto
                h-52
                w-52
                rounded-full
                overflow-hidden
              "
            >
              <img src="assets/images/client/07.jpg" class="" alt="" />
              <div
                class="
                  absolute
                  inset-0
                  bg-gradient-to-b
                  from-transparent
                  to-black
                  h-52
                  w-52
                  rounded-full
                  opacity-0
                  group-hover:opacity-100
                  transition-all
                  duration-500
                  ease-in-out
                "
              ></div>

              <ul
                class="
                  list-none
                  absolute
                  right-0
                  left-0
                  -bottom-20
                  group-hover:bottom-5
                  transition-all
                  duration-500
                  ease-in-out
                "
              >
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="facebook" class="h-4 w-4"></i
                  ></a>
                </li>
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="instagram" class="h-4 w-4"></i
                  ></a>
                </li>
                <li class="inline">
                  <a
                    href=""
                    class="
                      btn btn-icon btn-sm
                      rounded-full
                      border border-violet-600
                      bg-violet-600
                      hover:border-violet-600 hover:bg-violet-600
                      text-white
                    "
                    ><i data-feather="linkedin" class="h-4 w-4"></i
                  ></a>
                </li>
              </ul>
              <!--end icon-->
            </div>

            <div class="content mt-3">
              <a
                href=""
                class="
                  text-lg
                  font-semibold
                  hover:text-violet-600
                  transition-all
                  duration-500
                  ease-in-out
                "
                >Johnny English</a
              >
              <p class="text-slate-400">Designer</p>
            </div>
          </div>
        </div>
      </div>
      <!--end grid-->
    </div>
    <!--end container-->

    <div class="container lg:mt-24 mt-16">
      <div class="grid grid-cols-1 pb-8 text-center">
        <h6 class="text-violet-600 font-medium mb-2">Our Minds</h6>
        <h3
          class="
            mb-4
            md:text-3xl
            text-2xl
            md:leading-snug
            leading-snug
            font-semibold
          "
        >
          Latest Blog or News
        </h3>

        <p class="text-slate-400 max-w-xl mx-auto">
          We are a huge marketplace dedicated to connecting great artists of all
          Giglink with their fans and unique token collectors!
        </p>
      </div>
      <!--end grid-->

      <div
        class="grid lg:grid-cols-3 md:grid-cols-2 grid-cols-1 mt-8 gap-[30px]"
      >
        <div
          class="
            group
            relative
            overflow-hidden
            bg-white
            dark:bg-slate-900
            rounded-md
            shadow
            dark:shadow-gray-700
            hover:shadow-md
            transition-all
            duration-500
          "
        >
          <img src="assets/images/blog/01.jpg" alt="" />

          <div class="relative p-6">
            <div class="absolute left-6 -top-4">
              <span
                class="
                  bg-violet-900
                  text-white
                  dark:bg-violet-800
                  text-[12px]
                  px-2.5
                  py-1
                  font-semibold
                  rounded-full
                  h-5
                "
                >Arts</span
              >
            </div>

            <div class="">
              <div class="flex mb-4">
                <span class="text-slate-400 text-[16px]"
                  ><i
                    class="
                      uil uil-calendar-alt
                      text-slate-900
                      dark:text-white
                      mr-2
                    "
                  ></i
                  >20th October, 2022</span
                >
                <span class="text-slate-400 text-[16px] ml-3"
                  ><i
                    class="uil uil-clock text-slate-900 dark:text-white mr-2"
                  ></i
                  >5 min read</span
                >
              </div>

              <a
                href="blog-detail.html"
                class="
                  title
                  text-lg
                  font-medium
                  hover:text-violet-600
                  duration-500
                  ease-in-out
                "
                >Mindfulness Activities for Kids & Toddlers with NFT</a
              >

              <div class="flex justify-between mt-4">
                <a
                  href="blog-detail.html"
                  class="
                    btn btn-link
                    text-[16px]
                    font-medium
                    hover:text-violet-600
                    after:bg-violet-600
                    duration-500
                    ease-in-out
                  "
                  >Read More <i class="uil uil-arrow-right"></i
                ></a>
                <span class="text-slate-400 text-[16px]"
                  >by
                  <a
                    href="creator-profile.html"
                    class="
                      text-slate-900
                      dark:text-white
                      hover:text-violet-600
                      dark:hover:text-violet-600
                      font-medium
                    "
                    >@StreetBoy</a
                  ></span
                >
              </div>
            </div>
          </div>
        </div>
        <!--end content-->

        <div
          class="
            group
            relative
            overflow-hidden
            bg-white
            dark:bg-slate-900
            rounded-md
            shadow
            dark:shadow-gray-700
            hover:shadow-md
            transition-all
            duration-500
          "
        >
          <img src="assets/images/blog/02.jpg" alt="" />

          <div class="relative p-6">
            <div class="absolute left-6 -top-4">
              <span
                class="
                  bg-violet-900
                  text-white
                  dark:bg-violet-800
                  text-[12px]
                  px-2.5
                  py-1
                  font-semibold
                  rounded-full
                  h-5
                "
                >Illustration</span
              >
            </div>

            <div class="">
              <div class="flex mb-4">
                <span class="text-slate-400 text-[16px]"
                  ><i
                    class="
                      uil uil-calendar-alt
                      text-slate-900
                      dark:text-white
                      mr-2
                    "
                  ></i
                  >20th October, 2022</span
                >
                <span class="text-slate-400 text-[16px] ml-3"
                  ><i
                    class="uil uil-clock text-slate-900 dark:text-white mr-2"
                  ></i
                  >5 min read</span
                >
              </div>

              <a
                href="blog-detail.html"
                class="
                  title
                  text-lg
                  font-medium
                  hover:text-violet-600
                  duration-500
                  ease-in-out
                "
                >Save Thousands Of Lives Through This NFT</a
              >

              <div class="flex justify-between mt-4">
                <a
                  href="blog-detail.html"
                  class="
                    btn btn-link
                    text-[16px]
                    font-medium
                    hover:text-violet-600
                    after:bg-violet-600
                    duration-500
                    ease-in-out
                  "
                  >Read More <i class="uil uil-arrow-right"></i
                ></a>
                <span class="text-slate-400 text-[16px]"
                  >by
                  <a
                    href="creator-profile.html"
                    class="
                      text-slate-900
                      dark:text-white
                      hover:text-violet-600
                      dark:hover:text-violet-600
                      font-medium
                    "
                    >@CutieGirl</a
                  ></span
                >
              </div>
            </div>
          </div>
        </div>
        <!--end content-->

        <div
          class="
            group
            relative
            overflow-hidden
            bg-white
            dark:bg-slate-900
            rounded-md
            shadow
            dark:shadow-gray-700
            hover:shadow-md
            transition-all
            duration-500
          "
        >
          <img src="assets/images/blog/03.jpg" alt="" />

          <div class="relative p-6">
            <div class="absolute left-6 -top-4">
              <span
                class="
                  bg-violet-900
                  text-white
                  dark:bg-violet-800
                  text-[12px]
                  px-2.5
                  py-1
                  font-semibold
                  rounded-full
                  h-5
                "
                >Music</span
              >
            </div>

            <div class="">
              <div class="flex mb-4">
                <span class="text-slate-400 text-[16px]"
                  ><i
                    class="
                      uil uil-calendar-alt
                      text-slate-900
                      dark:text-white
                      mr-2
                    "
                  ></i
                  >20th October, 2022</span
                >
                <span class="text-slate-400 text-[16px] ml-3"
                  ><i
                    class="uil uil-clock text-slate-900 dark:text-white mr-2"
                  ></i
                  >5 min read</span
                >
              </div>

              <a
                href="blog-detail.html"
                class="
                  title
                  text-lg
                  font-medium
                  hover:text-violet-600
                  duration-500
                  ease-in-out
                "
                >A place where technology meets craftsmanship</a
              >

              <div class="flex justify-between mt-4">
                <a
                  href="blog-detail.html"
                  class="
                    btn btn-link
                    text-[16px]
                    font-medium
                    hover:text-violet-600
                    after:bg-violet-600
                    duration-500
                    ease-in-out
                  "
                  >Read More <i class="uil uil-arrow-right"></i
                ></a>
                <span class="text-slate-400 text-[16px]"
                  >by
                  <a
                    href="creator-profile.html"
                    class="
                      text-slate-900
                      dark:text-white
                      hover:text-violet-600
                      dark:hover:text-violet-600
                      font-medium
                    "
                    >@ButterFly</a
                  ></span
                >
              </div>
            </div>
          </div>
        </div>
        <!--end content-->
      </div>
      <!--end grid-->
    </div>
    <!--end container-->
  </section>
  <!--end section-->
  <!-- End -->

  <!-- Back to top -->
  <a
    href="#"
    onclick="topFunction()"
    id="back-to-top"
    class="
      back-to-top
      fixed
      hidden
      text-lg
      rounded-full
      z-10
      bottom-5
      right-5
      h-9
      w-9
      text-center
      bg-violet-600
      text-white
      leading-9
    "
    ><i class="uil uil-arrow-up"></i
  ></a>
  <!-- Back to top -->
</template>

<script setup>
</script>

<style  scoped>
</style>