<script setup>
    import ReviewReply from './components/ReviewReply.vue'
</script>


<template>
    <main class="p-4 container max-w-5xl mx-auto">
        <div class="my-4">
            <h1 class="font-black text-xl">MARA Vue example</h1>
            <p class="text-gray-500">
                The following app is a minimal example of streaming review replies with MARA. If you have any questions, please contact i.lange@mara.solutions.
            </p>
            <p class="text-gray-500 mt-2">
                The JWT token provided manually here should be generated and updated by your backend in production as needed.
            </p>
            <p class="text-gray-500 mt-2">
                In production, the smart snippets, which can be set directly here for simplicity, should be sent via a settings profile.
            </p>
        </div>
        <div class="mt-6">
            <ReviewReply />
        </div>
    </main>
</template>