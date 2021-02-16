<script>
	import Button1 from "./Button1.svelte";
	import Button2 from "./Button2.svelte";
	import Button3 from "./Button3.svelte";
	
	function Click1() {
    alert("Привет, Мир!");
  }
	
	function Click2() {
    alert("Hello, World!");
  }
	
	function Click3() {
    alert("Hallo, Welt!");
  }
</script>

<Button1 on:click={Click1} />
<Button2 on:click={Click2} />
<br>
<br>
<Button3 on:click={Click3} />
