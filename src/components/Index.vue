<template>
  <div>
    <h1 style="text-align:center">清澜山学生站</h1>
    <v-card>
      <v-card-title><h3>关于我们</h3></v-card-title>
      <hr>
      <v-img
            height="80"
            width="120"
            src="https://cdn.vuetifyjs.com/images/cards/store.jpg"
            style="margin:15px;border-radius:5px"
          ></v-img>
      <v-card-text>
        清澜山学生网是一个Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi temporibus officia nemo odit, delectus consequatur et reprehenderit ut! Deleniti voluptas non inventore sequi porro consequuntur velit expedita quisquam neque quas.
        清澜山学生网是一个Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi temporibus officia nemo odit, delectus consequatur et reprehenderit ut! Deleniti voluptas non inventore sequi porro consequuntur velit expedita quisquam neque quas.
        清澜山学生网是一个Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi temporibus officia nemo odit, delectus consequatur et reprehenderit ut! Deleniti voluptas non inventore sequi porro consequuntur velit expedita quisquam neque quas.
      </v-card-text>
    </v-card> 
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
