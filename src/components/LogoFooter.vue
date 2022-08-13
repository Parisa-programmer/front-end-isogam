<template>
    <div class="footer">
        <v-row class="my-12 justify-center px-xl-12 px-lg-12 px-md-8 px-sm-4 px-xs-0">
            <div class="footerDiv">
                <vs-images hover="blur">
                    <vs-image :key="i" :src="item" v-for="(item, i) in images" />
                </vs-images>
            </div>
        </v-row>
    </div>
</template>

<script>
import image1 from '../assets/logo-1.png'
import image2 from '../assets/logo-2.png'
import image3 from '../assets/logo-3.png'
import image4 from '../assets/logo-4.png'
export default {
    name: "LogoFooter",
    data: () => ({
        images: [image1, image2, image3, image4],
    }),
};
</script>
