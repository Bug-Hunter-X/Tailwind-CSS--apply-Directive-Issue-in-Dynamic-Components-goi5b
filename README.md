# Tailwind CSS @apply Directive Issue in Dynamic Components

This repository demonstrates a bug related to Tailwind CSS's `@apply` directive when used within dynamically generated or conditionally rendered components.  The issue arises because Tailwind's JIT compiler might not correctly process `@apply` directives during runtime.

## Bug Description

When using `@apply` inside a component that is conditionally rendered or dynamically created, the expected styles might not be applied. This often occurs in frameworks like Next.js or Nuxt.js.

## How to Reproduce

1. Clone the repository.
2. Install dependencies: `npm install`
3. Run the development server (instructions may vary depending on the framework).
4. Observe the unexpected styling behavior in the dynamically rendered component.

## Solution

The provided solution addresses this issue by using a different approach to apply styles to conditionally rendered components, avoiding runtime processing of the `@apply` directive.

## Contributing

Contributions are welcome!