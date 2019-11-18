<template>
  <div>
    <DomainList />
  </div>
</template>
<script>
import DomainList from '@/components/DomainList'
export default {
  name: 'home',
  components: {
    DomainList
  }
}
</script>
<style>
#slogan {
  margin-top: 30px;
  margin-bottom: 30px;
}
#main {
  background-color: #c07a7a;
  padding: 30px 0px;
}
</style>
