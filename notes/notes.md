# Tech Stack & Tooling

## Next.js

<!-- TODO: learn Next.js -->

Provides a lot of the boilerplate and tooling needed for building a React app including the config
for setting up server side rendering.

Provides a thing called `getInitialProps` which is a more clear interface to tell SSR to wait on the
component to resolve props before returning a rendered component.

### Structure

- components - all our (TBD) components
- pages - the actual pages for our application
- \_app.js - is an application level wrapper and allows us to persist state across each page.
