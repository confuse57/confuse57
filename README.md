# Hi, I'm Bhavin

Solo founder at Tagbudy Services, Valsad-Gujarat-India. Building **BEHAVR**.

## BEHAVR: visual memory API for AI apps & AI websites

Give your AI app persistent visual memory in two calls. `remember()` an image or video, `ask()` about it later.

```js
await behavr.remember({ file, externalUserId });
const { answer } = await behavr.ask({ question, externalUserId });
```

- Try it, no signup: https://behavr.in/#/playground
- Docs: https://behavr.in/#/docs
- SDK: `npm install behavr-sdk` (https://www.npmjs.com/package/behavr-sdk)
- MCP server: `npx -y behavr-mcp` (https://github.com/confuse57/behavr-mcp), tested with Claude Code
- Full example app: https://github.com/confuse57/behavr-example-app

Building in public on X: @bhavin_Confuse and @Behavr_AI
