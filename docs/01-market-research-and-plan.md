# Co-Parenting App: Market Research, Suggestions & Project Plan

*Prepared 21 October 2026. Research only. No code has been written yet.*

---

## 1. Your goal in one paragraph

You want one app for separated or divorced parents. It would include:

- **Messaging** where messages can never be deleted
- A **shared, colour-coded calendar**
- A **shared finance tracker**
- **Photo and video sharing**
- **Secure storage for court orders and parenting plans**
- A **child details "passport"**: sizes, growth, and contacts for school, the doctor and specialists
- A **link to Dexcom Follow** so both homes can see diabetes events

> **Analogy:** Most co-parents today use a "junk drawer" of tools: WhatsApp for messages, a paper calendar on the fridge, a spreadsheet for money, and a shoebox for court papers. Your app is a single, well-labelled filing cabinet that both parents share. Some drawers are locked so nothing can be secretly removed.

---

## 2. Who is already in the market

| App | What it's known for | Price (approx.) | Main praise | Main complaints |
|---|---|---|---|---|
| **OurFamilyWizard (OFW)** | The "court standard". Judges in the US and elsewhere often order it. | ~US$99–199 **per parent** per year. ToneMeter is extra. | Records are trusted in court. The ToneMeter tone checker. Info Bank for child details. | Expensive, because *both* parents pay. Crashes and freezes. Notification problems. Can't save drafts. Calendar, journal and expenses feel "isolated" and require typing things twice. Most-requested feature: **sync with Google/Apple calendars**. Trustpilot score ~2.5–2.8 vs ~4.5 in app stores. |
| **TalkingParents** | Documentation for high-conflict cases | Free tier. Paid plans from ~US$7/month. | "Unalterable records": PDFs with a digital signature and 16-digit verification code. Recorded calls. | Slow loading, crashes, automatic logouts. Attachment and notification problems. Billing issues. Free users must pay ~US$50 per record export. |
| **AppClose** | Feature-rich and cheaper | ~US$8–9/month after a 60-day trial. Free for hardship cases and domestic-violence survivors. | Unalterable messages, calendar, expenses with receipts, built-in payments, recorded calls. | Few independent reviews were found, so treat its claims as marketing. Ratings vary by country (4.0 in an older Australian store snapshot). |
| **2houses** | Popular in Europe, UK and Australia. One subscription covers the whole family. | Cheapest of the main apps | Shared calendar, expenses, messages, photo album, child info (sizes, doctor and coach contacts). Mediators can join. | Less court recognition than OFW |
| **BestInterest** | New. Uses AI to protect *you* from hostile messages. | Free download with in-app purchases | Works **even if the other parent won't join**. Screens incoming messages and summarises or blocks hostile content. "Tone Guardian" checks your drafts. | Very new. No independent evidence yet on accuracy or privacy. |
| **Our Children (Australia)** | Platform studied by Australian researchers | — | 18 of 20 women surveyed found it beneficial | Some abusive ex-partners used it to continue the abuse |

**Gap worth noting:** none of the major apps connect to diabetes or health devices. A Dexcom link would be a genuine **point of difference**.

---

## 3. What the feedback tells us (themes)

1. **Cost and fairness.** People resent both parents paying. A **one-subscription-per-family** model (as 2houses uses) is popular.
2. **Reliability is the product.** The most common complaint across all apps is crashes, slow loading and missed notifications. If a message about a sick child doesn't arrive, nothing else matters.
   > **Analogy:** A smoke alarm with fancy features is useless if the battery dies. Boring reliability is your most important feature.
3. **Duplicate typing.** Users hate entering the same thing in several places. For example, a dentist visit should be entered once and appear in the calendar, the expense list and the child's medical record.
4. **Calendar sync.** This is the most-requested feature. Parents already live in Google or Apple calendars.
5. **Court-ready records.** This is the main reason people choose OFW and TalkingParents. Exports must be tamper-evident and easy to verify.
6. **Tone and conflict help.** ToneMeter and BestInterest's filters are well liked. The best design checks *your own* drafts (as OFW does) and can also *shield you* from incoming hostility (as BestInterest does).
7. **Safety cuts both ways.** Australian research (ANU, QUT, Griffith, Flinders, Relationships Australia Victoria) found these apps help many survivors of family violence by creating a record. It also found abusers can misuse them. One tactic is putting abuse in the child's name or subject line so it gets past restrictions. Apps are "harm-minimisation tools, not a panacea."
8. **Support and billing.** Slow customer support and being billed after accounts broke are common Trustpilot complaints.

---

## 4. Suggestions: your features, improved

### 4.1 Messaging that can't be deleted
- **Append-only design.** Messages can only ever be *added*. To correct a mistake, a parent sends a follow-up, which is shown as "Correction to message of 3:04pm".
  > **Analogy:** It's a bound notebook with numbered pages, not a whiteboard. You can't tear out a page without the gap showing.
- **Tamper-evidence ("hash chain").** Each message carries a digital fingerprint of the message before it. If anyone, even the company, altered an old message, the chain of fingerprints would visibly break.
- **Read receipts with timestamps.** Show when a message was first opened. Parents value this as evidence that it was seen.
- **Court export.** A PDF or printout with a verification code that a lawyer or court can check on a website. TalkingParents does this; you could include it free for every plan.
- **Draft tone check.** Optional and private: "This message may come across as hostile. Send anyway?"
- **Incoming shield (optional).** Hostile messages are blurred with a neutral summary, and the original is always kept and viewable.
- **Topic threads.** Separate threads for "School", "Medical", "Handover" and "Money". This keeps logistics out of arguments.
- **Quick replies** for common logistics, such as "Running 10 mins late" and "Confirmed".
- **Watch out:** in some countries, privacy laws (e.g. the UK/EU "right to erasure") can clash with "never delete". This needs legal advice before launch (see Section 6).

### 4.2 Shared colour-coded calendar
- One colour per parent, plus colours for each child and for shared events. Use patterns or icons as well as colours, for colour-blind users.
- **Custody schedule templates**, such as week-on/week-off, 2-2-3 and every second weekend. Enter the parenting plan once and the calendar fills itself in.
- **Swap requests.** "Can we swap the 14th for the 21st?" The other parent accepts or declines, and the request and decision are logged permanently, like messages.
- **Two-way sync** with Google, Apple and Outlook calendars. This is the #1 request in reviews.
- **Handover events** with a checklist: medication, school bag, Dexcom sensor supplies, favourite toy.
- **Custody-time report.** The actual number of days or nights with each parent, useful for child-support calculations.

### 4.3 Shared finance tracker
- Log an expense, attach a photo of the receipt, choose a split (e.g. 50/50 or 60/40, set once per family), and request reimbursement.
- Statuses: *Requested → Approved / Disputed → Paid*. Every step is permanently logged.
- **Categories** such as school, medical, diabetes supplies, activities and clothing. Diabetes costs (sensors, insulin, pump supplies) can be large and recurring, so allow **recurring expenses**.
- Monthly and yearly summaries, exportable for accountants, lawyers or tax time.
- *Later:* built-in payments (AppClose has this). Holding or moving money brings heavy regulation, so start with "mark as paid" and add payments much later, if ever.

### 4.4 Photos and videos
- A shared album per child, so both parents see the school concert even if they weren't there.
- Remove location data hidden inside photos (EXIF/GPS) automatically. **This is an important safety feature.**
  > **Analogy:** Every phone photo has an invisible sticky note on the back saying where it was taken. For a parent who has fled violence, that note could reveal their new address. Peel it off automatically.
- Clear limits on video size and length, with automatic compression to keep storage costs manageable.

### 4.5 Court orders & parenting plans vault
- Upload PDFs and photos. The app records who uploaded each document and when, and keeps every version.
- **Key-clause highlights.** A parent can pin "Clause 7: Christmas alternates years" so it's easy to find in a dispute.
- *Later:* the app reads the parenting plan and *suggests* calendar entries, which a person confirms.
- Optional view-only sharing with a lawyer, mediator or family consultant.

### 4.6 Child details ("Child Passport")
- **Growth history.** Store height and weight as dated entries, not a single number, and show a simple growth chart.
- **Sizes**: clothing, shoes, school uniform. Each shows a "last updated" date so you know whether it's current.
- **Contacts directory**: school, teachers, GP, paediatrician, endocrinologist, diabetes educator, dentist, specialists. Each has one-tap call or email.
- **Medical**: allergies, medications, Medicare or insurance numbers, immunisations, and the **diabetes management plan**.
- **Emergency card.** A one-page summary you can hand to a babysitter, grandparent or school camp: diabetes info, hypo instructions, emergency contacts.
- **Permissions.** Optional limited access for grandparents, step-parents or babysitters, e.g. they see the emergency card but not the messages or money.

### 4.7 Dexcom / diabetes features (see Section 5 for the technical reality)
- **Diabetes diary**: hypos, highs, insulin doses, carbs, sensor changes, sick days. Some entries come automatically from Dexcom, and parents can add manual notes.
- **Handover summary**: "Last 24 hours at Mum's: 2 lows overnight, sensor changed Tuesday, 3 days of supplies sent in bag."
- **Supplies tracker**: how many sensors and insulin pens are at each house, with a reorder reminder.
- **Important:** the app should **not** replace the Dexcom Follow app for real-time alarms. It should present itself as a *shared diary and history*, and tell parents to keep Dexcom Follow installed for urgent alerts.

### 4.8 Extra features worth considering (not in your list)
| Idea | Why |
|---|---|
| One subscription per family | The most common cost complaint |
| Works solo if the other parent won't join | BestInterest's main selling point |
| Professional access (lawyer, mediator) | Read-only access for proceedings |
| Safety mode | Hide the app behind a neutral icon. Never share either parent's location. Quick-exit button. Easy reporting of abusive content. |
| Journal / private notes | Notes only you can see, timestamped |
| Child's voice (later, for older kids) | A limited view for teens to see their schedule |
| Offline mode | View the emergency card and contacts without internet signal |
| Multi-language support | Many separated families speak different first languages |

---

## 5. The Dexcom link: what's actually possible

> **Analogy:** Dexcom's data is like a bank account. You can't just peek in. The account owner has to give your app permission, a bit like an authorised third party on a bank account. Dexcom decides which apps it allows in, and at what speed.

| Option | How it works | Speed of data | Verdict |
|---|---|---|---|
| **A. Official Dexcom Developer API** | The parent who holds the child's Dexcom account logs in through Dexcom's own secure sign-in (called *OAuth*) and grants your app permission. Your app then reads glucose readings, events such as carbs and insulin, alerts and device info. | Third-party sources report **~1 hour delay in the US, ~3 hours outside the US**. Real-time access is only for invited "partners". | ✅ **Recommended.** Free sandbox (test data) to start. A "limited" tier for up to ~5 real users suits a pilot. A full commercial partnership requires Dexcom approval, which can take **weeks to months**, so apply early. |
| **B. Apple Health / Google Health Connect** | Dexcom writes data into the phone's health app, and your app reads it from there. | ~3-hour delay | ✅ Good backup option. Only works on the phone where the data lives. |
| **C. Unofficial "Share" API** (used by hobby projects like Nightscout) | The app stores the parent's Dexcom username and password and imitates the Follow app. | Near real-time | ❌ **Not recommended** for a commercial app. Storing passwords is a security risk, it isn't officially supported, it could stop working at any time, and it may break Dexcom's terms. |

**Key consequences:**
- Because of the delay, your app is a **history and handover tool**, not an alarm system. That's actually a good fit for co-parenting. It also keeps you clear of being classed as a **medical device**. Apps that show real-time glucose for treatment decisions can fall under the FDA (US), TGA (Australia) or MHRA (UK).
- Diabetes data is **health information**. Health information has the strictest privacy rules: Australia's Privacy Act ("sensitive information"), UK/EU GDPR ("special category data"), and US health-data and breach-notification rules. It needs stronger security and clear consent.
- The parent who controls the child's Dexcom account decides whether to share. The app must handle the case where one parent connects Dexcom and the other only views.
- Dexcom's official developer documentation and terms must be checked directly before committing. The figures above come mostly from third-party summaries, as the official site couldn't be reached during this research.

---

## 6. Risks to plan for early

1. **"Never delete" vs privacy law.** Get legal advice on retention periods and what happens when a parent closes their account. A likely approach: the account closes, but the shared record is kept for the other parent for a set period.
2. **Court acceptance.** Records only help if lawyers trust them. Talk to 2–3 family lawyers or mediators *before* building the export feature.
3. **Abuse misuse.** Design with family-violence safety in mind from day one. Consider consulting a family-violence service such as 1800RESPECT in Australia, Refuge in the UK, or WomensLaw resources in the US.
4. **Health data security.** Use encryption, careful access controls, and cloud providers that handle health data.
5. **Reliability.** This is competitors' biggest weakness, so it's your opportunity. Budget time for testing and monitoring.
6. **Dexcom approval timeline.** This is out of your control, so start the process early.

---

## 7. The plan: from idea to app store

> **Analogy:** Building an app is like building a house. You don't start by laying bricks. First you check who'll live there (research), then draw the plans (design), pour the foundations (accounts, security, database), then build one room at a time (features), have it inspected (testing and legal), and finally move in (launch).

### Phase 0: Key decisions (1–2 weeks)
Questions only you can answer (see Section 9). They decide the country and laws, the budget, and whether you build it yourself, with help, or hire developers.

### Phase 1: Validate the idea (2–4 weeks)
- Interview **10–15 separated parents**, including some with diabetic children, and **2–3 family lawyers or mediators**.
- Ask what they use now, what frustrates them, and what they'd pay.
- Write a one-page "who is this for" summary (a *persona*), e.g. "Sam, 38, shares week-on/week-off care of a 9-year-old with type 1 diabetes."
- **Apply for Dexcom sandbox developer access now**, because approval takes time.

### Phase 2: Design (3–4 weeks)
- Sketch every screen as simple boxes, called *wireframes*: like a floor plan before choosing paint colours.
- Turn the sketches into a clickable mock-up (using a tool like Figma) and test it with 5 of the parents from Phase 1.
- Decide on the visual style: calm colours, clear colour coding, accessible text sizes.

### Phase 3: Technical foundations (2–3 weeks)
Recommended approach for a small team or solo builder:
- **One codebase for iPhone, Android and web**, using a *cross-platform framework* such as React Native (Expo) or Flutter.
  > **Analogy:** Instead of writing the same book separately in English, French and Spanish, you write it once and a translator produces all three editions.
- **A "backend"**: the app's engine room in the cloud that stores messages, files and accounts. A managed service such as Supabase or Firebase gives you login, a database and file storage without building them from scratch.
- Set up: accounts and login, linking two parents into one "family", encryption, and automatic backups.

### Phase 4: Build the MVP, one room at a time (10–16 weeks)
An *MVP* (Minimum Viable Product) is the smallest version that's genuinely useful: a sturdy one-bedroom house you can live in while you plan the extension.

Suggested build order (each depends on the one before):
1. **Accounts and family linking**: invite the other parent, add children
2. **Child Passport**: contacts, sizes, medical info, emergency card. Low risk and immediately useful.
3. **Messaging**: append-only, tamper-evident, notifications
4. **Shared calendar**: colour coding, custody templates, swap requests
5. **Documents vault**: court orders and parenting plans
6. **Finance tracker**: expenses, receipts, splits, approvals
7. **Photos and videos**: with location data stripped automatically
8. **Exports**: court-ready PDF of messages, calendar and expenses

### Phase 5: Diabetes features (4–6 weeks, can overlap Phase 4)
- Manual diabetes diary and supplies tracker first. These need no Dexcom approval.
- Then connect the Dexcom sandbox (test data), then a limited pilot with real families once Dexcom permits.
- Apple Health / Google Health Connect as a fallback.

### Phase 6: Testing, safety & legal checks (4–6 weeks)
- **Beta test** with 10–20 real families through TestFlight (iPhone) and Google Play testing.
- Security review (ideally an independent "penetration test", where experts try to break in).
- Legal review: privacy policy, terms, data retention, health-data rules in your launch country.
- Family-violence safety review.

### Phase 7: Launch & improve (ongoing)
- Publish to the Apple App Store and Google Play. Both review apps before listing, and health-related apps get extra scrutiny.
- Set up crash monitoring so you hear about problems before users do.
- *Later additions:* calendar sync, AI tone check and shield, professional access, built-in payments, parenting-plan reading, multi-language.

**Rough total to first public launch: about 7–10 months** for a small team. Expect longer if solo or part-time. These are planning estimates, not promises.

---

## 8. Mini glossary

| Term | Plain-English meaning |
|---|---|
| **App / frontend** | What you see and tap on your phone: the shop floor |
| **Backend** | Computers in the cloud that store and send the data: the warehouse behind the shop |
| **Database** | An organised set of digital filing cabinets |
| **API** | A "service window" through which one program asks another for data, e.g. our app asking Dexcom for readings |
| **OAuth** | A safe way to grant access without sharing your password, like giving a valet key that only starts the car but can't open the boot |
| **Encryption** | Scrambling data so only the right people can read it, like a letter in a code only you and the recipient know |
| **Hash** | A unique digital fingerprint of a piece of data. Change one letter and the fingerprint changes completely. |
| **Append-only** | Data can be added but never edited or removed |
| **MVP** | Minimum Viable Product: the simplest useful version |
| **Wireframe** | A rough sketch of a screen's layout |
| **Cross-platform** | One set of code that runs on iPhone, Android and web |
| **Sandbox** | A practice area with fake data, for safe testing |

---

## 9. Questions for you before Phase 1

1. **Which country will you launch in first?** Your spelling suggests Australia, the UK, NZ or Canada. This decides privacy laws, court-export formats, and Dexcom data delays.
2. **Will you build it yourself, learn as you go, or hire developers?** This changes the timeline and budget a lot.
3. **Budget and business model.** Free with paid extras? One family subscription? Free for family-violence survivors?
4. **iPhone, Android, web, or all three?**
5. **Is the diabetes feature for a specific family (e.g. your own) or a core selling point?** This decides how early to approach Dexcom.

---

## Sources

- 2houses, [Best co-parenting apps for separated parents 2026](https://www.2houses.com/en/blog/best-co-parenting-apps-for-separated-parents-2026) and [2houses vs OurFamilyWizard](https://www.2houses.com/en/blog/2houses-vs-ourfamilywizard) (vendor content)
- Stange Law Firm, [Co-Parenting Apps Besides Our Family Wizard](https://stangelawfirm.com/articles/co-parenting-apps-besides-our-family-wizard-alternatives-pros-and-cons/)
- HackerNoon, [The 7 best coparenting apps in 2026](https://hackernoon.com/the-7-best-coparenting-apps-in-2026)
- iTechGuides, [The Best Co-Parenting Apps in 2026](https://www.itechguides.com/best/co-parenting-apps/)
- ThePricer, [How much does OurFamilyWizard cost](https://www.thepricer.org/how-much-does-ourfamilywizard-cost/)
- Multnomah County, [Co-parenting apps (2024)](https://multco.us/file/co-parenting_apps_%282024%29/download)
- LSNJ Law, [Co-parenting applications](https://lsnjlaw.org/legal-topics/family-relationships/custody-visitation/general-information/pages/co-parenting-applications)
- Marlvel, [OurFamilyWizard user reviews, decoded](https://marlvel.ai/apps/ourfamilywizard-co-parent-app/reviews) (automated aggregator)
- Trustpilot, [OurFamilyWizard reviews](https://nz.trustpilot.com/review/www.ourfamilywizard.com)
- OurFamilyWizard, [Info Bank support](https://support.ourfamilywizard.com/hc/en-us/sections/26332519743885-Info-Bank)
- Justuseapp, [TalkingParents reviews](https://justuseapp.com/en/app/1092220726/talkingparents/reviews); Apple App Store, [TalkingParents](https://apps.apple.com/app/id1092220726); TalkingParents, [legal brochure](https://legal.talkingparents.com/files/digital-brochure-8-5x11.pdf)
- AppClose, [Pricing](https://appclose.com/pricing) and [Brochure](https://appclose.com/info/AppClose-Pro-Brochure-PDF.pdf); AppFollow, [AppClose AU listing](https://apps.appfollow.io/ios/appclose/1019290876?country=au)
- BusinessWire, [BestInterest launch](https://www.businesswire.com/news/home/20241021896159/en/Frustrated-Parent-Launches-Innovative-AI-Powered-Co-Parenting-App-BestInterest); Apple App Store, [BestInterest](https://apps.apple.com/us/app/bestinterest-for-coparents/id6503981502)
- Relationships Australia Victoria, [Smartphone apps for separated co-parents (Aug 2024)](https://relationshipsvictoria.org.au/media/uhgd5yzr/smartphone-apps-for-separated-co-parents-information-sheet_rav_aug-2024.pdf)
- ANU, [Post-Separation Parenting App Information](https://polis.cass.anu.edu.au/files/docs/2025/6/Post-Separation-Parenting-App-Information-v6.pdf) and [Post-separation co-parenting apps project](https://csrm.cass.anu.edu.au/research/projects/post-separation-parenting-apps)
- ANU, [Post-separation parenting apps: potential benefits and risks](https://researchportalplus.anu.edu.au/en/publications/post-separation-parenting-apps-potential-benefits-and-risks-in-th/)
- QUT Law, Technology & Humans, [study of mothers' experiences](https://lthj.qut.edu.au/article/download/3403/1479/13199)
- Griffith University, [DFV survivors' experiences with an online co-parenting platform](https://research-repository.griffith.edu.au/items/0bef42c6-aca5-4b4b-af08-79ce507d1a78)
- Flinders University, [Internet-based co-parenting apps: protecting women and children](https://researchnow.flinders.edu.au/en/publications/internet-based-co-parenting-apps-protecting-women-and-children-ag/)
- WomensLaw, [How can co-parenting technology help me stay safe?](https://www.womenslaw.org/about-abuse/abuse-using-technology/ways-courts-use-technology/co-parenting-apps/how-can-co-parenting)
- UEA Family Courts, [Co-parenting apps](https://www.uea.ac.uk/groups-and-centres/family-courts/co-parenting-apps)
- Dexcom Developer, [v3 endpoint overview](https://developer.dexcom.com/docs/dexcomv3/endpoint-overview)
- Momentum, [Dexcom API integration developer guide](https://themomentum.ai/blog/dexcom-api-integration-developer-guide) (third-party)
- Dexcom, [Sharing CGM data: clinics, apps and followers](https://www.dexcom.com/en-GB/faqs/how-many-sharers-can-i-follow)
- BusinessWire, [Dexcom real-time API FDA clearance (2021)](https://www.businesswire.com/news/home/20210715006049/en); MobiHealthNews, [New Dexcom API](https://mobihealthnews.com/node/143364)
- pub.dev, [dexcom package](https://pub.dev/packages/dexcom) (notes on Share API and data delays)
- Scott Hanselman, [Bridging Dexcom Share and Nightscout](https://www.hanselman.com/blog/bridging-dexcom-share-cgm-receivers-and-nightscout)
