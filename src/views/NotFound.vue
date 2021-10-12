<template>
    <h1>opps</h1>
    <h3> the {{ resource }} you are trying to access doesn't exist</h3>
    <router-link :to="{name: 'EventList'}">Back to the home page
    </router-link>
</template>

<script>
export default {
    prop:{
        resource:{
            type:  String,
            required: true,
            default: 'page'
        }
    }
}
</script>