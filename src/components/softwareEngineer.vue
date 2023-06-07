<script setup>
import {NButton,NIcon} from 'naive-ui'
import {FunnelOutline,AccessibilityOutline,ArrowBackCircleOutline} from '@vicons/ionicons5'
</script>

<template>
    <div>
      <n-icon size="50" class="mb-5 bg-red"><ArrowBackCircleOutline/></n-icon>
       <h1>Software Engineer Groups</h1> 
       <p>Join a study group to increase motivation accountability, gain diverse perspectives and build and build valuable relationships with your field </p>
                  
       <div class="diverse">
       <div class="fin">
        <img style="height: 120px; width: 140px;" src="../assets/avatar.jpeg" alt="">
       </div>
       <div class="finna">
       
        <h4 class="text-default">Can't find a group?</h4> 
        <p>You can also start a new group with other colleagues.Please make sure you have searched enough before starting your own group </p>
       </div>

       <n-space>
    <n-button class="mt-4 p-3" type="info" >
      New Group
    </n-button>
  </n-space>
      
    </div>
    </div>
</template>

<style scoped>
h1{
   /* font-style: italic; */
   font-weight: bold;
}

h4{
    font-weight: bold;
}

.diverse{
    display: flex;
    flex-wrap: wrap;
    margin-top: 35px;
    justify-content: space-between;
    border: 1px solid rgba(224, 210, 210, 0.884);
    padding: 15px;
    padding-bottom: 18px;
}


</style>