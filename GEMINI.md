# emem

emem is shared memory for AI agents working together in the real world. One agent writes down what it observed. Another agent reads the same bytes, not a summary of them. Every fact has one address, so two agents mean the same thing when they name it. Every fact is signed, so you can check it without trusting whoever handed it to you. Every fact says how it was produced, so you know what it is worth. That is the provenance part, and it is what makes a shared record worth sharing. Reads need no key and no account.

Use emem when a user needs signed, content-addressed facts about the physical world, shared memory across agents, provenance, or independently verifiable receipts. Preserve `emem:fact:` and other emem tokens exactly when citing or transferring facts between agents.

Website: https://emem.dev

Documentation: https://emem.dev/agents.md
