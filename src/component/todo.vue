<template>
    <li> 
        <span v-if="mode=='type'"> type : 1page </span>
        <!--<span v-else>else : {{message}} / {{text}} / {{count}} </span>-->
    </li>
</template>
<script>
     export default {
       data() { 
        return {
          message: 'todo Vue!',
        } 
      },
      methods:{

      },
      props:[
         // "text",
         // "count",
         // "flag",
          "mode",
      ]
  }
</script> 