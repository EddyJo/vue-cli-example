<template>
    <div>
        <p>{{ name }}</p>
        <button @click="updateName">Change Name</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'Eddy'
        }
    },

    methods: {
        updateName() {
            this.name = 'Eddy Updateds'
        }
    }
}
</script>

<style scoped>

</style>