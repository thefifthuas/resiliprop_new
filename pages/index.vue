<template>
  <!DOCTYPE html>
  <html>
    <head>
      <meta charset="utf-8" />
      <meta http-equiv="X-UA-Compatible" content="IE=edge" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Resiliprop</title>
    </head>
    <body>
      <div
        id="flipbok"
        class="_df_book"
        source="/ebook/Resili Prop Brochure.pdf"
      ></div>
    </body>
  </html>
</template>
<script>
export default {
  name: 'IndexPage',
  head() {
    return {
      link: [
        {
          rel: 'stylesheet',
          href: require('~/assets/dflip/css/dflip.min.css'),
        },
        {
          rel: 'stylesheet',
          href: require('~/assets/dflip/css/themify-icons.min.css'),
        },
      ],
      script: [
        {
          src: 'dflip/js/libs/jquery.min.js',
          body: true,
        },
        {
          src: 'dflip/js/dflip.min.js',
          body: true,
        },
      ],
    }
  },
}
</script>
