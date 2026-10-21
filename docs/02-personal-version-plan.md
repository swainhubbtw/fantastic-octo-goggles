# Personal Version: Updated Plan

*Updated 21 October 2026. This replaces Sections 7 and 9 of `01-market-research-and-plan.md` for now. The market research in that file still stands as background if you later decide to share the app with other families.*

## Your decisions

| Question | Your answer | What it changes |
|---|---|---|
| Country | **Australia** | Data stored in Australia (Sydney). Dexcom data comes from its non-US servers, with a reported ~3-hour delay. |
| Who builds it | **You, learning as you go**, with my help | A simpler tech approach. We build one small piece at a time, and I explain each step. |
| Pricing | **One family subscription** | Not needed for now. We keep the "family" structure in the design so it's ready if you share the app later. |
| Audience | **Just your family for now** | No app store, no market interviews, no commercial Dexcom deal, and much lighter legal requirements. |
| Focus | **Neurodiverse families (ASD)** plus type 1 diabetes | Adds the child's "what works for me" profile, handover notes, routines, NDIS/therapy tracking, and a tip of the day. |
| Core purpose | **"I never need to speak to my ex, and he can't claim I didn't tell him."** | Every important message becomes a **notice with proof of delivery**. This is now the heart of the app. |

---

## 1. The heart of the app: "proof you told him"

> **Analogy:** Think of registered post. You don't just drop a letter in a box; you get a receipt saying it was sent, and another when it was signed for. Every important message in your app works like registered post.

### How it works
1. **Every message is permanent**, as planned: add-only, with a digital fingerprint chain, so tampering would be visible.
2. **Every message shows its status:** *Sent → Delivered → Opened*, each with a time stamp.
3. **"Notices" that need acknowledgement.** For important things (a medical change, a school event, a schedule change), you tick "Needs acknowledgement". He sees an **"I've read this"** button. Until he taps it, the notice shows as *Awaiting acknowledgement*. The app sends him reminders and keeps a log of each reminder.
4. **Automatic email copies, to him and to you.** This is the most important protection, for a reason explained below.
5. **Updates count as telling him.** If you change the child's shoe size, a medication dose or a dentist appointment, the app automatically sends him a logged notice: "Shoe size updated to 2 (21 Oct, 7:42pm)". He can't say he didn't know.
6. **Monthly summary email** listing every notice sent and whether he acknowledged it.
7. **Export** to PDF for your lawyer, with verification codes.

### Why email copies matter so much: the "you built it" problem
Because **you** built and control this app, your ex could argue in court that you could have changed the records. The fingerprint chain helps, but a much stronger answer is the email copy.

> **Analogy:** It's like posting a carbon copy of every letter to his own letterbox. Even if he claims your filing cabinet was tampered with, the copy sitting in *his* Gmail (or similar), date-stamped by Google rather than by you, says otherwise. You can't edit someone else's inbox.

An email copy also means the message reaches him **even if he never installs or opens the app**.

### Honest limits
- "Opened" proves the message was opened, not that he read or understood it. The acknowledgement button is stronger. The email copy is the fallback if he never taps it.
- Courts decide how much weight to give any record. Australian lawyers note that parenting matters can be more flexible about evidence than property matters, but a complete, exported, time-ordered record carries more weight than screenshots. **Before you rely on this app, ask your family lawyer:** "If I use a self-built app with email copies to both of us, will its records carry weight?" If a court order already names a specific app, keep using that app as well.
- **Emergencies.** With type 1 diabetes in the picture, a strict "never speak" rule could be risky in a genuine emergency. I suggest an **Urgent** message type that sends a text (SMS) and a push notification, requires acknowledgement, and tells him to call if he hasn't acknowledged it within X minutes. You'd rarely need it, but it's there.
- **Message helper (optional).** This uses the "BIFF" approach (Brief, Informative, Friendly, Firm), a well-known method for writing to a high-conflict ex. Fill-in-the-blank templates keep your messages factual and hard to argue with.

---

## 2. Neurodiversity-focused features

### 2.1 "What works for [child]" profile
This is shared with him and logged, so he can never say he didn't know.
- Sensory needs (noise, clothing textures, lighting), triggers, early warning signs
- Calming and regulation strategies that work, and ones that don't
- How your child communicates best, plus special interests and favourite things
- Food preferences and safe foods
- Sits alongside the Child Passport (sizes, growth, contacts) from the first plan

### 2.2 Consistency across two homes
Autism organisations suggest the goal isn't two identical homes. Instead, keep **a few anchors the same in both**: the order of the day, the words used at transitions, the sleep routine, and regulation tools.
- **Shared routine cards**: e.g. the bedtime steps, with pictures
- **Comfort items checklist**: things that must travel with your child at every handover

### 2.3 Handover notes
A short structured form, quick to fill in and kept concise and positive, as recommended in an autism transition case study. It covers sleep, mood, meltdowns, **diabetes summary**, medications, homework, and items packed. It's sent as a notice he must acknowledge.

### 2.4 Child's visual view (later)
A simple picture screen for your child: "Tonight I sleep at **Mum's**", with a countdown ("3 sleeps until Dad's"). Predictability reduces anxiety around transitions.

### 2.5 Therapy & NDIS
- Providers directory: OT, speech pathologist, psychologist, paediatrician, endocrinologist, diabetes educator
- Therapy appointments on the shared calendar. Missed sessions are a common casualty of separation.
- Store the NDIS plan, therapy reports and school support plans in the documents vault
- Expense categories for NDIS, therapy and diabetes supplies
- A record of who is the contact person for each service

### 2.6 Observation log
A factual, dated record of behaviour, meltdowns, sleep and health. Useful for therapists, and kept neutral rather than accusatory.

### 2.7 Tip of the day
- One short tip on the home screen each day, shown to **both** parents. It's a gentle, neutral way to share strategies without it feeling like *you* are telling *him* how to parent.
- Tips come from reputable, Australian, neurodiversity-affirming sources: **Raising Children Network** (government-funded), **Autism CRC**, **Amaze**, and **Reframing Autism**. Each tip shows its source and a "read more" link.
- I can draft a starter library of tips with sources for you to review and approve. We wouldn't use made-up or unchecked AI tips.
- Optional tags so tips can match what's on (e.g. transitions, school holidays, sensory needs, diabetes and autism together).

### 2.8 Calm design
A predictable layout, few notifications, clear labels, structured forms instead of blank text boxes, and muted colours with the colour coding. This is good for your child's visual view and easier for every parent.

---

## 3. Diabetes (Dexcom) for a personal app

The personal-use decision makes this **much easier**:
- Dexcom offers a free **sandbox** (practice data) and, according to third-party guides, a **"Limited" tier for up to about 5 real users**. That's plenty for your family, and you wouldn't need the months-long commercial partnership.
- In Australia, data comes through Dexcom's non-US servers, with a reported **~3-hour delay**. So, as planned, the app is a **shared diabetes diary and handover summary**, not an alarm. **Both of you should keep Dexcom Follow** for real-time alerts.
- **Whoever holds your child's Dexcom account** logs in once to give the app permission.
- Check which device you use (G7 or Dexcom ONE+). The official documentation mentions both.
- Start with manual diary entries (hypos, sensor changes, supplies). Add the Dexcom link later.

---

## 4. Technical approach for a learner

> **Analogy:** Instead of building a car from raw metal, we buy a reliable chassis and engine and build the body and interior ourselves.

| Piece | Recommendation | Plain-English role |
|---|---|---|
| App type | **Web app installable on phones (a "PWA")** | Opens from a link, can be added to the home screen like a normal app, and needs **no app store**. Your ex just clicks a link. Push notifications work on iPhone (once it's added to the home screen) and on Android. |
| Building blocks | **React + TypeScript** | A popular, well-documented way to build screens. TypeScript catches typos in code, like spell-check. |
| Engine room (backend) | **Supabase, Sydney region** | Login, database, file storage, and security rules out of the box. Keeps data in Australia. |
| Email copies | An email service such as **Postmark** or **Resend** | Sends the "carbon copy" emails and records delivery |
| SMS for Urgent | **Twilio** or similar (later) | Text messages for emergencies |
| Hosting | **Vercel** or **Netlify** | Puts the app on the internet |
| Code storage | **GitHub** (this repository) | Saves every version of the code, like "track changes" for the whole project |

**Rough running cost:** likely **A$0–30 a month** at your scale, mostly on free tiers. SMS costs a few cents per message. Check current prices before signing up.

**Privacy:** personal use is likely outside most Australian Privacy Act obligations, but it still holds your child's health information and your ex's details. We'll keep it **invite-only (just the two of you)**, encrypted, and backed up.

---

## 5. Updated plan: build order for one family

Each step is a small project you can finish, see working, and learn from. I'll explain the new idea in each step as we go.

| Step | What you'll have | What you'll learn |
|---|---|---|
| **0. Setup** | Accounts (GitHub, Supabase, Vercel); a "Hello" page live on the internet | How code goes from your computer to a website |
| **1. Paper design** (homework you can do now) | A list of the screens you want, plus every field for your child's profile | Thinking like a designer: wireframes |
| **2. Login + family** | You and your ex can log in; nobody else can | Accounts and security rules |
| **3. Child Passport + "What works for me"** | Profile, sizes with dates, contacts, sensory profile; updates send logged notices | Databases: tables are like spreadsheets that talk to each other |
| **4. Messaging + notices** ⭐ core | Permanent messages, Sent/Delivered/Opened, "I've read this" button, email copies to both | How emails are sent and logged; fingerprint chains |
| **5. Calendar** | Colour-coded custody schedule, appointments, swap requests | Dates and repeating events (trickier than they sound!) |
| **6. Handover notes** | Structured handover form with acknowledgement | Forms and reusing the notice system |
| **7. Documents vault** | Court orders, parenting plan, NDIS plan, reports | File uploads and storage |
| **8. Tip of the day** | Reviewed tips library on the home screen | Storing and choosing content |
| **9. Expenses** | Receipts, split, approve or dispute, NDIS and diabetes categories | Calculations and statuses |
| **10. Photos & videos** | Shared album with location data removed | Image handling and privacy |
| **11. Exports** | PDF record for your lawyer | Generating documents |
| **12. Diabetes** | Manual diary first, then the Dexcom link (apply for the sandbox early) | Connecting to another company's API |
| **13. Urgent + child view** | SMS for emergencies, picture schedule for your child | Notifications and simple, kid-friendly design |

**Before inviting your ex:** test it yourself with two practice accounts, then have the lawyer conversation from Section 1.

**Timing:** at a learner's pace, expect the core (steps 0–4) to take a few weeks of regular sessions. The full list will take a few months. It's fine to start using it as soon as steps 2–4 work.

---

## 6. Sources (new for this update)

- Dexcom Developer, [v3 endpoint overview](https://developer.dexcom.com/docs/dexcomv3/endpoint-overview) (regional servers, sandbox, rate limits)
- pub.dev, [dexcom package docs](https://pub.dev/documentation/dexcom/latest/) (reported 1-hour US / 3-hour non-US delay, secondhand)
- Momentum, [Dexcom API integration guide](https://themomentum.ai/blog/dexcom-api-integration-developer-guide) (access tiers, unverified)
- GlucoPilot wiki, [Connecting data sources](https://github.com/Paco5687/GlucoPilot/wiki/Connecting-Data-Sources)
- Clayton Utz / CGW, [How digital evidence is actually used in family law disputes (Dec 2025)](https://cgw.com.au/publications/screenshots-dms-and-secret-recordings-how-digital-evidence-is-actually-used-in-family-law-disputes/)
- Justice Family Lawyers, [Can photos of text messages be used in court](https://justicefamilylawyers.com.au/avo/can-photos-of-text-messages-be-used-in-court/)
- Barton Family Law, [Text messages in family court](https://bartonfamilylaw.com.au/blogs/commonly-asked-questions/text-messages-family-court/)
- Middletown Centre for Autism, [Case study: transitioning between separated parents](https://managing-change.middletownautism.com/casestudies/case-for-transitioning-between-separated-parents)
- Special Learning, [Keeping things steady for your autistic child across two homes](https://special-learning.com/autism/two-homes-after-separation/)
- National Autistic Society community, [Joint residence co-parenting tips](https://community.autism.org.uk/f/parents-and-carers/36834/joint-residence-co-parenting-tips)
- Nelsons Law, [Living arrangements for autistic children](https://www.nelsonslaw.co.uk/living-arrangements-for-autistic-children/)
