<script lang="ts">
	export let data;

	const { user } = data;
</script>

<div>
	<h1>Account</h1>
	<p>Welcome, {user.name}</p>
</div>

<form action="?/logout" method="post">
	<button type="submit">Logout</button>
</form>
