
<template>
    <div class="card">
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
    .card{
        width : calc( (100% / 6) - 40px);
        margin: 0 20px;
        margin-top: 30px;

        img{
            width: 150px;
            height: 150px;
            object-fit: cover;
        }

        p{
            margin-top: 10px;
            font-size: .8rem;
            text-transform: uppercase;
        }
    }
</style>