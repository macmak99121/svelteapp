<script>


	const customStrings = [elementName="Kexchoklad", elementName="Powerking", elementName="Kong Strong", elementName="Redbull" ];

	function showStrings()
	{
		window.alert("Här står det: " + document.getElementById("t4").innerHTML);
	}


</script>

<style>
	h1
	{
		color: purple;
	}
</style>


{#each customStrings as text}
	<p id="t4" on:click={()=>showStrings(this)}>{text}</p>
{/each}
