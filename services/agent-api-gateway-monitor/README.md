# agent-api-gateway-monitor

> Service: monitor for Intelligent API Gateway

## Installation

```bash
npm install @agent-api-gateway/agent-api-gateway-monitor
```

## Usage

```javascript
import { AgentApiGatewayMonitor } from '@agent-api-gateway/agent-api-gateway-monitor';

const service = new AgentApiGatewayMonitor();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
