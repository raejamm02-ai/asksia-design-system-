---
version: "1.0"
name: AskSia
description: AskSia is an AI-powered study assistant web application that positions itself as a personal learning companion — built around a confident indigo-purple primary ({colors.action}), clean neutral surfaces, and an Inter-based typography system optimised for long-form reading and chat interfaces. The design language pairs near-white container layers ({colors.surface-container-lowest}) with precisely tiered border tokens to create clear depth without heavy shadow. Semantic color roles (text, surface, border, icon) alias cleanly into a full 50-900 base palette, giving every component a predictable, accessible contract. Core surfaces lean on soft neutrals; interactive elements snap to the primary indigo (#4e4df4) and its hover/active variants. The library covers a chat-first product (chat bubbles, file cards, summary panels), a sidebar-driven navigation shell, rich tab and chip systems, and a growing set of modular study-oriented cards (essay, flashcard, folder, file placeholder). The IP mascot character ({brand.ip-character}) provides warmth across empty, error, and onboarding states.

colors:
  # ── Brand primitives ───────────────────────────────────────
  primary-50:  "#eeeefe"
  primary-100: "#dcdbfd"
  primary-200: "#b8b8fb"
  primary-300: "#9594f8"
  primary-400: "#7171f6"
  primary:     "#4e4df4"
  primary-600: "#3e3ec3"
  primary-700: "#2f2e92"
  primary-800: "#1f1f62"
  primary-900: "#100f31"

  neutral-10:  "#f8f8f9"
  neutral-25:  "#f1f1f3"
  neutral-50:  "#eaeaec"
  neutral-100: "#dedee1"
  neutral-200: "#c7c7ce"
  neutral-300: "#b0afba"
  neutral-400: "#9998a7"
  neutral:     "#818193"
  neutral-600: "#686776"
  neutral-700: "#4e4d58"
  neutral-800: "#34343b"
  neutral-900: "#1a1a1d"

  success-50:  "#e1f5f0"
  success-100: "#c4ece2"
  success-200: "#93e3cf"
  success-300: "#66dec0"
  success-400: "#33d3ab"
  success:     "#00c896"
  success-600: "#00a078"
  success-700: "#00785a"
  success-800: "#00503c"
  success-900: "#00281e"

  error-50:  "#fae0e3"
  error-100: "#f7ccd1"
  error-200: "#ef99a3"
  error-300: "#e76676"
  error-400: "#e03348"
  error:     "#d8001a"
  error-600: "#ad0015"
  error-700: "#810010"
  error-800: "#56000a"
  error-900: "#2b0005"

  warning-50:  "#faf1e4"
  warning-100: "#f7e8d2"
  warning-200: "#f9daaf"
  warning-300: "#fbcd8c"
  warning-400: "#fdbf68"
  warning:     "#ffb245"
  warning-600: "#cc8e37"
  warning-700: "#996b2a"
  warning-800: "#66471c"
  warning-900: "#33240e"

  info-50:  "#f1f4ff"
  info-100: "#e4e9ff"
  info-200: "#cad3ff"
  info-300: "#afbcfe"
  info-400: "#95a6fe"
  info:     "#7a90fe"
  info-600: "#6273cb"
  info-700: "#495698"
  info-800: "#313a66"
  info-900: "#181d33"

  # ── Semantic — Text ────────────────────────────────────────
  text-primary:           "#1a1a1d"
  text-secondary:         "#34343b"
  text-secondary-mid:     "#686776"
  text-tertiary:          "#818193"
  text-disabled:          "#b0afba"
  text-on-disabled:       "#f8f8f9"
  text-action:            "#4e4df4"
  text-on-action:         "#ffffff"
  text-action-hover:      "#3e3ec3"
  text-success:           "#00785a"
  text-warning:           "#cc8e37"
  text-error:             "#d8001a"
  text-info:              "#495698"
  text-info-light:        "#7a90fe"

  # ── Semantic — Surface ─────────────────────────────────────
  surface-container-lowest:   "#ffffff"
  surface-container-lower:    "#f8f8f9"
  surface-container-low:      "#f1f1f3"
  surface-container:          "#eaeaec"
  surface-container-high:     "#dedee1"
  surface-container-highest:  "#c7c7ce"
  surface-container-dark:     "#9998a7"
  surface-container-darker:   "#686776"
  surface-container-darkest:  "#4e4d58"
  surface-container-black:    "#34343b"
  surface-highlight:          "#eeeefe"
  surface-blue:               "#f1f4ff"
  surface-yellow:             "#fbf3e8"
  surface-green:              "#e1f5f0"
  surface-action:             "#4e4df4"
  surface-action-hover:       "#3e3ec3"
  surface-action-hover-2:     "#dcdbfd"
  surface-action-secondary:   "#7a90fe"
  surface-success:            "#c4ece2"
  surface-warning:            "#f7e8d2"
  surface-error-low:          "#fae0e3"
  surface-error:              "#f7ccd1"
  surface-error-high:         "#e03348"
  surface-error-higher:       "#d8001a"
  surface-info:               "#e4e9ff"
  surface-info-high:          "#7a90fe"
  surface-disabled:           "#dedee1"

  # ── Semantic — Border ──────────────────────────────────────
  border-default:         "#f8f8f9"
  border-secondary:       "#eaeaec"
  border-tertiary:        "#dedee1"
  border-outline:         "#9998a7"
  border-outline-variant: "#b0afba"
  border-action:          "#4e4df4"
  border-action-hover:    "#2f2e92"
  border-focus:           "#4e4df4"
  border-success:         "#66dec0"
  border-warning:         "#fbcd8c"
  border-error:           "#e76676"
  border-info:            "#e4e9ff"
  border-info-light:      "#95a6fe"
  border-disabled:        "#c7c7ce"

  # ── Semantic — Icon ────────────────────────────────────────
  icon-primary:           "#4e4df4"
  icon-secondary:         "#4e4d58"
  icon-tertiary:          "#818193"
  icon-action:            "#4e4df4"
  icon-on-action:         "#ffffff"
  icon-action-hover:      "#3e3ec3"
  icon-success:           "#00a078"
  icon-warning:           "#cc8e37"
  icon-error:             "#d8001a"
  icon-info:              "#495698"
  icon-info-light:        "#7a90fe"
  icon-disabled:          "#818193"
  icon-on-disabled:       "#b0afba"

typography:
  heading-h1:
    fontFamily: Inter
    fontSize: 60px
    fontWeight: 700
    lineHeight: 1.10
    letterSpacing: 0
  heading-h2:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: 0
  heading-h3:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: 700
    lineHeight: 1.20
    letterSpacing: 0
  heading-h4:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0
  heading-h5:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.30
    letterSpacing: 0
  heading-h6:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.35
    letterSpacing: 0
  heading-h7:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.40
    letterSpacing: 0
  heading-h8:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.40
    letterSpacing: 0
  body-lg-regular:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.50
    letterSpacing: 0
  body-lg-medium:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.50
    letterSpacing: -0.03px
  body-lg-semibold:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.50
    letterSpacing: -0.03px
  body-lg-bold:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.50
    letterSpacing: -0.03px
  body-md-regular:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: -0.03px
  body-md-medium:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.43
    letterSpacing: -0.03px
  body-md-semibold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.43
    letterSpacing: -0.03px
  body-md-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.43
    letterSpacing: -0.03px
  body-sm-regular:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: -0.03px
  body-sm-medium:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.33
    letterSpacing: -0.03px
  body-sm-semibold:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1.33
    letterSpacing: -0.03px
  caption-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  caption-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: 0
  caption-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.40
    letterSpacing: 0
  caption-xs:
    fontFamily: Inter
    fontSize: 8px
    fontWeight: 400
    lineHeight: 1.50
    letterSpacing: 0

rounded:
  none: 0
  xs:   4px
  sm:   6px
  md:   8px
  lg:   12px
  xl:   16px
  2xl:  20px
  3xl:  24px
  4xl:  32px
  full: 9999px

spacing:
  0:    0px
  0.5:  0.5px
  1:    1px
  2:    2px
  4xs:  4px
  3xs:  8px
  2xs:  10px
  xs:   12px
  sm:   16px
  md:   20px
  lg:   24px
  xl:   28px
  2xl:  32px
  3xl:  40px
  4xl:  48px
  5xl:  56px
  6xl:  60px
  7xl:  64px
  8xl:  72px
  9xl:  80px
  10xl: 96px
  11xl: 128px
  12xl: 256px

components:
  # ── Buttons ────────────────────────────────────────────────
  button-primary:
    backgroundColor: "{colors.surface-action}"
    textColor: "{colors.text-on-action}"
    typography: "{typography.body-md-medium}"
    rounded: "{rounded.xs}"
    padding: "0 16px"
    height: 40px
    iconGap: 8px
  button-primary-hover:
    backgroundColor: "{colors.surface-action-hover}"
  button-primary-sm:
    backgroundColor: "{colors.surface-action}"
    textColor: "{colors.text-on-action}"
    typography: "{typography.body-sm-medium}"
    rounded: "{rounded.xs}"
    padding: "0 12px"
    height: 32px
  button-primary-lg:
    backgroundColor: "{colors.surface-action}"
    textColor: "{colors.text-on-action}"
    typography: "{typography.body-lg-medium}"
    rounded: "{rounded.lg}"
    padding: "0 24px"
    height: 48px
  button-primary-xl:
    backgroundColor: "{colors.surface-action}"
    textColor: "{colors.text-on-action}"
    typography: "{typography.body-lg-medium}"
    rounded: "{rounded.lg}"
    padding: "0 28px"
    height: 68px
  button-primary-pill:
    backgroundColor: "{colors.surface-action}"
    textColor: "{colors.text-on-action}"
    rounded: "{rounded.full}"
  button-secondary:
    backgroundColor: "{colors.surface-container-lowest}"
    textColor: "{colors.text-secondary}"
    typography: "{typography.body-md-medium}"
    rounded: "{rounded.xs}"
    padding: "0 16px"
    height: 40px
    border: "1px solid {colors.border-tertiary}"
  button-secondary-hover:
    backgroundColor: "{colors.surface-container-low}"
  button-tertiary:
    backgroundColor: "transparent"
    textColor: "{colors.text-secondary}"
    typography: "{typography.body-md-medium}"
    rounded: "{rounded.xs}"
    padding: "0 16px"
    height: 40px
  button-tertiary-active:
    backgroundColor: "{colors.surface-action-hover-2}"
    textColor: "{colors.text-action}"
  button-icon-primary:
    backgroundColor: "{colors.surface-action}"
    iconColor: "{colors.icon-on-action}"
    rounded: "{rounded.full}"
    size-xl: 64px
    size-lg: 56px
    size-md: 48px
    size-sm: 36px
  button-icon-secondary:
    backgroundColor: "{colors.surface-container-lowest}"
    iconColor: "{colors.icon-secondary}"
    rounded: "{rounded.full}"
    border: "1px solid {colors.border-tertiary}"
  button-icon-subtle:
    backgroundColor: "transparent"
    iconColor: "{colors.icon-tertiary}"
    rounded: "{rounded.full}"

  # ── Text Inputs & Search ───────────────────────────────────
  input-default:
    backgroundColor: "{colors.surface-container-lowest}"
    textColor: "{colors.text-primary}"
    placeholderColor: "{colors.text-tertiary}"
    typography: "{typography.body-md-regular}"
    rounded: "{rounded.md}"
    height: 48px
    padding: "0 16px"
    border: "1px solid {colors.border-tertiary}"
  input-focused:
    border: "2px solid {colors.border-focus}"
  input-error:
    border: "1px solid {colors.border-error}"
  search-bar-default:
    backgroundColor: "{colors.surface-container-lower}"
    placeholderColor: "{colors.text-tertiary}"
    typography: "{typography.body-md-regular}"
    rounded: "{rounded.full}"
    height: 48px
    padding: "0 16px"
  search-bar-active:
    backgroundColor: "{colors.surface-container}"
    height: 48px
  search-bar-explore:
    backgroundColor: "{colors.surface-container-lower}"
    height: 36px
    rounded: "{rounded.full}"

  # ── Chips ──────────────────────────────────────────────────
  chip-input:
    backgroundColor: "{colors.surface-container-lowest}"
    textColor: "{colors.text-secondary}"
    typography: "{typography.caption-md}"
    rounded: "{rounded.xs}"
    height: 24px
    padding: "0 8px"
    border: "1px solid {colors.border-secondary}"
  chip-assist:
    backgroundColor: "{colors.surface-container-darkest}"
    textColor: "#ffffff"
    typography: "{typography.caption-md}"
    rounded: "{rounded.xs}"
    height: 24px
    padding: "0 8px"
  chip-tag:
    backgroundColor: "{colors.surface-highlight}"
    textColor: "{colors.text-action}"
    typography: "{typography.caption-md}"
    rounded: "{rounded.xs}"
    height: 24px
    padding: "0 8px"
  chip-filter:
    backgroundColor: "{colors.surface-container-lowest}"
    textColor: "{colors.text-secondary}"
    rounded: "{rounded.xs}"
    height: 28px
    padding: "0 12px"
    border: "1px solid {colors.border-tertiary}"
  chip-filter-active:
    backgroundColor: "{colors.surface-action}"
    textColor: "{colors.text-on-action}"

  # ── Tabs ───────────────────────────────────────────────────
  tab-default:
    backgroundColor: "transparent"
    textColor: "{colors.text-tertiary}"
    typography: "{typography.body-md-medium}"
    height: 40px
    padding: "0 16px"
    borderBottom: "2px solid transparent"
  tab-selected:
    textColor: "{colors.text-primary}"
    borderBottom: "2px solid {colors.border-action}"
  tab-with-icon:
    height: 48px
    iconGap: 8px
  switch-tab-pill:
    backgroundColor: "{colors.surface-container-lower}"
    rounded: "{rounded.full}"
    height: 48px
    padding: "4px"
    activeTab:
      backgroundColor: "{colors.surface-container-lowest}"
      rounded: "{rounded.full}"
  segment-control:
    backgroundColor: "{colors.surface-container-low}"
    rounded: "{rounded.md}"
    height: 40px
    padding: "2px"
    activeTab:
      backgroundColor: "{colors.surface-container-lowest}"
      rounded: "{rounded.sm}"

  # ── Navigation ─────────────────────────────────────────────
  sidebar-expanded:
    backgroundColor: "{colors.surface-container-lower}"
    width: 200px
    height: 876px
    padding: "12px"
  sidebar-collapsed:
    backgroundColor: "{colors.surface-container-lower}"
    width: 60px
    height: 876px
    padding: "12px 8px"
  sidebar-item:
    textColor: "{colors.text-secondary}"
    typography: "{typography.body-md-medium}"
    rounded: "{rounded.sm}"
    height: 36px
    padding: "0 12px"
  sidebar-item-active:
    backgroundColor: "{colors.surface-container}"
    textColor: "{colors.text-primary}"
  hero-nav:
    backgroundColor: "{colors.surface-container-lowest}"
    height: 56px
    width: 1440px
    padding: "0 24px"
    logoWidth: 196px
    tabGroupWidth: 286px
  breadcrumb:
    textColor: "{colors.text-tertiary}"
    typography: "{typography.body-sm-medium}"
    separatorColor: "{colors.text-tertiary}"
    height: 24px

  # ── Cards ──────────────────────────────────────────────────
  card-base:
    backgroundColor: "{colors.surface-container-lowest}"
    rounded: "{rounded.lg}"
    padding: "16px"
    border: "1px solid {colors.border-secondary}"
  card-file:
    backgroundColor: "{colors.surface-container-lowest}"
    rounded: "{rounded.lg}"
    padding: "16px"
    border: "1px solid {colors.border-secondary}"
    width: 300px
  card-library:
    backgroundColor: "{colors.surface-container-lowest}"
    rounded: "{rounded.xl}"
    padding: "20px"
    border: "1px solid {colors.border-secondary}"
  card-pricing:
    backgroundColor: "{colors.surface-container-lowest}"
    rounded: "{rounded.lg}"
    padding: "24px"
    border: "1px solid {colors.border-secondary}"
  card-pricing-featured:
    backgroundColor: "{colors.surface-container-lower}"
    rounded: "{rounded.lg}"
    padding: "24px"
    border: "2px solid {colors.border-action}"
  card-chat-summary:
    backgroundColor: "{colors.surface-container-lower}"
    rounded: "{rounded.lg}"
    padding: "16px"
    width: 699px
  card-flashcard:
    backgroundColor: "{colors.surface-container-lowest}"
    rounded: "{rounded.xl}"
    padding: "20px"

  # ── Chat ───────────────────────────────────────────────────
  chat-input-box:
    backgroundColor: "{colors.surface-container-lowest}"
    rounded: "{rounded.xl}"
    padding: "12px 16px"
    border: "1px solid {colors.border-secondary}"
    width: 630px
  chat-bubble-user:
    backgroundColor: "{colors.surface-action}"
    textColor: "{colors.text-on-action}"
    typography: "{typography.body-md-regular}"
    rounded: "{rounded.lg}"
    padding: "10px 14px"
    maxWidth: "70%"
  chat-bubble-ai:
    backgroundColor: "{colors.surface-container-lower}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body-md-regular}"
    rounded: "{rounded.lg}"
    padding: "10px 14px"
    maxWidth: "80%"
  chat-thinking-indicator:
    backgroundColor: "{colors.surface-container-low}"
    rounded: "{rounded.lg}"
    padding: "10px 14px"

  # ── Badges & Labels ────────────────────────────────────────
  badge-primary:
    backgroundColor: "{colors.surface-action}"
    textColor: "{colors.text-on-action}"
    typography: "{typography.caption-sm}"
    rounded: "{rounded.full}"
    padding: "2px 8px"
  badge-success:
    backgroundColor: "{colors.surface-success}"
    textColor: "{colors.text-success}"
    typography: "{typography.caption-sm}"
    rounded: "{rounded.full}"
    padding: "2px 8px"
  badge-warning:
    backgroundColor: "{colors.surface-warning}"
    textColor: "{colors.text-warning}"
    typography: "{typography.caption-sm}"
    rounded: "{rounded.full}"
    padding: "2px 8px"
  badge-error:
    backgroundColor: "{colors.surface-error-low}"
    textColor: "{colors.text-error}"
    typography: "{typography.caption-sm}"
    rounded: "{rounded.full}"
    padding: "2px 8px"
  badge-info:
    backgroundColor: "{colors.surface-info}"
    textColor: "{colors.text-info}"
    typography: "{typography.caption-sm}"
    rounded: "{rounded.full}"
    padding: "2px 8px"
  badge-neutral:
    backgroundColor: "{colors.surface-container}"
    textColor: "{colors.text-secondary-mid}"
    typography: "{typography.caption-sm}"
    rounded: "{rounded.full}"
    padding: "2px 8px"

  # ── Menus & Dropdowns ──────────────────────────────────────
  dropdown-menu:
    backgroundColor: "{colors.surface-container-lowest}"
    rounded: "{rounded.lg}"
    padding: "6px"
    border: "1px solid {colors.border-secondary}"
    shadow: "0 8px 24px rgba(0,0,0,0.10)"
    width: 200px
  dropdown-menu-item:
    textColor: "{colors.text-secondary}"
    typography: "{typography.body-md-regular}"
    rounded: "{rounded.sm}"
    height: 36px
    padding: "0 12px"
  dropdown-menu-item-hover:
    backgroundColor: "{colors.surface-container-lower}"
  dropdown-menu-item-destructive:
    textColor: "{colors.text-error}"

  # ── Dialogs & Popups ───────────────────────────────────────
  dialog:
    backgroundColor: "{colors.surface-container-lowest}"
    rounded: "{rounded.2xl}"
    padding: "24px"
    border: "1px solid {colors.border-secondary}"
    shadow: "0 16px 48px rgba(0,0,0,0.12)"
  dialog-overlay:
    backgroundColor: "rgba(0,0,0,0.32)"
  snackbar:
    backgroundColor: "{colors.surface-container-black}"
    textColor: "#ffffff"
    typography: "{typography.body-md-regular}"
    rounded: "{rounded.lg}"
    padding: "12px 16px"
    shadow: "0 4px 12px rgba(0,0,0,0.15)"
  tooltip:
    backgroundColor: "{colors.surface-container-darkest}"
    textColor: "#ffffff"
    typography: "{typography.caption-md}"
    rounded: "{rounded.sm}"
    padding: "6px 10px"

  # ── Progress ───────────────────────────────────────────────
  progress-bar:
    backgroundColor: "{colors.surface-container}"
    fillColor: "{colors.surface-action}"
    rounded: "{rounded.full}"
    height: 4px
  progress-bar-success:
    fillColor: "{colors.surface-success}"
  progress-circular:
    strokeColor: "{colors.surface-action}"
    trackColor: "{colors.surface-container}"

  # ── Avatars ────────────────────────────────────────────────
  avatar:
    backgroundColor: "{colors.surface-container}"
    textColor: "{colors.text-secondary}"
    typography: "{typography.body-sm-semibold}"
    rounded: "{rounded.full}"
    size-sm: 24px
    size-md: 32px
    size-lg: 40px
    size-xl: 48px

  # ── Switch / Toggle ────────────────────────────────────────
  switch-off:
    backgroundColor: "{colors.surface-container}"
    thumbColor: "{colors.surface-container-lowest}"
    width: 36px
    height: 20px
    rounded: "{rounded.full}"
  switch-on:
    backgroundColor: "{colors.surface-action}"
    thumbColor: "#ffffff"

brand:
  primary-color: "#4e4df4"
  font-family: "Inter"
  logo:
    component: "logo"
    styles: ["color", "white"]
    sizes: [16, 24, 32, 36, 40, 48, 72, 96]
  logotype:
    component: "logotype"
    orientations: ["horizontal", "vertical"]
    sizes: [16, 18, 24, 32, 48]
  ip-character:
    component: "IP"
    states: ["default", "default-sm", "hi", "wave", "error", "404", "thinking"]
    usage: "Empty states, onboarding, error pages, loading screens"
  icon-set: "Lucide Icons (16px / 1.2 stroke, 20px / 1.5 stroke, 24px / 1.8 stroke)"

patterns:
  surface-layering: |
    AskSia uses a 6-level surface stack. Use these in order from bottom to top:
      container-lower  (#f8f8f9) — page/shell background
      container-low    (#f1f1f3) — sidebar, panels
      container        (#eaeaec) — hover states, dividers
      container-high   (#dedee1) — selected rows, pressed states
      container-lowest (#ffffff) — cards, modals, inputs (always on top)
      highlight        (#eeeefe) — active/selected items with primary tint
  interactive-states: |
    Every interactive element follows this state sequence:
      default  → rest state, no fill change
      hover    → surface-container-lower or primary-hover-2 (#dcdbfd) for action elements
      active   → surface-container or primary (#4e4df4) for action elements
      focus    → 2px solid border-focus (#4e4df4), 2px offset
      disabled → surface-disabled (#dedee1) fill, text-disabled (#b0afba) text
  border-usage: |
    border-default   (#f8f8f9) — hairline separators within the same surface level
    border-secondary (#eaeaec) — card borders on white backgrounds
    border-tertiary  (#dedee1) — input fields, dropdown outlines
    border-outline   (#9998a7) — high-contrast emphasis outlines
    border-focus     (#4e4df4) — keyboard focus ring (2px)
  chat-layout: |
    Chat view: sidebar (200px) + main content (flex). Chat input box centered at 630px wide.
    User bubbles are right-aligned with action bg (#4e4df4); AI bubbles left-aligned with surface-lower.
    Thinking/loading state uses a pulsing indicator in surface-container-low.
  icon-sizing: |
    Use Lucide icons at three sizes with matching stroke widths:
      16px / stroke 1.2 — inline, table cells, tight UI
      20px / stroke 1.5 — standard buttons, list items
      24px / stroke 1.8 — hero icons, empty states, prominent actions
---
