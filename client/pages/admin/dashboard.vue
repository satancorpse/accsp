<template>
  <div class="flex h-screen bg-gray-100 font-sans">
    <!-- Side bar-->
    <div
      id="sidebar"
      class="
        h-screen
        w-16
        menu
        bg-white
        text-white
        px-4
        flex
        items-center
        nunito
        shadow
      "
    >
      <a
        href="#"
        class="block absolute align-middle top-3 no-underline text-gray-800"
      >
        <span class="w-full inline-block pb-1 md:pb-0 text-sm"
          ><Logo />&nbsp; Accountancy</span
        >
      </a>

      <ul class="list-reset">
        <li class="my-2 md:my-0">
          <a
            href="#"
            class="
              block
              py-1
              md:py-3
              pl-1
              align-middle
              text-gray-600
              no-underline
              hover:text-indigo-400
            "
          >
            <span class="w-full inline-block pb-1 md:pb-0 text-sm"
              >Home Page</span
            >
          </a>
        </li>
        <li class="my-2 md:my-0">
          <a
            href="#"
            class="
              block
              py-1
              md:py-3
              pl-1
              align-middle
              text-gray-600
              no-underline
              hover:text-indigo-400
            "
          >
            <span class="w-full inline-block pb-1 md:pb-0 text-sm"
              >Services</span
            >
          </a>
        </li>
        <li class="my-2 md:my-0">
          <a
            href="#"
            class="
              block
              py-1
              md:py-3
              pl-1
              align-middle
              text-gray-600
              no-underline
              hover:text-indigo-400
            "
          >
            <span class="w-full inline-block pb-1 md:pb-0 text-sm"
              >Messages</span
            >
          </a>
        </li>
        <li class="my-2 md:my-0">
          <a
            href="#"
            class="
              block
              py-1
              md:py-3
              pl-1
              align-middle
              text-gray-600
              no-underline
              hover:text-indigo-400
            "
          >
            <span class="w-full inline-block pb-1 md:pb-0 text-sm"
              >Analytics</span
            >
          </a>
        </li>
        <li class="my-2 md:my-0">
          <a
            href="#"
            class="
              block
              py-1
              md:py-3
              pl-1
              align-middle
              text-gray-600
              no-underline
              hover:text-indigo-400
            "
          >
            <span class="w-full inline-block pb-1 md:pb-0 text-sm"
              >Payments</span
            >
          </a>
        </li>
      </ul>
    </div>

    <div class="flex flex-row flex-wrap flex-1 flex-grow content-start">
      <div class="h-40 lg:h-20 w-full flex flex-wrap border-b">
        <nav
          id="header1"
          class="
            bg-gray-100
            w-auto
            flex-1
            border-b-1 border-gray-300
            order-1
            lg:order-2
          "
        >
          <div class="flex h-full justify-between items-center">
            <!--Search-->
            <div class="relative w-full max-w-3xl px-6">
              <div
                class="absolute h-10 mt-1 left-0 top-0 flex items-center pl-10"
              >
                <svg
                  class="h-4 w-4 fill-current text-gray-600"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                >
                  <path
                    d="M12.9 14.32a8 8 0 1 1 1.41-1.41l5.35 5.33-1.42 1.42-5.33-5.34zM8 14A6 6 0 1 0 8 2a6 6 0 0 0 0 12z"
                  ></path>
                </svg>
              </div>

              <input
                id="search-toggle"
                type="search"
                placeholder="search"
                class="
                  block
                  w-full
                  bg-gray-200
                  focus:outline-none
                  focus:bg-white
                  focus:shadow-md
                  text-gray-700
                  font-bold
                  rounded-full
                  pl-12
                  pr-4
                  py-3
                "
                onkeyup="updateSearchResults(this.value);"
              />
            </div>
            <!-- / Search-->

            <!--Menu-->

            <div class="flex relative inline-block pr-6">
              <div class="relative text-sm">
                <button
                  id="userButton"
                  class="flex items-center focus:outline-none mr-3"
                >
                  <img
                    class="w-8 h-8 rounded-full mr-4"
                    src="http://i.pravatar.cc/300"
                    alt="Avatar of User"
                  />
                  <span class="hidden md:inline-block">Hi, User </span>
                  <svg
                    class="pl-2 h-2"
                    version="1.1"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 129 129"
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                    enable-background="new 0 0 129 129"
                  >
                    <g>
                      <path
                        d="m121.3,34.6c-1.6-1.6-4.2-1.6-5.8,0l-51,51.1-51.1-51.1c-1.6-1.6-4.2-1.6-5.8,0-1.6,1.6-1.6,4.2 0,5.8l53.9,53.9c0.8,0.8 1.8,1.2 2.9,1.2 1,0 2.1-0.4 2.9-1.2l53.9-53.9c1.7-1.6 1.7-4.2 0.1-5.8z"
                      ></path>
                    </g>
                  </svg>
                </button>
                <div
                  id="userMenu"
                  class="
                    bg-white
                    nunito
                    rounded
                    shadow-md
                    mt-2
                    absolute
                    mt-12
                    top-0
                    right-0
                    min-w-full
                    overflow-auto
                    z-30
                    invisible
                  "
                >
                  <ul class="list-reset">
                    <li>
                      <a
                        href="#"
                        class="
                          px-4
                          py-2
                          block
                          text-gray-900
                          hover:bg-indigo-400
                          hover:text-white
                          no-underline
                          hover:no-underline
                        "
                        >My account</a
                      >
                    </li>
                    <li>
                      <a
                        href="#"
                        class="
                          px-4
                          py-2
                          block
                          text-gray-900
                          hover:bg-indigo-400
                          hover:text-white
                          no-underline
                          hover:no-underline
                        "
                        >Notifications</a
                      >
                    </li>
                    <li>
                      <hr class="border-t mx-2 border-gray-400" />
                    </li>
                    <li>
                      <a
                        href="#"
                        class="
                          px-4
                          py-2
                          block
                          text-gray-900
                          hover:bg-indigo-400
                          hover:text-white
                          no-underline
                          hover:no-underline
                        "
                        >Logout</a
                      >
                    </li>
                  </ul>
                </div>
              </div>
            </div>

            <!-- / Menu -->
          </div>
        </nav>
      </div>

      <!--Graph Content -->
      <div id="main-content" class="w-full flex-1">
        <!-- <div class="flex flex-1 flex-wrap"></div> -->
		<div class="bg-white px-4 w-11/12 mx-auto my-2">

			<h1>Hellos w</h1>

			<client-only placeholder="loading...">
				<ckeditor-nuxt v-model="contentHolder" :config="editorConfig"  />
			</client-only>
		
		</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

  layout: "admin",

  components: {
    'ckeditor-nuxt': () => { if (process.client) { return import('@blowstack/ckeditor-nuxt') } },
  },

	data() {
		return {
		editorConfig: {
			simpleUpload: {
			uploadUrl: 'path_to_image_controller',
			headers: {
				'Authorization': 'optional_token'
			}
			}
		},
			contentHolder: ""
		}
	}
};
</script>

<style>
.nunito {
  font-family: "nunito", font-sans;
}

.border-b-1 {
  border-bottom-width: 1px;
}

.border-l-1 {
  border-left-width: 1px;
}

hover\:border-none:hover {
  border-style: none;
}

#sidebar {
  z-index: 9999;
  width: 150px;
  box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
}
</style>
