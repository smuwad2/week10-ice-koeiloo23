<script>
    export default { 
        data() {
            return {
                soundEmojis: ['🔇', '🔈', '🔉', '🔊']
            }
        },
        // TODO: add code to define a necessary prop
        props: {
            level: Number
        },
        computed: {
            soundIcon(){
                return this.soundEmojis[this.level];
            }
        }
    }
</script>

<template>
    <!-- TODO: add your template code here. Use span element. --> 

    <span>{{ soundIcon }}</span>
</template>