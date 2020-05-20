<style lang="scss">

</style>

<script>
    const data = [{label: 'Item 1', completed: true}, {label: 'Item 2', completed:false}, {label: 'Item 3', completed:false}]; 
</script>

<ul>
{#each data as item}

<li>
    {item.label}

    {#if item.completed}
    | Completed
    {/if}
</li>
{/each}
</ul>