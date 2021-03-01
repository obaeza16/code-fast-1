<template>
    <div class="container mx-auto rounded bg-gray-900 ">
  <!-- Nav -->
  <ul class="block text-white">
    <li class="inline-flex ml-8 mr-1 px-4 py-2 rounded-t-lg shadow-sm text-xs font-medium text-100 bg-gray-700 hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"><a href="#"><span></span>Prompt</a></li>
    <!-- <li class="inline-flex items-center mr-1 px-4 py-2 rounded-t-lg shadow-sm text-xs font-medium text-gray-500 bg-gray-800 hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"><a href="#"><span></span>Solution</a></li>
    <li class="inline-flex items-center mr-1 px-4 py-2 rounded-t-lg shadow-sm text-xs font-medium text-gray-500 bg-gray-800 hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"><a href="#"><span></span>Support</a></li> -->
  </ul>
  <!-- Problem section -->
  <div class="p-8 bg-gradient-to-b from-gray-700 text-white">
    <!-- Title -->
    <div class="">
      <div class="flex space-x-1.5 items-center">
        <h2 class="text-2xl font-bold leading-7 sm:text-3xl sm:truncate">Validate Subsequence</h2>
        <button class="mt-2 text-sm" title="save"><svg class="flex-shrink-0 h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"/></svg></button>
        <button class="mt-2 text-sm" title="share"><svg class="inline-block flex-shrink-0 h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.684 13.342C8.886 12.938 9 12.482 9 12c0-.482-.114-.938-.316-1.342m0 2.684a3 3 0 110-2.684m0 2.684l6.632 3.316m-6.632-6l6.632-3.316m0 0a3 3 0 105.367-2.684 3 3 0 00-5.367 2.684zm0 9.316a3 3 0 105.368 2.684 3 3 0 00-5.368-2.684z"/></svg></button>
      </div>
      <div class="flex">
        <div class="p-2">
          <span class="text-gray-400">Difficulty: </span>
          <span class="text-gray-200">1</span>
        </div>
        <div class="p-2">
          <span class="text-gray-400">Points: </span>
          <span class="text-gray-200">0</span>
        </div>
        <div class="p-2">
          <span class="text-gray-400">Submissions: </span>
          <span class="text-gray-200">+38,213</span>
        </div>
      </div>
    </div>
    <hr class="">
    <!-- Body -->
    <div class="mt-6">
      <p class="text-base text-gray-200">Given an array Arr of N positive integers. Your task is to find the elements whose value is equal to that of its index value.</p>
      <div class="mt-2">
        <h2 class="font-bold text-gray-200">Example 1</h2>
        <pre><span>
          <strong>Input: </strong>N = 5
          arr[] = 90 100 78 89 67
          <strong>Output: </strong>89
          <strong>Explanation: </strong>After sorting the array 
          middle element is the median</span>
        </pre>
      </div>
      <div class="mt-4">
        <span>
          <svg class="inline-block flex-shrink-0 h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
          </svg>
        </span>
        Time Complexity: <span>O(N)</span>
      </div>
      <div class="mt-4" >
        <span>
          <svg class="inline-block flex-shrink-0 h-5 w-5 text-green-400" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 9l3 3-3 3m5 0h3M5 20h14a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
          </svg>
        </span>
        Space Complexity: <span>O(1)</span>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
    name: 'Promp',
    props: {
        
    }
}
</script>