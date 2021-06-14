<script lang="ts">
    export let title: string
</script>

<div class="container">
    <p>{title}</p>
    <slot></slot>
</div>

<style>
    .container {
        position: relative;
        margin-top: 2rem;
        border-top: 1px solid grey;
    }
    p {
        position: relative;
        top: -25px;
        width: max-content;
        padding: 1rem;
        background: white;
        margin: auto;
    }
</style>