# Playwright test commands

```bash
npm run test
npx playwright test
npm run test:report
```

Tests through a graphical user interface

```bash
npm run test -- --ui
npx playwright test --ui
```

## Make test is run in a specific browser

Install the browsers:

```bash
npx playwright install 
```

Tests in chrome:

```bash
npm run test -- --project chromium
npx playwright test --project chromium
```

Tests in firefox:

```bash
npm run test -- --project firefox
npx playwright test --project firefox
```

Tests in webkit:

```bash
npm run test -- --project webkit
npx playwright test --project webkit
```
