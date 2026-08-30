<p align="center">
  <a href="https://en.wikipedia.org/wiki/Infinite_monkey_theorem">
    <img src="./typewriter.svg" alt="A monkey hitting keys at random on a typewriter for an infinite amount of time will almost certainly type any given text.">
  </a>
  <br>
  <sub>— Émile Borel, 1913</sub>
</p>

[![Tokscale Stats](https://tokscale.ai/api/embed/Keonho-Chu/svg?view=3d&sort=cost)](https://tokscale.ai/u/Keonho-Chu)

## 🔧 Open Source Contributions

**[CozyClay](https://github.com/NomaDamas/CozyClay)** ★478 — open-source previs studio in the browser (Three.js / R3F)
- Failure containment: React error boundary, WebGL context-loss recovery, guarded storage writes — [#64](https://github.com/NomaDamas/CozyClay/pull/64) (merged)
- `npm run dev` on a fresh clone no longer dies without a Kimodo GPU host — [#72](https://github.com/NomaDamas/CozyClay/pull/72) (merged)
- Fresh-machine `npm test`: stated the real Node 22.13 floor for `node:sqlite` and fixed a float32 assertion that only passed where it was skipped — [#73](https://github.com/NomaDamas/CozyClay/pull/73) (merged)
- Aligned the controls table and ARDY docs with the code — [#54](https://github.com/NomaDamas/CozyClay/pull/54) (merged)
- Found & reported the File System Access re-auth bug and the MCP CI coverage gap — [#51](https://github.com/NomaDamas/CozyClay/issues/51), [#52](https://github.com/NomaDamas/CozyClay/issues/52) (both fixed upstream within a day)

**[oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)** ★68k — the agent harness for complex codebases
- `ulw_execute.auto_merge`: hold integration for user approval — [#7177](https://github.com/code-yeongyu/oh-my-openagent/pull/7177) (in review)
- Restore bash for Prometheus scoped to the ulw-plan scaffold script — [#7178](https://github.com/code-yeongyu/oh-my-openagent/pull/7178) (in review)
- Restore npm-launcher parity in the compiled `omo-native` entry — [#7489](https://github.com/code-yeongyu/oh-my-openagent/pull/7489) (in review)

**[Gajae Code](https://github.com/Yeachan-Heo/gajae-code)** ★2.6k — coding agent
- Implicit discovery of local vLLM servers — [#4898](https://github.com/Yeachan-Heo/gajae-code/pull/4898) (merged)
- Implicit discovery of local SGLang servers — [#4931](https://github.com/Yeachan-Heo/gajae-code/pull/4931) (merged)
- Allow unauthenticated vLLM runtime discovery — [#4895](https://github.com/Yeachan-Heo/gajae-code/pull/4895) (merged)
- Stop persisting the vLLM no-auth sentinel — [#4980](https://github.com/Yeachan-Heo/gajae-code/pull/4980) (merged)
- Match decomposed (NFD) Korean file names in path autocomplete — [#4997](https://github.com/Yeachan-Heo/gajae-code/pull/4997) (merged)
- Hangul chosung matching for fuzzy file search — [#5008](https://github.com/Yeachan-Heo/gajae-code/pull/5008) (merged)
- Decode quoted (non-ASCII) diff paths as UTF-8 bytes in the `gh` tool — [#5071](https://github.com/Yeachan-Heo/gajae-code/pull/5071) (in review)

**[GraphRAG](https://github.com/microsoft/graphrag)** ★35.7k — Microsoft's graph-based RAG system
- Caught a type mismatch in the `DynamicCommunitySelection` children lookup and proposed the fix — [#2124](https://github.com/microsoft/graphrag/pull/2124), resolved upstream in [#2159](https://github.com/microsoft/graphrag/pull/2159)

![Notable contributions](./metrics.notable.svg?v=7)
