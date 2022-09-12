<template>
    <footer id="footer"> 
        <p>Make burger &copy; 2022</p>
    </footer>
</template>

<script>

export default {
    name: 'Footer',
}
</script>

<style scoped>
    #footer {
      height: 80px;
      background-color: #222;
      border-top: 4px solid #111;
      color: #fcba03;
      display: flex;
      align-items: center;
      justify-content: center;
      bottom: 0;
      left:0;
      width: 100%;
      position: relative;
    }
</style>