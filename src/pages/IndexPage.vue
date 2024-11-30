<template>
  <q-page class="p-3 bg-gray-200">
    <div class="w-full px-6 py-6 mx-auto">

      <div class="flex flex-wrap -mx-3">
        <!-- card1 -->
        <div class="w-full max-w-full px-3 mb-6 sm:w-1/2 sm:flex-none xl:mb-0 xl:w-1/3">
          <div class="relative flex flex-col min-w-0 h-24 break-words bg-white shadow-soft-xl rounded-2xl bg-clip-border">
            <div class="flex-auto p-4">
              <div class="flex flex-row -mx-3">
                <div class="flex-none w-2/3 max-w-full px-2">
                  <div>
                    <p class="mb-0 font-sans font-semibold">Saldo atual</p>
                    <h5 class="mb-0 font-bold">
                      R$ 50.300,00
                    </h5>
                  </div>
                </div>
                <div class="px-2 text-right basis-1/3">
                  <div
                    class="inline-block w-12 h-12 text-center rounded-lg bg-gradient-to-tl from-purple-700 to-pink-500">
                    <i class="fa-solid fa-wallet text-lg relative top-3.5 text-white"></i>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- card2 -->
        <div class="w-full max-w-full px-3 mb-6 sm:w-1/2 sm:flex-none xl:mb-0 xl:w-1/3">
          <div class="relative flex flex-col min-w-0 h-24 break-words bg-white shadow-soft-xl rounded-2xl bg-clip-border">
            <div class="flex-auto p-4">
              <div class="flex flex-row -mx-3">
                <div class="flex-none w-2/3 max-w-full px-2">
                  <div>
                    <p class="mb-0 font-sans font-semibold">Entradas do mês</p>
                    <h5 class="mb-0 font-bold">
                      R$ 60.500,00
                    </h5>
                  </div>
                </div>
                <div class="px-2 text-right basis-1/3">
                  <div
                    class="inline-block w-12 h-12 text-center rounded-lg bg-gradient-to-tl from-purple-700 to-pink-500">
                    <i class="fa-solid fa-dollar text-lg relative top-3.5 text-white"></i>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- card3 -->
        <div class="w-full max-w-full px-3 mb-6 sm:w-1/2 sm:flex-none xl:mb-0 xl:w-1/3">
          <div class="relative flex flex-col min-w-0 h-24 break-words bg-white shadow-soft-xl rounded-2xl bg-clip-border">
            <div class="flex-auto p-4">
              <div class="flex flex-row -mx-3">
                <div class="flex-none w-2/3 max-w-full px-2">
                  <div>
                    <p class="mb-0 font-sans font-semibold">Saídas do mês</p>
                    <h5 class="mb-0 font-bold">
                      R$ 10.200,00
                    </h5>
                  </div>
                </div>
                <div class="px-2 text-right basis-1/3">
                  <div
                    class="inline-block w-12 h-12 text-center rounded-lg bg-gradient-to-tl from-purple-700 to-pink-500">
                    <i class="fa-solid fa-hand-holding-dollar text-lg relative top-3.5 text-white"></i>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="flex flex-wrap mt-6 -mx-3">
        <div class="w-full px-3 mb-6 lg:mb-0 lg:w-7/12 lg:flex-none">
          <div class="relative flex flex-col min-w-0 break-words bg-white shadow-soft-xl rounded-2xl bg-clip-border">
            <div class="flex-auto p-4">
              <div class="flex flex-wrap -mx-3">
                <div class="max-w-full px-3 lg:w-1/2 lg:flex-none">
                  <div class="flex flex-col h-full">
                    <p class="pt-2 mb-3 font-semibold">Aprenda a investir!</p>
                    <p class="mb-3">Para facilitar a sua vida, fizemos um levantamento dos melhores <b>cursos
                        gratuitos</b> de investimentos desde o nível iniciante até o avançado.</p>
                    <p class="">
                      Aposente-se mais cedo e deixe seu dinheiro trabalhar para você!
                    </p>
                    <a class="mt-auto mb-0 font-semibold leading-normal text-sm group text-slate-500" href="javascript:;">
                      Acessar a lista
                      <i
                        class="fas fa-arrow-right ease-bounce text-sm group-hover:translate-x-1.25 ml-1 leading-normal transition-all duration-200"></i>
                    </a>
                  </div>
                </div>
                <div class="max-w-full px-3 mt-12 ml-auto text-center lg:mt-0 lg:w-5/12 lg:flex-none">
                  <div class="h-full bg-gradient-to-tl from-purple-700 to-pink-500 rounded-xl">
                    <img src="../assets/waves-white.svg" class="absolute top-0 hidden w-1/2 h-full lg:block" alt="waves">
                    <div class="relative flex items-center justify-center h-full">
                      <img class="relative z-20 w-full pt-6" src="../assets/rocket-white.webp" alt="rocket">
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full max-w-full px-3 lg:w-5/12 lg:flex-none">
          <div
            class="border-black/12.5 shadow-soft-xl relative flex h-full min-w-0 flex-col break-words rounded-2xl border-0 border-solid bg-white bg-clip-border p-4">
            <div class="relative h-full overflow-hidden bg-cover rounded-xl"
              style="background-image: url('../src/assets/human-home-office.jpg')">
              <span
                class="absolute top-0 left-0 w-full h-full bg-center bg-cover bg-gradient-to-tl from-gray-900 to-slate-800 opacity-80"></span>
              <div class="relative z-10 flex flex-col flex-auto h-full p-4">
                <h5 class="pt-2 mb-6 font-bold text-white">Renda Extra no conforto da sua casa?!</h5>
                <p class="text-white">Veja quais são as oportunidades de renda extra promissoras para o ano de 2025</p>
                <a class="mt-auto mb-0 font-semibold leading-normal text-white group text-sm" href="javascript:;">
                  Acessar a lista
                  <i
                    class="fas fa-arrow-right ease-bounce text-sm group-hover:translate-x-1.25 ml-1 leading-normal transition-all duration-200"></i>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});
</script>
