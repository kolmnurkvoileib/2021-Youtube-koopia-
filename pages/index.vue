<template>
<div>
    <v-sheet
    class="mx-auto mb-2"
  >
    <v-slide-group
      show-arrows
    >
      <v-slide-item
        v-for="n in 25"
        :key="n"
        v-slot="{ active, toggle }"
        class="mt-"
      >
        <v-btn
          class="mx-2"
          :input-value="active"
          active-class="grey white--text"
          depressed
          rounded
          @click="toggle"
        >
          {{ keywords[n] }}
        </v-btn>
      </v-slide-item>
    </v-slide-group>
  </v-sheet>
   <!-- <v-card
      class="d-flex flex-row mb-5"
      :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'"
      flat
      tile
    > -->



    <v-row no-gutters>
      <v-card
        v-for="n in 6"
        :key="n"
        class="pl-11 mx-5 my-2"
        
      >
      <v-responsive
          v-if="n === 2"
          :key="`width-${n}`"
          width="100%" 
        ></v-responsive>
    <v-img class="py-1"
      src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/266d59f9-71c8-4052-9619-d2685b577200/dei68if-7d2a3b1f-7879-4761-86e5-667213897965.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzI2NmQ1OWY5LTcxYzgtNDA1Mi05NjE5LWQyNjg1YjU3NzIwMFwvZGVpNjhpZi03ZDJhM2IxZi03ODc5LTQ3NjEtODZlNS02NjcyMTM4OTc5NjUuanBnIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.33uWwBR-b5PS6RHdJHWVjhDcURbwZm8X_Fuvk4V-qTo"
      height="170px"
      width="170px"
    ></v-img>

    <v-card-title class="py-4">
      BIIB BOOB BEEB
    </v-card-title>

    <v-card-subtitle class="pa-0">
      Manny Khoshbin <v-icon>mdi-check-decagram</v-icon>
    </v-card-subtitle>

    <v-card-subtitle class="pa-0">
      1,000 views 1 hour ago
    </v-card-subtitle>
    </v-card>
    </v-row>





    <v-row no-gutters>
      <v-card
        v-for="n in 6"
        :key="n"
        class="pl-11 mx-5 my-2"
      >
      <v-responsive
          v-if="n === 2"
          :key="`width-${n}`"
          width="100%" 
        ></v-responsive>
    <v-img class="py-2"
      src="https://a9p9n2x2.stackpathcdn.com/wp-content/blogs.dir/1/files/2018/02/Betty-bimbo-minnie-the-mooc-e1540496277274.jpg"
      height="170px"
      width="170px"
    ></v-img>

    <v-card-title class="py-4">
      BIIB BOOB BEEB
    </v-card-title>

    <v-card-subtitle class="pa-0">
      Manny Khoshbin <v-icon>mdi-check-decagram</v-icon>
    </v-card-subtitle>

    <v-card-subtitle class="pa-0">
      1,000 views 1 hour ago
    </v-card-subtitle>
    </v-card>
    </v-row>






    <v-row no-gutters>
      <v-card
        v-for="n in 6"
        :key="n"
        class="pl-11 mx-5 my-2"
      >
      <v-responsive
          v-if="n === 2"
          :key="`width-${n}`"
          width="100%" 
        ></v-responsive>
    <v-img class="py-2"
      src="https://static.wixstatic.com/media/e237c0_3d7c664343164f62a179e90c736f4ec3~mv2.jpg/v1/fit/w_2500,h_1330,al_c/e237c0_3d7c664343164f62a179e90c736f4ec3~mv2.jpg"
      height="170px"
      width="170px"
    ></v-img>

    <v-card-title class="py-4">
      BIIB BOOB BEEB
    </v-card-title>

    <v-card-subtitle class="pa-0">
      Manny Khoshbin <v-icon>mdi-check-decagram</v-icon>
    </v-card-subtitle>

    <v-card-subtitle class="pa-0">
      1,000 views 1 hour ago
    </v-card-subtitle>
    </v-card>
    </v-row>




      <!-- <v-img class="pt-8 py-n1 px-5"
  lazy-src="https://i.pinimg.com/originals/c1/f6/c1/c1f6c13e3d221e002968dfcbb6f64715.jpg"
  max-height="250"
  max-width="249"
  src="https://i.pinimg.com/originals/c1/f6/c1/c1f6c13e3d221e002968dfcbb6f64715.jpg"
></v-img>

<v-sheet class="ms-2 py-1">
      {{ videoTitles[n] }}
      <v-icon
      class="ml-n2">mdi-dots-vertical</v-icon>
      </v-sheet>

<v-img class="pt-8"
  lazy-src="https://media3.giphy.com/media/Jbv9LhPjpiI5W/giphy_s.gif"
  max-height="250"
  max-width="249"
  src="https://media3.giphy.com/media/Jbv9LhPjpiI5W/giphy_s.gif"
></v-img>

<v-sheet class="ms-2 py-1 font-weight-bold text-subtitle-1">
      {{ videoTitles1[n] }}
      <v-icon
      class="ml-n2 ">mdi-dots-vertical</v-icon>
      <p class="font-weight-light text-subtitle-2">Manny Khoshbin <v-icon>mdi-check-decagram</v-icon></p> 
      <div class="font-weight-thin text-subtitle-2 pt-n5">1234 views 3 weeks ago</div>
      </v-sheet>

<v-img class="pt-8"
  lazy-src="https://coub-anubis-a.akamaized.net/coub_storage/coub/simple/cw_timeline_pic/1da8fb27b1e/da80c12cc9351d7745f48/med_1411476949_image.jpg"
  max-height="250"
  max-width="249"
  src="https://coub-anubis-a.akamaized.net/coub_storage/coub/simple/cw_timeline_pic/1da8fb27b1e/da80c12cc9351d7745f48/med_1411476949_image.jpg"
></v-img>

      <v-sheet class="ms-2 py-1">
      {{ videoTitles2[n] }}
      
      
      
      <v-icon
      class="ml-n2">mdi-dots-vertical</v-icon>
      </v-sheet>
      </v-card> -->
      





</div>
</template>
<script>

export default {
  data: () => ({
    keywords: ['Music', 'Mixes', 'COVID', 'Programming', 'League of Legends', 'Cryptocurrency', 'Rap', 'Vue', 'Sander stimmer', 'Tesla', 'Trailers', 'Tools', 'Experiments', 'Outer space', 'Snow'],
    videoTitles: ['','How nft Broke The Internet','Incredible Unknown Facts','8 Little-Known Facts About nft','The nft Guide For Everyone','The Untold Story of nft','What is nft All About?', 'Shining a Light on nft'],
    videoTitles1: ['','My Thoughts on nft','Nft For Beginners','Mastering nft','Mastering nft','Best & Worst nft Trends','A Chat About lol', 'Is lol Dead?'],
    videoTitles2: ['','Travis Scott - 2 MINUTES LATE','Travis Scott - ESCAPE PLAN','Travis Scott - MAFIA','Travis Scott - Blue Chips','Travis Scott - Pull Up','Travis Scott - Astroworld', 'Travis Scott - SICKO MODE'],
  }),
}
</script>

