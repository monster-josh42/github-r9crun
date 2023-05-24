<template>
    <div>
        <FullPageSliderContainer>

            <FullPageSliderItem
                class="bg-white"
                id="who-we-are"
                container-classes="flex flex-col h-full justify-center pt-24"
                content-classes="w-full h-max pt-8 flex flex-col"
                slide-name="Who we are"
            >
                <div class="h-full container mx-auto flex flex-col lg:items-center lg:justify-center px-6 lg:px-4">
                       <iframe src="https://player.vimeo.com/video/827586449?background=1&autoplay=1&loop=1&byline=0&title=0"
                frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
            </div>

                        <div class="w-full lg:w-3/4">
                            <h2 class="text-3xl xl:text-4xl text-secondary">Who We Are</h2>

                            <p class="mt-4">
                                GivEnergy are a British Owned Battery Storage Manufacturer
                                with manufacturing/Research and Development facilities in the
                                UK, Ireland, Australia and Shenzhen China (Shenzhen Givenergy
                                Technology Co., Ltd)
                            </p>

                            <h2 class="text-3xl xl:text-4xl text-secondary mt-12">
                                GivEnergy Purchase Process
                            </h2>

                            <p class="mt-4">
                                We aim to make our purchase process as simple as possible. Get
                                in touch with your local Approved Installer for product
                                information and quotes, and to arrange an installation date.
                                Once your system has been fitted, you can begin monitoring
                                your energy via the GivEnergy Monitoring Portal. Require
                                further information about our products? Our knowledge base can
                                help to guide you!
                            </p>
                        </div>
                    </div>
                </div>
            </FullPageSliderItem>


</template>
 
<style scoped>
  
  .body {
      overflow-x: hidden;
  }
  
    .column-50w {
    width: 50%;
    float: left;
    }

    .column-50w-100vm {
    height: 100vm;
    width: 50%;
    float: left;
    }

    .column-100w {
    width: 100%;
    float: left;
    }

main#Product-Banner-Scroll {
    padding: 0px;
    margin: -10px;
    height : 100vm;

}

.custom-column.custom-col-50.custom-inner-column.custom-element.custom-element-a684b36.ob-is-e3[data-v-938b83b0] {
    margin-top: -590px;
    margin-bottom: 590px;
    padding-left: 4em;
    padding-right: 4em;
    color : white;
}

h1.custom-heading-title.custom-size-large {
    font-family: "Open Sans", Sans-serif;
    font-size: 48px;
    font-weight: 700;
    line-height: 65px;
    letter-spacing: -0.02em;
    margin-bottom: -20px;
}

p.custom-heading-title.custom-size-large {
    font-family: "Open Sans", Sans-serif;
    font-size: 32px;
    font-weight: 400;
    line-height: 44px;
    letter-spacing: -0.03em;
}

span.custom-button-text {
    padding: 15px 30px 15px 30px;
    background-color: #51bbaa;
    color: #FFFFFF;
    border-radius: 64px;
    text-decoration: none;
}

h2.Heading-title {
    color: #404040;
    font-family: "Open Sans", Sans-serif;
    font-size: 38px;
    font-weight: 600;
    line-height: 51.75px;
    letter-spacing: -0.02em;
}

p.Large-paragraph {
    color: #404040;
    font-family: "Open Sans", Sans-serif;
    font-size: 22px;
    font-weight: 400;
    line-height: 40px;
    letter-spacing: -0.02em;
}

section.introduction-text {
    padding-left: 4em;
    padding-right: 4em;
}

.column-50w[data-v-938b83b0] {
    width: 50%;
    float: left;
    padding-top: 10em;
    padding-bottom: 10em;
}

.right-image-100-margin {
  margin-left: 100px;
}

</style>

<script>
export default {
    name: "AllinOnePage",

    head: {
        title: "All in One - GivEnergy",
        meta: [
            {hid: "description", name: "description", content: ""},
            {name: "format-detection", content: "telephone=no"},
        ],
        script: [
            {src: "https://api.tiles.mapbox.com/mapbox-gl-js/v2.9.2/mapbox-gl.js"},
        ],
        link: [
            {
                rel: "stylesheet",
                href: "https://api.tiles.mapbox.com/mapbox-gl-js/v2.9.2/mapbox-gl.css",
            },
        ],
    },
};

</script>
  