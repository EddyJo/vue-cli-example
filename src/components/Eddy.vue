<template>
    <div>
        <h1>{{ title }}</h1>
        <p>{{ name }}</p>
        <p>{{ nickname }}</p>
        <button @click="updateName">Change Name</button>
    </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            default: "Default Title",
            required: true
        },
        nickname :{
            type: String,
            default: "Eddy?",
            required: true
        }
    },
    data() {
        return {
            name: 'Eddy'
        }
    },

    methods: {
        updateName() {
            this.name = 'Eddy Updated'
        }
    }
}
</script>

<style scoped>

</style>