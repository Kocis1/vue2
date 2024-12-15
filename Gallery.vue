<template>
    <h1>Gallery</h1>
    <img src="https://i.pinimg.com/736x/fa/7d/7d/fa7d7d0dd96896a6d47f06fd2817ffa7.jpg">
    <div>Кол-во лайков: <strong>{{ likes }}</strong></div>
    <button>Лайк</button>
</template>
<script>
    export default
    {
        data()
        {
            return
            {
                likes:0;
            }
        }
    }
</script>
<style>
</style>