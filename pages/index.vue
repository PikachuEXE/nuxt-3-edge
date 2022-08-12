<template>
  <div
    class="max-w-3xl max-w-5xlmin-h-screen flex justify-center mx-auto my-12"
  >
    <main class="w-full">
      Nothing
    </main>
  </div>
</template>


<script setup>
import { useI18n } from '#i18n'

const I18n = useI18n()
const { t } = I18n


useHead({
  title: t("meta.title"),
})

</script>

<i18n lang="yaml">

en:
  meta:
    title: Home

zh:
  meta:
    title: 首頁

</i18n>
