<template>

    <section id="booking" class="py-20">

        <div class="max-w-xl mx-auto text-center px-6">

            <h2 class="text-3xl font-bold mb-6" data-aos="fade-up">
                Book Your Appointment
            </h2>

            <input v-model="name" placeholder="Your Name" class="w-full border p-3 rounded-lg mb-4" />

            <input v-model="phone" placeholder="Phone Number" class="w-full border p-3 rounded-lg mb-4" />

            <button @click="book" class="w-full py-3 rounded-full text-white font-semibold
bg-gradient-to-r from-rose-500 to-purple-500
hover:scale-105 transition">

                Book Now

            </button>

        </div>

    </section>

</template>

<script>
export default {

    name: "BookingSection",

    data() {
        return {

            name: "",
            phone: ""

        }
    },

    methods: {

        book() {

            if (!this.name || !this.phone) {

                alert("Please fill all fields")

                return
            }

            alert("Appointment request sent!")

        }

    }

}
</script>