# Angular CLI

Just my code from following [John Papa's course on Pluralsight](https://app.pluralsight.com/library/courses/angular-cli/table-of-contents).

## Tips:

 `ng lint --fix`

### Blueprints

`ng g \<blueprint\> \<name\>`

`--flat` - Should a folder be created?

`--prefix` - prefix the blueprint with a prefix

`--dry-run` - test without creating files first

### Building

```
npm install webpack-bundle-analyzer --save-dev
ng build --stats-json
npx webpack-bundle-analyzer dist/my-app/stats.json
```

Or

```
npm install source-map-explorer --save-dev
ng build
npx source-map-explorer dist/my-app/main.js
```

### Tests

`ng test --code-coverage`
`npm e2e`

### Tooling

`ng update` --> update angular + 3rd party libs

 `--dryRun` / `-d`

 `--all` (update everything)

[update.angular.io](https://update.angular.io) --> guide