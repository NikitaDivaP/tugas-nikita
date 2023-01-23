<script>
export default{

  data(){
    return{
      datasensor: "60",
      datasensor2: "80"
    }
  },
  created(){
    this.getData2()
  },
  methods:{
    getData(){
      this.datasensor = 100
    },
    getData2(){
      //alert('hello 2');
    },
  }
}

</script>

<template>
  <div>
    Hello {{ datasensor }} {{ datasensor2 }}
    <button @click="getData" class="bg-orange-500 p-2 rounded-sm">Ambil Data</button>&nbsp;
    <button @click="getData" class="bg-orange-500 p-2 rounded-sm">Ambil Data 2</button>
  </div>
</template>

