<script lang="ts">
  import Case from '$components/errCase.svelte';
  import type { CaseWithDrops } from '$lib';
  export let data: { caseData: CaseWithDrops };
</script>

<Case caseData="{data.caseData}" />
