---
version: alpha
name: LLM Lessons
description: Clean, academic reading layout for self-paced AI/ML education. High readability, minimal distraction, code-friendly.
colors:
  primary: "#111827"
  secondary: "#4B5563"
  tertiary: "#2563EB"
  neutral: "#F9FAFB"
  code-bg: "#F3F4F6"
  accent: "#10B981"
typography:
  h1:
    fontFamily: Inter
    fontSize: 2.25rem
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  h2:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.01em"
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.75
  code:
    fontFamily: "JetBrains Mono"
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.6
rounded:
  sm: 4px
  md: 8px
  lg: 12px
spacing:
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
components:
  card:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.primary}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  code-block:
    backgroundColor: "{colors.code-bg}"
    textColor: "{colors.primary}"
    rounded: "{rounded.sm}"
    padding: "{spacing.md}"
  tag:
    backgroundColor: "{colors.tertiary}"
    textColor: "#FFFFFF"
    rounded: "{rounded.sm}"
    padding: 6px
---

## Overview

A focused, high-contrast reading layout optimized for technical education. Uses Inter for body/headings and JetBrains Mono for code. Generous line-height and constrained max-width for comfortable reading. Cards group related concepts; code blocks are visually distinct but not overwhelming.

## Colors

- **Primary (#111827):** Near-black for all body text and headings.
- **Secondary (#4B5563):** Muted gray for metadata, timestamps, and captions.
- **Tertiary (#2563EB):** Blue accent for links, tags, and interactive highlights.
- **Neutral (#F9FAFB):** Page background.
- **Code-bg (#F3F4F6):** Subtle gray for code blocks and inline code.
- **Accent (#10B981):** Green for key takeaways and success indicators.

## Typography

Inter for all prose. JetBrains Mono for code. Tight letter-spacing on headings for a modern, editorial feel. Generous line-height (1.75) on body text for readability.

## Layout

Max-width container of 720px for optimal reading line length. Cards use 16px padding. Spacing scale follows 8px base units.

## Components

`card` wraps lesson sections with white background and subtle shadow. `code-block` provides a distinct background for snippets. `tag` is used for topic labels and badges.
