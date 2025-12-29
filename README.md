# OceanBase Developer Portal

This is the official developer portal and navigation hub for [OceanBase](https://oceanbase.github.io/), an enterprise-grade open-source distributed SQL database. 

OceanBase is an unlimited scalable distributed database for data-intensive transactional and real-time operational analytics workloads, with ultra-fast performance that has achieved world records in the TPC-C benchmark test. It has served over 1000 customers globally and supports all mission-critical systems in Alipay.

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Prerequisites

- Node.js >= 18.0
- pnpm >= 8.0

### Installation

```bash
$ pnpm install
```

### Local Development

```bash
$ pnpm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```bash
$ pnpm build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```bash
$ USE_SSH=true pnpm deploy
```

Not using SSH:

```bash
$ GIT_USER=<Your GitHub username> pnpm deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
