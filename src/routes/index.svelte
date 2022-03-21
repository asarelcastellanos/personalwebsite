<script>
    import Introduction from "../components/introduction.svelte";
    import Projects from "../components/projects.svelte";
    import MetaImage form "../assets/metaimage.png"
</script>
<svelte:head>
    <!-- Primary Meta Tags -->
    <title>Asarel Castellanos's Personal Website</title>
    <meta name="title" content="Asarel Castellanos's Personal Website">
    <meta name="author" content="Asarel Castellanos">
    <meta name="description" content="I am a Front-End / Web / MEAN Stack Developer. Eager to apply classroom learning with knowledge gained in a technical environment. An active and passionate volunteer with a focus on building socially conscious technologies.">

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://asarelcastellanos.com">
    <meta property="og:title" content="Asarel Castellanos's Personal Website">
    <meta property="og:description" content="I am a Front-End / Web / MEAN Stack Developer. Eager to apply classroom learning with knowledge gained in a technical environment. An active and passionate volunteer with a focus on building socially conscious technologies.">
    <meta name="image" property="og:image" content={MetaImage}>

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://asarelcastellanos.com">    
    <meta property="twitter:title" content="Asarel Castellanos's Personal Website">
    <meta property="twitter:description" content="I am a Front-End / Web / MEAN Stack Developer. Eager to apply classroom learning with knowledge gained in a technical environment. An active and passionate volunteer with a focus on building socially conscious technologies.">
    <meta property="twitter:image" content={MetaImage}>
</svelte:head>

<Introduction />
<Projects/>