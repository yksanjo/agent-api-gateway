# agent-api-gateway-database

> Integration: database for Intelligent API Gateway

## Installation

```bash
npm install @agent-api-gateway/agent-api-gateway-database
```

## Usage

```javascript
import { AgentApiGatewayDatabase } from '@agent-api-gateway/agent-api-gateway-database';

const service = new AgentApiGatewayDatabase();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
