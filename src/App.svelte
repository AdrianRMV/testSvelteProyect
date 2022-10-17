<script>
    import { Router, Route, Link, link } from 'svelte-routing';
	import Login from './views/Login.svelte'
	import Home from './views/Home.svelte'
</script>

<Router>
	<nav>
		<Link to='/'>Login</Link>
		<Link to='/home'>Home</Link>
	</nav>
	<div>
		<Route path="/" component={Login} />
		<Route path="/home" component={Home} />
	</div>
</Router>