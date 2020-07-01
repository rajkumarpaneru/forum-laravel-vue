<template>
    <div>
        <v-toolbar>
            <v-toolbar-title>Title</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-toolbar-items class="hidden-sm-and-down">
                <v-btn flat>Forum</v-btn>
                <v-btn flat>Ask Question</v-btn>
                <v-btn flat>Category</v-btn>
                <v-btn flat>Login</v-btn>
            </v-toolbar-items>
        </v-toolbar>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
