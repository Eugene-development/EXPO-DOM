<template>
  <div class="">

    <div class="relative pt-6 pb-16 sm:pb-24">
      <div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6">
          <nav class="relative flex items-center justify-between sm:h-10 md:justify-center" aria-label="Global">
            <div class="flex items-center flex-1 md:absolute md:inset-y-0 md:left-0">
              <div class="flex items-center justify-between w-full md:w-auto">
                <!--                <a href="#">-->
                <!--                  <span class="sr-only">Workflow</span>-->
                <!--                  <img class="h-8 w-auto sm:h-10" src="https://tailwindui.com/img/logos/workflow-mark-indigo-600.svg"-->
                <!--                       alt="">-->
                <!--                </a>-->
                <span
                  class="inline-flex items-center px-4 py-2 rounded-md text-sm font-medium bg-indigo-100 text-indigo-800">
                 EXPO-DOM.COM
                </span>
                <div class="-mr-2 flex items-center md:hidden">
<!--                  <button type="button"-->
<!--                          class="bg-gray-50 rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500"-->
<!--                          aria-expanded="false">-->
<!--                    <span class="sr-only">Open main menu</span>-->
<!--                    &lt;!&ndash; Heroicon name: outline/menu &ndash;&gt;-->
<!--                    <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"-->
<!--                         stroke="currentColor" aria-hidden="true">-->
<!--                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"-->
<!--                            d="M4 6h16M4 12h16M4 18h16"/>-->
<!--                    </svg>-->
<!--                  </button>-->
                </div>
              </div>
            </div>
            <!--            <div class="hidden md:flex md:space-x-10">-->
            <!--              <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Product</a>-->

            <!--              <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Features</a>-->

            <!--              <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Marketplace</a>-->

            <!--              <a href="#" class="font-medium text-gray-500 hover:text-gray-900">Company</a>-->
            <!--            </div>-->
            <div class="md:absolute md:flex md:items-center md:justify-end md:inset-y-0 md:right-0">
              <span class="inline-flex rounded-md shadow">
                <span
                   class="inline-flex items-center px-4 py-2 border border-transparent text-base font-medium rounded-md text-indigo-600 bg-white hover:bg-gray-50">
                  Регистрация
                </span>
              </span>
            </div>
          </nav>
        </div>
      </div>
    </div>


    <div class="relative overflow-hidden ">
      <div class="relative pt-12 pb-16 sm:pb-24">
        <main class="mt-16 mx-auto max-w-7xl px-4 sm:mt-24">
          <div class="text-center">
            <h1 class="my-12 text-3xl tracking-tight text-gray-900 sm:text-4xl md:text-7xl font-extrabold">8 (495) 147-55-50</h1>
            <h1 class="text-4xl tracking-tight text-gray-900 sm:text-5xl md:text-7xl font-medium">
              <span class="block xl:inline">Предварительная регистрация</span><br>
              <span class="block text-indigo-600 xl:inline">с 1 января 2022</span>
            </h1>
            <p class="mt-3 max-w-md mx-auto text-base text-gray-500 sm:text-lg md:mt-5 md:text-xl md:max-w-3xl">
              Современный агрегатор компаний где клиенты найдут вас
            </p>
            <div class="mt-5 max-w-md mx-auto sm:flex sm:justify-center md:mt-8">
              <div class="rounded-md shadow">
                <span
                   class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 md:py-4 md:text-lg md:px-10">
                  Ресурс бесплатный
                </span>
              </div>
              <!--            <div class="mt-3 rounded-md shadow sm:mt-0 sm:ml-3">-->
              <!--              <a href="#" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-indigo-600 bg-white hover:bg-gray-50 md:py-4 md:text-lg md:px-10">-->
              <!--                Live demo-->
              <!--              </a>-->
              <!--            </div>-->
            </div>
          </div>
        </main>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

