<template>
  <header class="sticky top-0 z-30  py-3 text-gray-500 text-lg backdrop-blur-md bg-white/75 dark:bg-black/75  shadow shadow-gray-200 dark:shadow-gray-800">
    <div class="container mx-auto sm:px-6 lg:px-8 px-4 max-w-7xl relative">
      <div class="flex justify-between items-center">
        <div class="flex items-center">
          <img class="w-14 h-14 inline-block" src="/logo.svg">
          <span class="text-xl text-black font-semibold dark:text-white">母婴产品商城</span>
        </div>
        <div class="grid grid-flow-col gap-4 items-center dark:text-[#BBBBBB]">
          <div class="lt-md:hidden rounded cursor-pointer dark:hover:text-gray-200 hover:duration-0.4s hover:text-gray-800">
            个人中心
          </div>
          <div class="lt-md:hidden rounded cursor-pointer dark:hover:text-gray-200 hover:duration-0.4s hover:text-gray-800">
            购物车
          </div>
          <div class="lt-md:hidden rounded cursor-pointer dark:hover:text-gray-200 hover:duration-0.4s hover:text-gray-800">
            注册登录
          </div>
          <DarkToggle />
        </div>
      </div>
    </div>
  </header>
</template>
