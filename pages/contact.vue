<template>
    <div>
        <div id="one">
            <h3>phone: 092022222</h3>
            <h4>address: irannnnn</h4>
            <br>
            <br>
            
            <h4> when you wanna meet us?</h4>
        </div>
       <div>
           
      </div>

<vc-calendar
      :value="null"
      color="red"
      is-dark
      is-range
      />
      <br>
      <br>
       <div>
        <button v-on:click="alertt" class="btn btn-dark">click</button>
    </div>
    </div>
   
</template>

<script>
    export default {
methods: {
    alertt: function() {
      alert('thanks for meeting us');
       
    }
}
};
</script>

<style scoped>
#one{
    text-align: center;
    margin: 10px;
    
    display: inline;
}
.vc-container{
    margin-left: 550px;
}
.btn{
    margin-left: 650px;
}

</style>