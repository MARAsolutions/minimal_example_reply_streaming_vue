<script setup>
    import ReviewReply from './components/ReviewReply.vue'
</script>


<template>
    <main class="p-4 container max-w-5xl mx-auto">
        <div class="my-4">
            <h1 class="font-black text-xl">MARA Vue example</h1>
            <p class="text-gray-500">
                The following app is a minimal example for the streaming solution of review replies with MARA. If you have any questions, please contact i.lange@mara.solutions. The JWT token provided here is generated in production in the app and refreshed as needed. Normally, the Smart Snippets are sent via the Settings Profile. This is also sent directly to the API for simplification.
            </p>
        </div>
        <div class="mt-6">
            <ReviewReply />
        </div>
    </main>
</template>