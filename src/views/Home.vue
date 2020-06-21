<template>
  <div class="flex">
    <div class="bg-gray-900 w-20 flex-none flex flex-col min-h-screen h-screen px-2 py-2">
      <div class="overflow-y-auto" >
        <ul class="text-center" >
          <li >
            <a href="#">
              <img class="w-12 h-12 rounded-full mx-auto" src="@/assets/images/icon_discord.svg" />
            </a>
            <div class="border-b border-gray-700 mx-2 my-3" />
          </li>
          <li >
            <a href="#">
              <img class="w-12 h-12 rounded-full mx-auto" src="@/assets/images/icon_vue.svg" />
            </a>
            <div class="border-b border-gray-700 mx-2 my-3" />
          </li>
          <li >
            <a href="#">
              <img class="w-12 h-12 rounded-full mx-auto" src="@/assets/images/icon_laravel.svg" />
            </a>
            <div class="border-b border-gray-700 mx-2 my-3" />
          </li>
          <li>
            <a class="w-12 h-12 bg-gray-800 hover:bg-teal-500 text-teal-800 hover:text-white inline-block rounded-full" href="#">
              <svg class="mx-auto mt-3" fill="currentColor" width="24" height="24"><path d="M24 10H14V0h-4v10H0v4h10v10h4V14h10z"/></svg>
            </a>
          </li>
        </ul>
      </div>
    </div>
    <div class="flex flex-col min-h-screen h-screen w-screen" >
      <div class="bg-red-500 flex" >
        <div class="bg-red-300 w-56 flex-none">Tailwind Css</div>
        <div>Rest of top bar</div>
      </div>
      <div class="flex-1 bg-green-600 flex overflow-y-hidden" >
        <div class="w-56 flex-none bg-green-300 flex flex-col justify-between">
          <div class="overflow-y-auto" >Hashtag sidebar</div>
          <div>buttons</div>
        </div>
        <div class="bg-green-800 flex-1 flex justify-between">
          <div class="bg-indigo-300 flex-1 flex flex-col justify-between" >
            <div class="overflow-y-auto">Display Chat Context..</div>
            <div class="bg-indigo-200" >Write message here</div>
          </div>
          <div class="bg-indigo-600 w-56 flex-none overflow-y-auto" >Users sidebar..</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
  })
}
</script>