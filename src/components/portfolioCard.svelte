<script lang="ts">
    export let title: string
    export let description: string
    export let liveLink: string
</script>

<div class="card">
    <h2>{title}</h2>
    <p>{description}</p>

<div class="buttonContainer">
    <ul class="actions">
        <li><a href={liveLink} target="blank">Live Project</a></li>

    </ul>
</div>
</div>

<style>
    a {
        text-decoration: none;
        color: white;
        background: black;
        border-radius: 5px;
        padding: 1rem 2rem;
    }
    h2 {
        text-align: center;
    }
    p {
        text-align: left;
    }
    ul {
        list-style: none;
    }
    .actions {
        display: flex;
        justify-content: center;
    }
    .buttonContainer {
        padding: 2rem 1rem;
    }
    .card {
        border: 1px solid black;
        border-radius: 5px; 
    }
</style>