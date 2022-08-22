## Problem

`[Violation] 'click' handler took 180ms`
when trying to open modal for the first time

## Ways to reproduce

1. Install latest nextjs

`npx create-next-app@latest`

2. Install mantine dependencies

`npm install @mantine/core @mantine/hooks @mantine/next @emotion/server @emotion/react`

3. Open https://mantine.dev/guides/next/;
   Create pages/\_document.tsx file and config it accordingly.

4. Add MantineProvider to pages/\_app.tsx:

5. Create a modal in index page
