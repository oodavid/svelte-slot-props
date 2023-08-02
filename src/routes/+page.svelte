<script>
	import SlotProps from './SlotProps.svelte';
</script>

<SlotProps let:prop>
  {#if prop == 'one'}
    It's one
  {/if}
  



  {#if prop == 'two'}
    It's two
  {/if}
</SlotProps>