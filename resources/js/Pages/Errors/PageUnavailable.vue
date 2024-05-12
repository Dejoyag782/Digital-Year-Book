<script setup>
import GuestLayout from '@/Layouts/GuestLayout.vue';
import PrimaryButton from '@/Components/PrimaryButton.vue';
import { Head, Link } from '@inertiajs/vue3';

// const form = useForm({
//     name: '',
//     email: '',
//     password: '',
//     password_confirmation: '',
// });

</script>

<template>
    <GuestLayout>
        <Head title="Register" />

        <div>
            <h1 class=" text-large text-gray-600 dark:text-gray-400 hover:text-gray-900 dark:hover:text-gray-100 rounded-md focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 dark:focus:ring-offset-gray-800" >404 - Page Not Found</h1>
            <p class=" text-large text-gray-600 dark:text-gray-400 hover:text-gray-900 dark:hover:text-gray-100 rounded-md focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 dark:focus:ring-offset-gray-800" >The page you are looking for does not exist.</p>
        </div>

        <div class="flex items-center justify-end mt-4">
            <Link
            href="/"
            class="underline text-sm text-gray-600 dark:text-gray-400 hover:text-gray-900 dark:hover:text-gray-100 rounded-md focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 dark:focus:ring-offset-gray-800"
            >
                <PrimaryButton class="ms-4">
                    Back to Welcome
                </PrimaryButton>
            </Link>
        </div>
        
    </GuestLayout>
</template>
