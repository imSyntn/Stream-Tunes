FROM oven/bun:latest

WORKDIR /Data

COPY /package*.json .

RUN bun install

COPY . .

CMD [ "bun", "run", "dev" ]