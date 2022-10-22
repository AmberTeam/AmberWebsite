<script>
  import cl from './Footer.module.sass'
  export default {
    data () {
      return { cl }
    }
  }
</script>


<template>
    <footer :class="cl.Footer"> 
        <p>AMBER © 2022</p>
    </footer>
</template>