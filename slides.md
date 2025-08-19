---
marp: true
theme: custom-theme
size: 16:9
paginate: true
header: "Product Docs — Technical"
footer: "Contact: 24f2005647@ds.study.iitm.ac.in"
style: |
  section::after {
    content: 'Page ' attr(data-marpit-pagination) ' / ' attr(data-marpit-pagination-total);
    position: absolute;
    right: 1rem;
    bottom: 0.6rem;
    font-size: 0.9rem;
    color: rgba(0,0,0,0.6);
  }
---

# Product X — Documentation Overview

📧 Contact: 24f2005647@ds.study.iitm.ac.in

---

![bg](assets/bg-architecture.jpg)

# Architecture Overview

System design and components at a glance.

---

# Key Features

- **High performance** data pipeline <!-- .element: class="fragment" -->
- **Secure by design** with audits <!-- .element: class="fragment" -->
- **Extensible** plugin system <!-- .element: class="fragment" -->

---

# Example: Config Parsing (Python)

```python
def parse_config(cfg):
    """Normalize config keys to lowercase"""
    return {k.lower(): v for k, v in cfg.items()}
