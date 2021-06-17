<script lang="ts">
    import PortfolioCard from './portfolioCard.svelte'
    const portfolioList = [
        {
            title: "DevProjectPlanner", 
            description: 'A project management application built with TypeScript, React, MaterialUI, and FireBase. Includes Task Manager, Bug Tracker, and Note Cards. Full CRUD and authentication used. At this time you need a GitHub account in order to log in to the live project.',
            liveLink: "https://elastic-williams-4c255e.netlify.app/"
        }, 
        {
            title: "Coffeeroasters Site",
            description: "A code challenge from Front End Mentor. A website for a fictitious coffee subscriptions service. Was provided with a design document and built the page with HTML JavaScript and TailwindCSS.",
            liveLink: "http://jimmyhannan.com/coffeeroasters-subscription-site/"
        }, 
        {
            title: "Math Flashcards",
            description: "A little application built to help my son study math. Built with HTML, CSS, and JavaScript.",
            liveLink: "https://jim9112.github.io/Math-Flashcards/"
        }
    ]
</script>


<div class="container">
   <!-- Add Portfolio card for each project -->
    {#each portfolioList as project}
        <PortfolioCard title={project.title} description={project.description} liveLink={project.liveLink} />
    {/each}
</div>

<style>
.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1rem;
}
</style>