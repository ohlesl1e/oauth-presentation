<script>
	import Slide from "$lib/Slide.svelte";
	import Deck from "$lib/Deck.svelte";
	import Vizzu from "$lib/Vizzu.svelte";
	import { data } from "https://lib.vizzuhq.com/test/integration/test_data/infinite_data.js?client";
	import Title from "../pages/Title.svelte";
	import Bullets from "../pages/Bullets.svelte";
	import OneFigure from "../pages/OneFigure.svelte";
	import TwoFigures from "../pages/TwoFigures.svelte";
	import Yelp from "../pages/Yelp.svelte";
	import Google from "../pages/Google.svelte";
	import Demo from "../pages/Demo.svelte";
	import Flow from "../pages/Flow.svelte";
	import Start from "../pages/Start.svelte";
	import ImFlow from "../pages/ImFlow.svelte";
</script>

<Deck>
	<Slide>
		<Title />
	</Slide>

	<Slide>
		<OneFigure title="SAML" image="saml_flow.png" />
	</Slide>

	<Slide>
		<div class="flex flex-col h-screen justify-center">
			<h1
				class="font-sans font-black text-neutral-900 text-center text-8xl tracking-tight max-w-6/6 mx-auto my-8 leading-none"
			>
				OAuth
			</h1>
			<div class="flex flex-row justify-center">
				<div class="i-mdi-arrow-bottom-left-thin text-7xl mr-20" />
				<div class="i-mdi-arrow-bottom-right-thin text-7xl ml-20" />
			</div>
			<div class="flex flex-row justify-center">
				<span
					class="font-sans font-normal text-center text-5xl text-neutral-900 w-1/4 mt-8 leading-relaxed animate__animated op0 start-1:op100 start-1:animate__fadeInUp"
				>
					Open
				</span>
				<span
					class="font-sans font-normal text-center text-5xl text-neutral-900 w-1/4 mt-8 leading-relaxed animate__animated op0 start-2:op100 start-2:animate__fadeInUp"
				>
					Authorization
				</span>
			</div>
		</div>
	</Slide>

	<Slide>
		<Yelp />
	</Slide>

	<Slide>
		<OneFigure image="LogIn-Yelp.png" />
	</Slide>

	<Slide>
		<OneFigure image="Google-Accounts.png" />
	</Slide>

	<Slide>
		<OneFigure image="Google-Consent.png" />
	</Slide>

	<Slide>
		<OneFigure title="Delegated authorization" image="valet.png" />
	</Slide>

	<Slide>
		<Bullets
			title="OAuth 2.0 Terminology"
			bullets={[
				"Resource owner",
				"Client",
				"Authorization server",
				"Resource server",
				"Scope",
				"Redirect URI",
				"Consent",
				"Access token",
			]}
		/>
	</Slide>

	<Slide>
		<TwoFigures
			items={["Resource owner", "Client"]}
			images={[
				"https://api.iconify.design/mdi/account.svg?width=512",
				"yelp-logo.png",
			]}
		/>
	</Slide>

	<Slide>
		<TwoFigures
			items={["Authorization server", "Resource server"]}
			images={["auth-server.png", "res-server.png"]}
		/>
	</Slide>

	<Slide>
		<OneFigure title="Scope" image="scope.png" />
	</Slide>

	<Slide>
		<OneFigure title="Redirect URI" image="redirect.png" />
	</Slide>

	<Slide>
		<OneFigure title="Consent" image="auth-grant.png" />
	</Slide>

	<Slide>
		<OneFigure
			title="Access token"
			image="https://api.iconify.design/mdi/hand-coin-outline.svg?width=300"
		/>
	</Slide>

	<Slide>
		<Bullets
			title="OAuth 2.0 flow"
			bullets={[
				"Authorization code flow",
				"Implicit Flow",
				"Resource owner password credentials",
				"Client credentials",
			]}
			animated="true"
		/>
	</Slide>

	<Slide><Start /></Slide>

	<Slide><Flow /></Slide>

	<Slide><Start /></Slide>

	<Slide><ImFlow /></Slide>

	<Slide><Demo src="http://photoprint:4000" /></Slide>

	<Slide>
		<Bullets
			title="Use cases (pre-2014)"
			bullets={[
				"Delegated authorization (OAuth 2.0)",
				"Single sign-on (OAuth 2.0)",
				"Mobile app login (OAuth 2.0)",
			]}
			animated="true"
		/>
	</Slide>

	<Slide>
		<TwoFigures
			items={["Scope", "Identity"]}
			images={[
				"scope.png",
				"https://api.iconify.design/mdi/badge-account-outline.svg?height=200",
			]}
		/>
	</Slide>

	<Slide
		><OneFigure title="OpenID Connect" image="OpenID-Connect.png" />
	</Slide>

	<Slide><Start /></Slide>

	<Slide><Demo src="https://developers.google.com/oauthplayground" /></Slide>

	<Slide>
		<OneFigure
			title="Twitter OAuth API Keys Leaked"
			image="twitter_oauth.jpg"
		/>
	</Slide>

	<Slide><Google /></Slide>

	<Slide>
		<div
			class="flex flex-wrap justify-center mx-auto max-w-22/24 pt-20 h-screen"
		>
			<h1
				class="my-auto font-sans font-black text-neutral-900 text-9xl text-left tracking-tighter"
			>
				Thanks! any questions?
			</h1>
		</div>
	</Slide>
</Deck>
