<script>
    let props = $props();
</script>

<img src={`src/lib/assets/${props.link}`} class="h-64 mt-1 justify-self-center" alt="Robot" />
<div class="italic justify-self-center mt-1 opacity-80">{props.text}</div>