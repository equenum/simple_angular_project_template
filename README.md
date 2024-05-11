# simple_angular_project_template

A simple Angular project template to use with the [`Project Templates`](https://github.com/cantonios/vscode-project-templates) VSCode extension.

### Save the template locally:

1. Clone or download the repository.
2. Copy all the files except for `.git` folder and `README.md` into a new empty folder.
3. Open the folder in VS Code.
4. Follow [the official documentation](https://github.com/cantonios/vscode-project-templates?tab=readme-ov-file#saving-a-project-as-a-template) to save the template.

### Project configurations:

- `no-strict` enabled.
- `standalone` disabled.
- `routing` disabled.
- `CSS` stylesheet format.
- `Server-Side Rendering (SSR)` and `Static Site Generation (SSG)` disabled.
- `Bootstrap3` included.

### Variable placeholders

1. PageTitle: represents the `index.html` page `<title>` element value (browser tab page name) as well as `AppComponent` title.

### Run locally:

```bash
cd my-app

npm install

ng serve
```
