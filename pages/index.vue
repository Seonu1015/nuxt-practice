<script setup>
// const sayHello = () => console.log("Hello");
const { sayHello } = useUtils();
sayHello();
</script>

<template>
  <div class="Main container py-3 mx-auto">
    <h1 class="text-teal-500">Hello World</h1>
    <!-- <img src="@/assets/1.jpg" alt="Discover Nuxt 3" /> -->
    <!-- public 에 넣으면 바로 이미지를 url에서 확인할 수 있다. 하지만 공용 폴더이기 때문에 파일을 숨길 수 없다(?) -->
    <!-- icones.js.org 아이콘 사이트? svg? -->
    <!-- <IconsBell /> -->
  </div>
</template>
