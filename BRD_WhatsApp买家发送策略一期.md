# WhatsApp Buyer Messaging Strategy (Phase 1) BRD

| Item | Content |
|------|---------|
| Document Status | v1.2 Release (shared with collaboration teams) |
| Date | 2026-08-17 |
| Author | Jolyne Zhang (Lifecycle / Buyer Side) |
| Reviewer | Shuhe |
| Related Documents | Visable WhatsApp Project Proposal v0.1 draft; 04 WhatsApp business strategy table; WhatsApp message access feasibility assessment (Confluence ARISE/436797534); Alibaba International WhatsApp data & strategy summary |

---

## 1. Project Overview

### 1.1 Background & Opportunity

| Fact | Basis | Implication |
|------|------|------|
| WhatsApp 2.5B+ global DAU, ≥50% penetration in Europe, #1 messaging app in 63/100 countries | Alibaba practice review | Core European buyer base (DE/FR/IT/ES) is natively on WhatsApp |
| Email/EDM open rates keep declining; SEO traffic squeezed by AI Search | GEO project / Push Tracking findings | Need a high-reach, low-frequency, high-value complementary channel |
| Two system-message mechanisms already defined: ① conversation reminder (supplier reply → notify buyer) ② buyer follow-up reminder (no reply → second nudge); buyer response baselines QDR wlw 18%/ep 36%, RFQ wlw 33%/ep 28% | PRD_Reminder Notification to improve AB2 (Confluence PRODTECH/63340593) | Follow-up reminders directly serve the AB2 North Star; WhatsApp carries both buyer-side system messages (email/app push channels already defined, CX-564 Done) |
| Alibaba International WhatsApp validated at scale (5M subscribers, 328K daily UV, ROI 1.2+) | Alibaba Yuque practice docs | Path is viable, but EU compliance bar is higher; subscriptions must be built from zero |

### 1.2 Positioning (lessons validated / falsified)

- ✅ **WhatsApp = "walkie-talkie" that accelerates first response**: first response ≤5min → AB2 rate 59.6% (+25pp vs >9h).
- ❌ **≠ Off-site order chasing**: disproven (−7.7pp); Phase 1 excludes "order-chasing" marketing.
- **Phase 1 buyer-side positioning**: carry and amplify existing touch effects, shorten first response time, prevent conversation loss — NOT independent new-user acquisition or order chasing.

### 1.3 North Star Metric

> **Daily AB2 ≥ 8** (by FY26/27 year-end 2027-03-31; funnel derivation in 2.1 and Appendix 9.1; all metrics are daily averages from send onwards)

### 1.4 Phase 1 Goals (by message type, daily funnel basis)

**North Star (total): daily AB2 ≥ 8** (by FY26/27 year-end 2027-03-31) = **system messages contribution (floor ≥ 3)** + **marketing messages contribution (floor ≥ 5)**. Contribution split to be locked via AB2 conversations analysis (under calculation).

**A. System message goals (details owner: Utkarsha · PRD_Reminder basis) — activate existing stock, event-driven, no dependence on subscription pool ramp-up:**

| Objective | Target |
|--------|------|
| Follow-up coverage (unanswered requests) | 100% (once per request; skip if already replied; stop after AB2 established) |
| Buyer response rate uplift (after follow-up) | wlw 26% → 28%, ep 29% → 31% (PRD success metrics) |
| Conversation reminder first response | Accelerate first response (≤5min → AB2 rate 59.6%, +25pp) |
| North Star contribution | **Daily AB2 ≥ 3** (floor, locked via AB baseline) |

**B. Marketing message goals (owner: Jolyne) — incremental acquisition, subscription-pool funnel:**

| Objective | Target |
|--------|------|
| Cumulative subscriptions by FY end (2027-03-31) | ≥ 35,000 |
| Reachable (valid authorization, 60%) | ≥ 21,000 |
| Daily sends (1 round/week, 14%/day audience selection) | ≥ 2,940/day |
| Daily UV reached (CTR 6%, after frequency decay) | ≥ 176/day |
| Daily AB (UV→AB 20%) | ≥ 35/day |
| North Star contribution | **Daily AB2 ≥ 8.8** (110% buffer over the target of 8) |

**C. Global guardrails (shared by both types):** delivery rate ≥ 90%, 48h read rate ≥ 50%, unsubscribe rate < 5%, complaint/block rate < 2%.

---

## 2. Benchmark Baseline (daily-average basis)

### 2.1 Marketing Funnel Baseline (V target baseline from business strategy table, daily average, subscription-pool driven)

**Funnel breakdown**: North Star daily AB2 ≥ 8 is delivered by **two independent tracks** — ① **system messages** (event-driven: follow-up + conversation reminders, activating existing conversations, target contribution ≥ 3, see 4.1 / PRD_Reminder) ② **marketing messages** (subscription-pool funnel, target contribution ≥ 8.8, i.e. table below). Marketing frequency benchmarked to Alibaba: FY26 target **2 rounds/week/user** (Yuque "WhatsApp Annual Review & Strategy Planning"); EU compliance stricter, Visable starts at **1 round/week**, A/B validation cap of 2 rounds/week.

| Funnel stage | Derivation | Alibaba (benchmark) | V target (FY26/27 year-end) |
|---------|------|---------------|-------------------|
| ① Cumulative subscriptions | Back-calculated | 870,000 (1.5+ years) | **35,000** |
| ② Reachable (valid authorization) | ① × 60% | 348,000 | **21,000** |
| ③ Daily sends (1 round/week, 14%/day) | ② × 14% | 80,000/day (incl. system messages, different basis) | **2,940/day** |
| ④ Daily UV reached (CTR 10% → 6%, decay 0.6) | ③ × 6% | 10,000/day | **176/day** |
| ⑤ Daily AB (UV→AB 20%) | ④ × 20% | — (ABpro level not aligned) | **35/day** |
| ⑥ **Daily AB2 (AB→AB2 25%)** | ⑤ × 25% | **4,785/day** (ABpro, ≈ AB2) | **8.8/day ✓** (target ≥ 8, 10% buffer) |

> **Frequency basis**: Alibaba FY26 target is **2 rounds/week/user** (Yuque "WhatsApp Annual Review & Strategy Planning": weekly reach 1.7M ÷ subscription pool); 328K daily UV achieved by 2026-03. Visable starts at **1 round/week** (14%/day, full pool in 7 days), CTR conservatively taken as 10% × 0.6 decay (frequency doubling → open rate decline, Alibaba FY26 target basis), pilot A/B validates **2 rounds/week** (28%/day) as cap.

> **Subscription collection is the top priority** — Alibaba accumulated 1.5+ years; Visable starts from zero. Funnel basis, key assumptions (60% reachable, daily-average derivation, sensitivity) and Alibaba comparison details in Appendix 9.1 / 9.2.

> **Post-subscription onboarding (benchmarked to Alibaba subscription welcome flow, included in Phase 1)**: **T+0 send 1 message** after subscription confirmed (double opt-in completed) — ① confirm subscription + preview what they'll receive (RFQ opportunity alerts / product recommendations / seller messages) ② preference settings (categories + frequency: 1/week / important-only) ③ unsubscribe method (compliance). One message only, one-off, **does not consume the weekly 1-round marketing quota**; template targets Utility (€0.035/message, incl. subscription-confirmation wording), €0.11 if Meta classifies as Marketing (costs in Ch.7 ⑥). Value: ① subscription confirmation reduces number-quality risk ② preference data enables precise audience selection ("important-only" preference auto-downgrades frequency, unified with frequency capping) ③ high open rate on first message builds account quality score.

---

## 3. Phase 1 Scope

### 3.1 In Scope

1. **Subscription collection**: standalone checkbox on registration page (unchecked by default) + second ask after phone verification + popup after inquiry submission + Subscription Center unified management (reuse UPR-55 Lifecycle entry)
2. **System/transactional messages launch** (details: Utkarsha · PRD_Reminder): two buyer-side system messages (① conversation reminder: notify buyer when supplier replies; ② buyer follow-up reminder: nudge if no reply by day after supplier reply, directly serves AB2 North Star, reuse PRD_Reminder rules), all via Utility templates. Billing: free within WhatsApp 24h customer-service window (recent message in buyer's dialog); paid Utility template outside window (~€0.03–0.04/message; on-site behavior does not open a window)
3. **Marketing pilot** (BRD focus, owner: Jolyne, see 4.2): two-strategy second touch (RFQ marketing + product recommendation)
4. **Sending infrastructure**: three-state subscription service (subscribed/unsubscribed/unknown), frequency capping (24h/once per relationship pair, ≤3/day per user), tracking loop (push_id + visitor_sk attribution)
5. **Templates**: Utility first batch EN+DE, neutral wording; Marketing templates enter review process but not sent at scale yet

### 3.2 Out of Scope

- ❌ Full-scale Marketing delivery (browse→AB and other Phase-2 candidate strategies) → Phase 2 (pending Legal sign-off + subscription ramp-up)
- ❌ AI personalization generation (LLM summary/intent) → P2
- ❌ Two-way messaging → Phase 1 send-only (upgradable later, no re-application needed)
- ❌ Off-site order-chasing scenarios (disproven)

---

## 4. Solution Design

### 4.1 Send Scenarios · System/Transactional (Phase 1 priority, low compliance pressure)

Buyer-side system messages: **2 types** (details: **Utkarsha** · PRD_Reminder owner; aligned with [PRD_Reminder Notification to improve AB2](https://visable.atlassian.net/wiki/spaces/PRODTECH/pages/63340593/PRD_Reminder+Notification+to+improve+AB2); email/app push channels defined, CX-564 email template Done; WhatsApp carries both buyer-side types):

| Scenario | Trigger | Message content | Compliance type | Relation to North Star AB2 |
|------|---------|---------|---------|-------------------|
| ① Conversation reminder (supplier reply → notify buyer) | Real-time event after supplier reply | Quote/reply card + AI-summarized key fields (price range/MOQ/lead time) + one-tap reply | Utility (transactional) | Indirect: keeps conversation warm, accelerates first response (≤5min → AB2 rate 59.6%) |
| ② Buyer follow-up reminder (buyer no reply → second nudge) | Day after supplier reply, buyer still hasn't replied (PRD basis: wlw 10am / ep 9am) | Follow-up copy (reuse PRD templates: "Supplier Waiting for Your Reply" etc.) | Utility (transactional) | **Direct: buyer response to positive connection = AB2** |

**Follow-up guardrails (inherited from PRD_Reminder):** one follow-up per request/message; skip if already replied; open status only (no send for expired / frozen / not interested / archived); stop after AB2 established.

> **Billing path**: free if both messages land inside the WhatsApp 24h customer-service window (recent message in buyer's dialog); paid Utility template outside the window (~€0.03–0.04/message; on-site behavior does not open a window). Follow-up timing consistent with PRD (next-day 10am/9am), different time slots from marketing second touch (4.2) to avoid repeated disturbance of the same user.

### 4.2 Send Scenarios · Marketing (owner: Jolyne; Phase 1 pilot core: two-strategy second touch)

**Phase 1 pilot: two strategies (selected from existing PUSH/EDM marketing strategies, see 01 push business strategy table / 02 edm business strategy table):**

| Strategy | PUSH counterpart | EDM counterpart | Current volume | Open rate (wlw / ep) | Rationale |
|------|----------|---------|---------|-------------------|-----------|
| ① **RFQ marketing** | PN_RFQ_MARKETING | RfQ promo-recurring (multilingual templates) | push ~7,405/day | 6.4% / 5.4% | One of the largest-volume strategies; audience has clear RFQ intent; same source as system RfQ chain, can link up |
| ② **Product recommendation** | PN_RECOMMENDATION | Product recommendations (multilingual templates) | push ~1,545/day | 33% (ep) | Open rate several times higher than other marketing strategies; content is product cards — best fit for WhatsApp rich media |

**Assets & landing pages (reuse existing Push assets, no new creation):**

- **RFQ marketing → landing page: RFQ creation page** (direct entry to RFQ form, shortest path; reuse PN_RFQ_MARKETING copy and RFQ value props)
- **Product recommendation (browse/search recall) → strategy & landing page reuse [PRD Push-Led App Retention — Lifecycle Strategy](https://visable.atlassian.net/wiki/spaces/ARISE/pages/69206790/PRD+Push-Led+App+Retention+Lifecycle+Strategy)**: browsed-but-not-searched → `browse_recall` landing page (personalized "i-i" recommendations); searched-but-no-AB → `search_recall` landing page (personalized "q-i" recommendations); copy sets reuse `pn_mkt_prod_browse_active` / `pn_mkt_prod_search_active` (incl. ${keyword} template variables); WhatsApp and Push share the same landing-page strategy for the same user in the same round — naturally deduplicated

**Why these two (pilot selection rationale):**

| Basis | Explanation |
|------|------|
| Direct landing of "carry + amplify" | RFQ marketing / product recommendation already touch large volumes daily (push combined ~8,950/day), but "touched, no AB" users get no further action — existing investment marginalizes; WhatsApp second touch on this cohort is the direct landing of "carry + amplify existing touch effects" |
| Channel advantage | WhatsApp read rate 40–62.8% (system 62.8% / marketing 40–50%), far above EDM; re-touch the same value prop via a high-reach channel |
| Cost-efficiency & control | Only targets users with existing touch history, no cold start; cohort has behavioral baseline, pilot results comparable, risk controllable |

**Audience pools (rolling by touch round):**

| Pool | Selection condition | Size |
|----|---------|--------|
| Opened-but-no-conversion | Touched by previous-round RFQ marketing / product recommendation (PUSH+EDM), opened but no AB | 300K (two-strategy pool; final size locked by actual selection before pilot) |
| Visited-but-no-conversion | Visited site after previous-round touch but no AB | 20K (same) |

> The two pools are mutually exclusive and deduplicated; subscription-status check before sending (must be "subscribed"); actual send volume = subscribed subset.

**Send flow (aligned with existing channels, rolling 1 round/week):**

1. **D0**: original-channel touch (RFQ marketing / product recommendation via PUSH + EDM — both channels are **fixed batch + behavior-triggered**: PUSH Mon/Fri 9:30 local, EDM fixed batch weekday TBD)
2. **From D2 (1 round/week)**: take previous-round touched-but-no-AB users → subscription check (must be "subscribed") → **onboarding cooldown check (no re-touch within 7 days of subscription; onboarding already covered)** → fatigue check (no other WhatsApp message for this user in 24h; global daily cap ≤ 15K sessions circuit breaker); pilot A/B validates 2 rounds/week cap (benchmarked to Alibaba weekly 2x)
3. **Content**: carry RFQ marketing / product recommendation value props and assets, WhatsApp Marketing templates (enabled after Legal sign-off); **landing pages reuse existing Push assets** (RFQ marketing → RFQ creation page; product recommendation → browse_recall / search_recall, see "Assets & landing pages" above)
4. **Send time**: 10:00 AM buyer local time
5. **Tracking**: push_id spans original channel and WhatsApp; visitor_sk attribution

**Pilot measurement (validate two propositions):**

| Proposition | Validation method | Pass criteria |
|------|---------|---------|
| Carry-over effectiveness | WhatsApp second-touch group AB rate vs untouched control group | Increment significantly positive (threshold locked before pilot) |
| Compliance chain | double opt-in full flow + Marketing template approval + zero violation complaints | No Abmahnung/complaints |

**Pilot cadence:** DE single-country canary (after Legal sign-off + Marketing template approval) → run 2–3 rounds (**1 round/week**) to evaluate → frequency A/B (1 vs 2 rounds/week; observe disturbance/unsubscribe/complaints) → expand countries/scale after passing (FR/IT/ES following template review).

### 4.3 Subscription Scenarios (collection touchpoints + double opt-in solution)

| Touchpoint | Location | Level-1 consent | Level-2 confirmation |
|------|------|------------|-------------|
| Standalone checkbox on registration | Registration flow | Unchecked by default, opt-in | WhatsApp confirmation message/link |
| Second ask after phone verification | Phone verification step | Popup ask after success | WhatsApp confirmation message/link |
| Popup after inquiry submission | Inquiry submit success | Scenario-bound authorization (strongest compliance) | WhatsApp confirmation message/link |
| Subscription Center | Account settings | Self-service on/off | Changes take effect immediately |
| Off-site entries (IG/FB/link) | Social pages/landing pages | Form checkbox or keyword reply | SMS/email confirmation code; subscribed after reply |

**Marketing double opt-in solution (must be delivered in Phase 1):**

1. **Level-1 consent**: user actively authorizes at on-site touchpoints (checkbox/popup), stating content, frequency, unsubscribe method, linking privacy notice; keep evidence of "who, when, which entry, exact consent wording".
2. **Level-2 confirmation**: confirmation sent via WhatsApp template (or SMS code); user marked "subscribed" only after replying to confirm / clicking the confirmation link.
3. Users who **fail Level-2 confirmation** are set to "unknown" after 24h, excluded from send pool (three-state subscription service as backstop).
4. **Consent record storage**: align storage solution with data team; serves as Legal audit evidence.
5. **Unsubscribe chain**: Subscription Center + off-site STOP/UNSUBSCRIBE/ABMELDEN, effective immediately, synced to three states.
6. **Post-subscription onboarding (T+0, 1 message, one-off)**: welcome message immediately after Level-2 confirmation — ① confirm subscription + preview what they'll receive (RFQ opportunity alerts / product recommendations / seller messages) ② preference settings (categories + frequency: 1/week / important-only; "important-only" auto-downgrades frequency) ③ unsubscribe method (Subscription Center + STOP). Template targets Utility (incl. subscription-confirmation wording, €0.035/message); €0.11 if Meta classifies as Marketing. **Does not consume the weekly 1-round marketing quota; excluded from audience pool for 7 days after subscription** (benchmarked to Alibaba subscription welcome flow).

### 4.4 Send Strategy (coordination with existing channels)

- **Cadence**: WhatsApp ranks after Visable's existing PUSH/EDM touches; **second touch** on users who responded to existing touches; frequency **starts at 1 round/week** (benchmarked to Alibaba FY26 marketing target of 2 rounds/week; EU compliance starts lower; pilot A/B caps at 2 rounds/week) — a "carry + amplify" relationship with existing PUSH/EDM, not a parallel independent channel.
- **Trigger timing**: marketing second touch at 10:00 AM buyer local time (Alibaba BRD §5.4 experience); system: conversation reminder real-time on event, follow-up reminder per PRD_Reminder cadence (next day after supplier reply, wlw 10am / ep 9am).
- **Languages**: DE/EN start; FR/IT/ES follow template review.
- **Fatigue**: EU tolerance is low, capping strict (24h/1 per relationship pair, ≤3 per user per 24h, global daily circuit breaker ≤ 15K sessions against script attacks).
- **Post-subscription onboarding**: T+0 one message after subscription (welcome + preference settings), does not consume weekly 1-round marketing quota; "important-only" preference auto-downgrades frequency, unified with capping.

### 4.5 Explicitly Out of Scope (red lines)

| Red line | Explanation |
|------|------|
| ❌ Batch marketing to non-double-opt-in users | Marketing messages must complete Level-2 confirmation |
| ❌ Undifferentiated push on sensitive categories | Audience selection by category/cohort |
| ❌ Product push on first contact | First message leads with service/subscription guidance |

---

## 5. Technical Implementation & Dependencies

### 5.1 Architecture

```
Inquiry / RFQ Service event stream (incl. follow-up reminder, reusing requests-service triggers)
        ↓
Orchestration layer (subscription-state lookup → frequency capping → template routing → tracking)
        ↓
Direct Meta Cloud API (reuse existing channel, dedicated number + display name)
```

Data granularity: three levels of scenario id - message id - user id (aligned with Alibaba BRD), tracking fields incl. push_id + visitor_sk (reuse existing attribution chain).

### 5.2 Dependency List

| Dependency | Owner | Key date |
|------|--------|---------|
| Subscription entry changes (registration checkbox / post-verification ask / inquiry popup) | Product (Muke) | Schedule locked within August |
| Consent record storage solution | Data team (TBD) | Before Legal consultation starts |
| Legal consultation conclusion (B2B consent threshold) | Legal | ASAP (Marketing send gate) |
| Meta Cloud API channel & template submission | Harry / Shuhe | September (Utility first batch) |
| System-message detail definition (follow-up rules/templates/guardrails) | Utkarsha / PRD_Reminder team | Within August |

---

## 6. Risks & Compliance

| Risk | Severity | Mitigation |
|------|--------|------|
| GDPR/ePrivacy penalties | 🔴 High | Legal upfront; unchecked by default; double opt-in; evidence retention |
| Meta Marketing template rejection / quality downgrade | 🟡 Medium | Neutral wording; Utility first then Marketing; A/B multi-variants |
| Subscription ramp-up below expectation (35,000 baseline, precondition for daily AB2 ≥ 8) | 🟡 Medium | Start collection ASAP (benchmark: Alibaba 1.5-year accumulation); multi-touchpoint rollout; monitor opt-in rate, add touchpoints timely |
| Fatigue conflict with EDM/Push | 🟡 Medium | Unified fatigue pool in orchestration layer; staggered scheduling |
| Number quality decline → throttling | 🟡 Medium | Strict capping + immediate unsubscribe + complaint monitoring |

Compliance prerequisites: GDPR Art.7 + ePrivacy explicit consent, double opt-in, evidence retention (who/when/entry/exact wording), immediate unsubscribe, Abmahnung risk.

---

## 7. Monthly Cost Estimate

**Billing model (Meta WhatsApp pay-as-you-go)**: no account application fee / fixed monthly fee / subscription fee; billed per **template message** only (price varies by category); conversation messages within the 24h customer-service window are free.

| Message category | Unit price | Scope |
|---------|------|---------|
| Marketing | ~€0.11/message | Marketing second touch (two strategies) |
| Utility | ~€0.03–0.04/message (use €0.035) | System messages (conversation reminder / follow-up reminder) |

**Monthly cost estimate (ramps with subscription pool, not steady-state):**

Subscription collection canary goes live in September; marketing pilot starts October (pending Legal conclusion) — send volume ramps with the subscription pool, costs rise monthly, not flat from launch. Model assumptions: daily new subscriptions increase as touchpoints scale from September (Sep: 1-country 1-scenario canary → full-channel multi-touchpoint scale-up, converging in the March sprint), reaching 35,000 by FY end 2027-03-31 (~212 days, daily new ≈ 165); "mid-month cumulative subscriptions" in the table are estimates, actual follows collection progress. **Marketing frequency basis: 1 round/week (14%/day)**; 2-rounds/week tier (A/B cap) doubles marketing cost.

| Month | Phase | Mid-month cumulative subscriptions | Reachable (60%) | Daily sends (1 round/week, 14%/day) | Marketing monthly cost | System monthly cost | Total |
|------|------|-------------------|-------------|----------------------------|-----------|-------------|------|
| 2026-09 | Subscription collection canary (1 country 1 scenario) + template review/integration | ~1,600 | ~950 | No sends (marketing not started) | €0 | ≈ €0 (review period, small test traffic only) | **≈ €0** |
| 2026-10 | System messages full launch + marketing pilot start | ~5,600 | ~3,360 | ~470 | ≈ €1,550 | ≈ €30–130 (~30% ramp coverage) | **≈ €1,600–1,700** |
| 2026-11 | Scale-up ramp | ~10,700 | ~6,420 | ~900 | ≈ €3,000 | ≈ €50–200 (~45% ramp coverage) | **≈ €3,100–3,200** |
| 2026-12 | Scale-up ramp | ~15,700 | ~9,420 | ~1,320 | ≈ €4,400 | ≈ €70–260 (~60% ramp coverage) | **≈ €4,500–4,700** |
| 2027-01 | Scale-up ramp | ~20,800 | ~12,480 | ~1,750 | ≈ €5,800 | ≈ €80–330 (~75% ramp coverage) | **≈ €5,900–6,100** |
| 2027-02 | Sprint | ~25,900 | ~15,540 | ~2,180 | ≈ €7,200 | ≈ €100–400 (~90% ramp coverage) | **≈ €7,300–7,600** |
| 2027-03 | Sprint (FY goal achieved) | ~30,900 | ~18,540 | ~2,600 | ≈ €8,600 | ≈ €110–440 (near-full) | **≈ €8,700–9,000** |
| From 2027-04 | Steady state (after FY goal) | ≥ 35,000 | ≥ 21,000 | ≥ 2,940 | ≈ €9,700/month | €110–440/month | **≈ €9,800–10,100/month** |

> Notes: ① Ramp-up period (2026-10 to 2027-03) cumulative ≈ €31,000–32,300 (marketing ≈ €30.5K + system ≈ €0.4K–1.8K); steady state ≈ €9,800–10,100/month (annualized ≈ €118K–121K); ② if frequency A/B validates full switch to **2 rounds/week** (benchmarked to Alibaba weekly 2x), steady-state marketing cost doubles to ≈ €19,400/month (total ≈ €19,500–19,900/month, annualized ≈ €234K–239K), AB2 output doubles (≥ 17.6/day) — cost and AB2 roughly linear, per-AB2 cost unchanged; ③ system messages billed conservatively at full out-of-window rate — free if within 24h window, actual below ceiling; marketing messages mostly out-of-window (proactive touch, buyer no recent dialog), billed at full Marketing rate; ④ system-message steady volume (100–440/day) and subscription coverage ramp (2026-10 ~30% → 2027-03 full) are estimates, locked by AB2 conversations analysis; ⑤ steady-state per-AB2 channel cost ≈ €37 (steady monthly cost ÷ 265 monthly AB2, Meta template fee only, 1 round/week tier, independent of subscription scale); ramp-up per-AB2 ≈ €38 (cumulative cost ÷ 829 cumulative AB2); Alibaba overall CPUV $0.1 / CPPB $11.4 (incl. other costs, scale reference only); ⑥ **subscription onboarding (one-off, T+0 one message after subscription)**: FY cumulative ≤ 35,000 messages, ≈ €1,200 at Utility, ≈ €3,900 if classified Marketing (template category pending Meta review); not in monthly main table; with onboarding, ramp-up cumulative ≈ €32,200–36,200.

---

## 8. Milestones

| Time | Milestone | Deliverable |
|------|--------|------|
| August | BRD finalized & published → subscription-entry change scheduling → Legal consultation kickoff | BRD release, schedule confirmed |
| September | Subscription collection live (canary 1 country 1 scenario) + **post-subscription onboarding** + Utility template submission + technical integration | Subscription chain works, templates approved |
| October | System messages full launch (conversation reminder + follow-up reminder) + marketing pilot start (1 round/week, pending Legal) + first ROI report | System message validation; pilot propositions validated |
| 2027 Q1 | Subscription sprint to FY target 35,000 + North Star daily AB2 ≥ 8 verification | FY end (2027-03-31) goals achieved |
| Later | Pilot country/scale expansion → P2 AI enhancement → P3 scale (100K+ UV/day) | Scale path |

---

## 9. Appendices

### 9.1 Funnel Basis & Key Assumptions (derivation details)

**Funnel basis & key assumptions**: all funnel metrics from send onwards are **daily averages**. Key assumptions: reachable rate **60%** (Visable builds double opt-in from zero, subscription quality higher than Alibaba mixed-consent measured 40%), marketing frequency **1 round/week** (daily send rate 14%, full pool in 7 days; benchmarked to Alibaba FY26 weekly 2x, EU compliance starts lower), CTR 10% × decay 0.6 = **6%** (open rate declines as frequency rises, Alibaba FY26 target basis), UV→AB 20%, AB→AB2 25% (measured baseline validation: buyer response to positive connection currently QDR wlw 18%/ep 36%, RFQ wlw 33%/ep 28%; 25% within range, PRD_Reminder basis). Daily-average derivation (**target: daily AB2 ≥ 8**): subscriptions 35,000 → reachable 21,000 (×60%) → daily sends 2,940 (×14%) → daily UV 176 (×6%) → daily AB 35 (×20%) → **daily AB2 8.8 (×25%)**. **Breakeven subscription baseline: 8 ÷ 25% ÷ 20% ÷ 6% ÷ 14% ÷ 60% ≈ 31,700** — target 35,000 = 110% buffer over breakeven (still ≥ 8 at CTR decayed to 5.5%; exactly at target if 32,000). Why 35,000 instead of the original 67,000: the old 67,000 implied a slow "25-day round" frequency basis; after raising frequency to 1 round/week, the breakeven subscription demand halves naturally (daily new 316 → 165; DAU 45K conversion 0.70% → 0.37%); if frequency A/B switches to 2 rounds/week (28%/day), breakeven further drops to ~16,000.

**Sensitivity**: frequency is the biggest lever on AB2 output (biweekly 7%/day → weekly 14%/day → 2/week 28%/day; sends double linearly, AB2 doubles; CTR conservatively discounted at 0.6 decay, higher output if decay is gentler). At fixed baseline 35,000: 2/week tier gives daily AB2 ≈ 17.6. If subscription ramp under-delivers (32,000), 1 round/week still exactly meets AB2 = 8; if 16,000, needs 2/week frequency + measured CTR ≥ 6% jointly. Conversely if measured reachable rate < 60%, subscription baseline must be raised.

**System-message funnel (event-driven, not audience-pool based)**: follow-up / conversation reminders don't depend on subscription-pool ramp — AB baseline (current daily positive connections, AB2 conversations analysis data) → WhatsApp subscribed coverage (system messages need Level-1 opt-in only) → follow-up touch (next-day wlw 10am / ep 9am, once per request) → buyer response rate uplift 2pp (PRD target) → AB2 increment. Floor contribution ≥ 3/day; exact number locked by AB baseline measurement.

### 9.2 Alibaba International Measured Data (feasibility evidence)

| Metric | Alibaba measured | Note |
|------|-----------|------|
| Subscription → reachable | 5M → 2M (40%) | Alibaba mixed-consent measured; Visable double opt-in assumed 60% (pending data-team validation) |
| CTR | 13.7% (Dec weekly avg) | 23% when system-message dominated; marketing 10%+ |
| Read rate | System 62.8% / marketing 40–50% | Communication unread alerts |
| UV→PB | 1.3% (overall) | System 0.68% → marketing higher (6x cost) |
| CPPB / CPUV | $11.4 / $0.1 | Optimized from $148 at restart, −87%+ |
| Attribution ROI | 1.16 (Dec) → 1.2+ (Q3 achieved) | Marketing messages positive from end of Dec |
| Daily scale | UV 10K / PB 137 (Dec 21 week) | By 2026-03: UV 328K/day, PB 750/day |
| Marketing frequency | **2 rounds/week/user (FY26 target: weekly reach 1.7M ÷ subscription pool)** | Cart abandonment: 1/week after click, 1/month if not clicked; 7-day churn recall +10K UV/day at launch |
| Daily ABpro | **4,785/day** | ≈ Visable AB2 tier (benchmark basis, daily average) |
| Global circuit breaker | 15K sessions/day | Billing risk red line |

> Interpretation: Phase 1 is a "validate the chain" scale, not scale-up scale. 35,000 subscriptions (FY-end cumulative, daily new ≈ 165) is the target baseline for daily AB2 ≥ 8 (110% buffer over breakeven 32,000); subscription collection remains the top priority (EU consent is strict; Alibaba accumulated 1.5+ years; Visable starts from zero), but pressure is significantly reduced from the original 67,000 (daily new ≈ 316). Reachable rate assumed 60% (double opt-in quality higher; Alibaba measured 40% as conservative floor), pending data-team validation; if below 60% in practice, subscription baseline must be raised accordingly.

### 9.3 Glossary

| Term | Definition |
|------|------|
| WABA | WhatsApp Business Account (Meta-side business account) |
| AB / AB2 | Visable AB funnel tiers: AB = valid inquiry behavior; AB2 = second-level positive connection (**North Star: daily ≥ 8**) |
| Three-state subscription | Subscribed / Unsubscribed / Unknown (double opt-in incomplete or status unclear) |
| Session | WhatsApp 24h dialog window, billing unit |

### 9.4 References

| Source | Location |
|------|------|
| WhatsApp official account application SOP (Option 2 direct connection) | Confluence ARISE/449445930 |
| WhatsApp message access feasibility assessment (Shuhe) | Confluence ARISE/436797534 |
| Visable WhatsApp project proposal v0.1 draft | DingTalk 2Amq4vjg89jyZdNnCmvXZ7omW3kdP0wQ |
| WhatsApp inquiry reception solution research | DingTalk mExel2BLV59rgdDPiPDejPGbVgk9rpMq |
| 04 WhatsApp business strategy table (target baseline) | DingTalk XPwkYGxZV347LdvpH3O5D5ozJAgozOKL |
| WhatsApp delivery strategy planning | DingTalk QG53mjyd800agdlKHexxrMad86zbX04v |
| AB2 conversations analysis 2026 | Teams/SharePoint (Muke/Benjamin/Vaish) |
| Alibaba International WhatsApp data & strategy summary | Local [Alibaba_WhatsApp_数据与策略支撑汇总.md](Alibaba_WhatsApp_数据与策略支撑汇总.md) |
| Alibaba Yuque knowledge base (amb5ap, 7 articles extracted) | https://yuque.alibaba-inc.com/amb5ap |
| PRD_Reminder Notification to improve AB2 (buyer/supplier follow-up, buyer response baseline) | Confluence PRODTECH/63340593 |

---

## Part 2 · 中文版（内部对照）

# WhatsApp 买家发送策略（一期）BRD

| 项 | 内容 |
|----|------|
| 文档状态 | v1.2 发布版（协作团队共享） |
| 日期 | 2026-08-17 |
| 作者 | Jolyne Zhang（Lifecycle / 买家侧） |
| 评审人 | 述合 |
| 关联文档 | Visable WhatsApp 项目方案 v0.1 草案；04 whatsapp 业务策略表；WhatsApp 消息接入可行性评估（Confluence ARISE/436797534）；Alibaba 国际站 WhatsApp 数据与策略支撑汇总 |

---

## 一、项目概述

### 1.1 背景与机会

| 事实 | 依据 | 推论 |
|------|------|------|
| WhatsApp 全球日活 25 亿+，欧洲渗透率 ≥ 50%，63/100 国家消息类应用第一 | Alibaba 实践梳理 | 欧洲核心买家群（DE/FR/IT/ES）天然在 WhatsApp |
| 邮件 EDM 打开率持续走低、SEO 流量受 AI Search 挤压 | GEO 项目 / Push Tracking 结论 | 需要高触达率、低频高价值的补充触达渠道 |
| 系统消息双机制已定义：① conversation 提醒（供应商回复→通知买家）② 买家催复提醒（未回复→二次催复）；buyer response 基线 QDR wlw 18%/ep 36%、RFQ wlw 33%/ep 28% | PRD_Reminder Notification to improve AB2（Confluence PRODTECH/63340593） | 催复提醒直接服务 AB2 北极星；WhatsApp 承接 buyer 侧两类系统消息（email/app push 渠道已定义，CX-564 Done） |
| Alibaba 国际站 WhatsApp 已验证可规模化（订阅 500w、日均触达 UV 32.8w、ROI 1.2+） | 国际站语雀实践 | 路径可行，但欧洲合规门槛更高、订阅需从 0 积累 |

### 1.2 定位（已证伪的教训）

- ✅ **WhatsApp = 拉快首响的"对讲机"**：首响 ≤5min → AB2 率 59.6%（+25pp vs >9h）。
- ❌ **≠ 站外追单**：已证伪（−7.7pp），一期不做"催下单/追单"类营销。
- **买家侧一期定位**：承接+放大已有触达效果、缩短首响时间、防对话流失，而非独立拉新追单。

### 1.3 北极星指标

> **日均 AB2 ≥ 8 个**（FY26/27 财年底 2027-03-31 达标；漏斗推导见 2.1 及附录 9.1，自发送起均为日均口径）

### 1.4 一期目标（按消息类型拆分，日均漏斗口径）

**北极星（合计）：日均 AB2 ≥ 8 个**（FY26/27 财年底 2027-03-31 达标）＝ **系统消息贡献（下限 ≥ 3）** ＋ **营销消息贡献（下限 ≥ 5）**。分配比例以 AB2 conversations analysis 数据锁定（测算中）。

**A. 系统消息目标（细节负责：Utkarsha · PRD_Reminder 口径）——存量激活，事件驱动，不依赖订阅池爬坡：**

| 目标项 | 数值 |
|--------|------|
| 催复覆盖率（未回复 request） | 100%（每 request 仅 1 次；已回复不发；AB2 建立后停止） |
| buyer response 率提升（催复后） | wlw 26% → 28%、ep 29% → 31%（PRD 成功指标） |
| conversation 提醒首响 | 拉快首响（首响 ≤5min AB2 率 59.6%，+25pp） |
| 对北极星贡献 | **日均 AB2 ≥ 3**（下限，以 AB 基线测算锁定） |

**B. 营销消息目标（负责：Jolyne）——增量拉新，订阅池圈人漏斗：**

| 目标项 | 数值 |
|--------|------|
| 财年底累计订阅（2027-03-31） | ≥ 35,000 |
| 可触达（授权有效，60%） | ≥ 21,000 |
| 日均发送（每周 1 轮，14%/日圈人） | ≥ 2,940/日 |
| 日均触达 UV（CTR 6%·频次衰减后） | ≥ 176/日 |
| 日均 AB（UV→AB 20%） | ≥ 35/日 |
| 对北极星贡献 | **日均 AB2 ≥ 8.8**（达标线 8 的 110% 缓冲） |

**C. 全局护栏（两类共享）：** 送达率 ≥ 90%、48h 已读率 ≥ 50%、退订率 < 5%、投诉/拉黑率 < 2%。

---

## 二、对标基线（日均口径）

### 2.1 营销漏斗基线（业务策略表 V 目标基线，日均口径，订阅池驱动）

**漏斗拆分说明**：北极星日均 AB2 ≥ 8 由**两条独立链路**汇合——① **系统消息**（事件驱动：催复 + conversation 提醒，激活存量对话，目标贡献 ≥ 3，见 4.1 / PRD_Reminder）② **营销消息**（订阅池圈人漏斗，目标贡献 ≥ 8.8，即下表）。营销频次对标国际站：FY26 目标**周均 2 次/用户**（语雀《WhatsApp 年度总结&策略规划》），欧洲合规从严，Visable 起步**每周 1 次**、A/B 验证周 2 次上限。

| 漏斗层级 | 推导 | 国际站（对标） | V 目标（FY26/27 财年底） |
|---------|------|---------------|-------------------|
| ① 订阅量（累计） | 反推 | 870,000（1.5 年+） | **35,000** |
| ② 可触达（授权有效） | ① × 60% | 348,000 | **21,000** |
| ③ 日均发送（每周 1 轮，14%/日圈人） | ② × 14% | 80,000/日（含系统消息，口径不同） | **2,940/日** |
| ④ 日均触达 UV（CTR 10% → 6%，频次衰减 0.6） | ③ × 6% | 10,000/日 | **176/日** |
| ⑤ 日均 AB（UV→AB 20%） | ④ × 20% | —（ABpro 上级口径未对齐） | **35/日** |
| ⑥ **日均 AB2（AB→AB2 25%）** | ⑤ × 25% | **4,785/日**（ABpro，≈ AB2） | **8.8/日 ✓**（目标 ≥ 8，缓冲 10%） |

> **频次口径**：国际站 FY26 目标为**周均 2 次/用户**（语雀《WhatsApp 年度总结&策略规划》：周均触达 170w ÷ 订阅池），2026-03 已实现日均触达 UV 32.8w；Visable 起步**每周 1 次**（14%/日，7 天轮一遍全池），CTR 按 10% × 0.6 衰减系数保守取值（频次翻倍 → 打开率下降，国际站 FY26 目标口径），试点期 A/B 验证**每周 2 次**（28%/日）上限。

> **订阅收集是重中之重**——国际站累积了 1.5 年+，Visable 要从 0 开始。漏斗口径与关键假设（可触达率 60%、日均口径推导、敏感性）与 Alibaba 对标明细见附录 9.1 / 9.2。

> **订阅后 onboarding（参考国际站订阅欢迎流，一期包含）**：订阅成功（二级确认完成）后 **T+0 发 1 条**欢迎消息——① 确认订阅成功 + 预告将收到什么（RFQ 机会提醒 / 产品推荐 / 卖家消息）② 偏好设置入口（品类 + 频次：每周 1 次 / 仅重要消息）③ 退订方式（合规）。仅 1 条、一次性、**不占每周 1 轮营销额度**；模板争取 Utility（€0.035/条，含订阅确认措辞），Meta 判 Marketing 则按 €0.11 计（费用见七章⑥）。价值：① 订阅确认降号码质量分风险 ② 偏好数据支撑精准圈人（"仅重要消息"偏好自动降频，与频控统一）③ 首条消息打开率高，养账号质量分。

---

## 三、一期范围界定

### 3.1 In（一期核心）

1. **订阅收集链路**：注册页独立勾选框（默认不勾选）+ 手机号验证后二次询问 + 询盘发出后弹窗 + Subscription Center 统一管理（复用 UPR-55 Lifecycle 入口）
2. **系统/交易类消息首发**（细节负责：Utkarsha · PRD_Reminder）：两类买家侧系统消息（① conversation 提醒：供应商回复即通知买家；② 买家催复提醒：供应商回复次日未回复则催复，直接服务 AB2 北极星，复用 PRD_Reminder 规则），均走 Utility 模板。计费路径：买家在 WhatsApp 对话框内 24h 客服窗口内有消息时免费发送；窗口外走 Utility 模板付费（约 €0.03-0.04/条，站内行为不产生窗口）
3. **营销试点（BRD 重点，负责：Jolyne，详见 4.2）**：两大策略二次触达（RFQ 营销 + 产品推荐）
4. **发送基础设施**：订阅态三态服务（订阅/退订/未知）、频次控制（关系对 24h/次、用户 24h ≤ 3 次）、埋点闭环（push_id + visitor_sk 归因）
5. **模板**：Utility 首批 EN+DE，措辞中性；Marketing 模板进入送审流程但暂不全量发

### 3.2 Out（一期不做）

- ❌ Marketing 全量投放（浏览→AB 等二期候选策略）→ 二期（等 Legal sign-off + 订阅量爬坡）
- ❌ AI 个性化生成（LLM 总结/意图）→ P2
- ❌ 双向消息 → 一期只发不收（后续可升级，不需重新申请）
- ❌ 站外追单类场景（已证伪）

---

## 四、方案设计

### 4.1 发送场景 · 系统/交易类（一期优先，合规压力小）

买家侧系统消息共 **2 类**（细节负责：**Utkarsha** · PRD_Reminder owner；对齐 [PRD_Reminder Notification to improve AB2](https://visable.atlassian.net/wiki/spaces/PRODTECH/pages/63340593/PRD_Reminder+Notification+to+improve+AB2)，email/app push 渠道已定义、CX-564 邮件模板 Done；WhatsApp 承接 buyer 侧两类）：

| 场景 | 触发时机 | 消息内容 | 合规类型 | 与北极星 AB2 的关系 |
|------|---------|---------|---------|-------------------|
| ① conversation 提醒（供应商回复 → 通知买家） | 供应商回复后事件实时 | 报价/回复卡片 + AI 总结关键字段（价格区间/MOQ/交期）+ 一键回复 | Utility（交易通知） | 间接：维持对话热度、拉快首响（首响 ≤5min AB2 率 59.6%） |
| ② 买家催复提醒（buyer 未回复 → 二次催复） | 供应商回复次日 buyer 仍未回复（PRD 口径：wlw 10am / ep 9am） | 催复文案（复用 PRD 模板："Supplier Waiting for Your Reply" 等） | Utility（交易通知） | **直接：buyer response to positive connection = AB2** |

**催复护栏（承接 PRD_Reminder 既有规则）：** 每个 request/message 仅发一次催复；用户已回复不发；仅 open 状态（expired / frozen / not interested / archived 不发）；AB2 建立后不再发。

> 计费路径：两类消息若落在 WhatsApp 24h 客服窗口内（买家对话框内最近有消息）免费；窗口外走 Utility 模板付费（约 €0.03-0.04/条，站内行为不产生窗口）。催复触发节奏与 PRD 定义一致（次日 10am/9am），与营销二次触达（4.2）不同时段，避免同一用户重复打扰。

### 4.2 发送场景 · 营销类（负责：Jolyne；一期试点核心：两大策略二次触达）

**一期试点两大策略（从现有 PUSH/EDM 营销策略中选定，详见 01 push业务策略表 / 02 edm业务策略表）：**

| 策略 | PUSH 对应 | EDM 对应 | 当前量级 | 打开率（wlw / ep） | 选它的理由 |
|------|----------|---------|---------|-------------------|-----------|
| ① **RFQ 营销** | PN_RFQ_MARKETING | RfQ promo-recurring（多语言模板） | push 日均发送 ~7,405 | 6.4% / 5.4% | 发送量最大策略之一；人群有明确 RFQ 意图；与系统消息 RfQ 链路同源可联动 |
| ② **产品推荐** | PN_RECOMMENDATION | Product recommendations（多语言模板） | push 日均发送 ~1,545 | 33%（ep） | 打开率数倍于其他营销策略；内容即商品卡片，WhatsApp 富媒体承接性最强 |

**素材与落地页（复用既有 Push 资产，不新造）：**

- **RFQ 营销 → 落地页：RFQ 创建页**（点击直进 RFQ 表单，路径最短；素材复用 PN_RFQ_MARKETING 文案与 RFQ 利益点）
- **产品推荐（品搜推荐）→ 策略与落地页复用 [PRD Push-Led App Retention — Lifecycle Strategy](https://visable.atlassian.net/wiki/spaces/ARISE/pages/69206790/PRD+Push-Led+App+Retention+Lifecycle+Strategy)**：浏览未搜索 → `browse_recall` 落地页（个性化 "i-i" 推荐）；搜索未 AB → `search_recall` 落地页（个性化 "q-i" 推荐）；文案组复用 `pn_mkt_prod_browse_active` / `pn_mkt_prod_search_active`（含 ${keyword} 模板变量）；WhatsApp 与 Push 同用户同轮走同一落地页策略，天然去重

**为什么是它（试点选型依据）：**

| 依据 | 说明 |
|------|------|
| 承接+放大的直接落地 | RFQ 营销/产品推荐每日触达大量用户（push 合计 ~8,950/日），但"已触达、未转化 AB"的用户没有任何再触达动作，既有投入边际沉没；WhatsApp 对这批用户做二次触达，正是"承接+放大已有触达效果"定位的直接落地 |
| 渠道优势 | WhatsApp 已读率 40-62.8%（系统 62.8% / 营销 40-50%），远高于 EDM；同样的利益点换高触达渠道再触达一次 |
| 成本效率可控 | 只打"已有触达行为"的用户，不做冷启动；人群有行为基线，试点效果可对照、风险可控 |

**圈人池（按触达轮次滚动）：**

| 池 | 圈人条件 | 规模 |
|----|---------|--------|
| 打开未转化池 | 上一轮 RFQ 营销/产品推荐（PUSH+EDM）触达打开过但未 AB | 30w（双策略池，试点前按实际圈人量核定） |
| 进站未转化池 | 上一轮 RFQ 营销/产品推荐触达后进站但未 AB | 2w（同上） |

> 两个池互斥去重；发送前过订阅态检查（必须"已订阅"），实际发送量以已订阅子集为准。

**发送流程（与现有渠道衔接，每周 1 轮滚动）：**

1. **D0**：原渠道触达（RFQ 营销 / 产品推荐的 PUSH + EDM——两渠道均为**固定批次 + 行为触发**：PUSH 当地周一/周五 9:30，EDM 固定批次周几待定）
2. **D2 起（每周 1 轮）**：取上一轮已触达未 AB 用户 → 订阅态检查（必须"已订阅"）→ **onboarding 冷却检查（订阅成功 7 天内不重复触达，onboarding 已覆盖）** → 疲劳度检查（该用户 24h 内无其他 WhatsApp 消息；当日全局发送 ≤ 1.5w session 熔断）；试点期 A/B 验证每周 2 轮上限（对标国际站周均 2 次）
3. **内容**：承接 RFQ 营销/产品推荐利益点与素材，WhatsApp Marketing 模板（Legal sign-off 后启用）；**落地页复用既有 Push 资产**（RFQ 营销 → RFQ 创建页；产品推荐 → browse_recall / search_recall，见上文"素材与落地页"）
4. **发送时间**：买家本地时间上午 10 点
5. **埋点**：push_id 贯穿原渠道与 WhatsApp，visitor_sk 归因

**试点衡量（跑通验证两个命题）：**

| 命题 | 验证方式 | 达标口径 |
|------|---------|---------|
| 承接有效性 | WhatsApp 二次触达组 AB 率 vs 未触达对照组 AB 率 | 增量显著为正（具体阈值试点前定） |
| 合规链路 | double opt-in 全流程 + Marketing 模板过审 + 零违规投诉 | 无 Abmahnung/投诉 |

**试点节奏：** DE 单国灰度（Legal sign-off + Marketing 模板过审后启动）→ 跑通 2-3 轮（**每周 1 轮**）评估 → 频次 A/B（每周 1 次 vs 每周 2 次，观察打扰率/退订/投诉）→ 达标后扩国/扩容（FR/IT/ES 随模板送审推进）。

### 4.3 订阅场景（收集触点 + double opt-in 方案）

| 触点 | 位置 | 一级同意机制 | 二级确认机制 |
|------|------|------------|-------------|
| 注册页独立勾选框 | 注册流程 | 默认不勾选，主动勾选 | WhatsApp 内确认消息/链接 |
| 手机号验证后二次询问 | 手机号验证步骤 | 验证成功后弹窗询问 | WhatsApp 内确认消息/链接 |
| 询盘发出后弹窗 | 询盘提交成功 | 场景绑定授权（最强合规） | WhatsApp 内确认消息/链接 |
| Subscription Center | 账号设置 | 用户自助开启/关闭 | 变更即时生效 |
| 站外入口（IG/FB/链接） | 社媒主页/落地页 | 表单勾选或回复关键词 | 短信/邮件确认码，回复确认后订阅 |

**营销 double opt-in 解决方案（一期必须落地）：**

1. **一级同意**：用户在站内触点主动授权（勾选/弹窗），说明内容、频次、退订方式并链接隐私声明；留证"谁、何时、哪个入口、同意文案原文"。
2. **二级确认**：通过 WhatsApp 模板消息发送确认（或短信验证码），用户回复确认/点击确认链接后才置为"已订阅"。
3. **未完成二级确认**的用户 24h 后置为"未知"态，不进入发送池（订阅态三态服务兜底）。
4. **同意记录存储**：与数据侧对齐存储方案，作为 Legal 审计证据。
5. **退订链路**：Subscription Center + 站外 STOP/UNSUBSCRIBE/ABMELDEN，即时生效并同步三态。
6. **订阅成功 onboarding（T+0，1 条，一次性）**：二级确认完成后立即发欢迎消息——① 确认订阅成功 + 预告将收到什么（RFQ 机会提醒 / 产品推荐 / 卖家消息）② 偏好设置入口（品类 + 频次：每周 1 次 / 仅重要消息，"仅重要消息"自动降频）③ 退订方式（Subscription Center + STOP）。模板争取 Utility（含订阅确认措辞，€0.035/条）；Meta 判 Marketing 则按 €0.11 计。**不占每周 1 轮营销额度，订阅后 7 天内不进入圈人池**（参考国际站订阅欢迎流）。

### 4.4 发送策略（与现有渠道的协同关系）

- **节奏**：WhatsApp 排在 Visable 现有 PUSH / EDM 触达之后，对已触达有效果的用户做**二次触达**，频率**每周 1 次起步**（对标国际站 FY26 营销目标周均 2 次，欧洲合规从严从低起步；试点期 A/B 验证每周 2 次上限）——与现有 PUSH/EDM 触达策略是"承接+放大"关系，不是并行独立渠道。
- **触发时机**：营销二次触达为买家本地时间上午 10 点（Alibaba BRD §5.4 经验）；系统类：conversation 提醒按事件实时、催复提醒按 PRD_Reminder 节奏（供应商回复次日 wlw 10am / ep 9am）。
- **多语种**：DE/EN 起步，FR/IT/ES 随模板送审推进。
- **疲劳度**：欧洲容忍度低，频控从严（关系对 24h/1 次、单用户 24h ≤ 3 次、每日全局熔断 ≤ 1.5w session 防脚本攻击）。
- **订阅后 onboarding**：订阅成功 T+0 1 条（欢迎 + 偏好设置），不占每周 1 轮营销额度；"仅重要消息"偏好自动降频，与频控统一。

### 4.5 明确不做的（红线）

| 红线 | 说明 |
|------|------|
| ❌ 未 double opt-in 的批量营销群发 | 营销类消息必须完成二级确认 |
| ❌ 敏感品类无差别推送 | 按品类/人群圈选 |
| ❌ 首次接触即推商品 | 首条消息以服务/订阅引导为主 |

---

## 五、技术实现与依赖

### 5.1 架构

```
Inquiry / RFQ Service 事件流（含催复提醒，复用 requests-service 触发）
        ↓
编排层（订阅态查询 → 频控 → 模板路由 → 埋点）
        ↓
直连 Meta Cloud API（复用既有通道，独立号码 + display name）
```

数据颗粒度：场景 id - 消息 id - 用户 id 三级（对齐 Alibaba BRD 口径），埋点字段含 push_id + visitor_sk（复用既有归因链路）。

### 5.2 依赖清单

| 依赖 | 负责方 | 关键日期 |
|------|--------|---------|
| 订阅入口改造（注册页勾选/验证后询问/询盘弹窗） | 产品（牧可） | 8 月内定排期 |
| 同意记录存储方案 | 数据侧（TBD） | Legal 咨询启动前 |
| Legal 咨询结论（B2B 同意门槛） | Legal | 越早越好（Marketing 发送 Gate） |
| Meta Cloud API 通道与模板送审 | Harry / 述合 | 9 月（Utility 首批） |
| 系统消息细节定义（催复规则/模板/护栏） | Utkarsha / PRD_Reminder 团队 | 8 月内 |

---

## 六、风险与合规

| 风险 | 严重度 | 缓解 |
|------|--------|------|
| GDPR/ePrivacy 处罚 | 🔴 高 | Legal 前置；默认不勾选；double opt-in；留证 |
| Meta Marketing 模板拒审/Quality 降级 | 🟡 中 | 措辞中性；先 Utility 后 Marketing；A/B 多版本 |
| 订阅量爬坡不及预期（35,000 基线，日均 AB2 ≥ 8 的前提） | 🟡 中 | 尽早开收集（对标国际站 1.5 年累积）；多触点铺设；监控 opt-in 率及时补触点 |
| 与 EDM/Push 疲劳度冲突 | 🟡 中 | 编排层统一疲劳度池；错峰排期 |
| 号码质量分下降被限流 | 🟡 中 | 严格频控 + 退订即时生效 + 投诉监控 |

合规前置：GDPR Art.7 + ePrivacy 明示同意、double opt-in、留证（谁/何时/入口/文案原文）、退订即时生效、Abmahnung 风险。

---

## 七、月度费用测算

**计费模型（Meta WhatsApp 按量计费）**：无账号申请费/固定月费/订阅费，仅按**模板消息条数**计费（类别不同单价不同）；24h 客服窗口内的会话消息免费。

| 消息类别 | 单价 | 适用范围 |
|---------|------|---------|
| Marketing（营销类） | 约 €0.11/条 | 营销二次触达（两大策略） |
| Utility（交易类） | 约 €0.03–0.04/条（取 €0.035） | 系统消息（conversation 提醒 / 催复提醒） |

**月度费用估算（随订阅池爬坡递增，非稳态）：**

订阅收集 9 月上线灰度、营销试点 10 月启动（视 Legal 结论）——发送量随订阅池爬坡递增，费用逐月上升，不是启动即满额。模型假设：订阅自 9 月上线后日均新增随触点放量递增（9 月灰度 1 国 1 场景 → 全渠道多触点放量，3 月冲刺收敛），2027-03-31 财年底收敛至 35,000 目标（约 212 天，日均新增 ≈ 165）；表中"月中累计订阅"为估算值，实际以订阅收集进度为准。**营销频次口径：每周 1 轮（14%/日）**；周 2 次档（A/B 上限）营销费用翻倍。

| 月份 | 阶段 | 月中累计订阅（假设） | 可触达（60%） | 日均发送（每周 1 轮，14%/日） | 营销月费用 | 系统消息月费用 | 合计 |
|------|------|-------------------|-------------|----------------------------|-----------|-------------|------|
| 2026-09 | 订阅收集灰度（1 国 1 场景）+ 模板送审/联调 | ~1,600 | ~950 | 无发送（营销未启动） | €0 | ≈ €0（送审期仅小流量测试） | **≈ €0** |
| 2026-10 | 系统消息全量 + 营销试点启动 | ~5,600 | ~3,360 | ~470 | ≈ €1,550 | ≈ €30–130（覆盖爬坡 ~30%） | **≈ €1,600–1,700** |
| 2026-11 | 放量爬坡 | ~10,700 | ~6,420 | ~900 | ≈ €3,000 | ≈ €50–200（覆盖爬坡 ~45%） | **≈ €3,100–3,200** |
| 2026-12 | 放量爬坡 | ~15,700 | ~9,420 | ~1,320 | ≈ €4,400 | ≈ €70–260（覆盖爬坡 ~60%） | **≈ €4,500–4,700** |
| 2027-01 | 放量爬坡 | ~20,800 | ~12,480 | ~1,750 | ≈ €5,800 | ≈ €80–330（覆盖爬坡 ~75%） | **≈ €5,900–6,100** |
| 2027-02 | 冲刺 | ~25,900 | ~15,540 | ~2,180 | ≈ €7,200 | ≈ €100–400（覆盖爬坡 ~90%） | **≈ €7,300–7,600** |
| 2027-03 | 冲刺（财年目标达成） | ~30,900 | ~18,540 | ~2,600 | ≈ €8,600 | ≈ €110–440（接近全量） | **≈ €8,700–9,000** |
| 2027-04 起 | 稳态（财年目标达成后） | ≥ 35,000 | ≥ 21,000 | ≥ 2,940 | ≈ €9,700/月 | €110–440/月 | **≈ €9,800–10,100/月** |

> 说明：① 爬坡期（2026-10 至 2027-03）累计费用约 €31,000–32,300（营销 ≈ €30.5k + 系统 ≈ €0.4k–1.8k），稳态后约 €9,800–10,100/月（年化 ≈ €118k–121k）；② 若频次 A/B 验证后全量切到**每周 2 次**（对标国际站周均 2 次），稳态营销费用翻倍至 ≈ €19,400/月（合计 ≈ €19,500–19,900/月，年化 ≈ €234k–239k），AB2 产出同步翻倍（≥ 17.6/日）——费用与 AB2 近似线性，单 AB2 成本不变；③ 系统消息按窗口外全额保守计费——若命中 24h 客服窗口则免费，实际费用低于上限；营销消息基本均在窗口外（主动触达，买家近期无对话），按 Marketing 单价全额计费；④ 系统消息稳态量级（100–440/日）及订阅覆盖率爬坡（2026-10 ~30% → 2027-03 全量）均为估算，待 AB2 conversations analysis 实测锁定；⑤ 稳态单 AB2 通道成本 ≈ €37（稳态月费用 ÷ 月 AB2 265 个，仅 Meta 模板费，每周 1 次档，与订阅规模无关）；爬坡期单 AB2 成本 ≈ €38（累计费用 ÷ 累计 AB2 829 个）；Alibaba 国际站整体 CPUV $0.1 / CPPB $11.4（含其他成本，仅参照量级）；⑥ **订阅 onboarding（一次性，订阅成功 T+0 1 条）**：财年累计 ≤ 35,000 条，按 Utility 计 ≈ €1,200、判 Marketing 则 ≈ €3,900（模板类别待 Meta 审核）；不入月度主表，叠加后爬坡期累计 ≈ €32,200–36,200。

---

## 八、里程碑

| 时间 | 里程碑 | 交付 |
|------|--------|------|
| 8 月 | BRD 定稿发布 → 订阅入口改造排期 → Legal 咨询启动 | BRD 发布、排期确认 |
| 9 月 | 订阅收集上线（灰度 1 国家 1 场景）+ **订阅后 onboarding** + Utility 模板送审 + 技术联调 | 订阅链路跑通、模板过审 |
| 10 月 | 系统类消息全量（conversation 提醒 + 催复提醒）+ 营销试点启动（每周 1 轮，视 Legal 结论）+ 首个 ROI 报告 | 系统类消息验证；试点命题验证 |
| 2027 Q1 | 订阅冲刺财年目标 35,000 + 北极星日均 AB2 ≥ 8 达成验证 | 财年底（2027-03-31）目标达成 |
| 后续 | 试点扩国/扩容 → P2 AI 增强 → P3 规模化（10w+ UV/日） | 规模化路径 |

---

## 九、附录

### 9.1 漏斗口径与关键假设（推导细节）

**漏斗口径与关键假设**：漏斗自发送起均为**日均值**。关键假设：可触达率 **60%**（Visable 从 0 做 double opt-in，订阅质量高于 Alibaba 混合授权实测 40%）、营销频次**每周 1 轮**（日发送率 14%，7 天轮一遍全池；对标国际站 FY26 周均 2 次，欧洲合规从低起步）、CTR 10% × 衰减系数 0.6 = **6%**（频次提升后打开率下降，国际站 FY26 目标口径）、UV→AB 20%、AB→AB2 25%（实测基线验证：buyer response to positive connection 现为 QDR wlw 18%/ep 36%、RFQ wlw 33%/ep 28%，25% 落在区间内，PRD_Reminder 口径）。按日均口径推导（**目标：日均 AB2 ≥ 8**）：订阅 35,000 → 可触达 21,000（×60%）→ 日均发送 2,940（×14%）→ 日均 UV 176（×6%）→ 日均 AB 35（×20%）→ **日均 AB2 8.8（×25%）**。**达标订阅基线：8 ÷ 25% ÷ 20% ÷ 6% ÷ 14% ÷ 60% ≈ 31,700**——订阅目标 35,000 = 达标线 110% 缓冲（CTR 衰减到 5.5% 仍保 8 个；若只到 32,000 恰好达标）。订阅目标从 67,000 降至 35,000 的依据：原 67,000 隐含"25 天一轮"的慢频次口径，频次提到每周 1 轮后达标订阅需求自然腰斩（日均新增 316 → 165，DAU 4.5w 转化 0.70% → 0.37%）；若频次 A/B 后切周 2 次（28%/日），达标基线进一步降至 ~16,000。

**敏感性**：频次是 AB2 产出的最大杠杆（双周 7%/日 → 每周 14%/日 → 周 2 次 28%/日，发送量线性翻倍，AB2 同步翻倍；CTR 按 0.6 衰减系数保守折算，若实测衰减更缓则产出更高）。订阅基线 35,000 不变时：周 2 次档日均 AB2 ≈ 17.6。若订阅爬坡不及预期（只到 32,000），每周 1 次口径仍恰可达标 AB2 = 8；若到 16,000，需周 2 次频次 + 实测 CTR ≥ 6% 双条件。反之若可触达率实测低于 60%，订阅基线需相应上调。

**系统消息漏斗（事件驱动，非圈人）**：催复 / conversation 提醒不依赖订阅池爬坡——AB 基线（现有 positive connections 日均量，AB2 conversations analysis 数据）→ WhatsApp 已订阅覆盖率（系统消息一级 opt-in 即可）→ 催复触达（次日 wlw 10am / ep 9am，每 request 一次）→ buyer response 率提升 2pp（PRD 目标）→ AB2 增量。贡献下限 ≥ 3 个/日，具体数值以 AB 基线测算锁定。

### 9.2 Alibaba 国际站实测（可行性佐证明细）

| 指标 | 国际站实测 | 说明 |
|------|-----------|------|
| 订阅 → 可触达 | 500w → 200w（40%） | Alibaba 混合授权实测；Visable double opt-in 按 60% 假设（待数据侧验证） |
| 点击率 | 13.7%（12 月周均） | 系统消息为主时 23%；营销 10%+ |
| 已读率 | 系统 62.8% / 营销 40-50% | 沟通未读提醒 |
| UV→PB | 1.3%（整体） | 系统 0.68% → 营销更高（成本 6 倍） |
| CPPB / CPUV | $11.4 / $0.1 | 从重启时 $148 优化降 87%+ |
| 归因 ROI | 1.16（12 月）→ 1.2+（Q3 达成） | 营销消息 12 月底做正 |
| 日均规模 | UV 1w / PB 137（12.21 周） | 2026.03 已到 UV 32.8w/日、PB 750/日 |
| 营销触达频次 | **周均 2 次/用户（FY26 目标：周均触达 170w ÷ 订阅池）** | 购物车流失：点击后每周 1 次、未点击 1 月/次；7 天流失召回上线即 +10,000 UV/日 |
| 日均 ABpro | **4,785/日** | ≈ Visable AB2 层（对标口径，日均值） |
| 全局熔断 | 1.5w session/日 | 计费风险红线 |

> 解读：一期是"跑通链路"的量级，不是规模化量级。订阅 35,000（财年底累计，日均新增 ≈ 165）是日均 AB2 ≥ 8 的目标基线（达标线 32,000 的 110% 缓冲），订阅收集仍是重中之重（欧洲授权严格，国际站累积了 1.5 年+，Visable 要从 0 开始），但压力已从原 67,000（日均新增 ≈ 316）显著降低。可触达率按 60% 假设（double opt-in 订阅质量更高，Alibaba 实测 40% 为保守下限），需数据侧验证；若实际低于 60%，订阅基线需相应上调。

### 9.3 术语表

| 术语 | 定义 |
|------|------|
| WABA | WhatsApp Business Account，Meta 侧企业账号 |
| AB / AB2 | Visable AB 漏斗层级：AB = 有效询盘行为；AB2 = 二级有效连接（**北极星指标：日均 ≥ 8 个**） |
| 订阅态三态 | 订阅 / 退订 / 未知（未完成 double opt-in 或状态不明） |
| session | WhatsApp 24h 对话窗口计费单元 |

### 9.4 参考资料

| 资料 | 位置 |
|------|------|
| WhatsApp 官方号申请 SOP（方案二直连） | Confluence ARISE/449445930 |
| WhatsApp 消息接入可行性评估（述合） | Confluence ARISE/436797534 |
| Visable WhatsApp 项目方案 v0.1 草案 | 钉钉 2Amq4vjg89jyZdNnCmvXZ7omW3kdP0wQ |
| WhatsApp 询盘接待方案调研 | 钉钉 mExel2BLV59rgdDPiPDejPGbVgk9rpMq |
| 04 whatsapp 业务策略表（目标基线） | 钉钉 XPwkYGxZV347LdvpH3O5D5ozJAgozOKL |
| WhatsApp 投放策略规划 | 钉钉 QG53mjyd800agdlKHexxrMad86zbX04v |
| AB2 conversations analysis 2026 | Teams/SharePoint（Muke/Benjamin/Vaish） |
| Alibaba 国际站 WhatsApp 数据与策略支撑汇总 | 本地 [Alibaba_WhatsApp_数据与策略支撑汇总.md](Alibaba_WhatsApp_数据与策略支撑汇总.md) |
| Alibaba 语雀知识库（amb5ap，7 篇已提取） | https://yuque.alibaba-inc.com/amb5ap |
| PRD_Reminder Notification to improve AB2（买家/供应商催复，buyer response 基线） | Confluence PRODTECH/63340593 |
