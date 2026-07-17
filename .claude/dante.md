# Dante Workflows

## Development

### JS Style

- Use arrow functions.

### CSS Style

- Attach styles to classNames, not elements, attributes, etc. If an element needs to be styled but does not have a className, add it in the component.

### Validation Steps

- **Lint:** `npm lint`
- **Test:** `npm test`
- **Live Test:** Run `npm start` to run the application locally. Use Playwright CLI to access the live application and verify that calculation works as expected. Store a screenshot in the repo's `.claude/dante-resources` folder (which is gitignored) for use in the Pull Request phase.

## Pull Request

- Include the screenshot of the running application taken in the Development step.
