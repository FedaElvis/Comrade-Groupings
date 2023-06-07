<script setup>
import {NCard,NSpace,NProgress,NIcon} from 'naive-ui'
import {PeopleOutline,LocateOutline,PeopleSharp} from '@vicons/ionicons5'

</script>


<template>
    <div class="d-flex fd-row mt-5 flex-wrap">
        <div>
  <n-card title="Code Crunchers" class="p-3">
    
    <template #header-extra>
  
  <n-progress type="circle" :percentage="55" status="success" style="height: 35px; width: 60px;">
    <span style="text-align: center"><n-icon size="25" color="green"><PeopleOutline/></n-icon></span>
  </n-progress>
</template>
    
   This group is for programmers who love to solve problems and tackle complex coding challenges.Join us to flex your coding
   <h6 class="mt-3"> <n-icon><PeopleSharp/></n-icon> Elvis,Eben,Collins,Frank,Donne,Harry</h6>
   <h6> <n-icon><LocateOutline/></n-icon>Introduction to Software Engineering</h6>
    <!-- <template #footer>
      #footer
    </template> -->
    <!-- <template #action>
      #action
    </template> -->
  </n-card>
</div>
<div>
  <n-card title="Code Crunchers" class="p-3">
    
    <template #header-extra>
  
  <n-progress type="circle" :percentage="55" status="success" style="height: 35px; width: 60px;">
    <span style="text-align: center"><n-icon size="25" color="green"><PeopleOutline/></n-icon></span>
  </n-progress>
</template>
    
   This group is for programmers who love to solve problems and tackle complex coding challenges.Join us to flex your coding
   <h6 class="mt-3"> <n-icon><PeopleSharp/></n-icon> Elvis,Eben,Collins,Frank,Donne,Harry</h6>
   <h6> <n-icon><LocateOutline/></n-icon>Introduction to Software Engineering</h6>
    <!-- <template #footer>
      #footer
    </template> -->
    <!-- <template #action>
      #action
    </template> -->
  </n-card>
</div>
<div>
  <n-card title="Code Crunchers" class="p-3">
    <template #header-extra>
        <n-progress class="margin-left-20" type="circle" status="success"  :percentage="55" style="height: 35px; width: 60px;">
    <span style="text-align: center"><n-icon size="25" color="green"><PeopleOutline/></n-icon></span>
  </n-progress>

    </template>
    This group is for programmers who love to solve problems and tackle complex coding challenges.Join us to flex your coding
    <h6 class="mt-3"> <n-icon><PeopleSharp/></n-icon> Elvis,Eben,Collins,Frank,Donne,Harry</h6>
   <h6> <n-icon><LocateOutline/></n-icon>Introduction to Software Engineering</h6>
    <!-- <template #footer>
      #footer
    </template> -->
    <!-- <template #action>
      #action
    </template> -->
  </n-card>
</div>
<div>
  <n-card title="Code Crunchers " class="p-3">
    <template #header-extra>
      <n-progress type="circle" :percentage="55" status="success"  style="height: 35px; width: 60px;">
    <span style="text-align: center"><n-icon size="25" color="green"><PeopleOutline/></n-icon></span>
  </n-progress>
    </template>
    This group is for programmers who love to solve problems and tackle complex coding challenges.Join us to flex your coding
    <h6 class="mt-3"> <n-icon><PeopleSharp/></n-icon> Elvis,Eben,Collins,Frank,Donne,Harry</h6>
   <h6> <n-icon><LocateOutline/></n-icon>Introduction to Software Engineering</h6>
    <!-- <template #footer>
      #footer
    </template> -->
    <!-- <template #action>
      #action
    </template> -->
  </n-card>
</div>
</div>
</template>

<style scoped>
.n-card{
    width: 500px;
    
    margin: 10px;
    
}


@media (max-width: 1024px){
    .card{
        flex-direction: column;
    }
}
</style>