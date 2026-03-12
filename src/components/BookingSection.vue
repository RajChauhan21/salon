<template>

    <section id="booking" class="py-20 bg-gray-50">

        <div class="max-w-xl mx-auto text-center px-6">

            <h2 class="text-3xl font-bold mb-6" data-aos="fade-up">
                Book Your Appointment
            </h2>

            <!-- Name -->

            <input v-model="name" placeholder="Your Name" class="w-full border p-3 rounded-lg mb-4" />

            <!-- Phone -->

            <input v-model="phone" placeholder="Phone Number" class="w-full border p-3 rounded-lg mb-4" />

            <!-- Service Request -->

            <input v-model="service" placeholder="Requested Service (Haircut, Facial, Beard Trim...)"
                class="w-full border p-3 rounded-lg mb-4" />

            <!-- Date -->

            <input type="date" v-model="date" class="w-full border p-3 rounded-lg mb-6" />

            <!-- WhatsApp Button -->

            <button @click="sendWhatsapp" class="w-full py-3 rounded-full text-white font-semibold
bg-gradient-to-r from-rose-500 to-purple-500
hover:scale-105 transition shadow-md">

                Book via WhatsApp

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
            phone: "",
            service: "",
            date: "",

            // Replace with salon owner's number
            whatsappNumber: "919876543210"

        }
    },

    methods: {

        sendWhatsapp() {

            if (!this.name || !this.phone || !this.service || !this.date) {

                alert("Please fill all fields")

                return

            }

            const message =
                `Hello, I would like to book an appointment.

Name: ${this.name}
Phone: ${this.phone}
Service: ${this.service}
Preferred Date: ${this.date}`

            const url =
                `https://wa.me/${this.whatsappNumber}?text=${encodeURIComponent(message)}`

            window.open(url, "_blank")

        }

    }

}

</script>