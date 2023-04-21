---
title: Tailwind center text layout 
description: How to center text in the middle of the screen using Tailwind CSS
tags: tailwindcss, frontend, how-to
date: 2023-04-21
pinned: false
unlisted: false
draft: false
toc: false
showHeader: true
showTitle: true
showDescription: true
showMeta: true
---

The following code snippets can be used to achieve a result similar to the screenshot below:

![img](/img/tailwind-center-layout-example.png)

To preview this, visit [stamos.xyz](https://stamos.xyz)

## HTML

```html
<div className="flex min-h-screen items-center justify-center bg-white dark:bg-black">
	<div className="mx-auto max-w-2xl text-center">
		<p className="text-black dark:text-white">
			This text will be in the center of the screen
		</p>
    </div>
</div>
```

## React

```ts
export default function Layout() {
	return (
		<div className="flex min-h-screen items-center justify-center bg-white dark:bg-black">
			<div className="mx-auto max-w-2xl text-center">
				<p className="text-black dark:text-white">
					This text will be in the center of the screen
				</p>
    		</div>
		</div>
	)
}
```