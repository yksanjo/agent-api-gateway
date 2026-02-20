# agent-api-gateway-cli

> Package 4: cli for Intelligent API Gateway

## Installation

```bash
npm install @agent-api-gateway/agent-api-gateway-cli
```

## Usage

```javascript
import { AgentApiGatewayCli } from '@agent-api-gateway/agent-api-gateway-cli';

const service = new AgentApiGatewayCli();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
