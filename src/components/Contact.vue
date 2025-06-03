<template>
    <section id="contatti" class="bg-gray-50 py-12 px-6 md:px-0">
        <div class="max-w-2xl mx-auto">
            <h2 class="text-3xl font-bold text-indigo-700 mb-6 text-center">
                Contattami
            </h2>
            <form action="https://formspree.io/f/your-form-id" method="POST"
                class="bg-white p-6 rounded-xl shadow-md space-y-5">
                <div>
                    <label for="name" class="block text-sm font-medium text-gray-700">Nome</label>
                    <input type="text" id="name" name="name" required
                        class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-indigo-500 focus:border-indigo-500 text-gray-900" />

                </div>

                <div>
                    <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
                    <input type="email" id="email" name="email" required
                        class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-indigo-500 focus:border-indigo-500 text-gray-900" />

                </div>

                <div>
                    <label for="message" class="block text-sm font-medium text-gray-700">Messaggio</label>
                    <textarea id="message" name="message" rows="5" required
                        class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-indigo-500 focus:border-indigo-500 text-gray-900"></textarea>

                </div>

                <button type="submit"
                    class="w-full bg-indigo-600 text-white py-2 rounded-md font-semibold hover:bg-indigo-700 transition">
                    Invia messaggio
                </button>
            </form>
        </div>
    </section>
</template>
