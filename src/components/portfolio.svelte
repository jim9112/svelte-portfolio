<script lang="ts">
    import PortfolioCard from './portfolioCard.svelte'
    const portfolioList = [
        {title: "DevProjectPlanner"}, {title: "Coffeeroasters Site"}, {title: "Math Flashcards"}
    ]
</script>


<div class="container">
   <!-- Add Portfolio card for each project -->
    {#each portfolioList as project}
        <PortfolioCard title={project.title} />
    {/each}
</div>

<style>
.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1rem;
}
</style>