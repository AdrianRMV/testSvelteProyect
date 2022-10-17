<script>
    import { Router, Route, Link, link } from 'svelte-routing';
	import Login from './views/Login.svelte'
	import Home from './views/Home.svelte'
</script>

<Router>
	<div>
		<Route path="/" component={Login} />
		<Route path="/home" component={Home} />
	</div>
</Router>