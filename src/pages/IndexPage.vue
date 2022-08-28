<template>
  <q-page class="flex bg-black flex-center">
    <div>
      <div class="text-center flex text-white flex-center mainFont" style="font-size: 20vh">
        <span class="text-blue-2">The</span> Elite<span style="font-size: 15vh" class="text-blue secondFont">DAO</span> <span class="blink">.</span>
      </div>

      <div class="text-h2 mainFont text-center text-white" style="opacity:.8">
        WELCOME
      </div>

      <q-btn class="q-mt-xl" color="white" text-color="blue" unelevated to="/" label="Go Home" no-caps />
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Silkscreen:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Righteous&display=swap');

.mainFont {
  font-family: 'Silkscreen', cursive;
}

.secondFont {
  font-family: 'Righteous', cursive;
}

.blink {
  animation: blink-animation 0.8s steps(2, start) infinite;
  -webkit-animation: blink-animation 0.8s steps(2, start) infinite;
}

@keyframes blink-animation {
  to {
    visibility: hidden;
  }
}
</style>
