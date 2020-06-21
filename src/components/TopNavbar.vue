<template>
    <div class="flex text-white h-12" >
        <div class="bg-gray-800 w-56 flex-none flex items-center justify-between border-b border-gray-900 px-3 py-2">
          <div>Tailwind Css</div>
          <button>
            <img class="w-8 h-8" src="@/assets/images/down-chevron.svg" />
          </button>
        </div>
        <div class="flex-1 bg-gray-750 flex items-center justify-between border-b border-gray-900 px-4">
          <div class="flex items-center" >
            <div class="text-gray-500 text-2xl">#</div>
            <div class="ml-2 text-sm text-white">General</div>
            <div class="border-l pl-3 ml-3 border-gray-600 text-xs text-gray-400">General discussion of tailwind</div>
          </div>
          <div class="flex items-center text-gray-400" >
            <a href="#" class="ml-4"><i class="fa fa-bell hover:text-white" aria-hidden="true" /></a>
            <a href="#" class="ml-4"><i class="fa fa-thumb-tack hover:text-white" aria-hidden="true" /></a>
            <a href="#" class="ml-4"><i class="fa fa-users hover:text-white" aria-hidden="true" /></a>
            <a href="#" class="ml-4">
                <form action="#" class="relative">
                    <input type="text" placeholder="Search" class="rounded bg-gray-900 text-gray-200 text-xs px-2 py-1" >
                    <span class="absolute right-0 top-0 mr-1" >
                        <i class="fa fa-search w-4 h-4 text-gray-500 hover:text-gray-200" aria-hidden="true" />
                    </span>
                </form>
            </a>
            <a href="#" class="ml-4"><i class="fa fa-at hover:text-white" aria-hidden="true" /></a>
            <a href="#" class="ml-4"><i class="fa fa-question-circle hover:text-white" aria-hidden="true" /></a>
          </div>
        </div>
    </div>
</template>