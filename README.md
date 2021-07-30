# Frontity OSS Licenses

This repository contains a summary of all the licenses used in the Frontity Project.

To view them, please visit: https://frontity.github.io/oss-licenses/

## Updating Licenses

To retrieve the licenses from a repository, follow the next steps:

- Update the relevant `package.json`.
- Run `npm install`.
- Run `npx nlf > liceneses.txt --summary detail`.
- Copy and paste the new licenses (ordered by license) to the `index.md` file.
- Run `npx nlf > liceneses.csv -c`.
- Transform the csv file into a markdown table.
  _You can use [this tool](https://donatstudios.com/CsvToMarkdownTable)._
- Copy and paste the new table to the `index.md` file.
- Change the "Updated" field.
- Finally, transform the markdown file into HTML.
  _You can use [this VS Code extension](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)._
