<template>
    <section class="bg-white w-screen h-screen">
        <div class="text-primary p-5">
            <h1 class="font-bold">Hola Again</h1>
            <p class="font-extralight">Welcome back! Please enter your credentials to securely access your account. 
            </p>
        </div>
        <div class="flex items-center justify-center">
            <img src="public/assets/login.svg" alt="Logo" class="max-w-full max-h-full">
        </div>
        <section class="grid gap-4 ">
            <div class="flex items-center justify-center">
                <input type="text" placeholder="Enter your email" class="border-0 text-primary border-b-2 border-primary w-4/5 focus:outline-none focus:border-b-2 focus:ring-0 focus:border-primary">
            </div>
            <div class="flex items-center justify-center">
                <input type="text" placeholder="password" class="border-0 text-primary border-b-2 border-primary w-4/5 focus:outline-none focus:border-b-2 focus:ring-0 focus:border-primary">
            </div>
            <a href="" class="flex items-center justify-center  text-primary"><p>Forgot Password?</p></a>
            <div class="flex items-center justify-center">
                <button type="button" class="flex items-center justify-center text-white bg-primary hover:bg-gray-800 focus:outline-none focus:ring-4 focus:ring-gray-300 font-bold rounded-full w-4/5 py-3">Log In</button>
            </div>
            <p class="flex items-center justify-center  text-primary">OR</p>
            <div class="flex items-center justify-center ">
                <button type="button" class="flex items-center justify-center text-white bg-primary hover:bg-gray-800 focus:outline-none focus:ring-4 focus:ring-gray-300 font-bold rounded-full w-4/5 py-3">Create Account</button>
            </div>
            
        </section>
        
    </section>
</template>
<script>
export default {
    name: 'loginView.vue',
}
</script>      