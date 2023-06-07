<script setup>
import { NIcon } from 'naive-ui';
import { FunnelOutline } from '@vicons/ionicons5';
</script>

<template>
    <div class="search">
        <input type="text" placeholder="Search" >
        <div class="first">
 
            <select name=" <n-icon><FunnelOutline/></n-icon>only my notes" id="" class="p-2 m-2">
                <option value="" class="values">Only my notes</option>
                <option value="" class="values">lil man</option>
                <option value="" class="values">hkuytg7yt</option>
            </select>
        
            
            <select name="" id="" class="p-2 m-2">
                <option value="" class="values">Latest</option>
                <option value="" class="values">lil man</option>
                <option value="" class="values">hkuytg7yt</option>
            </select>
        
    </div>
    </div>
</template>

<style scoped>
.search{
    margin-top:40px ;
    display: flex;
    justify-content: space-between;
}


input{
    border-radius: 15px;
    width: 350px;
    border: 1px solid rgb(206, 203, 203);
    padding: 8px;
}

ion-icon {
  color: blue;
}
.option{
    padding: 50px;
}

</style>