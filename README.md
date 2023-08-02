## Test Automation Playwright

## Links

- testing page https://practicesoftwaretesting.com/#/
- code repostory

## Commands

- check `NodeJS` version  
  `node -v`

- new project with Playwright  
  `npm init playwright@latest`

## Extensions

- Prettier
- Gitlens

## Playwright Config modifications

### Playwright snippets

- import:
  ```typescript
  import { test, expect } from "@playwright/test";
  ```

- test:
  ```typescript
  test("test name", async ({ page }) => {});
  ```
- describe:

  ```typescript
  test.describe("Group description", () => {
    //your code
  });
  ```
- running given test: `test.only`
