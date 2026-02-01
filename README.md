# Homebrew Tap for TransactRx

## Installation

```bash
brew tap transactrx/tap
brew install nats-discover
```

## Available Formulas

- **nats-discover** - CLI tool to discover NATS services using the nats-service framework

## Usage

After installation:

```bash
# List all services
nats-discover -s nats://localhost:4222

# Get API docs for a specific service
nats-discover -s nats://localhost:4222 -S orders.api

# Show version
nats-discover --version
```

For more information, see the [nats-service repository](https://github.com/transactrx/nats-service).
