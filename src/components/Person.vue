<template>
    <div class="person">
        <h2>姓名：{{name}}</h2>
        <h2>姓名：{{age}}</h2>
        <button @click="changename">修改名字</button>
        <button @click="showTel">查看联系方式</button>

    </div>
  </template>
  
  <script lang="ts">
    export default {
      name:'Person',
      data() {
        return{
            name:'林俊杰',
            age:'18',
            tel:'13888888888'
        }

      },
      methods:{
        changename(){
            this.name='案件聚焦军'
        },
        showTel(){
        alert(this.tel)
      }
      }
    }
  </script>
  
  <style>
  .person {
  background-color: rgb(53, 153, 44);
  color:rgb(41, 11, 173);
  font-size: 40px;
  
  }
  </style>