# agent-api-gateway-analyzer

> Service: analyzer for Intelligent API Gateway

## Installation

```bash
npm install @agent-api-gateway/agent-api-gateway-analyzer
```

## Usage

```javascript
import { AgentApiGatewayAnalyzer } from '@agent-api-gateway/agent-api-gateway-analyzer';

const service = new AgentApiGatewayAnalyzer();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
