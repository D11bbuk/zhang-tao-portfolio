**Findings**

- [P1] Browser-rendered visual comparison unavailable.
  Location: Homepage and project reader.
  Evidence: The source visual truth is the supplied PDF at `D:/Program Files/Files/personal file/整合/作品集/files/作品集_张涛_l.pdf`; the in-app browser blocks opening the local prototype URL by policy, so an implementation screenshot cannot be captured.
  Impact: Final viewport-level comparison of typography, spacing, particle behavior, and responsive image fitting has not been possible.
  Fix: Open the local `index.html` in a browser and provide a screenshot or a locally accessible preview URL for a final visual-QA pass.

**Open Questions**

- Implementation is deliberately a black-and-white exhibition interpretation of the supplied PDF, rather than a pixel-perfect reproduction of its interior page backgrounds.

**Implementation Checklist**

- Confirmed every page reference resolves to an exported A3 landscape image.
- Confirmed the homepage and three project readers preserve their intended PDF page order.
- Confirmed JavaScript syntax for background interaction, sound feedback, and reader controls.

**Follow-up Polish**

- Review at desktop and mobile sizes to adjust the exact particle density and the hero cover scale to personal preference.

Source visual truth path: `D:/Program Files/Files/personal file/整合/作品集/files/作品集_张涛_l.pdf`

Implementation screenshot path: unavailable — local file URLs are blocked by the in-app browser policy.

Viewport: unavailable.

State: homepage initial state; project-reader initial state intended.

Full-view comparison evidence: unavailable.

Focused region comparison evidence: unavailable because no browser-rendered implementation screenshot could be captured.

Primary interactions tested: static code validation only; in-browser interaction testing blocked.

Console errors checked: unavailable because browser navigation was blocked.

Comparison history: initial QA blocked before a screenshot could be captured.

final result: blocked
