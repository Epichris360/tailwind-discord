<template>
  <div class="flex">
    <channel-sidebar />
    <div class="flex flex-col min-h-screen h-screen w-screen" >
      <top-navbar />
      <div class="flex-1 flex overflow-y-hidden" >
        <hashtag-sidebar />
        <div class="flex-1 flex justify-between ">
          <div class="bg-gray-750 flex-1 flex flex-col justify-between" >
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
import ChannelSidebar from '@/components/ChannelSidebar'
import TopNavbar from '@/components/TopNavbar'
import HashtagSidebar from '@/components/HashtagSidebar'

export default {
  components:{
    ChannelSidebar,
    TopNavbar,
    HashtagSidebar
  }
}
</script>