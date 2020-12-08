<template>
  <div>
    <client-only>
      <lingallery width="100%" :items="items"/>
    </client-only>
  </div>
</template>
<script>
  export default {
    data() {
      return {
        responsive: true,
        items: [{
          src: '/ref1.png',
          thumbnail: '/ref1.png',
        },
        {
          src: '/1024x748.png',
          thumbnail: '/1024x748.png'
        },
        {
          src: '/1024x748-2.png',
          thumbnail: '/1024x748-2.png'
        },
        {
          src: '/1024x748-3.jpeg',
          thumbnail: '/1024x748-3.jpeg'
        },
        {
          src: '/1024x748-4.jpeg',
          thumbnail: '/1024x748-4.jpeg'
        },
        {
          src: '/hauer.png',
          thumbnail: '/hauer.png'
        },
        {
          src: '/zell.png',
          thumbnail: '/zell.png'
        },
        {
          src: '/schau.png',
          thumbnail: '/schau.png'
        },
        {
          src: 'referenz-arzt-zitowebdesign-1030x498.png',
          thumbnail: 'referenz-arzt-zitowebdesign-1030x498.png'
        },
        {
          src: 'tour-guide-1030x630.png',
          thumbnail: 'tour-guide-1030x630.png'
        },
        {
          src: 'little-elbi-1030x674.png',
          thumbnail: 'little-elbi-1030x674.png'
        },
        {
          src: 'linke-1030x689.png',
          thumbnail: 'linke-1030x689.png'
        },
        {
          src: 'hacke-1030x747.png',
          thumbnail: 'hacke-1030x747.png'
        },
        {
          src: 'dorfen-1030x587.png',
          thumbnail: 'dorfen-1030x587.png'
        },
      ]};
    },
    components: {

    }
  }
</script>
