# agent-api-gateway-sdk

> Package 3: sdk for Intelligent API Gateway

## Installation

```bash
npm install @agent-api-gateway/agent-api-gateway-sdk
```

## Usage

```javascript
import { AgentApiGatewaySdk } from '@agent-api-gateway/agent-api-gateway-sdk';

const service = new AgentApiGatewaySdk();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
