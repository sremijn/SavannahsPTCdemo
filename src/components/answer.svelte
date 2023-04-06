
<script>
   export let answer = false;
</script>
{#if answer}
<p class="correct">Great job! That was the answer!</p>
{:else}
<p class="incorrect">That answer wasn't quite right...</p>
{/if}

<style>
   .correct, .incorrect{
font-weight:bold; 
text-decoration: underline;
   }
   
 .correct  {
   color:green; 
 }
   .incorrect {
      color: red; 
   }
</style>
