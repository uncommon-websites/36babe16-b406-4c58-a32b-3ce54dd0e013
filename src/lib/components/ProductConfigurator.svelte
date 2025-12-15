<script lang="ts">
  let selectedCourse = 'heartsaver';
</script>

<section id="courses" class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Multiple courses. <span class="text-gray-400">All certifications valid 2 years.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Heartsaver CPR & AED</h3>
      <p class="text-gray-500 text-sm">Essential lifesaving skills for the workplace.</p>
    </div>

    <!-- Course Image -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="/generated/image-small-business-team-practicing-cpr-in-th-1765836028071-9.webp" class="h-full w-full object-cover" alt="CPR Training" />
    </div>

    <!-- Course Provider Badges -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="px-4 py-2 rounded-full bg-red-100 border-2 border-red-500 text-red-700 text-xs font-medium">American Heart Association</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-xs font-medium hover:bg-gray-200">American Red Cross</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-xs font-medium hover:bg-gray-200">HSI</button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>4-5 hours</span>
      <span>CPR & AED</span>
      <span>2-year cert</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Group pricing available <span class="font-bold text-gray-900">starting at $75/person</span><br>
      Minimum 5 participants • We bring all equipment
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">See all options</span>
        <span class="text-primary-600">View all courses</span>
      </button>
      <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M8 2v4"/><path d="M16 2v4"/><rect width="18" height="18" x="3" y="4" rx="2"/><path d="M3 10h18"/></svg>
        Schedule training ->
      </button>
    </div>
  </div>
</section>
