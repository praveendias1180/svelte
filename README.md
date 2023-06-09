# Svelte KIT

![](images/kit.png)

![](images/sri-lanka.png)

# Svelte

https://svelte.dev/tutorial/basics

![](images/start.png)


## Creating a project

```bash
npm create svelte@latest
npm create svelte@latest my-app
```

## Developing

```bash
npm run dev
npm run dev -- --open
```

## Building

```bash
npm run build
npm run preview
```

![](images/svelte-setup.png)


# Hello Svelte!

![](images/hello.png)



# $: doubled = count * 2

> Don't worry if this looks a little alien. It's valid (if unconventional) JavaScript, which Svelte interprets to mean 're-run this code whenever any of the referenced values change'. Once you get used to it, there's no going back.

![](images/no-back.png)

# {#if user.loggedIn}

![](images/svelte-if.png)

```
{#if user.loggedIn}
	<button on:click={toggle}>
		Log out
	</button>
{:else}
	<button on:click={toggle}>
		Log in
	</button>
{/if}
```


> A # character always indicates a block opening tag. A / character always indicates a block closing tag. A : character, as in {:else}, indicates a block continuation tag. Don't worry — you've already learned almost all the syntax Svelte adds to HTML.