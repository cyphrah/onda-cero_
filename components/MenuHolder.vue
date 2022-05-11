<template>
    <div class="ctos_holder">
        <div class="ctos">
            <div class="home">
                home
            </div>
            <div class="explorer">
                explorer
            </div>
            <div class="library">
                library
            </div>
            <div class="radio">
                radio
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style lang="postcss" scoped>
    .ctos_holder{
        @apply flex w-full justify-center p-4 bg-red-300;
    }
    .ctos{
        @apply flex items-center justify-between w-full;
    }
</style>