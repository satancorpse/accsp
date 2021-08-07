<template>
<section class="service">
    <div class="pt-24">
      <div class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center">
        <!--Left Col-->
        <div class="flex flex-col w-full md:w-3/5 justify-center items-start text-center md:text-left">
          <p class="uppercase tracking-loose w-full">Need a quote?</p>
          <h1 class="my-4 text-5xl font-bold leading-tight">
            Contact us
          </h1>
        </div>
        <!--Right Col-->
        <div class="w-full md:w-2/5 py-6 text-center">
          <img class="w-full md:w-3/5 z-50" src="~/assets/images/contact.png"/>
        </div>
      </div>
    </div>
    <section class="bg-white border-b py-8">
      <div class="container max-w-5xl mx-auto m-8">
        <h1 class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800">
          Get in touch with us
        </h1>
        <div class="w-full mb-16">
          <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"></div>
        </div>
        <div class="flex flex-wrap w-1/2 mx-auto">
          <form class="w-full max-w-lg">
            <div class="flex flex-wrap -mx-3 mb-6">
              <div class="w-full px-3 mb-6 md:mb-0">
                <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
                  Your Name
                </label>
                <input class="appearance-none block w-full bg-gray-200 text-gray-700 border border-red-500 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" id="grid-first-name" type="text" placeholder="Jane">
                <p class="text-red-500 text-xs italic">Please fill out this field.</p>
              </div>
            </div>

              <div class="flex flex-wrap -mx-3 mb-6">
              <div class="w-full px-3 mb-6 md:mb-0">
                <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
                  Your Email
                </label>
                <input class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-300 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" id="grid-first-name" type="email" placeholder="jane@example.com">
              </div>
            </div>

            <div class="flex flex-wrap -mx-3 mb-6">
              <div class="w-full px-3 mb-6 md:mb-0">
                <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
                  Your Message
                </label>
                <textarea class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-300 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white"
                id="grid-first-name" rows="6" placeholder="Start typing..."></textarea>
              </div>
            </div>

            <div class="submit">
              <button class="bg-blue-500 hover:bg-blue-700
              text-white font-bold py-2 px-4 border
              border-blue-700 rounded">Submit</button>
            </div>
          </form>
        </div>
      </div>
    </section>
</section>
</template>

<style>
th {
  text-align: left;
}
th, tr, td {
  border: 1px solid #ddd;
  padding: 1em
}
</style>
