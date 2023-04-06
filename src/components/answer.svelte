
<script>
   export let answer = false;
</script>
{#if answer}
<p>
   
   Great job! That was the answer!
</p>
{:else}
<p>
   That answer wasn't quite right...
</p>
{/if}


