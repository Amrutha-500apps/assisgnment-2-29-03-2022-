<template>
  <div class="hello">
    <p> Amrutha</p>
    <child></child>
    <Question></Question>
    <Table></Table>
  </div>
</template>
<script>

import child from '../components/child'
import Question from'../components/Q1'
import Table from'../components/Q2'
export default {
  name: 'HelloS33',
  components:{
    child,
    Question,
    Table,
  },
  props :{
    Name:String
   }
}
</script>
