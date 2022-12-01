<script>
export default{
    data(){
        return{
            user:{
                firstName: "Gabriella",
                surName: "Chessa",
            }
        }
    },

    methods: {
        getUsername(){
            return this.user.firstName + " " + this.user.surName
        }
    }
}
</script>

<template>
    <div>
        <h2>
            Benvenuta {{getUsername()}}
        </h2>
    </div>
</template>