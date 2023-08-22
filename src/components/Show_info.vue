<template>
    <div>

    </div>
</template>

<script>
    export default {
        data() {
            return {
                num_friends: [2, 6, 5],
                logged_in: true,
                tweet: ['More than you', 'Life is sweet', 'Remember to keep it low key'],
        }
    

    },
    mounted(){
        for(let i=0; i<this.number_friends.length; i++){
            document.body.insertAdjacentHTML('beforeend', '<h1>$(this.nums[i]</h1>');
        }
    },
    
    }
</script>

<style lang="scss" scoped>

</style>