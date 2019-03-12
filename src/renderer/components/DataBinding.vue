<template>
  
  <div id="wrapper">
    <h1>11111111111111111111112222222222222222</h1>
    <div class="container">
        <h1>The multiplication table of 4.</h1>
        <ul class="list-group">
        
            <li class="list-group-item" v-for="i in 11" :key="i">
                {{ i }} times 4 equals {{ i * 4 }}.
            </li>
          
        </ul>
        <ul class="list-group">
        
            <li class="list-group-item" v-for="story in stories" :key="story">
                오늘 뉴스 {{story}}.
            </li>
          
        </ul>
    </div>    
  </div>
</template>

<script>
// Full spec-compliant TodoMVC with localStorage persistence
// and hash-based routing in ~120 effective lines of JavaScript.

import Vue from 'vue'

    new Vue({
        el: '.container',
        data: {
          stories:[
            "연세대",
            "세브란스병원",
            "응급실"
          ]
        }
    })

</script>

<style>

</style>
