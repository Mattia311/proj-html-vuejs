<template>
  <div>
      <ul class="d-flex"  >
            <li v-for="(list,index) in menu" :key="index"><nav><a href="" :list="list">{{list}}</a></nav></li>
            <li><nav><a href=""><i class="fas fa-shopping-cart"></i></a></nav></li> 
      </ul>

  </div>
</template>

<script>
export default {
    data() {
        return {
            menu : ['Home','Culinary History','Our Team','Our Menu','Takeout','Bulletin','Reservation',]
        }
    }

}
</script>

<style>

</style>