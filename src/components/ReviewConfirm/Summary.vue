<template>
  <div class="summary-container">
    <SummaryDefineCompany/>
  </div>
</template>

<script lang="ts">
// Libraries
import { Component, Vue } from 'vue-property-decorator'

// Components
import { SummaryDefineCompany } from '@/components/Summary'

@Component({
  components: {
    SummaryDefineCompany
  }
})
export default class Summary extends Vue { }
</script>

<style lang="scss">
.summary-container {
  margin-top: 1rem;
}
</style>
