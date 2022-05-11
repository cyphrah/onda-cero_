<template>
    <div class="banner">
        <div class="info_holder">
            <div class="onda_logo"><img src="logo2.svg"></div>
            <h1>Para ti</h1>
        </div>
    </div>
</template>

<script>
    export default{
        data () {
            return{

            }
        }
    }
</script>

<style lang="postcss" scoped>
    .banner{
        @apply bg-[#42EC42] w-[348px] h-[164px] rounded-md mb-5 mr-5;
        @apply flex justify-center items-center;
        .info_holder{
            .onda_logo{

            }
            h1{
                @apply font-bold text-white text-sm;
            }
        }
    }
    .info_holder{
        @apply flex justify-center items-center;
    }
    h1{
        @apply font-bold text-[#EDF7ED] text-[24px];
    }
    .onda_logo{
        @apply w-[20px] mr-2;
    }
</style>