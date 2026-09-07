# Proper Job for Claude

Calculate and compare indicative UK building-work budgets with Proper Job from Claude Code or Cowork. The plugin connects Claude to Proper Job’s hosted, deterministic pricing service and adds a focused estimating workflow. It contains no pricing engine, internal rates or customer database.

Proper Job is owned and operated by [SR3H Ltd](https://www.proper-job.uk). See the [calculator documentation](https://www.proper-job.uk/chatgpt), [privacy policy](https://www.proper-job.uk/privacy), [terms](https://www.proper-job.uk/terms) and [support](https://www.proper-job.uk/support).

## What Claude can do

- Ask for the material scope details needed for a supported UK estimate.
- Calculate a new indicative GBP guide-price range using `calculate_guide_price`.
- Compare up to three supplied size, finish or scope alternatives using `compare_guide_scenarios`.
- Explain VAT treatment, assumptions, exclusions and items still to confirm.
- Render the optional Proper Job result card where the host supports MCP Apps.

No Proper Job account, subscription, API key or bearer token is required. Ordinary calculations have no Proper Job payment gate or free-use allowance. Short-window abuse controls and the host’s own limits remain. Proper Job still pays its normal hosting and database costs.

## Data and security boundary

The plugin connects only to `https://www.proper-job.uk/api/mcp` over Streamable HTTP. It sends typed scope supplied in the conversation. Use an outward postcode such as `BS3`; do not send an exact address.

There are no tools for customer accounts, jobs, saved estimates, exact addresses, drawings, payments, email, SQL, file access, source code or full rate-table exports. Calculations are not saved as projects. The package has no executable scripts, hooks, dependency installation, local-file access or telemetry. Public requests may produce standard operational logs and short-lived abuse counters as described in Proper Job’s privacy policy.

## Example

Ask Claude:

> Use Proper Job to calculate a guide price for a 30 m² rear extension in BS3, good domestic finish, balanced scope, semi-detached house, no kitchen work and no bathroom work. Then compare 40 m² with everything else unchanged.

A Guide Price is an early indicative budget, not a fixed contractor quotation. UK coverage only. VAT treatment is stated in every result.

## Publication status

This public repository is the reviewable source for a Claude community-plugin-directory submission. A submitted or installed plugin is separate from Anthropic’s verified Connectors Directory. Directory acceptance and recommendation are not guaranteed.

## License

The connector configuration and documentation are MIT licensed. The Proper Job logo and brand marks are excluded and remain their owner’s property; the included logo may be displayed to identify this integration. No rights to the hosted service, pricing data or source code are granted.
