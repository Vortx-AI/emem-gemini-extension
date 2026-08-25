# emem for Gemini CLI

Shared memory for AI agents working together in the real world.

emem is shared, signed and content-addressed memory of the physical world that AI agents can read, cite, transfer and independently verify.

emem is shared memory for AI agents working together in the real world. One agent writes down what it observed. Another agent reads the same bytes, not a summary of them. Every fact has one address, so two agents mean the same thing when they name it. Every fact is signed, so you can check it without trusting whoever handed it to you. Every fact says how it was produced, so you know what it is worth. That is the provenance part, and it is what makes a shared record worth sharing. Reads need no key and no account.

## Install

```bash
gemini extensions install https://github.com/Vortx-AI/emem-gemini-extension
```

Restart Gemini CLI after installation. Confirm that the extension and its MCP server are available:

```bash
gemini extensions list
gemini mcp list
```

The extension connects Gemini CLI to the public Streamable HTTP endpoint at `https://emem.dev/mcp`. It requires no API key or account for reads.

## Details

- Name: emem
- Version: 2.2.0
- Website: https://emem.dev
- Documentation: https://emem.dev/agents.md
- Tags: a2a-protocol, earth-observation, long-running-agents, long-term-memory, mcp, multi-agent, shared-memory, substrate, world-models

## License

Apache-2.0
