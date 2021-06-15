<script lang="ts">
    import Portfolio from '../components/portfolio.svelte'
import Header from '../components/header.svelte'
    import Hero from '../components/hero.svelte'
    import SectionContainer from '../components/sectionContainer.svelte'
    import SkillsSection from '../components/skillsSection.svelte'
    import AboutMe from '../components/aboutMe.svelte'
</script>


<Header />
<Hero />
<SectionContainer title={"Skills"}><SkillsSection /></SectionContainer>
<SectionContainer title={"My Portfolio"}><Portfolio /></SectionContainer>
<SectionContainer title={"About Me"}><AboutMe /></SectionContainer>

