<script>
    export let seoValue;
</script>

<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<title>{seoValue.title}</title>
<meta name="title" content={seoValue.title} />
<meta name="description" content={seoValue.description} />
<link rel="icon" href={seoValue.icon} />
<meta property="og:title" content={seoValue.title} />
<meta property="og:url" content={seoValue.url} />
<meta property="og:type" content="website" />
<meta property="og:description" content={seoValue.description} />
<meta property="og:image" content={seoValue.og_image ? seoValue.og_image : seoValue.image} />
<meta name="date" content={seoValue.date} />
<meta property="article:published_time" content={seoValue.published_time} />
