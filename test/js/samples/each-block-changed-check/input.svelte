{#each comments as comment, i}
	<div class='comment'>
		<strong>{i}</strong>

		<span class='meta'>
			{comment.author} wrote {elapsed(comment.time, time)} ago:
		</span>

		{@html comment.html}
	</div>
{/each}

<p>{foo}</p>