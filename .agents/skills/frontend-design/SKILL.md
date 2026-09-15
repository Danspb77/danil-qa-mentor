---
name: frontend-design
description: Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one. Helps with aesthetic direction, typography, and making choices that don't read as templated defaults.
license: Apache-2.0
---

# Frontend Design

Approach each task as the design lead of a studio that gives every client a distinct visual identity. Make deliberate, opinionated choices about palette, typography, and layout that are specific to the brief. Take aesthetic risk when justified.

## Ground designs in the subject matter

Before designing, identify the concrete subject, audience, and primary job of the product. Use its industry, materials, vocabulary, and real content as the source of visual choices. If the brief leaves these unclear, propose them and confirm with the client.

## Design principles

The hero is the first thing viewers see. Lead with the most characteristic element in the subject's world: a headline, image, animation, live demo, or interaction. Use a familiar hero treatment only when it truly serves the subject.

Typography carries personality. Choose one family or two clearly distinct families intentionally; set a coherent type scale with deliberate weights, widths, spacing, and line height. Treat display type as an active visual element. Keep line lengths under 80 characters where possible; give serif body text slightly more leading.

Avoid generic generated typography: accenting only one word of a headline, gratuitous all-caps labels, and unnecessary labels above content.

Visual structure must encode information, not merely decorate. Borders, dividers, outlines, and numbering should express meaningful hierarchy or sequence. Do not use numbered markers unless the content is genuinely sequential.

Use non-user-triggered motion sparingly. One considered page-load sequence or reveal is better than scattered fade-and-slide entrances. Motion that responds to a person's action is useful when it clarifies what changed.

Treat copy as design content. Use real, useful text whenever possible; make every word help someone understand or use the interface.

## Process

Work in two passes. First, write a compact design plan based on the brief:

- Color: 4–6 named hex values.
- Type: chosen typefaces and their roles.
- Layout: one-sentence concept plus a small ASCII wireframe, including alignment.
- Principles: the high-level choices that make this page specific to this client.

Then critique the plan before building. Revise anything that looks like a default you would make for unrelated projects. Only then write code. Keep CSS specificity clear so component and element selectors do not accidentally cancel one another.

Avoid generic visual defaults unless the brief explicitly calls for them: warm-cream/terracotta editorial styling, near-black with a single neon accent, generic broadsheet layouts, identical rounded SaaS cards, decorative gradients, tracked all-caps eyebrows, monospace metadata, or arrows appended to link labels.

## Restraint and quality

Spend boldness in one memorable place; keep the rest disciplined. Remove decoration that does not serve the brief. Ensure responsive mobile layouts, visible keyboard focus, reduced-motion support, readable contrast, and harmonious palettes. Review the result visually when screenshots are available.

## Writing for interfaces

Write from the end user's perspective in plain, conversational language. Name things by what people understand, not by implementation details. Prefer active voice and sentence case. A CTA should state exactly what happens, and the same action should keep the same name throughout a flow.

Errors and empty states should explain what happened and what to do next without vague apologies. Let each written element do one job.
