<template>
    <section class="bg-white w-screen h-screen">
        <div class="text-primary p-5">
            <h1 class="font-bold">You Forgot!</h1>
            <p class="font-extralight">Oops! Looks like your memory took a vacation. No worries, we'll help you get back in! Just follow the steps below to reset your password and you'll be back to your adventures in no time.
            </p>
        </div>
        <div class="flex items-center justify-center">
            <img src="public/assets/login.svg" alt="Logo" class="max-w-full max-h-full">
        </div>
        <section class="grid gap-4">
            <div class="flex items-center justify-center">
                <input type="text" placeholder="Email" class="border-0 text-primary border-b-2 border-primary w-4/5 focus:outline-none focus:border-b-2 focus:ring-0 focus:border-primary">
            </div>
            <div class="flex items-center justify-center">
                <input type="text" placeholder="New Password" class="border-0 text-primary border-b-2 border-primary w-4/5 focus:outline-none focus:border-b-2 focus:ring-0 focus:border-primary">
            </div>
            <div class="flex items-center justify-center">
                <input type="text" placeholder="Confirm Password" class="border-0 text-primary border-b-2 border-primary w-4/5 focus:outline-none focus:border-b-2 focus:ring-0 focus:border-primary">
            </div>
            <div class="flex items-center justify-center">
                <button type="button" class="flex items-center justify-center text-white bg-primary hover:bg-gray-800 focus:outline-none focus:ring-4 focus:ring-gray-300 font-bold rounded-full w-4/5 py-3">Confirm</button>
            </div>
            <div class="flex items-center justify-center">
                <button type="button" class="flex items-center justify-center text-white bg-primary hover:bg-gray-800 focus:outline-none focus:ring-4 focus:ring-gray-300 font-bold rounded-full w-4/5 py-3">Cancel</button>
            </div>
            
        </section>
        
    </section>
</template>
<script>
export default {
    name: 'loginView.vue',
}
</script>      