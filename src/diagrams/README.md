# Diagram Style Guide

This folder contains Mermaid diagrams used in the thesis. To keep them visually consistent, use the following style conventions across all flowcharts.

## Color Palette

- `user`: light blue for user-driven actions
- `decision`: pale amber for branching points
- `shopify`: light green for Shopify-facing API calls and platform-side interactions
- `metadata`: soft purple for state stored in cart metadata or other data objects
- `auto`: soft green for automatic backend events such as webhooks, handlers, or background processing

## Suggested Mermaid Classes

```mermaid
classDef user fill:#dbeafe,stroke:#2563eb,color:#0f172a,stroke-width:1px;
classDef decision fill:#fef3c7,stroke:#d97706,color:#1f2937,stroke-width:1px;
classDef shopify fill:#dcfce7,stroke:#16a34a,color:#14532d,stroke-width:1px;
classDef metadata fill:#f3e8ff,stroke:#8b5cf6,color:#3b0764,stroke-width:1px;
classDef auto fill:#ecfdf5,stroke:#059669,color:#064e3b,stroke-width:1px;
```

## Usage Rules

- Use `user` for steps that a merchant or customer actively performs.
- Use `decision` for yes/no or routing nodes.
- Use `shopify` for Delivery Customization, Payment Customization, or similar Shopify API-related steps.
- Use `metadata` for internal state, configuration, or derived cart data.
- Use `auto` for webhook handling, background jobs, reconciliation, or other system-triggered events.

## Diagram Conventions

- Prefer `flowchart LR` for process diagrams that should read left to right.
- Use `<br/>` for line breaks inside node labels.
- Prefer explicit subflow names when a diagram has multiple user paths.
- Keep terminal automatic events visually distinct from user actions.
- Reuse the same class names in every Mermaid file rather than inventing new palettes per diagram.

## Current Diagram

The current user-flow diagram in this folder is [shopickup-user-flows.mmd](shopickup-user-flows.mmd).

## Exporting to PNG

To export to PNG [Mermaid Live Editor](https://mermaid.live/) can be safely used without breaking the styling. Just copy over the ready Mermaid code from the `.mmd` file, paste it in the editor, and export as PNG. Make sure that sizing is sufficient to be readable, recommended minimum 2000px on the longest side.
