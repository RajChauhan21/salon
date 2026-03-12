<template>

    <section id="services" class="py-10">

        <div class="max-w-7xl mx-auto px-6">

            <h2 class="text-3xl font-bold text-center mb-12" data-aos="fade-up">
                Our Services
            </h2>

            <div class="grid md:grid-cols-3 gap-8">

                <div v-for="service in services" :key="service.title" class="bg-white rounded-2xl shadow-md p-6
hover:shadow-xl hover:scale-105 transition-transform
transition duration-300" data-aos="zoom-in">

                    <div class="text-4xl mb-3">
                        {{ service.icon }}
                    </div>

                    <h3 class="font-bold text-xl">
                        {{ service.title }}
                    </h3>

                    <p class="text-gray-600 mt-2">
                        {{ service.desc }}
                    </p>

                </div>

            </div>

        </div>

    </section>

</template>

<script>
export default {

    name: "ServicesSection",

    data() {
        return {

            services: [

                {
                    icon: "💇",
                    title: "Hair Styling",
                    desc: "Professional haircut and styling services."
                },

                {
                    icon: "🎨",
                    title: "Hair Coloring",
                    desc: "Trendy hair coloring and highlights."
                },

                {
                    icon: "🧔",
                    title: "Beard Grooming",
                    desc: "Precision beard trimming and styling."
                },

                {
                    icon: "✨",
                    title: "Facial Treatment",
                    desc: "Refreshing facial treatments for glowing skin."
                },

                {
                    icon: "💆",
                    title: "Hair Spa",
                    desc: "Deep conditioning and hair repair."
                },

                {
                    icon: "💅",
                    title: "Nail Care",
                    desc: "Manicure and pedicure services."
                }

            ]

        }
    }

}
</script>