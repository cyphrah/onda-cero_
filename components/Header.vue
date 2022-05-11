<template>
    <div class="info_holder">
            <div class="user">
        user
    </div>
    <div class="logo">
        logo
    </div>
    </div>
</template>

<script>

</script>

<style lang="postcss" scoped>
    .info_holder{
        @apply flex items-center justify-between w-full fixed top-0 left-0;
    }
    .user{
        @apply bg-slate-300 rounded-xl w-[50px]
    }
</style>