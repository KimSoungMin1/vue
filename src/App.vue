<script>   
export default{
  name:'App',
  data() {
    return {
      count: '0'
    }}
  }
  </script>
<template>
  <h3>{{count}}</h3>
  <p>vue로 확인하는 웹 페이지 입니다 아래 버튼을<br> 누르시면 값이 1씩 증가합니다</p>
  <button  @click='count++'>1+</button>
</template>