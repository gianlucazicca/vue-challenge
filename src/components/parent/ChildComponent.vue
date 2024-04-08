<template>
    <div>
        <h1>Child</h1>
        <GrandChild />
    </div>
</template>

<script>
export default {
    name: 'ChildComponent',
    components: {
        GrandChild: () => import('./GrandChild.vue')
    }
}
</script>