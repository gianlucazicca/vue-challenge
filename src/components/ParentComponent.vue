<template>
    <<<<<<< HEAD <div>
        <h1>Parent</h1>
        {{ data }}
        <Child />
        </div>
        =======
        <div>
            <h1>Parent</h1>
            {{ flex }}
            <Child />
        </div>
        >>>>>>> 1881d154c79b3470c51eb0b75c2c151d4784bb33
</template>

<script>
export default {
<<<<<<< HEAD
    name: 'ParentComponent',
    components: {
        Child: () => import('./parent/ChildComponent.vue')
    },
    data: () => ({
        data: 'Parent data'
    })
}
</script>
