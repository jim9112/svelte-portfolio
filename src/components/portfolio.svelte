<script lang="ts">
import { loop_guard } from 'svelte/internal';

    import PortfolioCard from './portfolioCard.svelte'
    const portfolioList = [
        'one', 'two', 'three'
    ]
</script>


<div>
    
    {#each portfolioList as portfolio}
    <PortfolioCard />
{/each}
</div>