# prag-ai

**Agentic AI 자율 에이전트를 만들고 가르칩니다. 사람이 하던 일을 멀티에이전트로 나눠 자동화하는 것이 전문입니다.**

FDE(Forward Deployed Engineer) — 현장에 들어가 업무를 보고, 데이터를 잇고, 돌아가는 에이전트까지 만듭니다.

## 하는 일

현장에는 사람이 여러 자료를 찾아보고 판단해서 처리하는 일이 많습니다. 저희는 이런 일을 조회, 정리, 판단 같은 단계로 나누고, 단계마다 에이전트를 하나씩 맡겨 이어 붙입니다.

원칙은 하나입니다. 에이전트는 찾고, 정리하고, 근거를 붙여 제안까지 합니다. 승인 같은 마지막 판단은 사람이 합니다.

예를 들어 공장 설비에 알람이 뜨면 원인은 알람이 뜬 설비가 아니라, 아직 알람이 없는 상류 설비에 있을 때가 많습니다. 그래서 알람 목록이 아니라 설비 사이의 연결부터 데이터로 잇습니다. 이 작업의 일부를 [factory-graph-mcp](https://github.com/prag-ai/factory-graph-mcp)로 공개했습니다.

기업에 AI 에이전트 개발을 강의하고 컨설팅합니다.

## 공개 프로젝트

| 저장소 | 내용 |
|---|---|
| [factory-graph-mcp](https://github.com/prag-ai/factory-graph-mcp) | 공장 설비에 알람이 떴을 때 어디부터 봐야 하는지 짚어 주는 MCP 서버. 설비 대장과 연결 테이블(CSV)을 읽어, AI가 전원·냉각수·압축공기를 보내는 상류 설비를 따라 올라가게 합니다. 원인을 단정하지 않고 볼 곳만 알려 줍니다. 읽기 전용, MIT 라이선스. |

## 블로그·문의

AI 개발 도구를 직접 돌려 보고 결과를 적는 블로그를 운영합니다. 강의·컨설팅 문의도 이곳으로 받습니다.

https://prag-ai.com

---

**English** — prag-ai builds and teaches agentic AI, working as forward deployed engineers: we go on site, connect the data, and ship agents that run. We split human work into steps and automate it with multi-agent systems; people keep the final call, such as approval. First public project: [factory-graph-mcp](https://github.com/prag-ai/factory-graph-mcp), a read-only MCP server that helps AI trace upstream equipment when a factory alarm fires. Blog and contact: https://prag-ai.com
