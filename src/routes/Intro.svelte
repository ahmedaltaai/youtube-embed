<script>
  import Youtube from "$lib/Youtube.svelte";
  import Prism from "./Prism.svelte";
</script>

<h1>Youtube Video Embed</h1>

<p>
  This provides a fast way to embed youtube videos since it loads the youtube
  thumbnail istead of the iframe. It loads the iframe and starts playing upong
  clicking the play button.
</p>

<h2>Default</h2>
<Youtube id="EBtsu6naB8g" />

<Prism code={`<Youtube id="EBtsu6naB8g" />`} />
