<template>
	<!-- This example requires Tailwind CSS v2.0+ -->
	<!-- NAVIGATION BAR -->
	<nav class="bg-gray-800">
		<div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
			<div class="relative flex items-center justify-between h-16">
				<div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
					<!-- Mobile menu button-->
					<button
						type="button"
						class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white"
						aria-controls="mobile-menu"
						aria-expanded="false"
					>
						<span class="sr-only">Open main menu</span>

						<!-- Icon when menu is open. -->
						<!-- Heroicon name: outline/x Menu open: "block", Menu closed: "hidden" -->
						<svg
							class="block h-6 w-6"
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 24 24"
							stroke="currentColor"
							aria-hidden="true"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M4 6h16M4 12h16M4 18h16"
							></path>
						</svg>

						<!-- Icon when menu is open. -->
						<!-- Heroicon name: outline/x Menu open: "block", Menu closed: "hidden" -->
						<svg
							class="hidden h-6 w-6"
							xmlns="http://www.w3.org/2000/svg"
							fill="none"
							viewBox="0 0 24 24"
							stroke="currentColor"
							aria-hidden="true"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M6 18L18 6M6 6l12 12"
							></path>
						</svg>
					</button>
				</div>
				<div
					class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start"
				>
					<div class="flex-shrink-0 flex items-center">
						<img
							class="block lg:hidden h-8 w-auto"
							src="https://tailwindui.com/img/logos/workflow-mark-indigo-500.svg"
							alt="Workflow"
						/>
						<img
							class="hidden lg:block h-8 w-auto"
							src="https://tailwindui.com/img/logos/workflow-logo-indigo-500-mark-white-text.svg"
							alt="Workflow"
						/>
					</div>
					<div class="hidden sm:block sm:ml-6">
						<div class="flex space-x-4">
							<!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
							<a
								href="#"
								class="bg-gray-900 text-white px-3 py-2 rounded-md text-sm font-medium"
								>What is Code Fast</a
							>
							<a
								href="#team"
								class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium"
								>Meet the Team</a
							>
							<a
								href="#"
								class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium"
								>Start Playing</a
							>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Mobile menu, show/hide based on menu state. -->
		<div class="sm:hidden" id="mobile-menu">
			<div class="px-2 pt-2 pb-3 space-y-1">
				<!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
				<a
					href="#"
					class="bg-gray-900 text-white block px-3 py-2 rounded-md text-base font-medium"
					>What is Code Fast</a
				>
				<a
					href="#team"
					class="text-gray-300 hover:bg-gray-700 hover:text-white block px-3 py-2 rounded-md text-base font-medium"
					>Meet the Team</a
				>
				<a
					href="#"
					class="text-gray-300 hover:bg-gray-700 hover:text-white block px-3 py-2 rounded-md text-base font-medium"
					>Start Playing</a
				>
			</div>
		</div>
	</nav>

	<!-- FIRST ROW -->
	<div class="bg-gray-800 h-5/6 mb-40 px-20">
		<div class="max-w-7xl mx-auto px-3 sm:px-6 lg:px-10 p-6">
			<img
				class="float-right"
				src="http://placeskull.com/450/400"
				alt="placeholder"
			/>
			<h1 class="text-white text-xl py-10 pl-3">Code Fast</h1>
			<p class="text-white pb-10 w-1/2">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat sit
				accusantium magnam, quasi deserunt voluptatibus!
			</p>
			<!-- h-12 px-6 m-2 text-lg text-indigo-100 transition-colors duration-150 bg-indigo-700 rounded-lg  hover:bg-indigo-800 -->
			<button
				class="inline-flex items-center bg-blue-500 hover:bg-blue-700 focus:shadow-outline text-white font-bold h-12 px-6 w-99 py-2 rounded-full"
			>
				Start Playing
				<svg
					class="w-5 h-5 ml-3 fill-current"
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 20 20"
					fill="currentColor"
				>
					<path
						fillrule="evenodd"
						d="M10.293 15.707a1 1 0 010-1.414L14.586 10l-4.293-4.293a1 1 0 111.414-1.414l5 5a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0z"
						cliprule="evenodd"
					></path>
					<path
						fillrule="evenodd"
						d="M4.293 15.707a1 1 0 010-1.414L8.586 10 4.293 5.707a1 1 0 011.414-1.414l5 5a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0z"
						cliprule="evenodd"
					></path>
				</svg>
			</button>
		</div>
	</div>

	<!-- CARD TITLE -->
	<div class="flex items-center justify-center h-20 pt-20 font-bold text-xl">
		<h2>What is Code Fast?</h2>
	</div>

	<!-- CARDS ROW -->
	<div
		class="flex items-center justify-center h-auto w-auto px-20 h-full pt-10 pb-20"
	>
		<div
			class="p-10 grid grid-cols-1 sm:grid-cols-1 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-5"
		>
			<!--Card 1-->
			<div class="rounded overflow-hidden shadow-lg">
				<img class="w-full" src="../assets/img/mountain.webp" alt="Mountain" />
				<div class="px-6 py-4">
					<div class="font-bold text-xl mb-2">Mountain</div>
					<p class="text-gray-700 text-base">
						Lorem ipsum dolor sit amet, consectetur adipisicing elit.
						Voluptatibus quia, nulla! Maiores et perferendis eaque,
						exercitationem praesentium nihil.
					</p>
				</div>
			</div>
			<!--Card 2-->
			<div class="rounded overflow-hidden shadow-lg">
				<img class="w-full" src="../assets/img/river.jpg" alt="River" />
				<div class="px-6 py-4">
					<div class="font-bold text-xl mb-2">River</div>
					<p class="text-gray-700 text-base">
						Lorem ipsum dolor sit amet, consectetur adipisicing elit.
						Voluptatibus quia, nulla! Maiores et perferendis eaque,
						exercitationem praesentium nihil.
					</p>
				</div>
			</div>
			<!--Card 3-->
			<div class="rounded overflow-hidden shadow-lg">
				<img class="w-full" src="../assets/img/forest.jpg" alt="Forest" />
				<div class="px-6 py-4">
					<div class="font-bold text-xl mb-2">Forest</div>
					<p class="text-gray-700 text-base">
						Lorem ipsum dolor sit amet, consectetur adipisicing elit.
						Voluptatibus quia, nulla! Maiores et perferendis eaque,
						exercitationem praesentium nihil.
					</p>
				</div>
			</div>
		</div>
	</div>

	<!-- TEAM TITLE -->
	<div class="flex items-center justify-center pt-8 font-bold text-xl">
		<h2 id="team">Meet the team</h2>
	</div>

	<!-- CARDS FOR TEAM -->
	<div
		class="flex items-center justify-center h-auto w-auto px-20 h-full pt-16 pb-20"
	>
		<div
			class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-2 xl:grid-cols-2 gap-4"
		>
			<div
				class="flex flex-col items-center justify-center bg-white p-4 shadow-lg rounded-lg"
			>
				<div
					class="inline-flex shadow-lg border border-gray-200 rounded-full overflow-hidden h-40 w-40"
				>
					<img src="../assets/img/oscar.jpg" alt="" class="h-full w-full" />
				</div>
				<h2 class="mt-4 font-bold text-xl">Óscar Baeza</h2>
				<h6 class="mt-2 text-sm font-medium">Co-creator</h6>
				<p class="text-xs text-gray-500 text-center mt-3">
					Biotechnologist, then Omics Data Analist and now studying Front-End
					Developer.
				</p>
				<ul class="flex flex-row mt-4 space-x-2">
					<li>
						<a
							href="https://www.linkedin.com/in/%C3%B3scar-baeza/"
							target="_blank"
							class="flex items-center justify-center h-8 w-8 border rounded-full text-gray-800 border-gray-800"
						>
							<i class="fa fa-linkedin" aria-hidden="true"></i>
						</a>
					</li>
					<li>
						<a
							href="mailto:oscarmaremar@gmail.com"
							class="flex items-center justify-center h-8 w-8 border rounded-full text-gray-800 border-gray-800"
						>
							<i class="fas fa-envelope" aria-hidden="true"></i>
						</a>
					</li>
					<li>
						<a
							href="https://obaeza16.github.io/"
							target="_blank"
							class="flex items-center justify-center h-8 w-8 border rounded-full text-gray-800 border-gray-800"
						>
							<i class="fa fa-user-circle-o" aria-hidden="true"></i>
						</a>
					</li>
				</ul>
			</div>
			<div
				class="flex flex-col items-center justify-center bg-white p-4 shadow-lg rounded-lg"
			>
				<div
					class="inline-flex shadow-lg border border-gray-200 rounded-full overflow-hidden h-40 w-40"
				>
					<img
						src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;w=128&amp;h=128&amp;q=60&amp;facepad=2"
						alt=""
						class="h-full w-full"
					/>
				</div>
				<h2 class="mt-4 font-bold text-xl">Joselyn Cáceres</h2>
				<h6 class="mt-2 text-sm font-medium">Co-creator</h6>
				<p class="text-xs text-gray-500 text-center mt-3">
					Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab enim
					molestiae nulla.
				</p>
				<ul class="flex flex-row mt-4 space-x-2">
					<li>
						<a
							href="https://www.linkedin.com/in/joselyn-caceres/"
							target="_blank"
							class="flex items-center justify-center h-8 w-8 border rounded-full text-gray-800 border-gray-800"
						>
							<i class="fa fa-linkedin" aria-hidden="true"></i>
						</a>
					</li>
					<li>
						<a
							href="mailto:caceres.joselyn@gmail.com"
							class="flex items-center justify-center h-8 w-8 border rounded-full text-gray-800 border-gray-800"
						>
							<i class="fas fa-envelope" aria-hidden="true"></i>
						</a>
					</li>
					<li>
						<a
							href=""
							target="_blank"
							class="flex items-center justify-center h-8 w-8 border rounded-full text-gray-800 border-gray-800"
						>
							<i class="fa fa-user-circle-o" aria-hidden="true"></i>
						</a>
					</li>
				</ul>
			</div>
		</div>
	</div>

	<!-- BECOME A CODE FASTER -->
	<div class="bg-gray-800 h-auto py-24 px-10">
		<h1 class="flex items-center justify-center pt-15 font-bold text-xl">
			<button
				class="inline-flex items-center bg-blue-500 hover:bg-blue-700 focus:shadow-outline text-white font-bold h-12 px-6 w-99 py-2 rounded-full"
			>
				Become a Code Faster
				<svg
					class="w-5 h-5 ml-3 fill-current"
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 20 20"
					fill="currentColor"
				>
					<path
						fillrule="evenodd"
						d="M10.293 15.707a1 1 0 010-1.414L14.586 10l-4.293-4.293a1 1 0 111.414-1.414l5 5a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0z"
						cliprule="evenodd"
					></path>
					<path
						fillrule="evenodd"
						d="M4.293 15.707a1 1 0 010-1.414L8.586 10 4.293 5.707a1 1 0 011.414-1.414l5 5a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0z"
						cliprule="evenodd"
					></path>
				</svg>
			</button>
		</h1>
	</div>

	<!-- FOOTER -->
	<footer
		class="footer bg-gray-800 relative border-b-2 border-blue-700 w-full text-center pt-1 px-60"
	>
		<div class="container mx-auto px-6">
			<div class="sm:flex sm:mt-8">
				<div
					class="mt-8 sm:mt-0 sm:w-full sm:px-8 flex flex-col md:flex-row justify-between"
				>
					<div class="flex flex-col">
						<!-- <span class="font-bold text-white uppercase mb-2"
								>Footer header 1</span
							> -->
						<span class="my-2"
							><a
								href="mailto:oscarmaremar@gmail.com?subject=Contacting from Code Fast&amp;cc=caceres.joselyn@gmail.com"
								class="text-white text-md hover:text-blue-500"
								>Contact Us</a
							></span
						>
					</div>
					<div class="flex flex-col">
						<!-- <span class="font-bold text-white uppercase mt-4 md:mt-0 mb-2"
								>Footer header 2</span
							> -->
						<span class="my-2"
							><a
								href="./legal.html"
								class="text-white text-md hover:text-blue-500"
								>Legal Stuff</a
							></span
						>
					</div>
					<div class="flex flex-col">
						<!-- <span class="font-bold text-white uppercase mt-4 md:mt-0 mb-2"
								>Footer header 3</span
							> -->
						<span class="my-2"
							><a href="#" class="text-white text-md hover:text-blue-500"
								>Reviews</a
							></span
						>
					</div>
				</div>
			</div>
		</div>

		<div class="container mx-auto px-6">
			<div class="mt-10 border-t-2 border-gray-300 flex flex-col items-center">
				<div class="sm:w-2/3 text-center py-6">
					<p class="text-sm text-white font-bold mb-2">
						© 2021 by Joselyn CÁCERES &amp; Óscar BAEZA
					</p>
				</div>
			</div>
		</div>
	</footer>
</template>

<script>
// @ is an alias to /src
import { library } from "@fortawesome/fontawesome-svg-core";
import { faFontAwesome } from "@fortawesome/free-brands-svg-icons";

library.add(faFontAwesome);
</script>
