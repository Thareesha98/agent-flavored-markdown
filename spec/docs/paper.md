---
hide:
  - navigation
---

# Paper

**Agent-Flavored Markdown: Natural Language Specifications for Framework-Agnostic Agent Development**

Maryam Ziyad Mohamed, Hasitha Aravinda, Rania Khalaf — WSO2

Published at [AgentCraft 2026](https://dl.acm.org/doi/10.1145/3742414.3794957){ target=_blank rel=noopener },
the Workshop on Agentic AI Systems Development, and collected in the
[Joint Proceedings of the ACM IUI 2026 Workshops](https://ceur-ws.org/Vol-4266/){ target=_blank rel=noopener }
(CEUR Workshop Proceedings, Vol. 4266). Limassol, Cyprus, July 2026.

[Read the paper (PDF)](https://ceur-ws.org/Vol-4266/paper03.pdf){ .md-button .md-button--primary target=_blank rel=noopener }

## Abstract

Building AI agents today requires either expertise in framework-specific APIs and abstractions, or reliance on
low-code platforms that couple agent logic with execution configuration. In both cases, the agent's core
behavioral instructions — expressed in natural language — become embedded within code or tool interfaces, while
framework-specific abstractions limit portability. We present Agent-Flavored Markdown (AFM), a natural
language-first specification for defining portable AI agents. AFM treats agent instructions as the primary
content, expressed in human-readable markdown, with configuration such as tools, model configuration, and
interfaces specified as structured YAML front matter. This separation of concerns keeps agent behavior readable
even as technical complexity grows, making it easier for both developers and domain experts to author and
collaborate while enabling the same agent definition to work with different frameworks through tools such as
interpreters or code generators. We describe the AFM specification and demonstrate its feasibility and
portability with reference implementations.

**Keywords:** AI agents, No-code agent builders, Agent portability

## Citation

<div class="wrap-code" markdown="1">

```bibtex
@inproceedings{mohamed2026afm,
  title={Agent-Flavored Markdown: Natural Language Specifications for Framework-Agnostic Agent Development},
  author={{Ziyad Mohamed}, Maryam and Aravinda, Hasitha and Khalaf, Rania},
  booktitle={Joint Proceedings of the ACM IUI 2026 Workshops co-located with the 31st Annual ACM Conference on Intelligent User Interfaces (IUI 2026)},
  editor={Tommasel, Antonela and Kahr, Patricia and Dinakar, Karthik and others},
  series={CEUR Workshop Proceedings},
  volume={4266},
  publisher={CEUR-WS.org},
  issn={1613-0073},
  year={2026},
  url={https://ceur-ws.org/Vol-4266/paper03.pdf}
}
```

</div>

The paper is published under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/){ target=_blank rel=noopener }
as part of CEUR-WS.org Vol-4266.
