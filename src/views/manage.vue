
<template>
  <v-container>
    Members:
    <v-avatar class="member-avatar">
      <img src="rontale.jpg" alt="Rontale" />
    </v-avatar>
    Rontale, Dan Keneth M.<br>

    <v-avatar class="member-avatar">
      <img src="rhigen.jpg" alt="Rhigen" />
    </v-avatar>
    Rhigen Abaca<br>

    <v-avatar class="member-avatar">
      <img src="nicolle.jpg" alt="Nicolle" />
    </v-avatar>
    Nicolle Gutierrez
  </v-container>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'manage',
});
</script>

<style>
.member-avatar {
  width: 100px; /* Adjust the size as needed */
  height: 100px; /* Adjust the size as needed */
  margin-right: 10px; /* Add some spacing between avatars */
  display: inline-block;
}
</style>