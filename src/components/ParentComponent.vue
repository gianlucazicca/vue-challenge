<template>
    <div>
        <h1>Parent</h1>
        {{ data }}
        <Child />
    </div>
</template>

<script>
export default {

    name: 'ParentComponent',
    components: {
        Child: () => import('./parent/ChildComponent.vue')
    },
    data: () => ({
        data: 'Parent data'
    })
}
</script>
