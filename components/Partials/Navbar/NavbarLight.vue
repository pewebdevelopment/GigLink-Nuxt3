<template>
  <!-- Start Navbar -->
  <nav id="topnav" class="defaultscroll is-sticky">
    <div class="container">
      <!-- Logo container-->
      <a class="logo pl-0" href="index.html">
        <img
          src="assets/images/logo-icon-28.png"
          class="inline-block sm:hidden"
          alt=""
        />
        <div class="sm:block hidden">
          <span class="inline-block dark:hidden">
            <img src="assets/images/logo-dark.png" class="l-dark h-7" alt="" />
            <img
              src="assets/images/logo-light.png"
              class="l-light h-7"
              alt=""
            />
          </span>
          <img
            src="assets/images/logo-white.png"
            height="24"
            class="hidden dark:inline-block"
            alt=""
          />
        </div>
      </a>

      <!-- End Logo container-->
      <div class="menu-extras">
        <div class="menu-item">
          <!-- Mobile menu toggle-->
          <a class="navbar-toggle" id="isToggle" onclick="toggleMenu()">
            <div class="lines">
              <span></span>
              <span></span>
              <span></span>
            </div>
          </a>
          <!-- End mobile menu toggle-->
        </div>
      </div>

      <!--Login button Start-->
      <ul class="buy-button list-none mb-0">
        <!-- <li class="sm:inline-block hidden mb-0"> -->
        <li class="inline-block mb-0">
          <div class="form-icon relative">
            <i
              class="
                uil uil-search
                text-lg
                absolute
                top-1/2
                -translate-y-1/2
                left-3
              "
            ></i>
            <input
              type="text"
              class="
                form-input
                pl-10
                rounded-3xl
                sm:w-44
                w-28
                bg-white
                dark:bg-slate-900
              "
              name="s"
              id="searchItem"
              placeholder="Search..."
            />
          </div>
        </li>

        <li class="inline-block pl-1 mb-0">
          <a
            id="connectWallet"
            class="
              btn btn-icon
              rounded-full
              bg-violet-600
              hover:bg-violet-700
              border-violet-600
              hover:border-violet-700
              text-white
            "
            ><i class="uil uil-wallet"></i
          ></a>
        </li>

        <li class="inline-block pl-1 mb-0">
          <a
            href=""
            class="
              btn btn-icon
              rounded-full
              bg-violet-600
              hover:bg-violet-700
              border-violet-600
              hover:border-violet-700
              text-white
            "
            ><img src="assets/images/client/05.jpg" class="rounded-full" alt=""
          /></a>
        </li>
      </ul>
      <!--Login button End-->

      <div id="navigation">
        <!-- Navigation Menu-->
        <ul class="navigation-menu nav-light justify-end">
          <li class="has-submenu parent-menu-item">
            <a href="javascript:void(0)">Home</a
            ><span class="menu-arrow"></span>
            <ul class="submenu">
              <li><a href="index.html" class="sub-menu-item">Home One</a></li>
              <li>
                <a href="index-two.html" class="sub-menu-item">Home Two</a>
              </li>
              <li>
                <a href="index-three.html" class="sub-menu-item">Home Three</a>
              </li>
              <li>
                <a href="index-four.html" class="sub-menu-item"
                  >Home Four
                  <span
                    class="
                      bg-gray-50
                      dark:bg-slate-800
                      text-[10px]
                      shadow shadow-gray-300
                      dark:shadow-gray-700
                      font-bold
                      px-2.5
                      py-0.5
                      rounded
                      h-5
                      ml-1
                    "
                    >Light</span
                  ></a
                >
              </li>
              <li>
                <a href="index-five.html" class="sub-menu-item"
                  >Home Five
                  <span
                    class="
                      bg-gray-50
                      dark:bg-slate-800
                      text-[10px]
                      shadow shadow-gray-300
                      dark:shadow-gray-700
                      font-bold
                      px-2.5
                      py-0.5
                      rounded
                      h-5
                      ml-1
                    "
                    >Light</span
                  ></a
                >
              </li>
              <li>
                <a href="index-six.html" class="sub-menu-item"
                  >Home Six
                  <span
                    class="
                      bg-gray-50
                      dark:bg-slate-800
                      text-[10px]
                      shadow shadow-gray-300
                      dark:shadow-gray-700
                      font-bold
                      px-2.5
                      py-0.5
                      rounded
                      h-5
                      ml-1
                    "
                    >Light</span
                  ></a
                >
              </li>
            </ul>
          </li>

          <li class="has-submenu parent-parent-menu-item">
            <a href="javascript:void(0)">Explore</a
            ><span class="menu-arrow"></span>
            <ul class="submenu">
              <li>
                <a href="explore-one.html" class="sub-menu-item">
                  Explore One</a
                >
              </li>
              <li>
                <a href="explore-two.html" class="sub-menu-item">
                  Explore Two</a
                >
              </li>
              <li>
                <a href="explore-three.html" class="sub-menu-item">
                  Explore Three</a
                >
              </li>
              <li>
                <a href="auction.html" class="sub-menu-item">Live Auction</a>
              </li>
              <li>
                <a href="item-detail.html" class="sub-menu-item">
                  Item Detail</a
                >
              </li>
              <li>
                <a href="activity.html" class="sub-menu-item"> Activities</a>
              </li>
              <li>
                <a href="collections.html" class="sub-menu-item">Collections</a>
              </li>
              <li>
                <a href="upload-work.html" class="sub-menu-item"
                  >Upload Works</a
                >
              </li>
            </ul>
          </li>

          <li><a href="wallet.html" class="sub-menu-item">Wallet</a></li>

          <li class="has-submenu parent-parent-menu-item">
            <a href="javascript:void(0)">Pages</a
            ><span class="menu-arrow"></span>
            <ul class="submenu">
              <li><a href="aboutus.html" class="sub-menu-item">About Us</a></li>
              <li class="has-submenu parent-menu-item">
                <a href="javascript:void(0)"> Creator </a
                ><span class="submenu-arrow"></span>
                <ul class="submenu">
                  <li>
                    <a href="creators.html" class="sub-menu-item"> Creators</a>
                  </li>
                  <li>
                    <a href="creator-profile.html" class="sub-menu-item">
                      Creator Profile</a
                    >
                  </li>
                  <li>
                    <a href="creator-profile-edit.html" class="sub-menu-item">
                      Profile Edit</a
                    >
                  </li>
                  <li>
                    <a href="become-creator.html" class="sub-menu-item">
                      Become Creator</a
                    >
                  </li>
                </ul>
              </li>
              <li class="has-submenu parent-menu-item">
                <a href="javascript:void(0)"> Blog </a
                ><span class="submenu-arrow"></span>
                <ul class="submenu">
                  <li><a href="blogs.html" class="sub-menu-item"> Blogs</a></li>
                  <li>
                    <a href="blog-detail.html" class="sub-menu-item">
                      Blog Detail</a
                    >
                  </li>
                </ul>
              </li>
              <li class="has-submenu parent-menu-item">
                <a href="javascript:void(0)"> Auth Pages </a
                ><span class="submenu-arrow"></span>
                <ul class="submenu">
                  <li><a href="login.html" class="sub-menu-item"> Login</a></li>
                  <li>
                    <a href="signup.html" class="sub-menu-item"> Signup</a>
                  </li>
                  <li>
                    <a href="reset-password.html" class="sub-menu-item">
                      Forgot Password</a
                    >
                  </li>
                  <li>
                    <a href="lock-screen.html" class="sub-menu-item">
                      Lock Screen</a
                    >
                  </li>
                </ul>
              </li>
              <li class="has-submenu parent-menu-item">
                <a href="javascript:void(0)"> Special </a
                ><span class="submenu-arrow"></span>
                <ul class="submenu">
                  <li>
                    <a href="comingsoon.html" class="sub-menu-item">
                      Coming Soon</a
                    >
                  </li>
                  <li>
                    <a href="maintenance.html" class="sub-menu-item">
                      Maintenance</a
                    >
                  </li>
                  <li><a href="error.html" class="sub-menu-item"> 404!</a></li>
                  <li>
                    <a href="thankyou.html" class="sub-menu-item"> Thank you</a>
                  </li>
                </ul>
              </li>
              <li class="has-submenu parent-menu-item">
                <a href="javascript:void(0)"> Help Center </a
                ><span class="submenu-arrow"></span>
                <ul class="submenu">
                  <li>
                    <a href="helpcenter-overview.html" class="sub-menu-item">
                      Overview</a
                    >
                  </li>
                  <li>
                    <a href="helpcenter-faqs.html" class="sub-menu-item">
                      FAQs</a
                    >
                  </li>
                  <li>
                    <a href="helpcenter-guides.html" class="sub-menu-item">
                      Guides</a
                    >
                  </li>
                  <li>
                    <a href="helpcenter-support.html" class="sub-menu-item">
                      Support</a
                    >
                  </li>
                </ul>
              </li>
              <li>
                <a href="terms.html" class="sub-menu-item">Terms Policy</a>
              </li>
              <li>
                <a href="privacy.html" class="sub-menu-item">Privacy Policy</a>
              </li>
            </ul>
          </li>

          <li><a href="contact.html" class="sub-menu-item">Contact</a></li>
        </ul>
        <!--end navigation menu-->
      </div>
      <!--end navigation-->
    </div>
    <!--end container-->
  </nav>
  <!--end header-->
  <!-- End Navbar -->
</template>

<script setup>
</script>

<style  scoped>
</style>