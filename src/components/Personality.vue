<template>
    <div class="describe">
        <slot />
    </div>
</template>

<script>
    export default{
        name: "Personality"
    };
</script>

<style >
    .describe{
        color:rgba(181, 236, 255, 0.849);
        flex-wrap: wrap;
        -ms-flex-wrap: wrap;
        padding: 40px 40px 00px 40px;
        text-align: center;
    }
</style>
