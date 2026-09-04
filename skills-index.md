# Skills Index — Quick Reference

> Use this file to look up which skill applies to a given task.
> Each entry: `skill-name` → trigger summary → related skills

---

## 🎨 Product Design & UX
| Skill | Trigger | Related |
|-------|---------|---------|
| `product-designer` | Design critique, user flows, component structures, Figma workflows, microcopy | `design-critique`, `ux-copy` |
| `product-manager` | Product decisions, prioritization, metrics, PRDs, roadmaps | `prd-writer`, `analytics` |
| `prd-writer` | "Write a PRD", "feature spec", "requirements document" | `product-manager`, `feature-linear-ticket` |

## 🏗️ Design System
| Skill | Trigger | Related |
|-------|---------|---------|
| `design-system-fluency` | Token architecture, color naming, Figma variables, theming | `audit-design-system` |
| `audit-design-system` | Review Figma screen for DS integration drift | `apply-design-system` |
| `apply-design-system` | Connect design to DS components, multi-section reconciliation | `audit-design-system` |
| `ds-linear-ticket` | Document component tokens/states as Linear issue | `ds-token-changelog` |
| `ds-token-changelog` | Record single token change, version tracking | `ds-linear-ticket` |

## 🖼️ Figma
| Skill | Trigger | Related |
|-------|---------|---------|
| `figma-use` | MANDATORY before any `use_figma` call | All figma skills |
| `figma-generate-design` | Build/update screens from design system in Figma | `figma-use` |
| `figma-generate-library` | Build design system (variables, components) in Figma | `figma-use` |
| `edit-figma-design` | Text-to-Figma design (mockup, wireframe, concept) | `figma-use` |

## 📝 Tickets & Docs
| Skill | Trigger | Related |
|-------|---------|---------|
| `feature-linear-ticket` | Feature/user-story engineering ticket from spec + Figma | `prd-writer` |

## ✨ Animation & Motion
| Skill | Trigger | Related |
|-------|---------|---------|
| `animate` | Build an animation from scratch (web) | `review-animations` |
| `animate-expo` | Build animation in React Native/Expo | `animate` |
| `emil-design-eng` | UI polish philosophy, component design, motion craft | `animate` |
| `apple-design` | Gesture UI, spring animations, fluid interfaces | `animate` |
| `animation-vocabulary` | Name an animation effect from description | — |
| `review-animations` | Critique animation code against craft bar | `improve-animations` |
| `improve-animations` | Audit codebase motion, produce fix roadmap | `review-animations` |
| `find-animation-opportunities` | Find places that should animate but don't | `animate` |

## 🏷️ Brand
| Skill | Trigger | Related |
|-------|---------|---------|
| `ionext-brand` | IONEXT brand voice, tone, values for any content | `ionext-brand-campaign` |
| `ionext-brand-campaign` | IONEXT marketing/campaign assets across channels | `ionext-brand` |

## 🖥️ Frontend
| Skill | Trigger | Related |
|-------|---------|---------|
| `frontend-design` | Distinctive visual design, aesthetic direction | `prototype` |
| `ask-sonner` | Sonner toast library guide/troubleshooting | `pick-ui-library` |
| `pick-ui-library` | Choose the right UI library for a task | — |
| `prototype` | Multiple UI variants behind a visual picker | — |

## 📊 Marketing — Strategy
| Skill | Trigger | Related |
|-------|---------|---------|
| `marketing-plan` | Comprehensive marketing plan (AARRR framework) | `product-marketing` |
| `marketing-ideas` | Growth inspiration and strategies | All marketing skills |
| `marketing-loops` | Recurring automated marketing workflows | `marketing-ideas` |
| `product-marketing` | Product/audience/positioning context document | `marketing-plan` |
| `marketing-psychology` | Psychological principles in marketing | `cro`, `copywriting` |

## 📊 Marketing — Acquisition
| Skill | Trigger | Related |
|-------|---------|---------|
| `copywriting` | Write/improve marketing page copy | `copy-editing` |
| `copy-editing` | Edit/polish existing copy | `copywriting` |
| `ads` | Paid ad campaign strategy & optimization | `ad-creative` |
| `ad-creative` | Generate/iterate ad copy at scale | `ads` |
| `cold-email` | B2B cold outreach emails & sequences | `prospecting` |
| `seo-audit` | Audit & diagnose SEO issues | `schema`, `ai-seo` |
| `ai-seo` | Optimize for AI search engines & LLM citations | `seo-audit` |
| `programmatic-seo` | SEO pages at scale with templates | `seo-audit` |
| `schema` | Structured data / JSON-LD for rich results | `seo-audit` |
| `social` | Social media content creation & scheduling | `content-strategy` |
| `content-strategy` | Plan content topics, clusters, calendar | `social`, `copywriting` |
| `public-relations` | Earned media, press, journalist outreach | `launch` |
| `prospecting` | Build prospect lists, qualify leads | `cold-email` |

## 📊 Marketing — Conversion
| Skill | Trigger | Related |
|-------|---------|---------|
| `cro` | Conversion rate optimization for any page | `signup`, `popups` |
| `signup` | Signup/registration flow optimization | `onboarding` |
| `onboarding` | Post-signup activation & first-run experience | `signup`, `emails` |
| `popups` | Popup/modal/overlay optimization | `cro` |
| `paywalls` | In-app upgrade/paywall optimization | `pricing` |
| `ab-testing` | Experiment design & implementation | `analytics` |
| `analytics` | Tracking setup, GA4, event tracking | `ab-testing` |

## 📊 Marketing — Retention & Revenue
| Skill | Trigger | Related |
|-------|---------|---------|
| `pricing` | Pricing strategy, packaging, monetization | `paywalls`, `offers` |
| `offers` | Offer design, value stacking, guarantees | `pricing`, `copywriting` |
| `churn-prevention` | Reduce churn, cancel flows, dunning | `emails` |
| `emails` | Email sequences & automation flows | `cold-email` |
| `sms` | SMS/MMS marketing & compliance | `emails` |
| `referrals` | Referral & affiliate programs | `launch` |
| `revops` | Revenue operations & lead lifecycle | `analytics` |

## 📊 Marketing — Content & Distribution
| Skill | Trigger | Related |
|-------|---------|---------|
| `lead-magnets` | Gated content for email capture | `free-tools` |
| `free-tools` | Free tools for lead gen & SEO | `lead-magnets` |
| `launch` | Product launch strategy & execution | `directory-submissions` |
| `directory-submissions` | Submit to directories for backlinks | `launch` |
| `image` | Marketing image creation & optimization | `ad-creative` |
| `video` | AI video creation & production | `social` |

## 📊 Marketing — Competitive
| Skill | Trigger | Related |
|-------|---------|---------|
| `competitor-profiling` | Research & profile competitors from URLs | `competitors` |
| `competitors` | Comparison/alternative pages for SEO | `competitor-profiling` |
| `co-marketing` | Partner marketing & joint campaigns | `referrals` |
| `community-marketing` | Community building for growth | `social` |

## 📊 Marketing — Sales
| Skill | Trigger | Related |
|-------|---------|---------|
| `sales-enablement` | Sales collateral, pitch decks, objection docs | `competitors` |
| `aso` | App Store / Google Play listing optimization | — |
| `site-architecture` | Website page hierarchy & URL structure | `seo-audit` |

## 🔌 Plugin Skills (Design)
| Skill | Trigger | Related |
|-------|---------|---------|
| `design-critique` | Review/critique mockup or screen | `product-designer` |
| `design-handoff` | Developer handoff specs from design | — |
| `design-system` (plugin) | Audit/document/extend design system | `audit-design-system` |
| `accessibility-review` | WCAG 2.1 AA audit | — |
| `ux-copy` | Write/review microcopy, error messages, CTAs | `ionext-brand` |
| `user-research` | Plan/conduct user research studies | `research-synthesis` |
| `research-synthesis` | Synthesize research into insights | `user-research` |
