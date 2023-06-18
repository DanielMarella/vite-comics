
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
        width : calc( (100% / 6) - 60px);
        margin: 0 30px;
        margin-top: 30px;

        img{
            width: 190px;
            height: 190px;
            object-fit: cover;
            object-position: top;
        }

        p{
            margin-top: 10px;
            font-size: .8rem;
            text-transform: uppercase;
        }
    }
</style>