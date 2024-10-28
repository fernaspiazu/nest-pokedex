<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Pokedex

## Run in dev mode

1. Clone the repo
2. Install dependencies

   ```
   pnpm install
   ```

3. Install Nest CLI

   ```shell
   npm i -g @nestjs/cli
   ```

4. Deploy MongoDB instance

   ```shell
   docker-compose up -d
   ```

5. Re-build database with a seed

   ```
   http://localhost:3000/api/v2/seed
   ```

## Used stack

- NodeJS
- NestJS
- MongoDB
