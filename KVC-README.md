<!-- KVC Brand Header -->
<div align="center">
<img src="https://cdn.abacus.ai/images/134ce4b7-b0d1-4ba8-8655-3afd323fb646.png" width="64" height="64"/>

# KVC Composio
### by KaliVibeCoding

**AI tool integrations — connected to the KVC enterprise.**
250+ app integrations. Wired to Kimi 3, Cloudflare, and GHL.

`Code to the Rhythm. Build by the Beat.`
</div>

## KVC Priority Integrations

| Integration | Purpose | KVC Use |
|------------|---------|---------|
| GoHighLevel | CRM | Contact sync, pipeline automation |
| Cloudflare | Infrastructure | Workers, R2, KV, D1 |
| GitHub | Code | KaliVibeCoding org automation |
| Google Workspace | Productivity | Drive, Sheets, Calendar |
| Stripe | Payments | Program enrollment, billing |

## Quick Setup
```python
from composio import ComposioToolSet

# KVC Composio toolset with Kimi 3
toolset = ComposioToolSet(api_key=os.environ["COMPOSIO_API_KEY"])
tools = toolset.get_tools(apps=["GITHUB", "GOOGLESHEETS", "STRIPE", "SLACK"])

# Wire to Kimi 3
from openai import OpenAI
kimi = OpenAI(
    base_url="https://api.moonshot.cn/v1",
    api_key=os.environ["MOONSHOT_API_KEY"]
)
```

Apply brand: `@import "./kvc-brand.css";` in frontend entry CSS.
