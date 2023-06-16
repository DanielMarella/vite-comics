
<template>
    <div>
        <img :src="cardElement.thumb" alt="">
        <p>
            {{ cardElement.series }}
        </p>
    </div>
</template>

<script>
export default {
    name : 'Card',

    props : [
        'cardElement'
    ]
}
</script>


<style lang="scss" scoped>
    
</style>