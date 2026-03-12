<template>

    <section id="gallery" class="py-20 bg-white">

        <div class="max-w-7xl mx-auto px-6">

            <h2 class="text-3xl font-bold text-center mb-12" data-aos="fade-up">
                Our Work
            </h2>

            <div class="grid md:grid-cols-3 gap-6">

                <img v-for="(img, i) in images" :key="i" :src="img"
                    class="rounded-2xl shadow-md hover:scale-105 transition" data-aos="zoom-in" />

            </div>

        </div>

    </section>

</template>

<script>
export default {

    name: "GallerySection",

    data() {
        return {

            images: [
                "https://images.unsplash.com/photo-1522337660859-02fbefca4702",
                "https://images.unsplash.com/photo-1521590832167-7bcbfaa6381f",
                "https://images.unsplash.com/photo-1595475038784-bbe439ff41e6",
                "https://images.unsplash.com/photo-1582095133179-bfd08e2fc6b3",
                "https://images.unsplash.com/photo-1605497788044-5a32c7078486",
                "https://images.unsplash.com/photo-1487412720507-e7ab37603c6f"
            ]

        }

    }

}
</script>