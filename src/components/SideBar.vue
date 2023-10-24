<template>
  <v-navigation-drawer expand-on-hover rail>
    <v-list-item
      prepend-avatar="https://qph.cf2.quoracdn.net/main-thumb-126103989-200-zznnaqrcesiwnhqtmpqnteoblncikoxe.jpeg"
      title="Giga Chad" subtitle="Chad@gmail.com" nav>
      <template v-slot:append>
        <v-btn variant="text" icon="mdi-chevron-left" @click.stop="rail = !rail"></v-btn>
      </template>
    </v-list-item>
    <v-divider />

    <v-list densicty="compact" nav>
      <v-list-item prepend-icon="mdi-image" title="Color Gallery" value="color" />
    </v-list>

    <v-list densicty="compact" nav>
      <v-list-item prepend-icon="mdi-dialpad" title="Grayspace Gallery" value="color" />
    </v-list>

  </v-navigation-drawer>
</template>