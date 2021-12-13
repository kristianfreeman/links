<script>
	import Link from '../components/Link.svelte';
</script>

<div class="mx-auto max-w-xl flex flex-col justify-center items-center p-8">
  <a href="/twitter">
	  <img
	  	alt="Code with Kristian"
	  	class="rounded-full w-24 transition-all hover:scale-110 hover:border-4 hover:border-orange-400 mb-4"
	  	src="/kristian.png"
	  />
  </a>

	<h1 class="text-2xl mb-4 font-bold">Code with Kristian</h1>

	<div class="flex mb-8 space-x-8">
		<a class="hover:text-orange-400 transition-all" href="/twitter">
			<img alt="Twitter" class="w-8" src="/icons/twitter.gif" />
    </a>

		<a class="hover:text-orange-400 transition-all" href="/sub">
			<img alt="YouTube" class="w-8" src="/icons/youtube.gif" />
    </a>

		<a class="hover:text-orange-400 transition-all" href="/github">
			<img alt="GitHub" class="w-8" src="/icons/github.gif" />
    </a>
	</div>

	<div class="space-y-4 w-full">
		<Link
      icon="star"
      iconStyle="fill-current text-orange-400"
			text="Weekly videos on programming, dev career, and more"
			url="/sub"
		/>

		<Link
      icon="video"
			text="Build persistent data-driven apps with Workers KV"
			url="https://egghead.io/courses/build-data-driven-applications-on-the-edge-with-workers-and-workers-kv-4932f3ea"
		/>

		<Link
      icon="book-open"
			text="Build Web3 Apps on Cloudflare"
			url="https://blog.cloudflare.com/get-started-web3/"
		/>

		<Link
      icon="video"
			text="Learn how to build a real-time chat app with Supabase"
			url="https://egghead.io/courses/build-a-real-time-data-syncing-chat-application-with-supabase-and-next-js-84e58958"
		/>

		<Link
      icon="video"
			text="Build APIs with Cloudflare Workers"
			url="https://egghead.io/courses/build-a-serverless-api-with-cloudflare-workers-d67ca551"
		/>

		<Link
      icon="video"
			text="My intro to Cloudflare Workers course"
			url="https://egghead.io/courses/introduction-to-cloudflare-workers-5aa3"
		/>
	</div>
</div>
