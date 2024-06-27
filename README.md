# Reservation

## Getting Started

### Prerequisites

- Node.js v20.0.0
- Docker

### Installation

1. Clone the repository
2. Install dependencies

```bash
yarn install
```

3. Create a `.env` file in the root directory

```bash
DB_NAME=root
DB_USER=root
DB_PASSWORD=root
DB_PORT=55432
```

4. Start the database

```bash
docker-compose up -d
```

5. Run the server

```bash
yarn start
```

6. Open the GraphQL Playground

```bash
http://localhost:4000/graphql
```
