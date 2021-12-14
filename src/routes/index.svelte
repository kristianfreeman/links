<script>
	import Link from '../components/Link.svelte';
</script>

<div class="mx-auto max-w-xl flex flex-col justify-center items-center px-2 md:px-8 py-8">
  <a href="https://kristianfreeman.com/twitter" tabindex="-1">
	  <img
	  	alt="Code with Kristian"
	  	class="rounded-full w-24 transition-all hover:scale-125 hover:border-4 hover:border-orange-400 mb-4"
	  	src="/kristian.png"
	  />
  </a>

	<h1 class="text-2xl mb-4 font-bold">Code with Kristian</h1>

	<div class="flex mb-8 space-x-8">
		<a class="focus:scale-125 hover:scale-125 transition-all" href="https://kristianfreeman.com/twitter">
			<img alt="Twitter" class="w-8" src="/icons/twitter.gif" />
    </a>

		<a class="focus:scale-125 hover:scale-125 transition-all" href="https://kristianfreeman.com/sub">
			<img alt="YouTube" class="w-8" src="/icons/youtube.gif" />
    </a>

		<a class="focus:scale-125 hover:scale-125 transition-all" href="https://kristianfreeman.com/github">
			<img alt="GitHub" class="w-8" src="/icons/github.gif" />
    </a>
	</div>

	<div class="w-full mt-4 space-y-6">
		<Link
      icon="star"
      iconStyle="fill-current text-orange-400"
			text="Weekly videos on programming & dev careers"
			url="https://kristianfreeman.com/sub"
		/>

		<Link
      icon="send"
			text="My (infrequent) newsletter for developers"
			url="https://www.getrevue.co/profile/signalnerve"
		/>

		<Link
      icon="video"
			text="Learn Recoil.js in 10 Minutes"
			url="https://www.youtube.com/watch?v=BchtCWxs7sA"
		/>

		<Link
      icon="video"
			text="GitHub Actions Tutorial"
			url="https://www.youtube.com/watch?v=J4EhgEskSZA&t=35s"
		/>
	</div>

  <h2 class="font-semibold text-xl mt-12 mb-8">Courses</h2>

	<div class="w-full space-y-6">
		<Link
      icon="video"
			text="Intro to Cloudflare Workers"
			url="https://egghead.io/courses/introduction-to-cloudflare-workers-5aa3"
		/>

		<Link
      icon="video"
			text="Build APIs with Cloudflare Workers"
			url="https://egghead.io/courses/build-a-serverless-api-with-cloudflare-workers-d67ca551"
		/>

		<Link
      icon="video"
			text="Build a real-time chat app with Supabase"
			url="https://egghead.io/courses/build-a-real-time-data-syncing-chat-application-with-supabase-and-next-js-84e58958"
		/>

		<Link
      icon="video"
			text="Build persistent data-driven apps with Workers KV"
			url="https://egghead.io/courses/build-data-driven-applications-on-the-edge-with-workers-and-workers-kv-4932f3ea"
		/>

	</div>

  <h2 class="font-semibold text-xl mt-12 mb-8">Open Source</h2>

	<div class="w-full space-y-6">
		<Link
      icon="link"
			text="Lilredirector: bulk redirect tool for Cloudflare Workers"
			url="https://github.com/signalnerve/lilredirector"
		/>

		<Link
      icon="code"
			text="Apollo GraphQL Server for Cloudflare Workers"
			url="https://github.com/signalnerve/workers-graphql-server"
		/>

		<Link
      icon="cloud"
			text="GitHub Actions Weather Bot"
			url="https://github.com/signalnerve/github-actions-weather-bot"
		/>

		<Link
      icon="database"
			text="Recoil.js example project"
			url="https://github.com/signalnerve/recoiljs-demo"
		/>
	</div>
</div>
