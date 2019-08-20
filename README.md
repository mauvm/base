# Base

> Base setup.

## Usage

- Setup
- Development
- Training classifier

### Setup

First setup directory and install Node dependencies:

```bash
git clone https://github.com/mauvm/base
cd base

yarn install
```

Configure the project:

```bash
cp .env.example .env
chmod 600

# Add configuration values to .env
edit .env
```

Finally, run the database migrations:

```bash
yarn knex migrate:latest
```

### Development

Run the following command for development:

```bash
yarn dev
```

The script will be restarted on file changes.

Before committing code, run:

```bash
yarn lint
yarn test
```

## To Do

- [ ] List to do's here

## Quirks & Caveats

- List quirks and caveats here

## License

See `LICENSE` file.
