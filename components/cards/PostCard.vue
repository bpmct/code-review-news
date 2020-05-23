<template>
  <generic-card
    :title="title"
    :image="image"
    :link="link"
    :image-dimensions="
      $siteConfig.posts.imageDimensions ||
        $siteConfig.cards.imageDimensions ||
        null
    "
  >
    <p class="description-wrapper">
      {{ subtitle }}
    </p>
    {{ '\n' }}
    <span v-if="date" class="date-wrapper">
      <strong>Published:</strong> {{ datePretty }}
    </span>
  </generic-card>
</template>

<script>
import GenericCard from './GenericCard'
import { getFormattedDate } from '~/helper'
export default {
  components: { GenericCard },
  props: {
    title: {
      type: String,
      default: ''
    },
    image: {
      type: String,
      default: ''
    },
    link: {
      type: String,
      default: ''
    },
    date: {
      type: String,
      default: ''
    },
    subtitle: {
      type: String,
      default: ''
    }
  },
  computed: {
    datePretty() {
      return getFormattedDate(this.date)
    }
  }
}
</script>

<style scoped lang="scss">
.description-wrapper {
  margin-top: 12px;
  margin-bottom: 12px;
}
</style>
