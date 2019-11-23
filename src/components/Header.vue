<template> 
    <div id="header">
        <div id="wrapper">
        <h1> A Mug of ETH </h1>
        <img id="logo" src="../assets/coffee-mug.png"/> <!-- Thank you and credit to: https://www.stockio.com/free-icon/coffee-icons-coffee-mug-->
        </div>

    </div>
</template>

<script>
export default {
  name: 'Header',
}

</script>

<style scoped>
#logo { 
    width: 62.5px;
    height: 62.5px;
}

h1 {
    padding-top: 10px;
}

#wrapper { 
    display: flex;
}

</style>