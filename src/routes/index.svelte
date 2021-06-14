<script lang="ts">
    import Header from '../components/header.svelte'
    import Hero from '../components/hero.svelte'
    import SectionContainer from '../components/sectionContainer.svelte'
    import SkillsSection from '../components/skillsSection.svelte'
</script>


<Header />
<Hero />
<SectionContainer title={"Skills"}><SkillsSection /></SectionContainer>
<SectionContainer title={"My Portfolio"}><p>test</p></SectionContainer>
<SectionContainer title={"About Me"}><p>test</p></SectionContainer>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
