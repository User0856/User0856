## About

I build APIs and developer tools for AI agents and automation.

Currently building [SnapRender](https://snap-render.com) - a screenshot API that lets developers and AI agents capture any web page programmatically. Used in agent frameworks, browser automation, monitoring pipelines, and link preview generators.

### SnapRender

| | |
|---|---|
| API | [snap-render.com](https://snap-render.com) |
| Node.js SDK | [`snaprender`](https://www.npmjs.com/package/snaprender) on npm |
| Python SDK | [`snaprender`](https://pypi.org/project/snaprender/) on PyPI |
| MCP Server | [`@snaprender/mcp-server`](https://www.npmjs.com/package/@snaprender/mcp-server) for Claude, Cursor, Windsurf |
| OpenAPI Spec | [openapi.json](https://api.snap-render.com/openapi.json) for GPT Actions and custom integrations |
| Postman | [Collection](https://github.com/User0856/snaprender-integrations) |

### What it does

- Renders full pages or elements as PNG, JPEG, WebP, PDF
- Device emulation (iPhone, Pixel, iPad, desktop)
- Dark mode capture, ad blocking, cookie banner removal
- Smart caching via Cloudflare R2
- Free tier: 500 screenshots/month, no credit card

### AI and agent integration

SnapRender is built to work with AI agents that need to see the web. The MCP server gives Claude and other LLM-based agents direct access to screenshot capabilities. The OpenAPI spec plugs into GPT Actions and any agent framework that supports tool use.

If you're building agents that interact with websites, monitoring tools, or anything that needs visual web data - [check it out](https://snap-render.com).
