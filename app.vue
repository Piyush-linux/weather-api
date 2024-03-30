<template>
  <div class="min-h-screen mx-auto max-w-screen bg-zinc-900 text-white">
    <div class="container">
      <div class="grid h-screen grid-cols-2 gap-4">
        
        <!-- c1 -->
        <div class="p-6 grid grid-cols-1 place-content-between">
            <!-- logo -->
            <div class="text-xl f1">Vatavaran</div>
            <!-- Render -->
            <div class="bottom-0 f1 flex items-center space-x-3">
              <!-- degree -->
              <div class="text-7xl f1">09 </div>
              <!-- txt -->
              <div class="text-md space-y-1">
                <div class="text-4xl f1 pb-1 border-b-2 border-gray-800">London</div>
                <div class="text-sm font-bold f2">06:32 | Sunday | 6 Oct, 2023</div>
              </div>
            </div>
        </div>
        
        <!-- c2 -->
         <div class="p-6 grid grid-cols-1 place-content-around">
          <div class="">
            <!-- <InputText label="Another Location" icon="material-symbols:location-on-rounded" /> -->
            <div class="flex items-center space-x-3">
              <input type="text" class="text-white outline-none bg-transparent p-1 rounded-none border-b-2 border-gray-350" placeholder="Another Location">
              <div class="border-2 border-white rounded-full p-2">
                <Icon name="material-symbols:search-rounded" color="white" class="w-5 h-5 "/>
              </div>
            </div>
          </div>
          <div class="border-2 border-rose-300">
            hello
          </div>
         </div>

      </div>
    </div>
  </div>
</template>
