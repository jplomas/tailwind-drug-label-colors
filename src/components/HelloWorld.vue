<template>
  <div class="sm:grid gap-4 grid-cols-4 space-y-4 sm:space-y-0 max-w-xl mx-auto">
    <div class="grid grid-cols-2 gap-6 items-center justify-center sm:block space-y-0 sm:space-y-4">
      <div class="flex justify-start sm:justify-center">
        <div><button class="py-3 px-6 rounded-lg bg-vasopressor hover:bg-vasopressor-400">Vasopressor</button>
        </div>
      </div>
      <div class="flex justify-start sm:justify-center">
        <div><button
            class="py-3 px-6 rounded-lg bg-anticholinergic hover:bg-anticholinergic-500">Anticholinergic</button>
        </div>
      </div>
      <div class="flex justify-start sm:justify-center">
        <div><button class="py-3 px-6 rounded-lg bg-opioid hover:bg-opioid-500">Opioid</button></div>
      </div>
      <div class="flex justify-start sm:justify-center">
        <div><button
            class="py-3 px-6 rounded-lg bg-neuromuscular-blocker hover:bg-neuromuscular-blocker-500">Neuromuscular
            Blocker</button></div>
      </div>
      <div class="flex justify-start sm:justify-center">
        <div><button class="py-3 px-6 rounded-lg bg-hypnotic hover:bg-hypnotic-700">Hypnotic</button></div>
      </div>
      <div class="flex justify-start sm:justify-center">
        <div><button
            class="py-3 px-6 rounded-lg bg-local-anaesthetic hover:bg-local-anaesthetic-500">Hypnotic</button>
        </div>
      </div>
      <div class="flex justify-start sm:justify-center">
        <div><button
            class="py-3 px-6 rounded-lg bg-induction-agent hover:bg-induction-agent-600">Hypnotic</button>
        </div>
      </div>
      <div class="flex justify-start sm:justify-center">
        <div><button class="py-3 px-6 rounded-lg bg-antiemetic hover:bg-antiemetic-400">Antiemetic</button>
        </div>
    </div>
  </div>
</div>

  <button class="m-4 bg-blue-400 text-black py-2 px-4 rounded">
    Vasopressor
  </button>
  <button class="m-4 bg-vasopressor text-black py-2 px-4 rounded">
    Vasopressor
  </button>
  <button class="m-4 bg-vasopressor hover:bg-vasopressor-600 text-black py-2 px-4 rounded">
    Vasopressor
  </button>

<div class="mt-10 mb-10 rounded-xl overflow-hidden flex flex-col relative bg-antiemetic-900"
  style="height: 23rem; max-width: 600px;">
  <div class="absolute left-1/2 top-12 transform -translate-x-1/2">
    <div class="text-center absolute left-10 top-10 right-10 bottom-10 flex items-center justify-center">
      <div class="text-6xl font-semibold tracking-tight text-white">75<sup class="text-2xl -top-6">%</sup></div>
    </div><svg width="200" height="200" viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
      <circle class="stroke-antiemetic-950" cx="100" cy="100" r="94" stroke="black" stroke-width="12"></circle>
      <mask id="path-2-inside-1_1_5" fill="white">
        <path
          d="M100 5.99978C100 2.68619 102.689 -0.0187616 105.996 0.179906C123.667 1.24125 140.779 6.97839 155.557 16.853C172.002 27.8412 184.819 43.459 192.388 61.7317C199.957 80.0043 201.937 100.111 198.079 119.509C194.22 138.907 184.696 156.725 170.711 170.711C156.725 184.696 138.907 194.22 119.509 198.079C100.111 201.937 80.0043 199.957 61.7317 192.388C43.459 184.819 27.8412 172.002 16.853 155.557C6.97838 140.779 1.24125 123.667 0.179906 105.996C-0.0187617 102.689 2.68619 100 5.99978 100V100C9.31337 100 11.9783 102.69 12.204 105.995C13.2483 121.291 18.2745 136.086 26.8303 148.89C36.4999 163.362 50.2437 174.641 66.3237 181.302C82.4037 187.962 100.098 189.705 117.168 186.31C134.238 182.914 149.919 174.533 162.226 162.226C174.533 149.919 182.914 134.238 186.31 117.168C189.705 100.098 187.962 82.4037 181.302 66.3237C174.641 50.2437 163.362 36.4999 148.89 26.8303C136.086 18.2745 121.291 13.2483 105.995 12.204C102.69 11.9783 100 9.31337 100 5.99978V5.99978Z">
        </path>
      </mask>
      <path
        class="stroke-antiemetic"
        d="M100 5.99978C100 2.68619 102.689 -0.0187616 105.996 0.179906C123.667 1.24125 140.779 6.97839 155.557 16.853C172.002 27.8412 184.819 43.459 192.388 61.7317C199.957 80.0043 201.937 100.111 198.079 119.509C194.22 138.907 184.696 156.725 170.711 170.711C156.725 184.696 138.907 194.22 119.509 198.079C100.111 201.937 80.0043 199.957 61.7317 192.388C43.459 184.819 27.8412 172.002 16.853 155.557C6.97838 140.779 1.24125 123.667 0.179906 105.996C-0.0187617 102.689 2.68619 100 5.99978 100V100C9.31337 100 11.9783 102.69 12.204 105.995C13.2483 121.291 18.2745 136.086 26.8303 148.89C36.4999 163.362 50.2437 174.641 66.3237 181.302C82.4037 187.962 100.098 189.705 117.168 186.31C134.238 182.914 149.919 174.533 162.226 162.226C174.533 149.919 182.914 134.238 186.31 117.168C189.705 100.098 187.962 82.4037 181.302 66.3237C174.641 50.2437 163.362 36.4999 148.89 26.8303C136.086 18.2745 121.291 13.2483 105.995 12.204C102.69 11.9783 100 9.31337 100 5.99978V5.99978Z"
        stroke-width="20" mask="url(#path-2-inside-1_1_5)"></path>
    </svg>
  </div>
  <div class="absolute left-1/2 transform -translate-x-1/2 bottom-16">
    <div class="h-12 text-center leading-tight pt-6 text-lg font-medium"><span
        class="text-white">Antiemetic prescribing</span></div>
  </div>
</div></template>
