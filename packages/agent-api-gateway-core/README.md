# agent-api-gateway-core

> Package 1: core for Intelligent API Gateway

## Installation

```bash
npm install @agent-api-gateway/agent-api-gateway-core
```

## Usage

```javascript
import { AgentApiGatewayCore } from '@agent-api-gateway/agent-api-gateway-core';

const service = new AgentApiGatewayCore();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
