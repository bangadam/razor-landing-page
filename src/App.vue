<script setup>
import ArrowRightIcon from "./icons/arrow-right.svg";
import AppleIcon from "./icons/apple.svg";
import PlayStoreIcon from "./icons/play-store.svg";
</script>

<template>
	<div class="relative bg-gray-800 w-full min-h-screen text-white">
		<img
			src="/img/circle.svg"
			alt=""
			class="top-0 left-0 absolute opacity-40 -translate-x-1/4 -translate-y-1/4"
		/>

		<div class="right-0 absolute inset-y-0 bg-gray-900 w-2/5"></div>

		<div class="relative mx-auto px-4 pt-8 max-w-7xl">
			<nav class="flex justify-between items-center">
				<div class="flex items-center gap-32">
					<a href="#" class="font-bold text-2xl">Razor</a>
					<ul class="flex items-center gap-12 font-medium text-gray-500">
						<li><a href="#" class="hover:text-white">Product</a></li>
						<li><a href="#" class="hover:text-white">Resources</a></li>
						<li><a href="#" class="hover:text-white">Support</a></li>
						<li><a href="#" class="hover:text-white">Pricing</a></li>
						<li><a href="#" class="hover:text-white">Blog</a></li>
					</ul>
				</div>

				<div class="flex items-center gap-4 font-medium text-gray-500">
					<a href="#" class="hover:text-white">Sign In</a>
					<a href="#" class="relative hover:text-white">
						<span>Request Demo</span>
						<img
							src="/img/decoration.svg"
							alt=""
							class="left-0 absolute w-32"
						/>
					</a>
				</div>
			</nav>
			<div class="grid grid-cols-2 pt-6">
				<div class="pr-24 max-w-xl">
					<div
						class="flex items-center gap-6 border-gray-700 pt-2 border-t w-36"
					>
						<span class="font-normal text-sm text-teal-500">
							Sales@razor.uk
						</span>
						<ArrowRightIcon class="w-4 h-4 text-teal-500" />
					</div>
					<div class="pt-16">
						<span>&#8212; Get the App</span>
						<h1
							class="bg-clip-text bg-gradient-to-br from-blue-400 to-emerald-400 pt-6 font-bold text-6xl text-transparent tracking-tight"
						>
							Enter your email <br />
							&#8212; We'll send you a download link
						</h1>
						<img src="/img/decoration.svg" alt="" class="-mt-2 w-96" />
						<div
							class="flex items-center shadow-glow focus-within:shadow-teal-500/40 mt-10 rounded-xl transition-shadow ease-out"
						>
							<input
								type="text"
								class="flex-1 border-2 border-gray-700 bg-gray-900 px-8 py-4 border-r-0 rounded-l-xl leading-6 focus:outline-none"
								placeholder="Sales@dstudio.digital"
							/>
							<button
								class="border-2 border-gray-700 bg-teal-500 px-8 py-4 border-l-0 rounded-r-xl font-bold text-gray-900 text-lg leading-6"
							>
								Get Link
							</button>
						</div>
						<p class="pt-8 font-normal text-gray-600 tracking-wide">
							By signing up, I agree to the Razor
							<a href="#" class="text-gray-500 underline">Privacy Policy</a> &
							<a href="#" class="text-gray-500 underline">Terms of Service</a>
						</p>
						<div class="flex items-center gap-4 pt-12">
							<button
								class="flex items-center gap-2 bg-gray-900 shadow-glow hover:shadow-teal-500/40 px-6 py-4 rounded-xl text-gray-500 transition hover:-translate-y-1 ease-out"
							>
								<PlayStoreIcon class="w-7 h-7" />
								Play Store
							</button>
							<button
								class="flex items-center gap-2 bg-gray-900 shadow-glow hover:shadow-teal-500/40 px-6 py-4 rounded-xl text-gray-500 transition hover:-translate-y-1 ease-out"
							>
								<AppleIcon class="w-7 h-7" />
								App Store
							</button>
						</div>
					</div>
				</div>
				<div class="pt-10">
					<div class="flex justify-center gap-8">
						<img
							src="/img/screen-1.png"
							alt=""
							class="w-64 h-full animate-hover"
						/>
						<img
							src="/img/screen-2.png"
							alt=""
							class="pt-20 w-64 h-full animate-hover"
						/>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>
