<template>
	<nav class="navbar">
		<div class="container">
			<div class="navbar-brand">
				<router-link class="navbar-item is-5" to="/">
					<img src="../assets/kcp.png" alt="Logo">
					<span class="is-hidden-touch">&nbsp;Klasa Community Plugins</span>
					<span class="is-hidden-desktop">&nbsp;KCP</span>
				</router-link>

				<router-link class="navbar-item is-hidden-desktop pull-end" to="/docs">
					<span class="icon">
						<i class="fa fa-lg fa-book"></i>
					</span>
				</router-link>

				<a class="navbar-item is-hidden-desktop" href="https://github.com/klasacommunityplugins" target="_blank">
					<span class="icon">
						<i class="fab fa-lg fa-github"></i>
					</span>
				</a>

				<a class="navbar-item is-hidden-desktop" href="https://discord.gg" target="_blank">
					<span class="icon">
						<i class="fab fa-lg fa-discord"></i>
					</span>
				</a>
			</div>

			<div class="navbar-end">
				<router-link class="navbar-item is-hidden-touch" to="/docs">
					<span class="icon"><i class="fa fa-lg fa-book"></i></span>Docs
				</router-link>

				<a class="navbar-item is-hidden-touch" href="https://github.com/klasacommunityplugins" target="_blank">
					<span class="icon">
						<i class="fab fa-lg fa-github"></i>
					</span>
					<span> Github </span>
				</a>

				<a class="navbar-item is-hidden-touch" href="https://discord.gg" target="_blank">
					<span class="icon">
						<i class="fab fa-lg fa-discord"></i>
					</span>
					<span> Discord </span>
				</a>
			</div>
		</div>
	</nav>
</template>

<script>
export default {
	name: 'Navbar'
};
</script>

<style lang="scss" scoped>
    .navbar-item {
        margin-right: unset;
        .icon {
            justify-content: unset;
            margin-right: 0.15em;
        }
    }

    .pull-end {
        margin-left: auto;
    }
</style>
