<template>
    <header>
    <div class="wrapper">
        <RouterLink to="/">
            <div>
                <h2>
                    INBIO
                </h2>
            </div>
        </RouterLink>
            <div class="header">
                <RouterLink to="/signin" > <h2 > CLIENTS </h2></RouterLink>
                <RouterLink to="/signup" > <h2 >PRICING </h2></RouterLink>
                <RouterLink to="/signup" > <h2 >BLOG </h2></RouterLink>
                <RouterLink to="/signup" > <h2 >CONTACT US </h2></RouterLink> 
            </div>
    </div>
  </header>
</template>

<script>
export default{
    
}
</script>

<style scoped>
.wrapper{
    display: flex;
    justify-content: space-between;
    background-color: #ECF0F3;
    padding: 10px;
    border-bottom: 1px solid #DCE1E4;
}

a{
    text-decoration: none;
}

.header{
    display: flex;
}
h2{
    padding: 20px;
    font-family: 'Noto Sans', sans-serif;
    font-family: 'Roboto', sans-serif;
    color: #2F3236;
}
h2:hover{
    color: #FF014F;
}
</style>


