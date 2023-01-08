<template>
  <div class="container mx-auto logos-wrapper bg-slate-700 p-4">
    <h2 class="font-bold text-5xl text-pink-200 pb-4">
      Find The Best Logo hereeeees
    </h2>
    <div class="grid grid-cols-4 grid-rows-2 gap-4">
      <div class="sm:col-span-4 md:col-span-7 row-span-2">
        <div class="card">
          Some Mysterious Card
          <img
            src="https://picsum.photos/300/200"
            class="w-full"
            alt="random"
          />
          <button class="btn-info mt-4">Contoh</button>
        </div>
      </div>
      <div class="col-span-1 row-span-1 bg-blue-100 text-center p-4 border-4 border-b-lime-600">
        <div class="card">
          Some Mysterious Card
          <img
            src="https://picsum.photos/300/200"
            class="w-full"
            alt="random"
          />
          <button class="btn-info mt-4">Contoh</button>
        </div>
      </div>
      <div class="col-span-1 row-span-1 bg-blue-100 text-center p-4">
        <!-- <img src="../assets/img/bango.png" alt=""> -->
        <div class="card">
          Some Mysterious Card
          <img
            src="https://picsum.photos/300/200"
            class="w-full"
            alt="random"
          />
          <button class="btn-info mt-4">Contoh</button>
        </div>
      </div>
      <div class="col-span-1 row-span-1 bg-blue-100 text-center p-4">
        <!-- <img src="../assets/img/bango.png" alt=""> -->
        <div class="card">
          Some Mysterious Card
          <img
            src="https://picsum.photos/300/200"
            class="w-full"
            alt="random"
          />
          <button class="btn-info mt-4">Contoh</button>
        </div>
      </div>
      <div class="col-span-1 row-span-1 bg-blue-100 text-center p-4">
        <!-- <img src="../assets/img/bango.png" alt=""> -->
        <div class="card">
          Some Mysterious Card
          <img
            src="https://picsum.photos/300/200"
            class="w-full"
            alt="random"
          />
          <button class="btn-info mt-4">Contoh</button>
        </div>
      </div>
    </div>
  </div>
  <button
    class="
      bg-blue-400
      hover:bg-blue-600 hover:text-white
      transition
      duration-300
      cursor-pointer
      py-2
      px-8
      rounded
    "
  >
    Some Cool Submit
  </button>
  <button
    class="
      bg-teal-400
      hover:bg-teal-600 hover:text-white
      transition
      duration-300
      cursor-pointer
      py-2
      px-8
      rounded
    "
  >
    Another Cool Submit
  </button>
</template>

<script>
export default {};
</script>

<style>
.btn-info {
  @apply bg-blue-400 transition duration-300 cursor-pointer py-2 px-8 rounded;
}

.btn-info:hover {
  @apply bg-blue-600 text-white;
}

.card {
  @apply bg-blue-100 rounded p-4 border-4 border-blue-800 text-center;
}
</style>