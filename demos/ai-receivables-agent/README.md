# Receivables agent: a field prototype

**Live demo:** [open in the browser](https://htmlpreview.github.io/?https://github.com/alihanarica/alihanarica/blob/main/demos/ai-receivables-agent/index.html)

A one-day prototype that shows how I prepare a value conversation with a customer: a working screen, a value case and pilot criteria, all in their own terms.

The scenario is a Turkish machinery maker whose collections team builds its daily call list by hand. The agent:

1. **Reads** open invoices, payment history, credit limits and open disputes.
2. **Scores** each invoice from five factors and shows the reasons behind every score.
3. **Proposes** one next action per invoice and drafts a reminder in Turkish.
4. **Waits for approval.** A collector approves or changes each action. Nothing is sent without a person.

The page also has:

- a **value case** with editable assumptions: cash released, financing cost saved, collector time saved and payback;
- **pilot acceptance criteria** agreed before the pilot starts;
- a **data map** showing where each field would come from in an SAP S/4HANA landscape, with the agent built in Joule Studio.

## What it is and is not

- It is not an SAP product and is not connected to any system.
- The company, customers and figures are invented.
- SAP offers its own Joule agents for receivables. A prototype like this helps a customer see the value before a pilot of the real product.

## How to run it

Open `index.html` in any browser. It is a single file with no dependencies and no API key. No data leaves the page.

Built with AI coding tools by [Alihan Arıca](https://www.linkedin.com/in/alihanarica), November 2026.
