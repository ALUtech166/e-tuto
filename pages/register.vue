<template>
    <div>

       <!--  <div class="">
            <div class="tw-relative tw-w-full tw-h-72">
                <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover"
                    src="https://img.freepik.com/free-photo/mother-helping-supporting-her-daughter-with-homeschool-while-staying-home-new-normal-lifestyle-concept_58466-14443.jpg?w=740&t=st=1692639699~exp=1692640299~hmac=231723b28dc1627c9811fae0070b55e4d89500cc7e8bc4f6550c187cd3568ccf"
                    alt="Banner Image">
                <div
                    class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-center tw-items-center tw-bg-gray-900 tw-bg-opacity-60">
                    <h1 class="tw-text-4xl tw-font-bold tw-text-white">Register</h1>
                </div>
            </div>
        </div>
 -->
        <section class="lg:tw-pb-10 lg:tw-px-3 tw-p-4 tw-flex-col tw-gap-4 tw-mt-8">
            <div class="tw-w-full">
                <div class="tw-flex tw-flex-col tw-mb-6 tw-px-2 md:tw-px-6 lg:tw-px-10 tw-w-full">

                    <div class="2xl:tw-px-20 tw-flex tw-justify-center tw-w-full tw-mb-20">
                        <div
                            class="tw-grid lg:tw-grid-cols-2 tw-gap-4 lg:tw-gap-0 tw-w-full tw-h-full tw-rounded-t-xl tw-shadow-2xl tw-shadow-gray-800">

                            <div
                                class=" tw-h-full tw-bg-white tw-block tw-cursor-pointer tw-rounded-xl tw-w-full tw-shadow-2xl tw-shadow-indigo-100">
                                <img alt="Home"
                                    src="https://img.freepik.com/premium-photo/child-development-specialist-working-with-little-girl_116547-17389.jpg?w=740"
                                    class="tw-h-full tw-w-full tw-object-cover tw-bg-opacity-60 tw-rounded-l-md tw-shadow-2xl" />


                            </div>

                            <div
                                class="tw-bg-white  tw-block tw-cursor-pointer tw-w-full tw-shadow-2xl tw-shadow-indigo-100">
                                <div class="tw-px-8 tw-bg-white">
                                    <h1 class="tw-text-5xl tw-font-extrabold tw-mt-4">
                                        Welcome <span class="text-color">e-tuto.</span>
                                    </h1>
                                    <p class="tw-text-black tw-text-md tw-mt-2">
                                        Tutors interested in joining e-tuto are kindly requested to complete and submit this
                                        form.
                                    </p>

                                    <div class="tw-flex tw-gap-4 tw-mt-4">
                                        <hr class="lg:tw-w-24 tw-w-12 tw-h-1 bg-color tw-my-1">
                                        <hr class="lg:tw-w-24 tw-w-12 tw-h-1 tw-bg-gray-500 tw-my-1">

                                    </div>
                                </div>
                                <form class="tw-bg-white lg:tw-mt-0 tw-shadow-2xl tw-rounded-r-md tw-px-8 tw-py-8"
                                    v-on:submit.prevent="sendMessage">

                                    <div class="tw-w-full tw-md:w-1/2">
                                        <v-text-field v-model="userName" :rules="rules" label="Full name"></v-text-field>
                                    </div>

                                    <div class="tw-w-full tw-md:w-1/2">
                                        <v-text-field v-model="userName" :rules="rules"
                                            label="Email Address"></v-text-field>
                                    </div>


                                    <div class="tw-w-full tw-md:w-1/2">
                                        <v-text-field v-model="userName" :rules="rules" label="Phone Number"></v-text-field>
                                    </div>

                                    <div class="tw-w-full tw-md:w-1/2">
                                        <v-text-field v-model="userName" :rules="rules" label="Company"></v-text-field>
                                    </div>

                                    <div class="tw-w-full tw-md:w-1/2">
                                        <v-text-field v-model="userName" :rules="rules" label="Position"></v-text-field>
                                    </div>

                                    <button
                                        class="tw-group bg-color tw-shadow-lg tw-rounded-md tw-relative tw-h-12 tw-mt-4 tw-cursor-pointer hover:tw-transform hover:tw-translate-x-2 hover:tw-transition-transform hover:tw-duration-300 hover:tw-shadow-2xl-blue-600 hover:tw-shadow-2xl-lg tw-w-48 tw-overflow-hidden tw-rounded-lg tw-text-lg tw-shadow-2xl-2xl">
                                        <div
                                            class="tw-absolute tw-inset-0 tw-w-full bg-color tw--transition-all tw-duration-[250ms] tw-ease-out group-hover:tw-w-full">
                                        </div>
                                        <span
                                            class="tw-relative tw-inline-flex tw-items-center tw-gap-2 tw-text-white group-hover:tw-text-white">
                                            Register

                                        </span>
                                    </button>


                                    
                                </form>



                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {

    computed: {
        breadcrumbItems() {
            const items = [{
                text: 'Home',
                href: '/',
            },
            {
                text: 'Register',

            },

            ];

            return items.map((item) => ({
                ...item,
                disabled: !item.href,
            }));
        },
    },


}
</script>

<style scoped>


.bg-color {
    background-color: #0B2447;
}

:hover.hover-bg {
    background-color: #0B2447;
}


.text-color,
label {
    color: #0B2447;
}


button {
    color: black
}
</style>
