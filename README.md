# Install
- Requires Node.js 20.6+
- Clone the project
- `pnpm install`

# Run
- `npm run dev` (or `node --run dev` if Node.js 22+)
- You should have the following error : `SyntaxError: The requested module './lib/receiver.js' does not provide an export named 'default'`


- Downgrade to `@swc-node/register@1.9.0` (`pnpm add -D @swc-node/register@1.9.0`)
- `npm run dev` (or `node --run dev` if Node.js 22+)
- It should works
