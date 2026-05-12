<script setup></script>

<template>
    <button class="button">
        <div>
            <slot name="icon"/>
        </div>
        <slot/>
    </button>
</template>

<style scoped>
.button {
    width: 335px;
    height: 68px;
    font-family: var(--button-font);
    background-color: var(--color-primary);
    border-radius: 100px;
    padding: 16px 10px;
    font-size: 24px;
    font-weight: 400;
    cursor: pointer;
}
</style>