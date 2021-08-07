<template>
<section class="service">
    <div class="pt-24">
      <div class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center">
        <!--Left Col-->
        <div class="flex flex-col w-full md:w-3/5 justify-center items-start text-center md:text-left">
          <p class="uppercase tracking-loose w-full">What business are you?</p>
          <h1 class="my-4 text-5xl font-bold leading-tight">
            Services and fees
          </h1>
        </div>
        <!--Right Col-->
        <div class="w-full md:w-2/5 py-6 text-center">
          <img class="w-full md:w-3/5 z-50" src="~/assets/images/service.png"/>
        </div>
      </div>
    </div>
    <section class="bg-white border-b py-8">
      <div class="container max-w-5xl mx-auto m-8">
        <h1 class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800">
          Our Services
        </h1>
        <div class="w-full mb-16">
          <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"></div>
        </div>
        <div class="flex flex-wrap">
          <table class="w-full text-gray-800">
									<thead>
										<tr>
											<th>Turnover</th>

											<th>Monthly</th>

										</tr>
									</thead>
									<tbody>

										<tr>
											<td>up to £30k</td>
											<td>£49.99</td>

										</tr>
										<tr>
											<td>£30k - £85k</td>

											<td>£59.99</td>

										</tr>
										<tr>
											<td>£85k - £150k</td>

											<td>£69.99</td>

										</tr>

									</tbody>

								</table>
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
