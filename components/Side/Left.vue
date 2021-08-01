<template>
  <div class="w-3/12 shadow pb-10">
    <div
      class="
        bg-secondary
        w-full
        h-auto
        flex flex-col
        justify-center
        items-center
        p-5
      "
    >
      <div class="rounded-full bg-white w-2/5 flex justify-center">
        <img src="/icon.png" class="rounded-full" />
      </div>
      <div class="flex items-center flex-col mt-2.5 mb-8">
        <h3 class="text-white text-xl">Fadlan Zunima</h3>
        <h3 class="text-white opacity-25 text-xl">Frontend Developer</h3>
      </div>
    </div>
    <div class="bg-primary h-auto px-3 py-5  h-3/4 overflow-y-scroll">
      <div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> Country: </span>
          <span class="text-white"> Indonesia 🇮🇩 </span>
        </div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> City: </span>
          <span class="text-white"> Tangerang </span>
        </div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> Age: </span>
          <span class="text-white"> 25 </span>
        </div>
      </div>
      <div class="border-t h-px opacity-25"></div>
      <div class="mt-7">
        <span class="text-white">Skills</span>
        <div class="flex flex-wrap">
          <div class="p-1 text-center">
            <radial-progress-bar
              :diameter="85"
              :completed-steps="completedSteps"
              :total-steps="totalSteps"
              :start-color="startColor"
              :stop-color="stopColor"
              :inner-stroke-color="innerStrokeColor"
              :stroke-width="strokeWidth"
              :inner-strokte-width="innerStrokeWidth"
            >
              <p class="text-white">{{ completedSteps }}%</p>
            </radial-progress-bar>
            <div class="text-white">Nuxtjs</div>
          </div>
          <div class="p-1 text-center">
            <radial-progress-bar
              :diameter="85"
              :completed-steps="completedSteps"
              :total-steps="totalSteps"
              :start-color="startColor"
              :stop-color="stopColor"
              :inner-stroke-color="innerStrokeColor"
              :stroke-width="strokeWidth"
              :inner-strokte-width="innerStrokeWidth"
            >
              <p class="text-white">{{ completedSteps }}%</p>
            </radial-progress-bar>
            <div class="text-white">Nuxtjs</div>
          </div>
          <div class="p-1 text-center">
            <radial-progress-bar
              :diameter="85"
              :completed-steps="completedSteps"
              :total-steps="totalSteps"
              :start-color="startColor"
              :stop-color="stopColor"
              :inner-stroke-color="innerStrokeColor"
              :stroke-width="strokeWidth"
              :inner-strokte-width="innerStrokeWidth"
            >
              <p class="text-white">{{ completedSteps }}%</p>
            </radial-progress-bar>
            <div class="text-white">Nuxtjs</div>
          </div>
          <div class="p-1 text-center">
            <radial-progress-bar
              :diameter="85"
              :completed-steps="completedSteps"
              :total-steps="totalSteps"
              :start-color="startColor"
              :stop-color="stopColor"
              :inner-stroke-color="innerStrokeColor"
              :stroke-width="strokeWidth"
              :inner-strokte-width="innerStrokeWidth"
            >
              <p class="text-white">{{ completedSteps }}%</p>
            </radial-progress-bar>
            <div class="text-white">Nuxtjs</div>
          </div>
          <div class="p-1 text-center">
            <radial-progress-bar
              :diameter="85"
              :completed-steps="completedSteps"
              :total-steps="totalSteps"
              :start-color="startColor"
              :stop-color="stopColor"
              :inner-stroke-color="innerStrokeColor"
              :stroke-width="strokeWidth"
              :inner-strokte-width="innerStrokeWidth"
            >
              <p class="text-white">{{ completedSteps }}%</p>
            </radial-progress-bar>
            <div class="text-white">Nuxtjs</div>
          </div>
        </div>
      </div>
      <div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> Country: </span>
          <span class="text-white"> Indonesia 🇮🇩 </span>
        </div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> City: </span>
          <span class="text-white"> Tangerang </span>
        </div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> Age: </span>
          <span class="text-white"> 25 </span>
        </div>
      </div>
      <div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> Country: </span>
          <span class="text-white"> Indonesia 🇮🇩 </span>
        </div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> City: </span>
          <span class="text-white"> Tangerang </span>
        </div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> Age: </span>
          <span class="text-white"> 25 </span>
        </div>
      </div>
      <div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> Country: </span>
          <span class="text-white"> Indonesia 🇮🇩 </span>
        </div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> City: </span>
          <span class="text-white"> Tangerang </span>
        </div>
        <div class="flex justify-between mb-2">
          <span class="text-white"> Age: </span>
          <span class="text-white"> 25 </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import RadialProgressBar from 'vue-radial-progress'

export default {
  components: {
    RadialProgressBar,
  },

  data() {
    return {
      completedSteps: 80,
      totalSteps: 100,
      startColor: '#FBC038',
      stopColor: '#FBC038',
      innerStrokeColor: '#000',
      strokeWidth: 5,
      innerStrokeWidth: 2,
    }
  },
}
</script>
