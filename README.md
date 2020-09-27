# vscode-sql-template-literal

Syntax highlighting for code like:

```ts
const query = prisma.$rawQuery`SELECT * FROM users`;
const query = prisma.$rawQuery<User[]>`SELECT * FROM users`;
```

## Publishing

https://code.visualstudio.com/api/working-with-extensions/publishing-extension#publishing-extensions

```
npm install -g vsce
vsce package
vsce publish
```
