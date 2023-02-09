<template>
  <header class="sticky top-0 z-30  py-3 dark:text-[#BBBBBB] text-gray-400 text-xl backdrop-blur-md shadow shadow-gray-200 dark:shadow-gray-800">
    <div class="mx-auto sm:px-6 lg:px-8 px-4 max-w-7xl relative">
      <div class="flex justify-between items-center">
        <div class="flex items-center">
          <img class="w-14 h-14 inline-block" src="/nuxt.png">
          <span class="ml-1 text-xl">母婴产品商城</span>
        </div>
        <div class="grid grid-flow-col gap-4 items-center">
          <div class="rounded cursor-pointer dark:hover:text-gray-200 hover:duration-0.4s hover:text-gray-800">
            个人中心
          </div>
          <div class="rounded cursor-pointer dark:hover:text-gray-200 hover:duration-0.4s hover:text-gray-800">
            购物车
          </div>
          <div class="rounded cursor-pointer dark:hover:text-gray-200 hover:duration-0.4s hover:text-gray-800">
            注册登录
          </div>
          <DarkToggle />
        </div>
      </div>
    </div>
  </header>
</template>
