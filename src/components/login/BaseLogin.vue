<template>
    <div class="login">
        <v-form>
            <v-text-field label="Email"></v-text-field>
            <v-text-field label="Password" placeholder="Enter your password"></v-text-field>
            <br>
            <v-btn :disabled="!form" :loading="loading" color="success" size="large" type="submit" variant="elevated"
                block>
                Sign In
            </v-btn>
        </v-form>
    </div>
</template>
<script>
export default {
    name: 'LoginPage'
}
</script>
<style scoped>
.login {
    background-color: #353d75;
}
</style>