<script lang="ts">
  let liked = [
    "Coding",
    "Neovim",
    "Linux",
    "Blahaj",
    "Ghostty",
    "Nix",
  ];
</script>

<div id="welcome">
	<h1>Hi, I'm Kyle!</h1>
	<h2>Welcome to codingcorner.dev!</h2>
</div>
<p>I'm a 16 year old developer, hack clubber, and student from New Zealand.</p>
<p>I like:</p>
<ul>
  {#each liked as item}
    <li>{item}</li>
  {/each}
  <li><button>88x31 Buttons</button></li> <!-- TODO: Make this open a thing with the buttons -->
</ul>
