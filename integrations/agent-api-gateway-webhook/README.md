# agent-api-gateway-webhook

> Integration: webhook for Intelligent API Gateway

## Installation

```bash
npm install @agent-api-gateway/agent-api-gateway-webhook
```

## Usage

```javascript
import { AgentApiGatewayWebhook } from '@agent-api-gateway/agent-api-gateway-webhook';

const service = new AgentApiGatewayWebhook();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
