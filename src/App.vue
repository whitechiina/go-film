<template>
    <div class="main">
        <router-view></router-view>
        <Util/>
    </div>
</template>

<script lang="ts" setup>


import Util from "./components/Util.vue";
</script>

<style>
html, body, #app {
    width: 100%;
    margin: 0;
    padding: 0;
}

/*背景色切换*/


#app, .main {
    max-width: 100%;
    min-height: 100vh;
    /*background: #222;*/
    color: rgb(221, 221, 221);
    background: rgb(34, 34, 34);
}


* {
    box-sizing: border-box;
}


/*全局a标签默认样式去除*/
a {
    color: #2d2e2f;
    outline: none;
    text-decoration: none;
    color: #888888;
}

a:hover {
    color: #888888;
}
</style>