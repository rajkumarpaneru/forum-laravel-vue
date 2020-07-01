<template>
    <div>
        <v-footer class="pa-3">
            Company
            <v-spacer></v-spacer>
            <div>&copy; {{new Date().getFullYear()}}</div>
        </v-footer>
    </div>
</template>

<script>
    import toolbar from './Toolbar'

    export default {
        components: {
            toolbar,
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
