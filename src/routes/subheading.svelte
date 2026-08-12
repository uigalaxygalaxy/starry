<script>
    let { id, text } = $props();
</script>

<div id={id}></div>
<div class="text-4xl text-(--primary) font-[Arial_nova] mt-5 ml-2 textGlow">
    {text}
</div>