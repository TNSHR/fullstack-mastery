# Full-Stack Web Development Mastery

## Master Syllabus --- MERN + PostgreSQL

**Learner level:** Absolute beginner\
**Daily study time:** 1 hour\
**Weekly cadence:** 6 study days + 1 rest/revision buffer day\
**Environment:** Ubuntu Linux + VS Code\
**Primary goal:** Job readiness, freelancing, and building/deploying
personal SaaS products\
**Learning approach:** Concepts → why it matters → how it works → guided
code → independent practice → debugging → notes → interview checkpoint

> This is the master syllabus and course source of truth. Follow it in
> order. A day is a study session, not necessarily a calendar day. At
> one hour per day, the full course is a long-term journey. Move forward
> based on demonstrated understanding, not speed. Web development
> evolves, so use current stable versions and official documentation
> when a phase begins.

------------------------------------------------------------------------

## Course Rules and Definition of Done

For every lesson:

1.  **Concept:** Explain the idea in beginner-friendly language.
2.  **Why:** Identify the problem it solves and when it is useful.
3.  **How:** Explain the execution flow and important details.
4.  **Demonstration:** Write and run a small example.
5.  **Independent practice:** Complete a task without copying the full
    solution.
6.  **Debugging:** Inspect at least one likely error or unexpected
    result.
7.  **Notes:** Record definitions, examples, commands, mistakes, and
    takeaways.
8.  **Interview checkpoint:** Answer questions in your own words.
9.  **Progress gate:** Fix important gaps before advancing.

### Weekly rhythm

-   **Days 1--4:** Learn and practice new concepts.
-   **Day 5:** Apply concepts in a small feature or mini-project.
-   **Day 6:** Review, debug, write notes, and complete checkpoint.
-   **Day 7:** Rest or catch up. Do not count it as a required study
    day.

### Definition of done for a phase

-   All listed topics have been studied.
-   Exercises and the phase assignment are complete.
-   The project runs locally and has a useful README.
-   Important bugs have been diagnosed rather than hidden.
-   Notes have been saved in the course repository.
-   The learner can explain the main concepts without reading the notes.
-   The checkpoint has been reviewed and gaps have been addressed.

------------------------------------------------------------------------

# Phase 0 --- Computer, Internet, Terminal, and Web Foundations

**Estimated study sessions:** 7

## Day 1 --- What web development is and how the web works

-   Understand websites versus web applications.
-   Learn frontend, backend, database, client, and server.
-   Trace a simple browser → server → response flow.
-   Understand browser rendering at a high level.
-   Practical: create the course workspace and `notes.md`.
-   Checkpoint: explain frontend, backend, database, and the
    request/response idea.

## Day 2 --- Files, folders, paths, and terminal basics

-   Files versus directories; file extensions and hidden files.
-   Absolute paths, relative paths, home directory, and `~`.
-   Commands: `pwd`, `ls`, `cd`, `mkdir`, `touch`, `cp`, `mv`, `cat`.
-   Safe use of `rm`; understand before deleting.
-   Practical: create a structured practice directory and move/copy
    files.
-   Debugging: diagnose "No such file or directory" and wrong-directory
    mistakes.

## Day 3 --- Linux environment and developer tools

-   What an operating system does; processes and permissions at a
    beginner level.
-   Commands: `whoami`, `uname -a`, `clear`, `man`, `which`, `file`.
-   Install/use VS Code, open a folder, edit and save a file.
-   Learn the integrated terminal and editor basics.
-   Practical: create, edit, and inspect a Markdown file.
-   Checkpoint: explain the difference between a terminal, shell,
    editor, and operating system.

## Day 4 --- Internet, DNS, IP addresses, ports, and hosting

-   Internet versus the Web.
-   IP address, domain name, DNS lookup, router, ISP, and server.
-   Ports and why different services use different ports.
-   Localhost, `127.0.0.1`, and `localhost`.
-   Practical: inspect a domain and identify its parts.
-   Checkpoint: describe how a browser finds a server.

## Day 5 --- URL, HTTP, HTTPS, requests, and responses

-   URL anatomy: scheme, domain, port, path, query string, fragment.
-   HTTP methods: GET, POST, PUT, PATCH, DELETE.
-   Status codes: 2xx, 3xx, 4xx, 5xx; common examples.
-   Request headers, response headers, body, JSON, and content types.
-   HTTPS and TLS at a conceptual level.
-   Practical: use browser DevTools Network tab and
    `curl -I https://example.com`.
-   Debugging: distinguish DNS, connection, HTTP, and application
    errors.

## Day 6 --- Browser DevTools and basic troubleshooting

-   Elements, Console, Network, Sources, and responsive device tools.
-   Inspect a request, status code, headers, and response.
-   Understand cache and hard refresh at a high level.
-   Read an error message carefully and reproduce a problem.
-   Practical: inspect a public webpage and record observations.
-   Checkpoint: explain what the browser sends and what it receives.

## Day 7 --- Phase 0 review and checkpoint

-   Review vocabulary and the request/response flow.
-   Re-run terminal commands without notes.
-   Draw the browser → internet/DNS → server → response flow.
-   Create `phase-0/README.md` with notes and lessons learned.
-   Checkpoint: explain five terms and troubleshoot one intentionally
    created path error.

**Phase assignment:** A documented developer workspace with a `notes.md`
file, terminal command notes, and a simple web request investigation.

------------------------------------------------------------------------

# Phase 1 --- HTML Foundations and Semantic Web Pages

**Estimated study sessions:** 12

## Day 1 --- HTML document structure

-   What HTML is and what it is not.
-   Tags, elements, attributes, nesting, and parent/child relationships.
-   `<!doctype html>`, `html`, `head`, `body`, title, charset, viewport.
-   Practical: create `index.html` and open it in a browser.

## Day 2 --- Text, headings, paragraphs, and semantic meaning

-   Headings, paragraphs, emphasis, strong importance, quotations, and
    code.
-   Why heading levels should represent document structure.
-   Whitespace and browser defaults.
-   Practical: create a structured personal introduction page.

## Day 3 --- Links, paths, and navigation

-   Absolute and relative URLs.
-   Internal links, external links, fragments, and `target`.
-   Safe use of new tabs and meaningful link text.
-   Practical: create a three-page mini-site with working navigation.

## Day 4 --- Images and media

-   Image sources, `alt` text, dimensions, and formats.
-   Relative asset paths and common broken-image causes.
-   Audio/video basics and captions overview.
-   Practical: add images with useful alternative text.

## Day 5 --- Lists and tables

-   Ordered and unordered lists; nested lists.
-   Table structure, headings, captions, rows, and cells.
-   Appropriate versus inappropriate use of tables for layout.
-   Practical: create a course schedule table and a nested topic list.

## Day 6 --- Forms: first principles

-   `form`, `label`, `input`, `button`, `textarea`, `select`.
-   Input types, `name`, `value`, placeholders, and labels.
-   GET versus POST form behavior conceptually.
-   Practical: build a contact form without backend submission.

## Day 7 --- Form validation and controls

-   `required`, `min`, `max`, `minlength`, `maxlength`, `pattern`.
-   Radio buttons, checkboxes, select options, and field grouping.
-   Client-side validation limits; server validation will be learned
    later.
-   Practical: build a registration form with sensible validation.

## Day 8 --- Semantic HTML and page landmarks

-   `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`.
-   Generic containers versus semantic elements.
-   Accessible landmarks and logical structure.
-   Practical: convert a non-semantic page into semantic HTML.

## Day 9 --- Accessibility foundations

-   Keyboard navigation, focus, labels, alt text, heading order.
-   Accessible names and why color alone must not convey meaning.
-   Introductory ARIA guidance: prefer native HTML when possible.
-   Practical: test a form and navigation using only the keyboard.

## Day 10 --- Metadata, SEO, and browser behavior

-   Title, description, viewport, favicon, and social metadata concepts.
-   Search indexing fundamentals and meaningful page titles.
-   HTML entities and character encoding.
-   Practical: add metadata to the mini-site.

## Day 11 --- Debugging and mini-project build

-   Validate nesting and fix missing attributes or broken paths.
-   Inspect browser rendering and console/network errors.
-   Build a multi-page personal profile or course information site.
-   Write a short README describing pages and features.

## Day 12 --- Revision and interview checkpoint

-   Explain tags versus attributes and semantic versus generic HTML.
-   Explain labels, `alt`, form names, and required validation.
-   Rebuild a simple page from a written specification.
-   Review and fix all checkpoint gaps.

**Phase assignment:** Accessible, semantic, multi-page personal website
with navigation, images, a table, and a validated form.

------------------------------------------------------------------------

# Phase 2 --- CSS, Layout, Responsive Design, and UI Fundamentals

**Estimated study sessions:** 18

## Day 1 --- CSS introduction

-   Inline, internal, and external CSS; why external stylesheets are
    preferred.
-   Selectors, declarations, properties, values, and comments.
-   Practical: connect `styles.css` to the HTML project.

## Day 2 --- Selectors and the cascade

-   Element, class, ID, attribute, combinator, and pseudo-class
    selectors.
-   Cascade, specificity, inheritance, source order, and `!important`.
-   Debug styles using browser DevTools.

## Day 3 --- Colors, units, and typography

-   Hex, RGB, HSL; contrast and design consistency.
-   `px`, `%`, `em`, `rem`, `vw`, and `vh`.
-   Font families, line height, weight, spacing, and readable line
    length.
-   Practical: create a small design token palette.

## Day 4 --- The box model

-   Content, padding, border, margin, `box-sizing`.
-   Width constraints, overflow, margin collapsing overview.
-   Practical: debug an element that is unexpectedly too wide.

## Day 5 --- Display and normal document flow

-   `block`, `inline`, `inline-block`, `none`.
-   Normal flow, replaced elements, overflow, and visibility
    differences.
-   Practical: build a navigation row and card list.

## Day 6 --- Positioning and stacking

-   `static`, `relative`, `absolute`, `fixed`, `sticky`.
-   Containing blocks, `z-index`, and stacking context basics.
-   Practical: create a sticky header and positioned badge.

## Day 7 --- Flexbox

-   Main axis, cross axis, wrapping, alignment, gaps, and sizing.
-   `flex-grow`, `flex-shrink`, `flex-basis`, and common pitfalls.
-   Practical: responsive navigation and profile cards.

## Day 8 --- CSS Grid

-   Grid tracks, columns, rows, gaps, `fr`, `minmax`, and repeat.
-   Auto-placement and responsive card grids.
-   Practical: create a dashboard layout.

## Day 9 --- Responsive design

-   Mobile-first design, media queries, breakpoints, fluid sizing.
-   Responsive images and overflow prevention.
-   Practical: adapt one page to mobile, tablet, and desktop.

## Day 10 --- Pseudo-classes and pseudo-elements

-   `:hover`, `:focus-visible`, `:checked`, `:disabled`, `::before`,
    `::after`.
-   Focus styles and keyboard usability.
-   Practical: style form states and interactive links.

## Day 11 --- Backgrounds, borders, shadows, and effects

-   Gradients, border radius, box shadows, object fit/position.
-   Transitions, transforms, and restrained animation.
-   Respect reduced-motion preferences.

## Day 12 --- Forms and component styling

-   Input states, validation feedback, buttons, field spacing.
-   Consistent component sizes and accessible focus.
-   Practical: create reusable form styles.

## Day 13 --- CSS variables and design systems

-   Custom properties, tokens, theme values, and reusable patterns.
-   Naming conventions and avoiding duplicated styles.
-   Practical: implement a light theme with shared variables.

## Day 14 --- Tailwind CSS introduction

-   Utility-first styling and responsive/state prefixes.
-   Reusable patterns and component extraction.
-   Learn when plain CSS is clearer; do not treat a framework as a
    replacement for CSS knowledge.

## Day 15 --- UI accessibility and visual polish

-   Contrast, readable spacing, focus indicators, responsive navigation.
-   Touch targets and reduced-motion considerations.
-   Practical: audit the portfolio UI.

## Day 16 --- Debugging and refactoring

-   Inspect computed styles and box model.
-   Find specificity conflicts and overflow issues.
-   Remove duplicated rules and improve naming.

## Day 17 --- Build the responsive project

-   Create a landing page with hero, feature cards, navigation, form,
    and footer.
-   Use responsive Grid/Flexbox and consistent design tokens.
-   Test at multiple viewport sizes.

## Day 18 --- Revision and checkpoint

-   Explain cascade, specificity, box model, Flexbox, Grid, and media
    queries.
-   Recreate a layout from a reference or written description.
-   Debug three CSS issues and document the fixes.

**Phase assignment:** Responsive landing page plus dashboard layout with
accessible navigation, forms, reusable styles, and a project README.

------------------------------------------------------------------------

# Phase 3 --- JavaScript from Fundamentals to Advanced

**Estimated study sessions:** 36

## Day 1 --- JavaScript and the browser

-   What JavaScript does; browser engine and runtime overview.
-   Inline scripts versus external scripts; use `defer` appropriately.
-   Console output and first script.

## Day 2 --- Variables and values

-   `let`, `const`, naming, reassignment, and declaration.
-   Primitive values versus objects at a high level.
-   Strict mode and avoiding accidental globals.

## Day 3 --- Data types and type conversion

-   String, number, boolean, undefined, null, bigint, symbol overview.
-   `typeof`, explicit conversion, coercion, and `NaN`.
-   Practical: predict and verify type-conversion results.

## Day 4 --- Operators and comparisons

-   Arithmetic, assignment, comparison, logical, nullish coalescing,
    optional chaining.
-   Truthy/falsy values and strict equality.
-   Practical: implement a simple eligibility checker.

## Day 5 --- Conditions

-   `if`, `else`, nested conditions, and `switch`.
-   Guard clauses and avoiding deeply nested logic.
-   Practical: grade calculator.

## Day 6 --- Loops

-   `for`, `while`, `do...while`, `break`, and `continue`.
-   Loop boundaries and off-by-one errors.
-   Practical: number patterns and sum calculations.

## Day 7 --- Functions

-   Function declarations, expressions, arrow functions.
-   Parameters, arguments, return values, defaults.
-   Pure functions and side effects.

## Day 8 --- Scope and hoisting

-   Global, function, and block scope.
-   `var` versus `let`/`const`; temporal dead zone.
-   Practical: diagnose scope errors.

## Day 9 --- Arrays

-   Create, read, update, and remove items.
-   Indexes, `length`, mutation, and copying.
-   Practical: shopping list manager.

## Day 10 --- Array methods

-   `map`, `filter`, `find`, `some`, `every`, `reduce`, `forEach`.
-   Choosing a method based on intent.
-   Practical: summarize and filter a set of transactions.

## Day 11 --- Objects

-   Properties, methods, computed keys, shorthand.
-   References, mutation, copying, and nested structures.
-   Practical: model a student and course.

## Day 12 --- Destructuring, spread, and rest

-   Array/object destructuring and defaults.
-   Spread for shallow copies and rest parameters.
-   Practical: transform API-like data.

## Day 13 --- Strings, numbers, dates, and Math

-   Template literals, string methods, parsing and formatting.
-   Number precision caveats and introductory date handling.
-   Practical: format a receipt and calculate totals.

## Day 14 --- Errors and debugging

-   Syntax, runtime, and logic errors.
-   `try`, `catch`, `finally`, and throwing errors.
-   Breakpoints, stepping, scope inspection, and stack traces.

## Day 15 --- DOM fundamentals

-   Document tree, `querySelector`, `querySelectorAll`.
-   Text content, attributes, classes, and element creation.
-   Practical: update a page from JavaScript.

## Day 16 --- DOM events

-   Event listeners, event objects, bubbling, delegation.
-   Default browser actions and `preventDefault`.
-   Practical: interactive list.

## Day 17 --- Forms and browser input

-   Read form data, validate fields, display feedback.
-   Form submission and keyboard behavior.
-   Practical: client-side registration form.

## Day 18 --- Web storage

-   `localStorage`, `sessionStorage`, serialization with JSON.
-   Storage limits and why secrets must not be stored in browser
    storage.
-   Practical: persist a preference.

## Day 19 --- Modules

-   `import`, `export`, named/default exports.
-   Module scope and organizing code across files.
-   Practical: split a small application into modules.

## Day 20 --- Callbacks

-   Passing functions, callback patterns, asynchronous callback
    overview.
-   Callback composition and error handling.
-   Practical: implement reusable operation functions.

## Day 21 --- Promises

-   Pending, fulfilled, rejected states.
-   `.then`, `.catch`, `.finally`; promise chaining.
-   Practical: handle success and failure paths.

## Day 22 --- Async/await

-   Awaiting promises and using `try/catch`.
-   Sequential versus concurrent asynchronous work.
-   Practical: coordinate multiple asynchronous tasks.

## Day 23 --- Fetch and HTTP from JavaScript

-   `fetch`, request options, response body parsing.
-   HTTP errors versus network failures.
-   Practical: fetch and display public API data.

## Day 24 --- Event loop and asynchronous execution

-   Call stack, task queue, microtask queue, timers.
-   Promise callbacks and timer ordering.
-   Explain execution order with small experiments.

## Day 25 --- `this`, call context, and binding

-   Method calls, regular functions, arrow functions.
-   `call`, `apply`, `bind` and common mistakes.

## Day 26 --- Prototypes and classes

-   Prototype chain, inheritance, constructor functions.
-   Class syntax, instance/static members, inheritance trade-offs.
-   Practical: model a small set of domain objects.

## Day 27 --- Closures

-   Lexical scope and functions retaining access to outer variables.
-   Private state and common closure patterns.
-   Practical: create a counter factory.

## Day 28 --- Functional programming and immutability

-   Pure functions, composition, side effects, immutability.
-   Shallow copies versus deep-copy concerns.
-   Practical: update nested state safely.

## Day 29 --- Regular expressions and input parsing

-   Patterns, character classes, quantifiers, anchors.
-   Basic input-format validation and its limitations.
-   Practical: parse and validate structured text.

## Day 30 --- JSON, serialization, and error boundaries

-   JSON supported values and serialization limitations.
-   Safe parsing, malformed data, and data contracts.
-   Practical: import/export local application data.

## Day 31 --- Memory and performance foundations

-   References, reachability, garbage collection concepts.
-   Accidental retained references and excessive DOM work.
-   Practical: inspect repeated event-listener or timer mistakes.

## Day 32 --- JavaScript coding exercises

-   Arrays, objects, strings, conditions, functions, and edge cases.
-   Write readable solutions and test boundary inputs.

## Day 33 --- Build a practical application

-   Expense tracker or quiz application.
-   State, DOM updates, form validation, and storage.
-   Separate data operations from rendering.

## Day 34 --- Refactor and debug

-   Split modules, improve names, handle invalid input.
-   Test empty, malformed, and boundary cases.
-   Document known limitations.

## Day 35 --- Revision and interview checkpoint

-   Explain scope, closures, promises, event loop, prototypes, and
    `this`.
-   Solve small coding tasks without a tutorial.
-   Explain a fetch request from initiation to UI update.

## Day 36 --- Final project review

-   Demonstrate the project.
-   Write README, setup steps, features, and lessons learned.
-   Review weak areas before React.

**Phase assignment:** An interactive expense tracker or quiz app with
modular JavaScript, validation, error handling, and persistent
non-sensitive data.

------------------------------------------------------------------------

# Phase 4 --- Git, GitHub, and Professional Workflow

**Estimated study sessions:** 6

## Day 1 --- Git and repository fundamentals

-   Working directory, staging area, commit history, repository.
-   `git --version`, `git init`, `git status`, `git add`, `git commit`.

## Day 2 --- History and branches

-   `git log`, `git diff`, branch concepts.
-   `git switch`, `git branch`, and safe local workflow.

## Day 3 --- GitHub and remotes

-   Remote repository, `git remote`, push, fetch, pull.
-   Authentication concepts and safe credential handling.
-   Never commit tokens, passwords, or `.env` files.

## Day 4 --- Collaboration and conflicts

-   Pull requests, reviews, merge conflicts, merge versus rebase
    overview.
-   Resolve conflicts carefully and inspect final changes.

## Day 5 --- `.gitignore`, releases, and repository quality

-   Ignore dependencies, build artifacts, local secrets.
-   Tags, versioning concepts, issue tracking, and README quality.

## Day 6 --- Practice and checkpoint

-   Create a repository, branch, commit, merge, and push.
-   Recover from a simple mistake using history.
-   Explain the difference between Git and GitHub.

**Phase assignment:** Publish earlier projects with meaningful commits,
clean README files, and no secrets.

------------------------------------------------------------------------

# Phase 5 --- React from Fundamentals to Professional Frontend

**Estimated study sessions:** 30

## Day 1 --- React and project setup

-   Why component-based UI; React versus vanilla DOM manipulation.
-   Create a project with a current stable, compatible toolchain.
-   Understand source files, scripts, and development server.

## Day 2 --- JSX

-   JSX syntax, expressions, attributes, fragments.
-   Conditional content and common JSX errors.

## Day 3 --- Components

-   Function components, naming, composition, reusable UI.
-   Component boundaries and responsibility.

## Day 4 --- Props

-   Passing data, defaults, children, one-way data flow.
-   Avoid changing props.

## Day 5 --- Lists and keys

-   Rendering arrays, stable keys, why array indexes can be risky.
-   Practical: render a product list.

## Day 6 --- Events and state

-   Event handlers, `useState`, state updates and rerendering.
-   Why state should not be mutated directly.

## Day 7 --- State design

-   Derived values, lifting state up, controlled components.
-   Avoid redundant state and stale assumptions.

## Day 8 --- Conditional rendering

-   Conditional expressions, early returns, empty states.
-   Practical: loading, error, and empty UI states.

## Day 9 --- Forms

-   Controlled inputs, form submission, validation feedback.
-   Practical: reusable form component.

## Day 10 --- Effects

-   `useEffect`, dependencies, cleanup, synchronization.
-   Avoid effects for values that can be calculated during render.

## Day 11 --- Refs

-   `useRef`, DOM access, mutable values that do not trigger rerenders.
-   Practical: focus an input.

## Day 12 --- Custom hooks

-   Extract reusable stateful behavior.
-   Rules of Hooks and naming conventions.

## Day 13 --- Context API

-   Shared state, provider boundaries, context rerenders.
-   When context helps and when it is unnecessary.

## Day 14 --- Reducers

-   `useReducer`, actions, state transitions, predictable updates.
-   Practical: cart or multi-step form state.

## Day 15 --- Routing

-   Client-side routing, route parameters, nested routes, layouts.
-   Not-found routes and navigation.

## Day 16 --- API integration

-   Fetching data, loading/error/success states, cancellation.
-   Separate API utilities from UI components.

## Day 17 --- Authentication UI concepts

-   Login forms, route guards as UI behavior, user state.
-   Understand that frontend route guards do not replace backend
    authorization.

## Day 18 --- State-management choices

-   Local state, lifted state, context, reducer, and external stores.
-   Learn the problem before choosing a library.

## Day 19 --- Component architecture

-   Presentational versus feature-oriented organization.
-   Reuse without over-abstraction.

## Day 20 --- Accessibility in React

-   Semantic elements, labels, keyboard support, focus handling.
-   Accessible modal and notification concepts.

## Day 21 --- Styling React applications

-   CSS modules/conventions, Tailwind integration, component styles.
-   Keep styles consistent and responsive.

## Day 22 --- Error boundaries and error UI

-   Rendering failures, fallback UI, API errors.
-   Understand which errors boundaries do and do not catch.

## Day 23 --- Performance fundamentals

-   React DevTools, rerender analysis, memoization.
-   `memo`, `useMemo`, and `useCallback` only when justified.

## Day 24 --- Data fetching and caching concepts

-   Cache, invalidation, retries, stale data, race conditions.
-   Intro to a query/cache library and when it helps.

## Day 25 --- Testing React

-   Component behavior, React Testing Library, user-oriented assertions.
-   Avoid tests coupled unnecessarily to implementation details.

## Day 26 --- Frontend security and reliability

-   XSS awareness, safe rendering, dependency hygiene.
-   Never treat client validation as a security boundary.

## Day 27 --- Build an admin dashboard

-   Tables, filters, pagination UI, forms, loading/error states.
-   Responsive layout and reusable components.

## Day 28 --- Debugging and refactoring

-   React DevTools, console warnings, stale closures, effect loops.
-   Fix keys, state mutations, and unnecessary effects.

## Day 29 --- Project completion

-   Complete task manager or teacher-rating frontend.
-   README, screenshots, feature list, and setup instructions.

## Day 30 --- Revision and checkpoint

-   Explain components, props, state, effects, refs, context, routing.
-   Build a small feature independently and test it.

**Phase assignment:** Responsive React dashboard with routing, forms,
API integration, error handling, and tests.

------------------------------------------------------------------------

# Phase 6 --- Node.js, Express, and REST API Development

**Estimated study sessions:** 24

## Day 1 --- Node.js runtime

-   JavaScript outside the browser; runtime and V8 overview.
-   Node versus browser APIs.

## Day 2 --- npm and project configuration

-   `package.json`, dependencies, scripts, lockfiles, semantic
    versioning.
-   Environment-specific configuration concepts.

## Day 3 --- Modules and filesystem

-   CommonJS versus ES modules.
-   File reads/writes, paths, and asynchronous I/O.

## Day 4 --- Event loop and asynchronous I/O

-   Non-blocking operations, promises, callbacks.
-   Why CPU-heavy work can block the event loop.

## Day 5 --- HTTP server basics

-   Request methods, headers, status codes, request body.
-   Create a tiny server and inspect responses.

## Day 6 --- Express setup

-   App initialization, routes, listening ports.
-   Environment variables and local server startup.

## Day 7 --- Request and response

-   Route parameters, query parameters, JSON bodies.
-   Correct status codes and response formats.

## Day 8 --- Middleware

-   Request lifecycle, middleware order, `next`.
-   Built-in, third-party, and custom middleware.

## Day 9 --- REST API design

-   Resources, nouns, HTTP methods, status codes.
-   Consistent response and error contracts.

## Day 10 --- Validation

-   Validate path, query, body, and uploaded input.
-   Schema validation libraries and readable error messages.

## Day 11 --- Error handling

-   Central error middleware, async errors, operational versus
    programming errors.
-   Avoid leaking stack traces or secrets to clients.

## Day 12 --- Configuration and secrets

-   Environment variables, `.env`, safe defaults, configuration
    validation.
-   Never commit production credentials.

## Day 13 --- Logging

-   Structured logs, request IDs, levels, redaction of sensitive fields.
-   Avoid logging passwords or tokens.

## Day 14 --- Pagination, filtering, and sorting

-   Limit/offset and cursor concepts.
-   Input limits and stable ordering.

## Day 15 --- CORS and browser security boundaries

-   Origins, preflight requests, allowed methods and headers.
-   CORS is not authentication.

## Day 16 --- File uploads

-   Multipart form data, size limits, file type validation.
-   Storage location, filenames, and upload security.

## Day 17 --- Email and external services

-   API integration, timeouts, retries, secrets, error handling.
-   Keep external service logic isolated.

## Day 18 --- Rate limiting and abuse prevention

-   Per-route limits, request-size limits, timeouts.
-   Identify expensive endpoints.

## Day 19 --- API documentation

-   OpenAPI/Swagger concepts, request/response schemas.
-   Document errors and authentication requirements.

## Day 20 --- Testing Express APIs

-   Unit versus integration tests, Supertest, isolated test data.
-   Test success, validation failure, unauthorized access, and missing
    records.

## Day 21 --- Graceful shutdown and health checks

-   Signal handling, closing connections, liveness/readiness concepts.
-   Avoid losing in-flight work unnecessarily.

## Day 22 --- Build a complete API

-   Implement a notes or products API with CRUD, validation, and errors.
-   Organize routes, controllers, and services.

## Day 23 --- Refactor and debug

-   Trace request lifecycle and middleware order.
-   Diagnose port conflicts, invalid JSON, and failed requests.

## Day 24 --- Revision and checkpoint

-   Explain Node runtime, middleware, REST, status codes, CORS, and
    errors.
-   Demonstrate and test the API.

**Phase assignment:** Documented, validated Express API with tests,
logging, pagination, and safe configuration.

------------------------------------------------------------------------

# Phase 7 --- MongoDB and Mongoose

**Estimated study sessions:** 18

## Day 1 --- NoSQL and document databases

-   Database, collection, document, BSON, and JSON relationship.
-   Document model and appropriate use cases.

## Day 2 --- CRUD operations

-   Insert, find, update, delete, projections.
-   Practical queries using a sample dataset.

## Day 3 --- Filters and query operators

-   Comparison, logical, array, and existence operators.
-   Avoid unbounded or accidental broad updates/deletes.

## Day 4 --- MongoDB data modeling

-   Embedding versus referencing.
-   Access patterns, duplication, document size, and relationships.

## Day 5 --- Mongoose schemas and models

-   Schema definitions, types, defaults, required fields.
-   Model methods and database connection lifecycle.

## Day 6 --- Validation and middleware

-   Schema validation, custom validation, hooks.
-   Understand validation and middleware execution.

## Day 7 --- Relationships and population

-   ObjectId references, `populate`, data retrieval trade-offs.
-   Avoid unnecessary population.

## Day 8 --- Updates and atomic operations

-   Update operators, upserts, atomic document updates.
-   Prevent lost updates where possible.

## Day 9 --- Aggregation pipelines

-   `$match`, `$group`, `$project`, `$sort`, `$unwind`, `$lookup`
    basics.
-   Practical: compute course enrollment statistics.

## Day 10 --- Indexes

-   Single-field, compound, unique, and text index concepts.
-   Read query plans and understand index trade-offs.

## Day 11 --- Transactions and consistency

-   When multi-document transactions are needed.
-   Cost and operational implications.

## Day 12 --- Pagination and query performance

-   Offset versus cursor pagination.
-   Stable sorting and indexed filters.

## Day 13 --- Security and data integrity

-   Validate inputs; avoid unsafe dynamic filters.
-   Least privilege, credential management, backups.

## Day 14 --- Atlas and deployment considerations

-   Managed database concepts, network access, users, connection
    strings.
-   Do not expose database credentials in frontend code.

## Day 15 --- Connect MongoDB to Express

-   Repository/service organization, connection handling.
-   Implement CRUD endpoints.

## Day 16 --- Testing and debugging

-   Duplicate keys, validation errors, failed connections, query issues.
-   Test empty results and malformed IDs.

## Day 17 --- Mini-project

-   Build a catalog or notes application with search and pagination.
-   Add tests and document the data model.

## Day 18 --- Revision and checkpoint

-   Explain embedding versus referencing, indexes, aggregation, and
    validation.
-   Design a document model from sample requirements.

**Phase assignment:** MongoDB-backed Express application with indexes,
validation, aggregation, tests, and documented schema choices.

------------------------------------------------------------------------

# Phase 8 --- PostgreSQL and SQL Mastery

**Estimated study sessions:** 24

## Day 1 --- Relational database foundations

-   Database, schema, table, row, column, and data type.
-   SQL versus NoSQL; relational strengths and trade-offs.

## Day 2 --- Tables and data types

-   Integer, numeric/decimal, text, boolean, date/time, UUID.
-   Null values and choosing appropriate types.

## Day 3 --- Constraints and keys

-   Primary, foreign, unique, check, not-null constraints.
-   Referential integrity and why constraints matter.

## Day 4 --- Basic SQL queries

-   `SELECT`, `FROM`, aliases, expressions, `DISTINCT`.
-   Query a small sample database.

## Day 5 --- Filtering and sorting

-   `WHERE`, comparison, `AND`, `OR`, `IN`, `BETWEEN`, `LIKE`.
-   `ORDER BY`, `LIMIT`, and null handling.

## Day 6 --- Insert, update, and delete

-   `INSERT`, `UPDATE`, `DELETE`, `RETURNING`.
-   Safe use of conditions and transactions.

## Day 7 --- Aggregation

-   `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`, `GROUP BY`, `HAVING`.
-   Practical reporting queries.

## Day 8 --- Joins

-   Inner, left, right, full joins.
-   Join keys, duplicate rows, and nulls.

## Day 9 --- Subqueries and CTEs

-   Scalar and correlated subqueries.
-   `WITH` clauses for readable queries.

## Day 10 --- Window functions

-   `OVER`, `PARTITION BY`, ordering, ranking, running totals.
-   Practical: rank students or courses.

## Day 11 --- Normalization and schema design

-   Functional dependencies at a practical level.
-   First, second, and third normal forms.
-   Avoid update, insert, and delete anomalies.

## Day 12 --- Relationships and many-to-many design

-   One-to-one, one-to-many, many-to-many.
-   Junction tables and composite uniqueness.

## Day 13 --- Transactions and ACID

-   Commit, rollback, atomicity, consistency, isolation, durability.
-   Practical: multi-step business operation.

## Day 14 --- Isolation and concurrency

-   Isolation levels, anomalies, locks, deadlocks.
-   Why transaction boundaries matter.

## Day 15 --- Indexes

-   B-tree default concepts, composite indexes, unique indexes.
-   Selectivity and write overhead.

## Day 16 --- Query plans and optimization

-   `EXPLAIN`, `EXPLAIN ANALYZE`.
-   Sequential scan, index scan, joins, and statistics.

## Day 17 --- Views and database-side logic

-   Views and materialized views.
-   Introductory functions and triggers; when not to overuse them.

## Day 18 --- Migrations

-   Schema evolution, forward changes, rollback planning.
-   Why production migrations need care.

## Day 19 --- PostgreSQL roles and permissions

-   Roles, grants, least privilege, separate application credentials.
-   Backup and restore concepts.

## Day 20 --- PostgreSQL operations

-   Connection settings, pooling, logs, backups, restore verification.
-   Understand local versus managed database setup.

## Day 21 --- PostgreSQL with Node.js

-   Driver concepts, parameterized queries, SQL injection prevention.
-   Connection pooling and transactions from the application.

## Day 22 --- Prisma ORM

-   Schema models, relations, generated client, migrations.
-   ORM benefits and limitations; raw SQL when appropriate.
-   Understand how schema changes reach the database.

## Day 23 --- Design the learning platform database

-   Users, courses, lessons, enrollments, quizzes, questions, attempts.
-   Define keys, relations, constraints, and query needs.

## Day 24 --- Revision and checkpoint

-   Write joins, aggregates, subqueries, and a window function.
-   Explain transactions, indexes, normalization, and query plans.
-   Defend the learning platform schema design.

**Phase assignment:** Document and implement a relational
learning-platform schema with migrations, realistic sample data, and
reporting queries.

------------------------------------------------------------------------

# Phase 9 --- TypeScript and Maintainable Architecture

**Estimated study sessions:** 18

## Day 1 --- TypeScript setup and type inference

-   Why static types; compiler versus runtime behavior.
-   Basic types and inference.

## Day 2 --- Functions and object types

-   Parameter and return types, optional fields, readonly properties.
-   Type aliases and interfaces.

## Day 3 --- Unions and narrowing

-   Literal unions, discriminated unions, type guards.
-   Exhaustive handling.

## Day 4 --- Arrays, tuples, enums, and alternatives

-   Typed arrays and tuples.
-   When literal unions are preferable to enums.

## Day 5 --- Generics

-   Generic functions, interfaces, and constraints.
-   Reusable type-safe utilities.

## Day 6 --- Utility types

-   `Partial`, `Pick`, `Omit`, `Record`, `ReturnType`, and related
    types.
-   Model input and output shapes.

## Day 7 --- Advanced type composition

-   `keyof`, indexed access, conditional and mapped types overview.
-   Avoid overly complex types without clear value.

## Day 8 --- Strict mode and safer code

-   Nullability, unknown versus any, assertions.
-   Handle uncertain external data safely.

## Day 9 --- TypeScript with React

-   Props, events, hooks, refs, children, form values.
-   Type component boundaries.

## Day 10 --- TypeScript with Express

-   Request/response types, middleware, error types.
-   Avoid pretending unvalidated input is safe.

## Day 11 --- Runtime validation

-   TypeScript types disappear at runtime.
-   Schema validation and inferred types.

## Day 12 --- API contracts

-   Request DTOs, response models, error shapes.
-   Keep database models separate from public API shapes.

## Day 13 --- Layered architecture

-   Routes, controllers, services, repositories.
-   Responsibilities and dependency direction.

## Day 14 --- Maintainability and refactoring

-   Cohesion, coupling, dependency injection concepts.
-   Avoid both giant files and unnecessary abstractions.

## Day 15 --- Shared contracts and error handling

-   Common validation schemas, error types, mapping failures to HTTP
    responses.
-   Avoid leaking internal implementation details.

## Day 16 --- Type-safe database access

-   Prisma-generated types and transaction handling.
-   Distinguish input types from database entities.

## Day 17 --- Convert a project

-   Migrate a small API or frontend to strict TypeScript.
-   Fix type errors without hiding them using `any`.

## Day 18 --- Revision and checkpoint

-   Explain narrowing, generics, null safety, runtime validation, and
    architecture.
-   Refactor one poorly structured module.

**Phase assignment:** A strictly typed React + Express feature with
validation, service boundaries, and documented API contracts.

------------------------------------------------------------------------

# Phase 10 --- Authentication, Authorization, and Application Security

**Estimated study sessions:** 18

## Day 1 --- Security foundations

-   Threats, assets, trust boundaries, least privilege.
-   Authentication versus authorization.

## Day 2 --- Password handling

-   Hashing versus encryption; salt and adaptive password hashing.
-   Never store plaintext passwords.

## Day 3 --- Registration and login

-   Input validation, duplicate accounts, generic errors.
-   Account lifecycle and secure defaults.

## Day 4 --- Sessions and cookies

-   Server-side sessions, session identifiers, cookie flags.
-   Expiration, renewal, invalidation, and session fixation.

## Day 5 --- JWT fundamentals

-   Header, payload, signature, claims, expiration.
-   A signed token is not automatically encrypted.

## Day 6 --- Access and refresh tokens

-   Short-lived access tokens, refresh rotation concepts, revocation
    trade-offs.
-   Storage and theft risks.

## Day 7 --- Authorization models

-   Roles, permissions, ownership checks, resource-level access.
-   Prevent insecure direct object references.

## Day 8 --- OAuth 2.0 and OpenID Connect

-   Authorization flows, identity provider, scopes, redirect URIs.
-   Authentication versus delegated authorization.

## Day 9 --- XSS

-   Untrusted content, safe rendering, sanitization concepts, CSP
    overview.
-   Avoid dangerous HTML insertion.

## Day 10 --- CSRF and cookie security

-   Cross-site requests, SameSite cookies, CSRF tokens.
-   Understand how frontend/backend architecture changes defenses.

## Day 11 --- SQL and NoSQL injection

-   Parameterized SQL, safe query construction, input schemas.
-   Never build queries by blindly concatenating user input.

## Day 12 --- API hardening

-   Rate limiting, payload size, secure headers, CORS configuration.
-   Safe errors and sensitive data redaction.

## Day 13 --- Password reset and email verification

-   Single-use, expiring tokens; safe recovery flows.
-   Avoid account enumeration.

## Day 14 --- Secrets and dependency security

-   Environment secrets, key rotation, dependency audits.
-   Avoid committing credentials or exposing secrets in logs.

## Day 15 --- Upload and resource security

-   File validation, storage permissions, size limits, path traversal
    risks.
-   Protect expensive endpoints.

## Day 16 --- Security testing

-   Test unauthenticated, unauthorized, expired, malformed, and
    cross-user access.
-   Build a small security test matrix.

## Day 17 --- Secure a multi-role application

-   Student, teacher, and admin permissions.
-   Verify authorization on the server for every protected operation.

## Day 18 --- Revision and security checkpoint

-   Explain sessions versus JWT, authentication versus authorization,
    XSS, CSRF, injection.
-   Demonstrate a protected endpoint and cross-user access test.

**Phase assignment:** Secure multi-role application with password
hashing, session/token design, server-side authorization, account
recovery, and security tests.

------------------------------------------------------------------------

# Phase 11 --- Testing and Quality Assurance

**Estimated study sessions:** 12

## Day 1 --- Testing fundamentals

-   Unit, integration, end-to-end, regression, smoke tests.
-   Test pyramid and risk-based testing.

## Day 2 --- Test design

-   Arrange/Act/Assert, fixtures, boundary cases.
-   Deterministic tests and readable assertions.

## Day 3 --- JavaScript unit tests

-   Test runner setup, assertions, setup/teardown.
-   Test pure functions and error paths.

## Day 4 --- React component tests

-   Render components, user interactions, accessible queries.
-   Test observable behavior.

## Day 5 --- Express API tests

-   Supertest, status codes, payloads, validation errors.
-   Isolate test configuration.

## Day 6 --- Database testing

-   Test database setup, migrations, cleanup, isolation.
-   Avoid accidentally modifying production data.

## Day 7 --- Mocking and external services

-   Mock boundaries, avoid over-mocking internal behavior.
-   Test timeouts and failure paths.

## Day 8 --- Browser automation

-   Playwright concepts, locators, navigation, form submissions.
-   Stable tests and screenshots/traces for failures.

## Day 9 --- Security and authorization tests

-   Role matrix, unauthorized requests, cross-user access.
-   Test validation and abuse limits.

## Day 10 --- Coverage and debugging

-   Coverage as a signal, not proof of quality.
-   Reproduce, isolate, fix, and prevent defects.

## Day 11 --- Add tests to a full-stack feature

-   Write unit, integration, and browser tests for a realistic workflow.
-   Document test commands.

## Day 12 --- Revision and checkpoint

-   Explain what belongs in each testing layer.
-   Diagnose a deliberately failing test.

**Phase assignment:** Automated test suite covering a key user journey,
backend endpoints, database behavior, and authorization.

------------------------------------------------------------------------

# Phase 12 --- Deployment, Linux Operations, Docker, and CI/CD

**Estimated study sessions:** 18

## Day 1 --- Development versus production

-   Build-time versus runtime configuration.
-   Production build, environment variables, logs, and errors.

## Day 2 --- Linux processes and networking

-   Processes, signals, ports, permissions, disk space.
-   Commands: `ps`, `top`, `ss`, `df`, `du`, `journalctl` basics.

## Day 3 --- Domains and DNS

-   Domain records, A/AAAA, CNAME, TTL.
-   DNS propagation and common misconfiguration.

## Day 4 --- TLS and HTTPS

-   Certificates, encryption in transit, renewal concepts.
-   Secure redirects and mixed content.

## Day 5 --- Deployment architecture

-   Static frontend, API service, database, network boundaries.
-   Choose a deployment platform based on needs and budget.

## Day 6 --- Environment variables and secrets

-   Separate local, staging, and production configuration.
-   Secret storage and rotation.

## Day 7 --- Deploy the frontend

-   Build output, hosting, routing fallbacks, caching.
-   Verify production assets and URLs.

## Day 8 --- Deploy the backend

-   Start command, port binding, process health, logs.
-   Configure frontend API URL and CORS.

## Day 9 --- Managed database deployment

-   Secure connectivity, database users, backups, migrations.
-   Never expose database ports or credentials unnecessarily.

## Day 10 --- Docker fundamentals

-   Image, container, layer, Dockerfile, build context.
-   Run and inspect a basic container.

## Day 11 --- Docker volumes and networking

-   Persistent data, container networking, port mapping.
-   Understand why container filesystems are ephemeral.

## Day 12 --- Docker Compose

-   Define frontend/backend/database services.
-   Environment, dependencies, health checks, and persistent volumes.

## Day 13 --- CI basics

-   Automated lint, tests, builds, and checks on pull requests.
-   GitHub Actions workflow fundamentals.

## Day 14 --- CD and release safety

-   Deployment pipelines, migrations, rollback plans.
-   Avoid exposing secrets in CI logs.

## Day 15 --- Observability

-   Logs, metrics, traces concepts, health endpoints.
-   Alert on actionable symptoms.

## Day 16 --- Backups and recovery

-   Backup schedules, retention, restore testing.
-   A backup is not proven until a restore has been tested.

## Day 17 --- Deploy a full-stack project

-   Deploy frontend, API, and database.
-   Verify critical workflows and document setup.

## Day 18 --- Revision and checkpoint

-   Explain DNS, TLS, Docker, CI/CD, logs, health checks, backups.
-   Diagnose a simulated failed deployment.

**Phase assignment:** Deployed application with HTTPS, production
configuration, CI checks, documented backup strategy, and a repeatable
release process.

------------------------------------------------------------------------

# Phase 13 --- Advanced Backend, Performance, and Scalability

**Estimated study sessions:** 18

## Day 1 --- Performance fundamentals

-   Latency, throughput, concurrency, bottlenecks.
-   Measure before optimizing.

## Day 2 --- Caching

-   Cache-aside, TTL, invalidation, stale data.
-   Avoid caching sensitive user-specific responses incorrectly.

## Day 3 --- Redis foundations

-   Key/value model, expiration, data structures, cache use.
-   Secure network access and credentials.

## Day 4 --- Queues and background jobs

-   Jobs, workers, retries, backoff, dead-letter concepts.
-   Why long-running tasks should leave the request path.

## Day 5 --- Idempotency and retries

-   Duplicate requests, idempotency keys, retry safety.
-   Avoid duplicate payments/orders/side effects.

## Day 6 --- Email and notification processing

-   Queue notification jobs, record outcomes, handle provider failure.
-   Prevent repeated notifications on retry.

## Day 7 --- WebSockets and real-time updates

-   Persistent connection concepts, events, reconnects.
-   When polling is sufficient versus a real-time channel.

## Day 8 --- Database performance

-   Query plans, indexes, N+1 queries, connection pools.
-   Diagnose slow requests from measurements.

## Day 9 --- Pagination and large datasets

-   Cursor pagination, stable sort keys, bounded queries.
-   Avoid returning unbounded collections.

## Day 10 --- Load testing

-   Virtual users, throughput, percentiles, bottleneck identification.
-   Establish a baseline before changes.

## Day 11 --- Memory and profiling

-   Heap growth, event-loop delay, profiling tools.
-   Investigate leaks and CPU-heavy code.

## Day 12 --- Object storage and CDNs

-   Direct uploads, signed URLs, content delivery, cache headers.
-   Keep access permissions and file lifecycle in mind.

## Day 13 --- Search

-   Database search, text indexes, external search service concepts.
-   Relevance, filtering, indexing, and consistency trade-offs.

## Day 14 --- Reliability and failure handling

-   Timeouts, circuit breaker concepts, retries, graceful degradation.
-   Avoid retry storms.

## Day 15 --- Scaling application services

-   Stateless services, horizontal scaling, reverse proxies.
-   Sessions and shared state under multiple instances.

## Day 16 --- Multi-tenant SaaS concerns

-   Tenant isolation, quotas, tenant-scoped authorization.
-   Avoid cross-tenant data leaks.

## Day 17 --- Improve an existing application

-   Add cache or queue, measure before/after, test failure scenarios.
-   Document trade-offs and operational implications.

## Day 18 --- Revision and checkpoint

-   Explain caching, idempotency, queues, WebSockets, scaling, and load
    testing.
-   Diagnose a measured bottleneck.

**Phase assignment:** Enhanced application with a queue or cache,
load-test results, performance notes, and documented failure handling.

------------------------------------------------------------------------

# Phase 14 --- System Design and Software Engineering

**Estimated study sessions:** 18

## Day 1 --- Requirements and constraints

-   Functional/non-functional requirements, assumptions, scope.
-   Capacity estimates at a basic level.

## Day 2 --- API and data-flow design

-   Endpoints, contracts, sequence diagrams, request lifecycle.
-   Define failure responses.

## Day 3 --- Architecture styles

-   Monolith, modular monolith, services, microservices.
-   Trade-offs and operational complexity.

## Day 4 --- Data modeling decisions

-   Relational versus document storage.
-   Access patterns, consistency, constraints, migrations.

## Day 5 --- Scalability fundamentals

-   Vertical/horizontal scaling, bottlenecks, statelessness.
-   Capacity and performance trade-offs.

## Day 6 --- Caching and data consistency

-   Cache invalidation, stale reads, write-through concepts.
-   Define acceptable consistency behavior.

## Day 7 --- Queues and event-driven systems

-   Producers, consumers, events, retries, duplicate delivery.
-   Eventual consistency and idempotent consumers.

## Day 8 --- Reliability and availability

-   Health checks, redundancy, recovery, failure domains.
-   SLO/SLI concepts and incident impact.

## Day 9 --- Security architecture

-   Trust boundaries, least privilege, secrets, tenant isolation.
-   Threat-model a sample product.

## Day 10 --- Observability and incident response

-   Logs, metrics, traces, alert quality.
-   Incident timeline, mitigation, root cause, follow-up actions.

## Day 11 --- Design patterns

-   Strategy, factory, adapter, observer, repository concepts.
-   Use patterns to solve real design problems, not as decoration.

## Day 12 --- Code quality and team practices

-   Code review, refactoring, naming, modularity, technical debt.
-   Small pull requests and clear commit history.

## Day 13 --- Architecture documentation

-   Context/container diagrams, sequence diagrams, decision records.
-   Explain why a choice was made and what alternatives were rejected.

## Day 14 --- Product delivery

-   Requirements breakdown, estimates, risks, milestones, acceptance
    criteria.
-   Scope control and iterative delivery.

## Day 15 --- Design a learning platform

-   Users, courses, enrollment, quizzes, progress, notifications.
-   Draw request/data flow and select storage.

## Day 16 --- Design a small e-commerce system

-   Catalog, cart, orders, inventory, idempotency.
-   Avoid oversimplifying transaction and payment boundaries.

## Day 17 --- Design review and trade-offs

-   Review scalability, security, operations, cost, and complexity.
-   Improve the design based on identified risks.

## Day 18 --- System design checkpoint

-   Explain an architecture from requirements through deployment.
-   Defend at least three key trade-offs.

**Phase assignment:** System design document, architecture diagrams, API
outline, database schema, security considerations, and decision records.

------------------------------------------------------------------------

# Phase 15 --- Capstone, Portfolio, Freelancing, and Interview Readiness

**Estimated study sessions:** 24--36

## Day 1 --- Select and scope the capstone

-   Pick a real problem and target user.
-   Write the MVP scope, acceptance criteria, and non-goals.

## Day 2 --- Requirements and user journeys

-   User stories, permissions, edge cases, and failure paths.
-   Define measurable completion criteria.

## Day 3 --- Architecture and technology decisions

-   Select React, Node, Express, and appropriate database(s).
-   Document why MongoDB, PostgreSQL, or both are justified.

## Day 4 --- Data model and API contract

-   ER diagram or document model, constraints, endpoint list.
-   Define request/response examples and error contracts.

## Day 5 --- Repository and project structure

-   GitHub repository, branches, README, `.gitignore`.
-   Environment configuration and setup instructions.

## Day 6 --- UI foundations

-   Navigation, layout, responsive shell, accessibility.
-   Reusable design tokens and components.

## Day 7 --- Registration and authentication

-   Implement secure account flow and session/token strategy.
-   Test invalid and expired credentials.

## Day 8 --- Authorization and roles

-   Define role and resource permissions.
-   Test unauthorized and cross-user operations.

## Day 9 --- Core CRUD workflow

-   Implement the main entity and API operations.
-   Validation, errors, and tests.

## Day 10 --- Database integration

-   Migrations or schema setup, seed data, indexes.
-   Verify constraints and data access.

## Day 11 --- Main frontend workflow

-   Forms, lists, details, loading, empty, and error states.
-   Integrate with the API.

## Day 12 --- Search, filters, and pagination

-   Implement useful query behavior.
-   Ensure stable ordering and sensible limits.

## Day 13 --- Secondary feature

-   Add a meaningful feature based on product needs.
-   Avoid adding scope without a clear purpose.

## Day 14 --- Notifications or background processing

-   Add email/notifications or a background job if justified.
-   Handle retries and duplicates.

## Day 15 --- Testing

-   Unit, integration, and end-to-end coverage for key journeys.
-   Include authorization and validation tests.

## Day 16 --- Security review

-   Audit secrets, cookies/tokens, validation, permissions, headers.
-   Review dependencies and data exposure.

## Day 17 --- Performance review

-   Inspect slow queries and unnecessary frontend work.
-   Measure rather than guess.

## Day 18 --- Deployment

-   Deploy frontend, backend, and database.
-   Verify environment configuration and production flow.

## Day 19 --- Monitoring and backup

-   Add useful logs, health checks, backup plan, restore considerations.
-   Document incident troubleshooting.

## Day 20 --- UX polish and accessibility

-   Keyboard navigation, responsive layouts, error messaging.
-   Test realistic user flows.

## Day 21 --- Documentation

-   README, screenshots, architecture, setup, environment variables, API
    docs.
-   Explain trade-offs and known limitations.

## Day 22 --- Freelance/product delivery practice

-   Write a project brief, milestones, assumptions, and acceptance
    criteria.
-   Practice explaining scope and managing change requests.

## Day 23 --- Frontend and JavaScript interview checkpoint

-   JavaScript fundamentals, async, closures, browser behavior, React.
-   Explain code and solve small practical tasks.

## Day 24 --- Backend, database, and system design checkpoint

-   Node, Express, REST, authentication, SQL, MongoDB, indexes,
    transactions.
-   Explain a complete request path and architecture.

### Optional capstone extension: 12 additional sessions

25. Load testing and performance tuning.\
26. Advanced security review and dependency audit.\
27. Add automated CI/CD checks.\
28. Add Docker Compose for local reproducibility.\
29. Improve observability and operational documentation.\
30. Conduct a mock code review.\
31. Fix technical debt and refactor.\
32. Practice a timed feature implementation.\
33. Practice a system design interview.\
34. Polish GitHub portfolio and pinned repositories.\
35. Prepare project demonstrations and resume bullets.\
36. Final assessment and retrospective.

**Capstone options:** Learning management system, teacher-rating
platform, e-commerce application, or a small multi-tenant SaaS product.
Choose one primary capstone; smaller projects can remain portfolio
exercises.

------------------------------------------------------------------------

# Cross-Course Reference Topics

These subjects are introduced at the relevant points above and revisited
as projects require.

## Browser and web platform

-   DOM, event propagation, forms, storage, cookies, caching, rendering,
    accessibility.
-   HTTP semantics, content types, CORS, TLS, URLs, status codes.

## Programming and problem-solving

-   Data structures, algorithmic complexity, arrays, objects, maps,
    sets, strings, recursion basics.
-   Reading unfamiliar code, debugging, boundary cases, code clarity.

## Databases

-   Data modeling, integrity, transactions, indexing, query plans,
    migrations, backups, restore testing.
-   MongoDB document design versus PostgreSQL relational design.

## Professional engineering

-   Git workflow, code review, documentation, tests, release practices,
    security, observability.
-   Requirements, estimates, technical trade-offs, maintenance, and
    incident learning.

## Further specialization after this course

These are valid next steps, not prerequisites for the core course: -
Next.js and server-rendered React applications. - GraphQL and
alternative API styles. - Microservices and event-driven architecture in
depth. - Advanced cloud services and infrastructure as code. -
Native/mobile development, advanced accessibility, and specialized
frontend animation. - Deeper algorithms, distributed systems, and
database internals.

------------------------------------------------------------------------

# Project Portfolio Map

  -----------------------------------------------------------------------
  Project                             Main skills demonstrated
  ----------------------------------- -----------------------------------
  Personal website                    Semantic HTML, accessibility,
                                      responsive CSS

  Interactive expense tracker or quiz JavaScript, DOM, modules, storage,
                                      debugging

  React task manager/dashboard        Components, state, routing, API
                                      integration, tests

  MongoDB-backed catalog API          Express, Mongoose, validation,
                                      indexes, aggregation

  PostgreSQL learning platform        SQL, relational modeling,
                                      transactions, Prisma

  Secure multi-role application       Authentication, authorization,
                                      security tests

  Production SaaS capstone            Architecture, testing,
                                      Docker/CI/CD, deployment,
                                      observability
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# Course Repository Structure

Use this layout as the course grows. Do not create every project
directory on day one; add folders as each phase begins.

``` text
fullstack-mastery/
├── README.md
├── syllabus.md
├── progress.md
├── notes/
│   ├── phase-0/
│   ├── phase-1/
│   ├── phase-2/
│   └── ...
├── exercises/
│   ├── phase-0/
│   ├── phase-1/
│   └── ...
├── projects/
│   ├── portfolio/
│   ├── javascript-app/
│   ├── react-dashboard/
│   ├── mongodb-api/
│   ├── postgres-learning-platform/
│   └── capstone/
└── resources/
    └── links.md
```

### `progress.md` template

``` markdown
# Course Progress

- Current phase: Phase 0
- Current day: Day 1
- Status: In progress

## Completed
- [ ] Phase 0 Day 1

## Questions to revisit
- 

## Current blockers
- 

## Next lesson
- Phase 0 Day 1 checkpoint, then Day 2
```

### Lesson notes template

``` markdown
# Phase X — Day Y: Lesson title

## Learning objectives

## Concepts in simple language

## Why this matters

## How it works

## Examples and commands

## My own explanation

## Practical assignment

## Bugs encountered and fixes

## Interview questions and my answers

## Review status
- [ ] I can explain the concept
- [ ] I can write a small example without copying
- [ ] I tested an edge case
- [ ] I completed the checkpoint
```

------------------------------------------------------------------------

# GitHub Repository Setup --- Ubuntu

## 1. Verify Git is installed

``` bash
git --version
```

If Git is missing, install it using Ubuntu's package manager:

``` bash
sudo apt update
sudo apt install git
```

## 2. Configure your Git identity

Use the name and email you want associated with your commits:

``` bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Check the configuration:

``` bash
git config --global --list
```

## 3. Create the local repository

``` bash
mkdir -p ~/fullstack-mastery
cd ~/fullstack-mastery
git init
```

Add the `syllabus.md`, `README.md`, and `progress.md` files. Then:

``` bash
git status
git add syllabus.md README.md progress.md
git commit -m "docs: add full-stack mastery course syllabus"
```

## 4. Create the GitHub repository

On GitHub, create a new repository named `fullstack-mastery`. For the
simplest initial push, create it **without** auto-generating a README,
license, or `.gitignore`, because those files will already be created
locally.

Then connect and push the local repository, replacing `YOUR_USERNAME`
with your GitHub username:

``` bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/fullstack-mastery.git
git push -u origin main
```

GitHub may ask you to authenticate using a supported sign-in flow or
credential method. Do not put a password or token directly into source
files or commit it to the repository.

If you have already created the remote repository with files, stop and
inspect the histories before pushing; the initial setup may need a
pull/merge step.

## 5. Verify the repository

``` bash
git status
git remote -v
git log --oneline -5
```

Check that: - The working tree is clean. - The `origin` remote points to
your repository. - The syllabus and course tracking files are visible on
GitHub.

------------------------------------------------------------------------

# Immediate Next Steps

1.  Save this file as `syllabus.md` in the course repository.
2.  Create `README.md` and `progress.md` using the templates above.
3.  Initialize Git and publish the repository to GitHub.
4.  Keep Phase 0 marked in progress until its checkpoint is complete.
5.  After Phase 0 is completed, start **Phase 1 --- Day 1: HTML document
    structure**.
6.  Do not skip ahead. If a checkpoint exposes a gap, revise that
    concept first.

**Course principle:** The goal is not to finish the syllabus quickly.
The goal is to become capable of building, explaining, testing,
debugging, deploying, and maintaining real applications independently.
