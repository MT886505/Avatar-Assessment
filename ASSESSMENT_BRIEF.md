# Avatar Investments — Forward Deployed Engineer · Technical assessment

## The context

Among the most painful and least digitized processes in manufacturing companies is the handling of **RFQs** (*Requests for Quotation*). A sales engineer receives, by email, a messy package — free text, technical specifications in PDF, drawings. From there they have to extract the technical and commercial parameters by hand, cross-check them between specification and drawing, and prepare a draft quote. For every single request, hours of slow, repetitive, error-prone work.

## The task

A sales engineer at a company that manufactures mechanical components for energy plants has just received the attached RFQ package for **RFQ QR-2026-0884** (part **CS-SPR-1140**): the customer's email, a material & product specification, and a detailed technical drawing. *Today they extract everything by hand and fill in the quote by hand.*

**Build a tool that lets them upload this RFQ package and, hands-off (single upload, no manual prompting), get a structured draft quote in about 60 seconds** ready to **review, correct, and export.**

## What's in the package

Everything inside `rfq-package/`:

- `RFQ_email.md` — the customer's email.
- `Material_Specification_Springs.pdf` — *Material & Product Specification* (REF QR-2026-0884, ITEM CS-SPR-1140, REQ. No. MR-26-3391 Rev 0).
- `CS-SPR-1140_Spring_Detail.png` — detailed technical drawing: compression spring (Dwg. **7820**) and protective end cap (item **7821**), with dimensions, loads, and tolerances.

> **Note — the package is deliberately "raw".** Like a real RFQ, it contains ambiguities and inconsistencies that a good tool should surface, not hide.

## Constraints

- **Delivery within 7 calendar days of receiving the brief, by end of day.**
- **Expected effort: maximum 2 hours of work.** You have 7 days to organize yourself however you prefer, but don't expect — and we don't expect — a finished product: we're interested in seeing how far you get in that time and what choices you make. The result we evaluate is indicative of what we'd expect from 2 hours of focused work.
- **Choose whatever stack you prefer.** What counts is delivering something that works, not using the tools we use.
- **Out of scope (don't waste time on it):** authentication, multi-tenancy, deployment infrastructure, scalability, exhaustive testing, marketing copy.

## What to deliver

- A **private** GitHub repository with a README that gets us up and running in under 5 minutes. We'll tell you which GitHub accounts to invite as collaborators.

## What we evaluate

- **Product judgment — the decisions under constraint**
- **Substance — does it work end-to-end?**
- **Clarity of thought & communication — can you defend what you cut?**
