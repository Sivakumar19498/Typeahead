<template>
  <div id="app">
    <h1>{{msg}}</h1>
    <typeahead :options="options" v-model="selected"></typeahead>
  </div>
</template>

<script>
import Typeahead from './components/Typeahead'
export default {
  name: 'app',
  components: {
    Typeahead
  },
  data() {
    return {
      msg: 'Search Country',
      selected: null,
      options: [
        {id: 1, text: 'Alabama'},
        {id: 2, text: 'Alaska'},
        {id: 3, text: 'Arizona'},
        {id: 4, text: 'Arkansas'},
        {id: 5, text: 'California'},
        {id: 6, text: 'Colorado'},
        {id: 7, text: 'Connecticut'},
        {id: 8, text: 'Delaware'},
        {id: 9, text: 'Florida'},
        {id: 10, text: 'Georgia'},
        {id: 11, text: 'Hawaii'},
        {id: 12, text: 'Idaho'},
        {id: 13, text: 'Illinois'},
        {id: 14, text: 'Indiana'},
        {id: 15, text: 'Iowo'},
        {id: 16, text: 'Kansas'},
        {id: 17, text: 'Kentucky'},
        {id: 18, text: 'Louisiana'},
        {id: 19, text: 'Maine'},
        {id: 20, text: 'Maryland'},
        {id: 21, text: 'Massachusetts'},
        {id: 22, text: 'Michigan'},
        {id: 23, text: 'Minnesota'},
        {id: 24, text: 'Mississippi'},
        {id: 25, text: 'Missouri'},
        {id: 26, text: 'Montana'},
        {id: 27, text: 'Nebraska'},
        {id: 28, text: 'Nevada'},
        {id: 29, text: 'New Hampshire'},
        {id: 30, text: 'New Jersey'},
        {id: 31, text: 'New Mexico'},
        {id: 32, text: 'New York'},
        {id: 33, text: 'North Carolina'},
        {id: 34, text: 'North Dakota'},
        {id: 35, text: 'Ohio'},
        {id: 36, text: 'Oklahoma'},
        {id: 37, text: 'Oregon'},
        {id: 38, text: 'Pennsylvania'},
        {id: 39, text: 'Rhode Island'},
        {id: 40, text: 'South Carolina'},
        {id: 41, text: 'South Dakota'},
        {id: 42, text: 'Tennessee'},
        {id: 43, text: 'Texas'},
        {id: 44, text: 'Utah'},
        {id: 45, text: 'Vermont'},
        {id: 46, text: 'Virginia'},
        {id: 47, text: 'Washington'},
        {id: 48, text: 'West Virginia'},
        {id: 49, text: 'Wisconsin'},
        {id: 50, text: 'Wyoming'},
        
      ]
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: 60px auto;
  width: 300px;
}
* {
  box-sizing: border-box;
}
</style>
