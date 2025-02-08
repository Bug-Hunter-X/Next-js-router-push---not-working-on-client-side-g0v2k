# Next.js router.push() Client-Side Navigation Issue

This repository demonstrates a common issue encountered when using the `router.push()` method in Next.js for client-side navigation.  The navigation works correctly during server-side rendering (SSR), but fails to redirect on client-side interactions. This is often due to improper use of `router.push()` within a component that might not have access to the router context during client-side hydration.