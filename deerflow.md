
  
  [User Input] → [System Prompt Injection (skill list
  + memory)] → [Lead Agent]
       ↓
  [Middleware Chain Processing] → [LLM Decision] →
  [Tool Call Selection]
       ↓
  [Local Tool Execution] or [Skill Invocation] or
  [Sandbox Tools] or [MCP Tools] or [Subagent
  Delegation]
       ↓
  [Result Aggregation] → [State Update] → [AI Response
   Generation] → [MemoryMiddleware Collects
  Conversation] → [Asynchronous Memory Update]
       ↓
  [Return User Response] → [May Trigger New Round of
  Conversation]
