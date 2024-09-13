# gitbook

## 0.4.0

### Minor Changes

-   5c35f36: Replace all icons, previously imported from Geist, by new package `@gitbook/icons`
-   1f24fe4: Add support for page icons
-   1f24fe4: Add support for icons style customization for sites
-   4c19014: Prevent search indexation for pages where it's configured as disabled
-   3422ad4: Update rendering of community ads to match new API response, and make it possible to preview ads.

### Patch Changes

-   aa32198: Avoid multiple <h1> in the page by using a <div> for the title in the header
-   51fa3ab: Adds content-visibility css property to OpenAPI Operation for better render performance
-   5fe7adb: RND-3532: drop down menu for hidden links at small screen size
-   6295881: Change dark mode shadow for multi-space search toolbar
-   13c7534: Use ellipsis and fix icon color for more links in the header on small screen
-   af9e66e: Only display spaces dropdown in compact header when site is multi-variants
-   17f71ba: Use url hash to open Expandable and scroll to anchor
-   3c07e65: Fix margin for paragraphs in quote blocks
-   689f553: Fix inconsistent click area in table because of scroll indicator
-   e914903: Synchronize response and response example tabs
-   4cbcc5b: Rollback of scalar modal while fixing perf issue
-   3996110: Optimize images rendered in community ads
-   0f1565c: Add optional env `GITBOOK_INTEGRATIONS_HOST` to configure the host serving the integrations
-   cb782a7: Fix "ip" being passed to BSA for community ads
-   Updated dependencies [51fa3ab]
-   Updated dependencies [cf3045a]
-   Updated dependencies [094e9cd]
-   Updated dependencies [5c35f36]
-   Updated dependencies [e914903]
-   Updated dependencies [4cbcc5b]
-   Updated dependencies [0f1565c]
-   Updated dependencies [237b703]
-   Updated dependencies [51955da]
-   Updated dependencies [a679e72]
-   Updated dependencies [c079c3c]
-   Updated dependencies [5c35f36]
-   Updated dependencies [776bc31]
    -   @gitbook/react-openapi@0.7.0
    -   @gitbook/icons@0.1.0
    -   @gitbook/react-contentkit@0.5.1
    -   @gitbook/react-math@0.6.0

## 0.3.0

### Minor Changes

-   24b785c: Update shiki for code block syntax highlighting, with support for more languages and fixes for diffs. It also patches the deployment on Cloudflare to support edge functions larger than 4MB.

### Patch Changes

-   acc3f2f: Fix error with the "Try it" of OpenAPI block because of the Scalar proxy failing on Cloudflare with the `cache` option
-   Updated dependencies [709f1a1]
-   Updated dependencies [ede2335]
-   Updated dependencies [0426312]
    -   @gitbook/react-openapi@0.6.0

## 0.2.2

### Patch Changes

-   Updated dependencies [3445db4]
    -   @gitbook/react-contentkit@0.5.0
    -   @gitbook/react-openapi@0.5.0
    -   @gitbook/react-math@0.5.0

## 0.2.1

### Patch Changes

-   Updated dependencies [24cd72e]
    -   @gitbook/react-contentkit@0.4.0
    -   @gitbook/react-math@0.4.0
    -   @gitbook/react-openapi@0.4.0

## 0.2.0

### Minor Changes

-   de747b7: Refactor the repository to be a proper monorepo and publish JS files on NPM instead of TypeScript files.

### Patch Changes

-   Updated dependencies [de747b7]
-   Updated dependencies [de747b7]
    -   @gitbook/react-contentkit@0.3.0
    -   @gitbook/react-openapi@0.3.0
    -   @gitbook/react-math@0.3.0
