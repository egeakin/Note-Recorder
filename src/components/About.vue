<template>
    <div class="about">
        <h1>Hello {{their_name}}, this is an about page</h1>
    </div>
</template>     

<script>
export default {
    name: 'Skills',
    data() {
        return {
            their_name: this.$route.params.name
        }
    }
}