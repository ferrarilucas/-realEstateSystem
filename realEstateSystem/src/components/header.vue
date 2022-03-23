<template>
    <div>
        <header>
            <h1>{{ title }}</h1>
        </header>
        <main>
            <slot></slot>
        </main>
    </div>
</template>

<script>
    export default{
        name: 'Header'

    }
</script>

<style>

</style>