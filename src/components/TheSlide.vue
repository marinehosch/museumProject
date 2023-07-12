<script>
import { computed, ref } from 'vue'
import { useFetchJson } from '../composables/fetchjson.js'


const url = computed(() => `https://data.culture.gouv.fr/api/records/1.0/search/?dataset=base-joconde-extrait&q=&facet=domaine&facet=departement&facet=ville`)

const { data: museums } = useFetchJson(url)



</script>

<template>

</template>

<style scoped>
</style>