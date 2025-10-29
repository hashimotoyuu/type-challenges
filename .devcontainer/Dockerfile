FROM node:20-slim

# pnpmを利用するためにcorepackを有効化
RUN corepack enable

WORKDIR /workspace
COPY . .

RUN pnpm install
