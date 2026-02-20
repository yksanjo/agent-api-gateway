# agent-api-gateway-api

> Package 2: api for Intelligent API Gateway

## Installation

```bash
npm install @agent-api-gateway/agent-api-gateway-api
```

## Usage

```javascript
import { AgentApiGatewayApi } from '@agent-api-gateway/agent-api-gateway-api';

const service = new AgentApiGatewayApi();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
