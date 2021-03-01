<template>
    <div class="container mx-auto rounded bg-gray-900 ">
  <!-- Nav -->
  <ul class="block text-white">
    <li class="inline-flex items-center ml-8 mr-1 px-4 py-2 rounded-t-lg shadow-sm text-xs font-medium text-100 bg-gray-700 hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"><a href="#"><span></span>Tips</a></li>
    <li class="inline-flex items-center mr-1 px-4 py-2 rounded-t-lg shadow-sm text-xs font-medium text-gray-500 bg-gray-800 hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"><a href="#"><span></span>Look</a></li>
    <li class="inline-flex items-center mr-1 px-4 py-2 rounded-t-lg shadow-sm text-xs font-medium text-gray-500 bg-gray-800 hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"><a href="#"><span></span>Info</a></li>
  </ul>
  <!-- Problem section -->
  <div class="p-8 bg-gradient-to-b from-gray-700 text-white">
   <div class="mt-4">
        <h3 class="font-bold text-gray-200">Hints</h3> 
        <div class="inline-block bg-gray-700 my-2 p-2 rounded">
          <div>
            <h4 class="inline">Hint 1</h4>
            <span>
              <svg class="inline-block flex-shrink-0 h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z" />
              </svg> 
            </span>
          </div>
          <div class="mt-2">
            <p class="text-sm text-gray-200">You can solve this question by iterating through the main input array once</p>
          </div>
        </div>
        <div class="inline-block bg-gray-700 my-2 p-2 rounded">
          <div class="flex space-x ">
            <h4 class="">Hint 1</h4>
            <span>
              <svg class=" flex-shrink-0 h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z" />
              </svg> 
            </span>
          </div>
          <div class="mt-2">
            <p class="text-sm text-gray-200">You can solve this question by iterating through the main input array once</p>
          </div>
        </div>
      </div>
  </div>
</div>
</template>

<script>
export default {
    name: 'Tips'
}
</script>
