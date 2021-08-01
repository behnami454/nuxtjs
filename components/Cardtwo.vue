<template>
    <div>
      <card>
  <!-- Card body -->
  <b-row align-v="center">
    <b-col md="auto">
      <!-- Avatar -->
      <a href="javascript:;" class="avatar avatar-xl rounded-circle">
        <img alt="" src="@/assets/img/unnamed.jpg">
        
        
      </a>
    </b-col>
    <b-col class="ml--2">
      <h4 class="mb-0">
        <a href="javascript:;">{{ Oneeii.id}}</a>
      </h4>
      <p class="text-sm text-muted mb-0">{{ Oneeii.body }}</p>
      <span class="text-success"> </span>
      <small>Active</small>
    </b-col>
    <b-col md="auto">
     <NuxtLink to="/detail" class="btn btn-dark">details</NuxtLink>
    </b-col>
  </b-row>
</card>
    </div>
</template>

<script>
    export default {
      props:['Oneeii']
        
    }
</script>

<style scoped>
#one{
    margin-left: 230px;
}
btn{
    text-align: center;
}
</style>