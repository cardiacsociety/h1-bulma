<template>
    <footer class="footer">
        <div class="container">
            <div class="columns">
                <div class="column heartbeat" @click="$router.push('/auth')">
                    <HeartBeat/>
                </div>
                <div class="column has-text-right">
                    <ActivityAddButton/>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>

    import ActivityAddButton from '~/components/Activity/ActivityAddButton'
    import HeartBeat from '~/components/Auth/HeartBeat'

    export default {

        components: {
            ActivityAddButton,
            HeartBeat,
        },
    }
</script>

<style scoped>
    .heartbeat:hover {
        cursor: pointer;
    }
</style>
