# Anchovies

Get all the World of Warcraft achievements!

## Development

- Clone repository
- Install [docsify](https://docsify.js.org/#/quickstart) globally or locally
- Run `docsify serve`
- Navigate to http://localhost:3000

## Adding New Content

- Create a new `.md` file in an appropriate location.
  - If needed, copy [content/\_template.md](content/_template.md) as a starter template.
- Add any necessary YAML front matter to the top.
  - Front matter variables can be referenced via mustache + dot-notation syntax (i.e. `{{ parent.child.grandchild }}`).
- Add a new relative link to the [sidebar](content/_sidebar.md) file.

## Troubleshooting

- Q: `[object Object]` appears at the top of the rendered HTML.
- A: Your YAML is invalid in some way. Check for single-quoted strings with apostrophes, empty YAML keys, etc.
