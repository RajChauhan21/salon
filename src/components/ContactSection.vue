<template>

    <section id="contact" class="py-10 bg-gray-50">

        <div class="max-w-7xl mx-auto px-6">

            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12" data-aos="fade-up">
                Contact Us
            </h2>

            <div class="grid md:grid-cols-2 gap-10 items-center">

                <!-- CONTACT INFO -->

                <div class="bg-white rounded-2xl shadow-md p-8" data-aos="fade-right">

                    <h3 class="text-2xl font-semibold mb-6">
                        Get In Touch
                    </h3>

                    <div class="space-y-6">

                        <div class="flex items-start space-x-4">

                            <div class="text-2xl">📍</div>

                            <div>
                                <h4 class="font-semibold">Address</h4>
                                <p class="text-gray-600">
                                    <!-- 123 Main Street, Andheri West,<br>
                                    Mumbai, Maharashtra -->
                                    shop Number 5, Sai Paradise, <br>
                                    Vijay Marg, Sector-1, New Panvel East, <br>
                                    Navi Mumbai,<br>
                                    Maharashtra 410206
                                </p>
                            </div>

                        </div>


                        <div class="flex items-start space-x-4">

                            <div class="text-2xl">📞</div>

                            <div>
                                <h4 class="font-semibold">Phone</h4>
                                <p class="text-gray-600">
                                    +91 73040 80058
                                </p>
                            </div>

                        </div>


                        <div class="flex items-start space-x-4">

                            <div class="text-2xl">✉️</div>

                            <div>
                                <h4 class="font-semibold">Email</h4>
                                <p class="text-gray-600">
                                    luxesalon@email.com
                                </p>
                            </div>

                        </div>

                    </div>


                    <button class="mt-8 px-6 py-3 rounded-full text-white font-semibold
bg-gradient-to-r from-rose-500 to-purple-500
hover:scale-105 transition shadow-md">

                        Book Appointment

                    </button>

                </div>


                <!-- GOOGLE MAP -->

                <div class="rounded-2xl overflow-hidden shadow-lg" data-aos="fade-left">

                    <!-- <iframe class="w-full h-[400px]"
                        src="https://www.google.com/maps?q=andheri%20west%20mumbai&output=embed" loading="lazy">
                    </iframe> -->

                    <iframe class="w-full h-[400px]"
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3772.463253274382!2d73.1153091739489!3d18.999297854378465!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3be7e92aa8430deb%3A0x622759e354b0dd76!2sScissors%20Salon!5e0!3m2!1sen!2sin!4v1773317745153!5m2!1sen!2sin"
                        loading="lazy"></iframe>

                </div>


            </div>

        </div>

    </section>

</template>

<script>

export default {

    name: "ContactSection"

}

</script>