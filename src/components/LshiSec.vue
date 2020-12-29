<template>
  <div >
  
    
<ul class="uk-grid-small uk-child-width-1-2 uk-child-width-1-4@s" uk-sortable="handle: .uk-card" uk-grid>
    <li>
        <div class="uk-card uk-card-default uk-card-body uk-text-center">Item 1</div>
    </li>
    <li>
        <div class="uk-card uk-card-default uk-card-body uk-text-center">Item 2</div>
    </li>
    <li>
        <div class="uk-card uk-card-default uk-card-body uk-text-center">Item 3</div>
    </li>
    <li>
        <div class="uk-card uk-card-default uk-card-body uk-text-center">Item 4</div>
    </li>
    <li>
        <div class="uk-card uk-card-default uk-card-body uk-text-center">Item 5</div>
    </li>
    <li>
        <div class="uk-card uk-card-default uk-card-body uk-text-center">Item 6</div>
    </li>
    <li>
        <div class="uk-card uk-card-default uk-card-body uk-text-center">Item 7</div>
    </li>
    <li>
        <div class="uk-card uk-card-default uk-card-body uk-text-center">Item 8</div>
    </li>
</ul>
  
  </div>



</template>


<script>
export default {
    name: 'LshiSec',
    props:{
        name : String
    },
    methods:{
        test: function(){
            alert(10);
        }
    }
}
</script>


<style scoped>

</style>
