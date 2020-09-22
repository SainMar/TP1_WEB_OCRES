<template>
    <quick-menu :menu-count=count :icon-class=icons :menu-url-list=list :background-color=backgroundColor :color=color :position=position :is-open-new-tab=getIsOpenNewTab @process=print></quick-menu>
</template>


<script>

import quickMenu from 'vue-quick-menu'


export default {
  name:"form_contact",
  components: {
    quickMenu,
  },
  props :{
      count : 3,
        icons:["fa fa-home","fa fa-graduation-cap", "fa fa-phone"],
        list:[{'isLink':false}, {'isLink':true, url:"/agile"}, {'isLink':true, url:"/contact"}],
        backgroundColor:'#17c4c5',
        color:'#ffffff',
        position:'top-left',
        isOpenNewTab:false
  }
  
}
</script>