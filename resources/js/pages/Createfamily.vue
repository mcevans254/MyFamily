<template>
    <div
        class="flex min-h-screen items-center justify-center bg-cover bg-center"
        style="background-image: url('/public/Images/background.jpg')"
    >
        <div
            class="bg-opacity-80 w-2/3 max-w-2xl rounded-lg bg-white p-8 shadow-lg"
        >
            <h2 class="mb-4 text-xl font-bold text-gray-800">
                Create your album!
            </h2>

            <form class="submitAlbum">
                <!-- Full Name -->
                <div class="mb-4">
                    <label class="block text-gray-700">Full Name</label>
                    <input
                        type="text"
                        class="w-full rounded-lg border px-4 py-2 focus:ring focus:ring-blue-300 focus:outline-none"
                        required
                    />
                </div>

                <!-- Role -->
                <div class="mb-4">
                    <label class="block text-gray-700">Role</label>
                    <input
                        type="text"
                        class="w-full rounded-lg border px-4 py-2 focus:ring focus:ring-blue-300 focus:outline-none"
                        required
                    />
                </div>
                <!--invite code-->
                <!-- <div class="mb-4">
                    <label class="block text-gray-700">Invite Code</label>
                    <div class="flex">
                        <input
                            v-model="form.code"
                            type="text"
                            class="w-full rounded-lg border px-4 py-2 focus:outline-none focus:ring focus:ring-blue-300"
                            readonly
                        />
                        <button
                            @click="generateInviteCode"
                            class="ml-2 rounded-lg bg-blue-500 px-4 py-2 text-white hover:bg-blue-600"
                        >
                            Generate
                        </button>
                    </div>
                </div> -->

                <!-- File Upload -->
                <div
                    class="mb-4 rounded-lg border-2 border-dashed border-gray-300 p-6 text-center"
                >
                    <input type="file" ref="fileInput" class="hidden" />
                    <div class="cursor-pointer">
                        <i
                            class="fas fa-cloud-upload-alt text-3xl text-gray-500"
                        ></i>
                        <p class="text-gray-600">
                            Drag and drop your Album photo here or select a
                            file!
                        </p>
                    </div>
                </div>

                <!-- Submit Button -->
                <button
                    type="submit"
                    class="w-full rounded-lg bg-gradient-to-r from-purple-500 to-blue-500 py-2 text-white shadow-md hover:opacity-90"
                >
                    Create Album
                </button>
            </form>
            <!--invite code-->
            <div class="mt-10 mb-4">
                <label class="block text-gray-700">Invite Code</label>
                <div class="flex">
                    <input
                        type="text"
                        class="w-full rounded-lg border px-4 py-2 focus:ring focus:ring-blue-300 focus:outline-none"
                        readonly
                    />
                    <button
                        class="ml-2 rounded-lg bg-blue-500 px-4 py-2 text-white hover:bg-blue-600"
                    >
                        Generate
                    </button>
                </div>
            </div>

            <!-- Social Media Icons -->
            <div class="mt-4 flex justify-center space-x-6 text-gray-700">
                <i class="fab fa-whatsapp text-2xl"></i>
                <i class="fab fa-facebook text-2xl"></i>
                <i class="fab fa-instagram text-2xl"></i>
            </div>
        </div>
    </div>
</template>
