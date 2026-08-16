# NEET UG 2025 Allotment Cutoffs — MCC (All India) & Karnataka (KEA) Reference Data

## Purpose & scope

This is a **data reference companion** to `MD-NEET-KB.md` (the narrative Margdarshak NEET knowledge base). Where that file explains *how* NEET counselling works, this file gives the **actual closing-rank (cutoff) data from the 2025 admission cycle** — the most recently completed full cycle at the time this file was built — for:

1. **MCC — All India Quota (15% AIQ) + Deemed Universities + Central Institutions**, Round 1 (Provisional), 2025 — 477 MBBS institutes and 86 BDS institutes, nationwide.
2. **KEA — Karnataka state-quota MBBS**, Rounds 1 and 2 (Final), 2025 — all 66 KEA-counselled MBBS colleges in Karnataka.
3. **KEA — Karnataka state-quota Dental (BDS)**, Round 2, 2025 — 39 colleges.
4. **KEA MBBS seat matrix, 2025 vs 2026** — KEA-counselled seat counts per college and how they changed year-on-year.

**Use this file to answer:** "What rank do I need for college X?", "Which government/private colleges can I realistically target with rank Y?", "How does college A compare to college B?", "Which Karnataka colleges are most competitive/most preferred?" For exam mechanics, counselling process, dates, and general context, defer to `MD-NEET-KB.md` instead — this file is numbers-only.

## How to read every table here — definitions

- **Opening Rank** = the best (lowest, i.e. most competitive) All-India Rank (AIR) allotted a seat in that college + course + category, in that round.
- **Closing Rank** = the worst (highest) AIR that still got allotted a seat — this is what "cutoff" conventionally means. **A rank numerically at or below the closing rank had a real shot at that seat in that round.**
- **Seats** = number of candidates actually allotted in that college + category in that round (a proxy for how many seats existed in that bucket that round — not the college's total sanctioned strength).
- All ranks are **2025 NEET UG All India Ranks (AIR)**, from actual allotment results — not qualifying-exam percentile cutoffs, and not projections.
- Blank cells mean **no seat was allotted in that college+category combination in that round** in the source data (could mean zero seats existed in that bucket, or that all such seats were filled in an earlier round and none remained) — not zero demand.

## Data provenance & methodology

| Source file | What it is | Rows analyzed |
|---|---|---|
| `MCC_R1P.xlsx` | MCC's official Provisional NEET-UG Counselling Seat Allotment result, **2025 Round 1**, India-wide (15% AIQ in every state government college + 100% of every Deemed University + AIIMS/JIPMER/BHU/AMU/Delhi University/IP University/ESIC and other central institutions) | 26,608 candidate-level allotment rows |
| `ALLOT_R2_copy (1).xlsx` | Karnataka's KEA MBBS allotment result for **2025**, with separate tabs for Round 1, Round 2, and the Round-2-Final reconciled list | R1: 8,321 rows · R2: 9,243 rows · R2-Final: 9,958 rows |
| `KEA_Dental_R2.xlsx` | KEA's Karnataka BDS (dental) allotment result, **2025 Round 2** | 2,812 rows |
| `MBBS_SEAT_MATRIX_COMPARISON_2025_vs_2026_Rev1.xlsx` | A college-by-college comparison of KEA-counselled MBBS seat counts between the 2025 and 2026 admission cycles (total seats, and the Kalyana-Karnataka/HK vs Rest-of-Karnataka/RK regional split) | 67 colleges |
| `MBBS+SEAT+MATRIX+2025_KEA.xlsx` | The detailed 2025 KEA seat-capacity matrix (seats broken down by every reservation category and region) — used here only to pull each college's **ownership type** (Government / Private / Deemed / Minority) | 66 colleges |

**Aggregation method:** for each table, the source candidate-level allotment rows were grouped by college + course + category, and the minimum and maximum AIR within each group were taken as the Opening and Closing rank. For the MCC national table, rows were first filtered to each institute's dominant allotment-quota channel (e.g., AIIMS Delhi's 48 "Open Seat Quota" MBBS seats) to exclude small unrelated quota pools riding on the same institute (e.g. a handful of "Foreign Country Quota" seats at AIIMS Delhi that are not part of the domestic merit list and would otherwise wrongly inflate its closing rank).

## Category code glossary

**MCC (national) categories:** Open (Unreserved/General) · EWS (Economically Weaker Section) · OBC (OBC-NCL) · SC · ST, each with a PwD (Persons with Disability) variant not included in the summary tables below (available in the source file for a finer cut).

**KEA (Karnataka) categories** follow the pattern `[Merit Ladder][Region][Horizontal]`:
- **Merit ladder prefix:** `GM` = General Merit (unreserved) · `1` = Category I · `2A`, `2B`, `3A`, `3B` = Karnataka's backward-class ladder · `SC` / `ST` = Scheduled Caste / Scheduled Tribe.
- **Region suffix:** `G` = General/state-wide (no regional-nativity requirement) · `R` = Rest-of-Karnataka regional-nativity quota · `K` = Kalyana-Karnataka / erstwhile Hyderabad-Karnataka (Article 371(J)) regional-nativity quota.
- **Horizontal suffix `H`:** a Persons-with-Disability/horizontal-reservation overlay — appears alone (e.g. `GMH`, `1H` = General-Horizontal) or appended to a region code (`RH`, `KH`, e.g. `2ARH`, `3BKH`).
- **Seat-type codes (not merit-ladder):** `OPN` = private-college management/open-fee seat · `GMP` = government-fee seat inside a private/deemed college · `NRI` = NRI quota (deemed/private colleges).
- **Other niche codes** you may see in the raw source but not summarized here (`MC`, `MM`, `MK`, `MU`, `MA`, `ME`, `NCC`, `SPO`, `JK`, `S&G`, `DK`, `D`, `XD`, `CAP`, `RC1`–`RC7`, etc.) are small special/minority/linguistic/sports/defence reservation categories — verify exact eligibility for these against KEA's current-year information bulletin before quoting a cutoff for one.

## Caveats — read before quoting a number to a parent

- **This is 2025 data, not 2026.** It is the best available *actual outcome* dataset and is extremely useful for **relative comparison** (which colleges are more/less competitive than which others, and by roughly how much) — but 2026 absolute ranks will differ because the 2026 exam was rated easier and the qualifying-mark band shifted up by roughly 69 marks at the lower bound (per `MD-NEET-KB.md` Section 7). Do not quote a 2025 closing rank as this year's cutoff without saying so explicitly.
- **MCC figures are Round 1 (Provisional) only.** Closing ranks loosen (go higher) substantially in Round 2, Round 3/Mop-up, and Stray Vacancy as seats vacated by upgrading candidates re-enter the pool — `MD-NEET-KB.md` notes 2025 AIQ government-college closing ranks reached roughly AIR ~26,000 by later rounds for General/OBC. Treat the Round 1 figures below as a **floor/best-case**, not the final word — a rank above a college's Round-1 closing rank in this table is *not* automatically out of contention for that college once later rounds are considered.
- **KEA figures include Round 1, Round 2, and Round-2-Final** for MBBS (so you can see how much a college's cutoff moved between rounds), but only **Round 2** for Dental — there was no separate Round 1 dental extract available.
- **College name spelling varies slightly between source files** (e.g. "Bangalore Medical College" vs "Bangalore Medical College and Research Institute, Bangalore" in the seat-matrix file) — this file normalizes names per-table but the seat-matrix table (Section 5) was **not** cross-merged with the cutoff tables (Sections 3–4) because the merge could not be done reliably; treat Section 5 as a standalone reference for seat counts, not row-aligned with Sections 3–4.
- **Two Karnataka colleges — Jawaharlal Nehru Medical College, Belgaum, and Farookh Academy of Medical Education — appear only in the Round 2/Final KEA data**, not Round 1 or the 2025 baseline seat matrix; their seats were evidently added mid-cycle (the source data flags JNMC Belgaum's 12 state-quota seats as "subject to the final outcome of W.P. No. 106257/2025"). Flag this pending-litigation status if a parent asks about JNMC Belgaum specifically.
- **"Type" (Government/Private/Deemed/Central/etc.) is inferred from the seat-allotment mechanism**, not an independent ownership registry — it is reliable for the vast majority of institutes but can mislabel a handful of colleges that draw meaningfully from two channels at once (e.g., a Delhi college with both AIQ and Delhi-University-quota seats).
- **Seats/opening/closing figures are allotment counts within the source round, not sanctioned intake.** A college showing 15 "Open" seats in MCC Round 1 may have a much larger total MBBS capacity once state quota, management quota, and later AIQ rounds are counted.

## "Which colleges are most preferred?" — read the ranking, don't guess

In a merit-based allotment system, a college's closing rank in the general/open category **is** the community's revealed preference — better-ranked candidates fill the most-wanted colleges first, so the colleges with the *lowest* closing ranks are, by definition, the most preferred. That is exactly what Sections 1 and 3 below are sorted by. Two curated top-15s, for quick reference:

**Most preferred nationally (MCC AIQ, Round 1 2025, Open category):**

1. **AIIMS New Delhi** (Delhi (NCT)) — Open closing rank **48**
2. **JIPMER Puducherry** (Puducherry) — Open closing rank **258**
3. **AIIMS Jodhpur** (Rajasthan) — Open closing rank **392**
4. **AIIMS Bhopal** (Madhya Pradesh) — Open closing rank **531**
5. **AIIMS Rishikesh** (Uttarakhand) — Open closing rank **685**
6. **Government Medical College & Hospital, Chandigarh** (Chandigarh) — Open closing rank **690**
7. **Madras Medical College, Chennai** (Tamil Nadu) — Open closing rank **695**
8. **AIIMS Bhubaneswar** (Odisha) — Open closing rank **706**
9. **AIIMS Nagpur** (Maharashtra) — Open closing rank **862**
10. **Seth G.S. Medical College, Mumbai** (Maharashtra) — Open closing rank **868**
11. **B.J. Medical College, Ahmedabad** (Gujarat) — Open closing rank **889**
12. **Institute of Medical Sciences, BHU** (Uttar Pradesh) — Open closing rank **1,165**
13. **Govt. Medical College, Kozhikode** (Kerala) — Open closing rank **1,173**
14. **S.M.S. Medical College, Jaipur** (Rajasthan) — Open closing rank **1,174**
15. **Vardhman Mahavir Medical College & Safdarjung Hospital, New Delhi** (Delhi (NCT)) — Open closing rank **1,221**

**Most preferred in Karnataka (KEA, Round 2 Final 2025, GM category):**

1. **Bangalore Medical College** (Government) — GM closing rank **3,025**
2. **Kasturba Medical College** (Deemed/Private University) — GM closing rank **6,786**
3. **Shri Atal Bihari Vajpayee Institute of Medical Science** (Government) — GM closing rank **7,669**
4. **Mysore Medical College** (Government) — GM closing rank **8,394**
5. **M.S.Ramaiah Medical College** (Deemed/Private University) — GM closing rank **11,776**
6. **ESI Medical College (Rajajinagar)** (Government) — GM closing rank **12,937**
7. **Karnataka Institute of Medical Sciences** (Government) — GM closing rank **13,488**
8. **Jagadguru Sri Shivarathreeswara Medical College** (Deemed/Private University) — GM closing rank **14,777**
9. **Mandya Institute of Medical Sciences** (Government) — GM closing rank **15,588**
10. **Kempegowda Institute of Medical Sciences** (Private) — GM closing rank **18,774**
11. **Shimoga Institute of Medical Sciences** (Government) — GM closing rank **21,676**
12. **Father Muller Institute of Med. Education & Research** (Minority (Linguistic/Religious)) — GM closing rank **21,705**
13. **Hassan Institute of Medical Sciences** (Government) — GM closing rank **21,862**
14. **Belgaum Institute of Medical Sciences** (Government) — GM closing rank **23,365**
15. **Gulbarga Institute of Medical Sciences** (Government) — GM closing rank **23,671**

**By institute type nationally (MBBS, Open category, Round 1 2025):**
- **Central Institutes (AIIMS/JIPMER/BHU, 23 institutes):** closing ranks span **48 to 3,597** — even the least-competitive central institute in this group is far more competitive than the median state government college, with the sole exception of the newest/most remote AIIMS/JIPMER campuses.
- **State government colleges via 15% AIQ (383 institutes):** closing ranks span **690 to 21,190**, median **11,345** — this is the largest and most-referenced pool.
- **Deemed universities (55 institutes, 100% AIQ, no reservation, NRI quota, no domicile requirement):** closing ranks span **40,008 to 734,672**, median **332,211** — this pool absorbs candidates across almost the entire qualified range, consistent with `MD-NEET-KB.md`'s note that deemed-university total cost commonly runs ₹85 lakh–₹1.3 crore.

## Section 1 — MCC All India Quota (AIQ) + Deemed + Central Institutes — MBBS — Round 1 (Provisional), 2025

All 477 institutes carrying MBBS seats through MCC in 2025 (state government 15% AIQ + 100% Deemed Universities + AIIMS/JIPMER/BHU/AMU/Delhi University/IP University/ESIC), sorted from most to least competitive by Open-category closing rank.

| College | State | Type | Open Opening | Open Closing | Open Seats | EWS Closing | OBC Closing | SC Closing | ST Closing |
|---|---|---|---|---|---|---|---|---|---|
| AIIMS New Delhi | Delhi (NCT) | Central Institute | 1 | 48 | 48 | 254 | 206 | 644 | 1,405 |
| JIPMER PUDUCHERRY Dhanvantari Nagar Gorimedu Puducherry | Puducherry | Central Institute | 50 | 258 | 52 | 1,362 | 738 | 3,877 | 6,283 |
| AIIMS Jodhpur | Rajasthan | Central Institute | 55 | 392 | 57 | 1,153 | 766 | 6,920 | 7,353 |
| AIIMS-Bhopal SAKET NAGAR BHOPAL | Madhya Pradesh | Central Institute | 148 | 531 | 47 | 1,582 | 1,142 | 7,030 | 11,713 |
| AIIMS Rishikesh | Uttarakhand | Central Institute | 230 | 685 | 48 | 1,540 | 1,077 | 8,240 | 11,475 |
| GOVERNMENT MEDICAL COLLEGE AND HOSPITAL CHANDIGAR | Chandigarh | State Govt (15% AIQ) | 98 | 690 | 10 | 1,933 | 2,578 | 14,060 | 26,373 |
| MADRAS MEDICAL COLLEGE CHENNAI | Tamil Nadu | State Govt (15% AIQ) | 260 | 695 | 14 | 3,168 | 920 | 6,518 | 50,544 |
| AIIMS Bhubaneswar | Odisha | Central Institute | 60 | 706 | 49 | 2,259 | 1,481 | 6,034 | 14,786 |
| AIIMS Nagpur | Maharashtra | Central Institute | 136 | 862 | 50 | 1,885 | 1,520 | 8,326 | 16,192 |
| SETH G.S. MEDICAL COLLEGE MUMBAI | Maharashtra | State Govt (15% AIQ) | 96 | 868 | 15 | 4,157 | 3,140 | 13,389 | 49,964 |
| B.J. MEDICAL COLLEGE AHMEDABAD | Gujarat | State Govt (15% AIQ) | 229 | 889 | 14 | 2,677 | 3,089 | 16,367 | 55,767 |
| INST.OF MED.SCIENCES BHU | Uttar Pradesh | Central Institute | 235 | 1,165 | 38 | 2,194 | 1,808 | 14,965 | 26,196 |
| GOVT. MEDICAL COLLEGE KOZHIKODE | Kerala | State Govt (15% AIQ) | 309 | 1,173 | 15 | 8,702 | 1,556 | 15,754 | 75,126 |
| S.M.S. MEDICAL COLLEGE JAIPUR | Rajasthan | State Govt (15% AIQ) | 331 | 1,174 | 15 | 1,892 | 1,656 | 13,827 | 12,960 |
| Vardhman Mahavir Medical College and Safdarjung Hospital New Delhi VMMC | Delhi (NCT) | IP University | 137 | 1,221 | 53 | 3,776 | 3,946 | 33,781 | 112,251 |
| AIIMS Raipur | Chhattisgarh | Central Institute | 710 | 1,235 | 48 | 2,621 | 1,914 | 12,231 | 22,885 |
| STANLEY MEDICAL COLLEGE CHENNAI | Tamil Nadu | State Govt (15% AIQ) | 709 | 1,258 | 14 | 8,671 | 1,735 | 11,335 | 63,833 |
| Bangalore Medical College and Research Institute K R ROAD FORT BENGALURU | Karnataka | State Govt (15% AIQ) | 398 | 1,338 | 15 | 4,514 | 3,040 | 23,872 | 39,918 |
| AIIMS Mangalagiri ALL INDIA INSTITUTE OF MEDICAL SCIENCES NEAR TADEPALLI MANGALAGIRI GUNTUR (Dt) ANDHRA PRADESH | Andhra Pradesh | Central Institute | 286 | 1,357 | 46 | 4,369 | 2,520 | 15,527 | 31,007 |
| AIIMS Patna | Bihar | Central Institute | 702 | 1,537 | 50 | 2,988 | 2,132 | 14,209 | 28,862 |
| KGMC LUCKNOW | Uttar Pradesh | State Govt (15% AIQ) | 188 | 1,628 | 14 | 2,830 | 3,102 | 15,774 | 47,323 |
| GOVT.MEDICAL COLLEGE THIRUVANANTHAPURAM | Kerala | State Govt (15% AIQ) | 213 | 1,695 | 13 | 8,450 | 2,301 | 39,027 | 90,752 |
| AIIMS Bathinda Jodhpur Romana near Giani Zail Singh College Mandi Dabwali Road Bathinda | Punjab | Central Institute | 653 | 1,733 | 39 | 2,999 | 2,369 | 19,176 | 36,036 |
| NDMC Medical College Delhi | Delhi (NCT) | State Govt (15% AIQ) | 541 | 1,744 | 4 | 2,370 | 2,683 | 15,798 |  |
| GOVT. KILPAUK MEDICAL COLLEGE CHENNAI | Tamil Nadu | State Govt (15% AIQ) | 1,084 | 1,758 | 8 | 14,863 | 2,383 | 18,270 | 68,755 |
| Dr. B.S.A. Medical College Delhi | Delhi (NCT) | State Govt (15% AIQ) | 505 | 1,772 | 8 | 2,636 | 2,504 | 15,448 | 13,670 |
| AIIMS Bibi Nagar | Telangana | Central Institute | 514 | 1,782 | 38 | 3,956 | 2,894 | 16,647 | 39,391 |
| LOKMANYA TILAK MUNICIPAL M C MUMBAI | Maharashtra | State Govt (15% AIQ) | 1,052 | 1,887 | 10 | 6,602 | 5,576 | 34,048 | 81,412 |
| Maulana Azad Medical College New Delhi | Delhi (NCT) | Delhi University | 76 | 1,908 | 94 |  | 5,555 | 48,312 | 127,408 |
| AIIMS Rajkot Admission cell | Gujarat | Central Institute | 93 | 1,997 | 29 | 3,215 | 2,998 | 21,306 | 39,706 |
| AIIMS Gorakhpur | Uttar Pradesh | Central Institute | 721 | 2,091 | 47 | 3,081 | 2,654 | 21,412 | 45,366 |
| GOVT. MEDICAL COLLEGE KOTTAYAM | Kerala | State Govt (15% AIQ) | 892 | 2,172 | 11 | 13,677 | 2,835 | 47,034 | 96,851 |
| Gandhi Medical College Musheerabad Secunderabad MUSHEERABAD | Telangana | State Govt (15% AIQ) | 1,260 | 2,173 | 14 | 4,977 | 3,554 | 33,424 | 49,216 |
| AIIMS Bilaspur Changar Palasiyan Himachal Pradesh | Himachal Pradesh | Central Institute | 621 | 2,183 | 38 | 3,630 | 2,959 | 20,587 | 40,476 |
| AIIMS Kalyani | West Bengal | Central Institute | 754 | 2,276 | 48 | 4,292 | 3,406 | 17,433 | 48,654 |
| Shri Atal Bihari Vajpayee Medical College & Research Institute Bengaluru | Karnataka | State Govt (15% AIQ) | 896 | 2,355 | 9 | 7,942 | 6,170 | 45,057 | 42,201 |
| GRANT MEDICAL COLL & SIR J.J.HOSP MUMBAI | Maharashtra | State Govt (15% AIQ) | 1,292 | 2,368 | 15 | 5,194 | 4,444 | 24,786 | 60,871 |
| Atal Bihari Vajpayee Institute of Medical Sciences & DR RML HOSPITAL NEW DELHI | Delhi (NCT) | IP University | 1,627 | 2,502 | 30 | 5,269 | 6,763 | 58,225 | 135,205 |
| B.J. Government Medical College Pune | Maharashtra | State Govt (15% AIQ) | 656 | 2,542 | 13 | 5,434 | 4,600 | 22,585 | 62,013 |
| MADURAI MEDICAL COLLEGE MADURAI | Tamil Nadu | State Govt (15% AIQ) | 303 | 2,543 | 15 | 16,698 | 3,337 | 18,462 | 103,611 |
| Govt. Medical College Srinagar | Jammu And Kashmir | State Govt (15% AIQ) | 663 | 2,592 | 11 | 9,681 | 10,134 | 65,652 | 42,022 |
| AIIMS Rai Bareli | Uttar Pradesh | Central Institute | 2,095 | 2,600 | 39 | 3,646 | 3,279 | 23,301 | 41,778 |
| S.C.B. MEDICAL COLLEGE CUTTACK | Odisha | State Govt (15% AIQ) | 990 | 2,618 | 15 | 4,961 | 4,882 | 34,846 | 91,819 |
| JIPMER KARAIKAL JIPMER Academic Campus | Puducherry | Central Institute | 1,596 | 2,633 | 16 | 5,105 | 3,452 | 18,865 | 46,911 |
| RUHS College of Medical Sciences Jaipur | Rajasthan | State Govt (15% AIQ) | 1,352 | 2,658 | 7 | 3,873 | 3,313 | 30,551 | 42,487 |
| GOVT.MEDICAL COLLEGE THRISSUR | Kerala | State Govt (15% AIQ) | 1,944 | 2,709 | 10 | 11,657 | 3,275 | 48,613 | 101,571 |
| MEDICAL COLLEGE KOLKATA | West Bengal | State Govt (15% AIQ) | 330 | 2,714 | 15 | 5,183 | 5,022 | 19,710 | 70,328 |
| TOPIWALA NATIONAL MEDICAL COLLEGE MUMBAI | Maharashtra | State Govt (15% AIQ) | 2,077 | 2,876 | 9 | 6,365 | 5,749 | 39,041 | 77,991 |
| INDIRA GANDHI MEDICAL COLL. SHIMLA | Himachal Pradesh | State Govt (15% AIQ) | 2,017 | 2,882 | 8 | 3,786 | 3,947 | 26,969 | 56,136 |
| Osmania Medical College Koti HYDERABAD | Telangana | State Govt (15% AIQ) | 401 | 2,892 | 14 | 6,616 | 4,329 | 34,828 | 46,941 |
| MEDICAL COLLEGE BARODA | Gujarat | State Govt (15% AIQ) | 929 | 2,986 | 15 | 5,870 | 4,716 | 31,499 | 63,863 |
| MYSORE MED.& RESEARCH INST. MYSORE Mysore Medical College and Research Institute | Karnataka | State Govt (15% AIQ) | 1,462 | 3,087 | 11 | 7,253 | 5,571 | 45,417 | 41,829 |
| AIIMS Deogarh | Jharkhand | Central Institute | 2,058 | 3,164 | 48 | 4,493 | 3,784 | 28,136 | 51,396 |
| Government Medical College Omandurar | Tamil Nadu | State Govt (15% AIQ) | 1,296 | 3,171 | 7 | 17,554 | 3,612 | 23,357 | 81,149 |
| AIIMS Guwahati PO-CHANGSARI | Assam | Central Institute | 509 | 3,177 | 38 | 5,310 | 4,063 | 30,794 | 54,984 |
| COIMBATORE MEDICAL COLLEGE COIMBATORE | Tamil Nadu | State Govt (15% AIQ) | 673 | 3,237 | 12 | 15,747 | 3,808 | 24,118 | 103,716 |
| INST OF PG MED EDU & RESEARCH KOLKATA | West Bengal | State Govt (15% AIQ) | 1,257 | 3,260 | 12 | 4,783 | 4,770 | 22,844 | 74,360 |
| SARDAR PATEL MEDICAL COLLEGE BIKANER | Rajasthan | State Govt (15% AIQ) | 1,386 | 3,278 | 15 | 4,472 | 3,662 | 30,407 | 43,157 |
| DR.S.N. MEDICAL COLLEGE JODHPUR | Rajasthan | State Govt (15% AIQ) | 1,314 | 3,286 | 13 | 4,938 | 3,912 | 33,440 | 48,971 |
| Dr Ram Manohar Lohia Inst. of Med. Sce. Lucknow | Uttar Pradesh | State Govt (15% AIQ) | 2,040 | 3,323 | 12 | 3,792 | 4,283 | 31,794 | 56,960 |
| AIIMS Jammu AIIMS | Jammu And Kashmir | Central Institute | 930 | 3,389 | 39 | 4,603 | 4,085 | 32,194 | 43,200 |
| T.D. MEDICAL COLLEGE ALLAPPUZHA | Kerala | State Govt (15% AIQ) | 2,955 | 3,414 | 10 | 15,032 | 3,940 | 51,931 | 113,270 |
| AIIMS Madurai | Tamil Nadu | Central Institute | 2,126 | 3,597 | 20 | 6,467 | 4,627 | 33,807 | 55,735 |
| PT. B.D. SHARMA PGIMS ROHTAK | Haryana | State Govt (15% AIQ) | 1,773 | 3,756 | 15 | 5,562 | 4,592 | 35,791 | 70,969 |
| PATNA MEDICAL COLLEGE PATNA | Bihar | State Govt (15% AIQ) | 2,510 | 3,797 | 11 | 5,254 | 4,258 | 41,551 | 71,068 |
| CHENGALPATTU MEDICAL COLL CHENGALPATTU | Tamil Nadu | State Govt (15% AIQ) | 1,435 | 3,814 | 6 | 17,005 | 4,245 | 20,765 |  |
| GOVERNMENT MEDICAL COLLEGE SURAT | Gujarat | State Govt (15% AIQ) | 71 | 3,869 | 13 | 6,259 | 5,432 | 40,475 | 67,542 |
| R.N.T. MEDICAL COLLEGE UDAIPUR | Rajasthan | State Govt (15% AIQ) | 1,495 | 3,890 | 17 | 5,007 | 4,208 | 33,922 | 45,589 |
| University College of Medical Sciences New Delhi | Delhi (NCT) | Delhi University | 2,078 | 3,924 | 58 | 6,992 | 8,467 | 66,641 | 158,270 |
| Andhra Medical College Visakhapatnam | Andhra Pradesh | State Govt (15% AIQ) | 2,785 | 3,935 | 16 | 7,095 | 5,104 | 40,812 | 57,960 |
| Govt Medical College Ernakulam | Kerala | State Govt (15% AIQ) | 3,443 | 3,969 | 6 | 16,822 | 4,577 | 53,765 | 111,935 |
| THANJAVUR MEDICAL COLL. THANJAVUR | Tamil Nadu | State Govt (15% AIQ) | 1,949 | 4,073 | 8 | 19,617 | 5,063 | 25,526 | 107,213 |
| Hinduhridayasamrat Balasaheb Thackeray Medical College and Dr. R. N. Cooper Municipal General Hospital Maharashtra | Maharashtra | State Govt (15% AIQ) | 2,104 | 4,153 | 10 | 8,531 | 6,279 | 43,828 | 87,349 |
| GOVT. MEDICAL COLLEGE PATIALA | Punjab | State Govt (15% AIQ) | 1,841 | 4,156 | 13 | 7,097 | 7,803 | 48,687 | 79,799 |
| M.G.M. MEDICAL COLLEGE INDORE | Madhya Pradesh | State Govt (15% AIQ) | 1,295 | 4,185 | 15 | 6,389 | 5,686 | 37,624 | 55,468 |
| GOVT. MEDICAL COLLEGE NAGPUR | Maharashtra | State Govt (15% AIQ) | 2,500 | 4,260 | 13 | 7,746 | 6,433 | 28,148 | 74,877 |
| JAWAHAR LAL NEHRU MEDICAL AJMER | Rajasthan | State Govt (15% AIQ) | 2,216 | 4,264 | 14 | 5,830 | 4,473 | 36,316 | 53,648 |
| DR.RAJENDRA PRASAD MC TANDA | Himachal Pradesh | State Govt (15% AIQ) | 3,707 | 4,392 | 6 | 5,308 | 5,651 | 38,629 | 51,266 |
| Govt institute of Medcial Sciences GREATER NOIDA | Uttar Pradesh | State Govt (15% AIQ) | 3,120 | 4,401 | 7 | 5,490 | 4,758 | 40,690 | 75,015 |
| GOVT. VELLORE MEDICAL COLLEGE VELLORE | Tamil Nadu | State Govt (15% AIQ) | 3,126 | 4,451 | 6 | 11,898 | 5,264 | 32,595 | 92,580 |
| GMC Manjeri | Kerala | State Govt (15% AIQ) | 3,528 | 4,453 | 6 | 16,227 | 5,058 | 60,586 | 111,918 |
| Indira Gandhi Institute of Medical Sciences Patna | Bihar | State Govt (15% AIQ) | 2,596 | 4,482 | 9 | 5,477 | 5,180 | 48,808 | 79,981 |
| Government Medical College Mumbai | Maharashtra | State Govt (15% AIQ) | 3,199 | 4,509 | 3 | 6,626 | 6,437 | 45,429 |  |
| Govt Medical College Kannur P.O Pariyaram Medical College | Kerala | State Govt (15% AIQ) | 2,917 | 4,510 | 5 | 18,568 | 4,799 | 67,550 | 114,542 |
| Dr. B.R. Ambedkar State Institute of Medical Sciences Sector 56 Mohali | Punjab | State Govt (15% AIQ) | 2,263 | 4,511 | 7 | 7,344 | 5,370 | 52,619 | 70,469 |
| RAJENDRA INST. OF MED. SCI. RANCHI | Jharkhand | State Govt (15% AIQ) | 1,786 | 4,515 | 11 | 6,622 | 5,315 | 61,029 | 83,756 |
| G.S.V.M. MEDICAL COLLEGE KANPUR | Uttar Pradesh | State Govt (15% AIQ) | 3,444 | 4,575 | 15 | 5,550 | 5,462 | 38,779 | 61,551 |
| L.L.R.M. MEDICAL COLLEGE MEERUT | Uttar Pradesh | State Govt (15% AIQ) | 3,232 | 4,621 | 9 | 7,780 | 5,741 | 44,973 | 68,635 |
| GOVT.MEDICAL COLLEGE KOTA | Rajasthan | State Govt (15% AIQ) | 1,047 | 4,680 | 14 | 6,519 | 5,100 | 39,693 | 46,112 |
| GANDHI MEDICAL COLLEGE BHOPAL | Madhya Pradesh | State Govt (15% AIQ) | 2,167 | 4,807 | 13 | 7,666 | 6,618 | 49,202 | 65,754 |
| Kalpana Chawla Govt. Medical College Karnal | Haryana | State Govt (15% AIQ) | 1,617 | 4,879 | 7 | 7,844 | 6,679 | 38,201 |  |
| S.N. MEDICAL COLLEGE AGRA | Uttar Pradesh | State Govt (15% AIQ) | 2,780 | 4,945 | 12 | 7,051 | 6,400 | 43,947 | 66,565 |
| MOTI LAL NEHRU MEDICAL COLL ALLAHABAD | Uttar Pradesh | State Govt (15% AIQ) | 4,367 | 4,991 | 12 | 7,089 | 6,175 | 44,991 | 72,549 |
| GUNTUR MEDICAL COLLEGE GUNTUR | Andhra Pradesh | State Govt (15% AIQ) | 1,558 | 5,030 | 13 | 9,219 | 7,898 | 43,238 | 71,488 |
| Government Doon Medcial College Dehradun | Uttarakhand | State Govt (15% AIQ) | 2,932 | 5,090 | 8 | 7,523 | 7,277 | 53,341 | 81,002 |
| GOVT.MEDICAL COLLEGE AMRITSAR | Punjab | State Govt (15% AIQ) | 1,950 | 5,197 | 16 | 9,124 | 9,023 | 52,382 | 84,935 |
| GOVT. MOHAN KUMARAMANGALAM M.C. SALEM | Tamil Nadu | State Govt (15% AIQ) | 1,487 | 5,228 | 6 | 21,479 | 5,620 | 29,781 | 108,842 |
| Govt Medical College Palakkad | Kerala | State Govt (15% AIQ) | 5,032 | 5,267 | 5 | 18,882 | 6,038 | 72,773 | 123,605 |
| KARNATAK INST. OF MEDICAL SC. HUBLI | Karnataka | State Govt (15% AIQ) | 2,878 | 5,413 | 11 | 12,300 | 8,560 | 45,608 | 36,875 |
| SHRI KALYAN GOVT MEDICAL COLLEGE SIKAR Shri Kalyan Govt. Medical College | Rajasthan | State Govt (15% AIQ) | 4,963 | 5,485 | 5 | 8,660 | 5,834 | 44,385 | 61,287 |
| NILRATAN SIRKAR MEDICAL COLLEGE KOLKATA | West Bengal | State Govt (15% AIQ) | 3,293 | 5,524 | 15 | 9,130 | 7,671 | 31,212 | 82,262 |
| GOVT. MEDICAL COLLEGE TIRUNELVELI | Tamil Nadu | State Govt (15% AIQ) | 1,402 | 5,527 | 14 | 20,871 | 6,468 | 31,919 | 119,888 |
| Lady Hardinge Medical College New Delhi | Delhi (NCT) | Delhi University | 2,360 | 5,577 | 70 | 14,522 | 13,303 | 76,771 | 166,697 |
| Pt. D.D.U MEDICAL COLLEGE RAJKOT | Gujarat | State Govt (15% AIQ) | 2,459 | 5,609 | 13 | 6,691 | 6,453 | 46,132 | 74,989 |
| JHALAWAR MEDICAL COLLEGE Jhalawar | Rajasthan | State Govt (15% AIQ) | 4,446 | 5,730 | 11 | 7,948 | 6,634 | 47,963 | 59,107 |
| RAJIV GANDHI MEDICAL COLLEGE THANE | Maharashtra | State Govt (15% AIQ) | 4,739 | 5,783 | 6 | 9,275 | 7,852 | 45,376 | 83,405 |
| Government Medical College Konni | Kerala | State Govt (15% AIQ) | 4,561 | 5,786 | 6 | 22,633 | 6,039 | 74,223 | 124,805 |
| M.P. SHAH MEDICAL COLLEGE JAMNAGAR | Gujarat | State Govt (15% AIQ) | 2,479 | 5,864 | 16 | 7,699 | 7,018 | 52,210 | 71,259 |
| MAHARAJA K.C. GAJAPATI M.C. BRAHMAPUR | Odisha | State Govt (15% AIQ) | 1,975 | 6,010 | 16 | 8,140 | 8,851 | 50,972 | 92,855 |
| B.R.D. MEDICAL COLLEGE GORAKHPUR | Uttar Pradesh | State Govt (15% AIQ) | 5,243 | 6,053 | 9 | 7,783 | 7,479 | 51,272 | 72,634 |
| NALANDA MEDICAL COLLEGE PATNA | Bihar | State Govt (15% AIQ) | 2,997 | 6,106 | 9 | 6,711 | 7,268 | 57,846 | 83,513 |
| GAJRA RAJA MEDICAL COLLEGE GWALIOR | Madhya Pradesh | State Govt (15% AIQ) | 2,230 | 6,115 | 12 | 8,631 | 7,170 | 55,037 | 66,728 |
| Govt Medical College Idukki | Kerala | State Govt (15% AIQ) | 5,001 | 6,126 | 7 | 22,337 | 6,769 | 71,598 | 122,317 |
| KURNOOL MEDICAL COLLEGE KURNOOL | Andhra Pradesh | State Govt (15% AIQ) | 2,814 | 6,159 | 14 | 8,126 | 11,587 | 33,311 | 83,520 |
| INDIRA GANDHI GOVT.MEDICAL COLL. NAGPUR | Maharashtra | State Govt (15% AIQ) | 4,741 | 6,168 | 13 | 7,223 | 8,175 | 45,726 | 84,031 |
| MAHARANI LAXMI BAI MEDICAL COLL JHANSI | Uttar Pradesh | State Govt (15% AIQ) | 5,257 | 6,180 | 8 | 8,885 | 8,044 | 61,250 | 85,744 |
| UTTARANCHAL F HOSP TRUST MC HALDWANI | Uttarakhand | State Govt (15% AIQ) | 3,241 | 6,264 | 7 | 8,694 | 9,129 | 62,474 | 90,836 |
| CALCUTTA NATIONAL MED COLL KOLKATA | West Bengal | State Govt (15% AIQ) | 4,137 | 6,375 | 15 | 9,437 | 8,258 | 44,753 | 89,140 |
| K.A.P. VISWANATHAM Govt Medical College TIRUCHIRAPALLI | Tamil Nadu | State Govt (15% AIQ) | 5,436 | 6,379 | 9 | 23,813 | 6,815 | 31,945 |  |
| THENI GOVT. MEDICAL COLLEGE THENI | Tamil Nadu | State Govt (15% AIQ) | 4,953 | 6,539 | 6 | 23,572 | 7,180 | 42,836 | 120,723 |
| MEDICAL COLLEGE BHAVNAGAR | Gujarat | State Govt (15% AIQ) | 1,060 | 6,717 | 10 | 8,150 | 7,497 | 58,426 | 75,318 |
| Govt. Medical College Jammu | Jammu And Kashmir | State Govt (15% AIQ) | 3,642 | 6,719 | 10 | 10,524 | 9,019 | 56,849 | 48,602 |
| GURU GOVIND SINGH MED COLL FARIDKOT | Punjab | State Govt (15% AIQ) | 4,253 | 6,757 | 8 | 11,442 | 9,590 | 57,502 | 96,892 |
| Government Medical College Bhilwara | Rajasthan | State Govt (15% AIQ) | 5,878 | 6,820 | 9 | 9,186 | 7,943 | 52,161 | 71,638 |
| SHRI ATAL BIHARI VAJPAYEE GOVERNMENT MEDICAL COLLEGE CHHAINSA | Haryana | State Govt (15% AIQ) | 4,570 | 6,948 | 6 | 10,384 | 9,896 | 47,058 | 78,248 |
| Pt. J N M MEDICAL COLLEGE RAIPUR | Chhattisgarh | State Govt (15% AIQ) | 2,625 | 6,949 | 13 | 11,214 | 9,870 | 58,783 | 90,844 |
| GUWAHATI MEDICAL COLLEGE GUWAHATI | Assam | State Govt (15% AIQ) | 3,326 | 7,008 | 12 | 10,395 | 10,025 | 42,675 | 61,091 |
| NETAJI SUBHASH CHANDRA BOSE MC JABALPUR | Madhya Pradesh | State Govt (15% AIQ) | 4,949 | 7,037 | 13 | 9,209 | 8,481 | 57,337 | 77,845 |
| College Government Medical College Alwar Government Medical College Alwar Jail Circle alwar | Rajasthan | State Govt (15% AIQ) | 4,927 | 7,064 | 7 | 9,325 | 9,182 | 51,109 | 71,707 |
| SKIMS Medical College Bemina | Jammu And Kashmir | State Govt (15% AIQ) | 2,797 | 7,138 | 8 | 12,621 | 12,809 | 76,564 | 49,520 |
| GOA MEDICAL COLLEGE PANAJI | Goa | State Govt (15% AIQ) | 4,338 | 7,141 | 12 | 11,758 | 10,305 | 61,252 | 87,969 |
| V.S.S. MEDICAL COLLEGE BURLA | Odisha | State Govt (15% AIQ) | 5,596 | 7,154 | 10 | 9,756 | 10,506 | 48,795 | 102,284 |
| Government Medical College Pali | Rajasthan | State Govt (15% AIQ) | 4,307 | 7,175 | 9 | 9,460 | 7,989 | 57,167 | 77,081 |
| KANYAKUMARI GOVT. MED. COLL. ASARIPALLAM | Tamil Nadu | State Govt (15% AIQ) | 5,060 | 7,186 | 8 | 23,028 | 7,655 | 59,491 | 133,959 |
| M.G.M. MEDICAL COLLEGE JAMSHEDPUR | Jharkhand | State Govt (15% AIQ) | 6,165 | 7,201 | 6 | 10,130 | 8,819 | 66,725 | 75,249 |
| Dr.Radhakrishnan Government Medical College Hamirpur | Himachal Pradesh | State Govt (15% AIQ) | 5,941 | 7,307 | 6 | 8,627 | 9,722 | 59,139 | 59,565 |
| Government Medical College Thiruvallur | Tamil Nadu | State Govt (15% AIQ) | 3,658 | 7,347 | 6 | 24,538 | 8,804 | 29,229 |  |
| Uttar Pradesh University of Medical Sciences Saifai | Uttar Pradesh | State Govt (15% AIQ) | 6,057 | 7,361 | 12 | 10,109 | 9,014 | 58,727 | 88,813 |
| BPS Govt. Med. College Sonepat | Haryana | State Govt (15% AIQ) | 5,685 | 7,449 | 6 | 11,735 | 9,940 | 74,227 | 96,928 |
| Dr. YS Parmar Govt. Medical College Nahan | Himachal Pradesh | State Govt (15% AIQ) | 3,949 | 7,501 | 7 | 8,356 | 9,347 | 59,417 | 87,699 |
| Rangaraya Medical College Kakinada | Andhra Pradesh | State Govt (15% AIQ) | 3,119 | 7,601 | 13 | 11,432 | 9,686 | 47,357 | 101,082 |
| MANDYA INST. OF MEDICAL SCI. MANDYA | Karnataka | State Govt (15% AIQ) | 5,444 | 7,639 | 8 | 15,375 | 10,488 | 65,232 | 82,535 |
| THOOTHUKUDI MEDICAL COLLEGE THOOTHUKUDI | Tamil Nadu | State Govt (15% AIQ) | 6,650 | 7,663 | 9 | 24,006 | 8,893 | 58,560 | 129,719 |
| BELGAUM INST. OF MEDICAL SCI. BELGAUM | Karnataka | State Govt (15% AIQ) | 5,587 | 7,756 | 8 | 12,526 | 11,043 | 75,425 | 65,058 |
| GOVT. MEDICAL COLLEGE AURANGABAD | Maharashtra | State Govt (15% AIQ) | 2,574 | 7,773 | 13 | 9,694 | 9,911 | 55,261 | 89,293 |
| SJP Medical College Bharatpur | Rajasthan | State Govt (15% AIQ) | 6,085 | 7,816 | 9 | 10,461 | 8,220 | 58,981 | 80,646 |
| Darbhanga Medical College Laheriasarai | Bihar | State Govt (15% AIQ) | 5,454 | 7,873 | 7 | 9,039 | 8,947 | 64,358 | 96,744 |
| VARDHMAN INSTITUTE OF MEDICAL SCIENCES NALANDA | Bihar | State Govt (15% AIQ) | 5,912 | 7,883 | 6 | 10,796 | 9,787 | 73,828 | 80,676 |
| Govt Medical College Churu | Rajasthan | State Govt (15% AIQ) | 6,870 | 7,986 | 8 | 10,889 | 9,043 | 62,644 | 75,129 |
| R.G. KAR MEDICAL COLLEGE KOLKATA | West Bengal | State Govt (15% AIQ) | 2,832 | 7,997 | 16 | 8,600 | 9,315 | 53,010 | 91,629 |
| Government Medical College Nashik | Maharashtra | State Govt (15% AIQ) | 6,859 | 8,011 | 3 |  | 10,842 | 78,673 | 72,412 |
| Govt. Medical College Kannauj | Uttar Pradesh | State Govt (15% AIQ) | 7,463 | 8,103 | 5 | 12,381 | 9,957 | 70,270 | 90,009 |
| GVMC VILLUPURAM | Tamil Nadu | State Govt (15% AIQ) | 2,108 | 8,176 | 5 | 24,331 | 8,924 | 36,171 | 104,456 |
| Pt. Jawahar Lal Nehru Govt. Med. College Chamba | Himachal Pradesh | State Govt (15% AIQ) | 6,792 | 8,311 | 7 | 10,034 | 9,441 | 61,897 | 64,330 |
| Sagar Dutta Medical College & Hospital Kolkata | West Bengal | State Govt (15% AIQ) | 6,440 | 8,390 | 8 | 10,336 | 9,832 | 54,924 | 102,218 |
| S.S. MEDICAL COLLEGE REWA | Madhya Pradesh | State Govt (15% AIQ) | 6,674 | 8,400 | 9 | 10,166 | 10,171 | 68,562 | 85,260 |
| IRT Perundurai Medical College Perundurai | Tamil Nadu | State Govt (15% AIQ) | 6,345 | 8,412 | 7 | 23,489 | 9,354 | 51,725 | 105,143 |
| GOVT. DHARAMAPURI MED COLL DHARMAPURI | Tamil Nadu | State Govt (15% AIQ) | 7,304 | 8,508 | 7 | 22,081 | 9,428 | 48,710 | 122,847 |
| Govt Medical College Barmer Rajasthan NH-15 | Rajasthan | State Govt (15% AIQ) | 7,600 | 8,652 | 8 | 10,691 | 9,907 | 60,750 | 86,623 |
| Sri Jagannath Medical College & Hospital Puri | Odisha | State Govt (15% AIQ) | 7,158 | 8,718 | 6 | 14,447 | 12,264 | 59,986 | 93,818 |
| Sri Venkateswara Medical College Tirupati | Andhra Pradesh | State Govt (15% AIQ) | 2,567 | 8,815 | 14 | 11,148 | 12,216 | 58,561 | 93,895 |
| Govt Medical College Nagaur Bikaner Road | Rajasthan | State Govt (15% AIQ) | 7,559 | 8,845 | 5 | 13,310 | 11,595 | 64,079 | 83,897 |
| ATAL BIHARI VAJPAYEE GOVERNMENT MEDICAL COLLEGE VIDISHA | Madhya Pradesh | State Govt (15% AIQ) | 5,761 | 8,856 | 12 | 10,678 | 10,178 | 53,247 | 78,687 |
| Indira Gandhi Medical College & RI Puducherry | Puducherry | State Govt (15% AIQ) | 3,489 | 8,875 | 10 | 18,099 | 12,017 | 62,291 | 99,309 |
| Government Medical College Tiruppur | Tamil Nadu | State Govt (15% AIQ) | 7,151 | 8,914 | 6 | 25,118 | 9,659 | 52,243 | 128,206 |
| NAMO Medical Education & Research Institute Govt Medical College Silvassa | Dadra And Nagar Haveli | State Govt (15% AIQ) | 6,885 | 8,919 | 9 | 11,816 | 10,161 | 72,392 | 64,012 |
| HASSAN INST. MEDICAL SCIENCES HASSAN | Karnataka | State Govt (15% AIQ) | 6,611 | 8,923 | 9 | 16,784 | 11,099 | 66,273 | 81,970 |
| Kakatiya Medical College Warangal SVP Road | Telangana | State Govt (15% AIQ) | 4,318 | 8,974 | 13 | 13,673 | 11,711 | 56,260 | 51,696 |
| Government Medical College Chittorgarh Government Medical College Chittorgarh Bojunda - Udaipur Road Chittorgarh | Rajasthan | State Govt (15% AIQ) | 8,461 | 9,008 | 5 | 12,570 | 10,122 | 59,538 | 82,664 |
| Government Medical College Jhunjhunu | Rajasthan | State Govt (15% AIQ) | 7,560 | 9,077 | 6 | 13,484 | 10,852 | 69,214 | 71,650 |
| Government Medical College Nilgiris | Tamil Nadu | State Govt (15% AIQ) | 5,706 | 9,136 | 8 | 22,451 | 12,179 | 70,369 | 139,363 |
| GMC DAUSA RAJASTHAN GMC DAUSA MITRAPURA BHANDAREJ MOD DAUSA | Rajasthan | State Govt (15% AIQ) | 6,842 | 9,156 | 5 | 9,592 | 10,620 | 60,226 | 81,530 |
| GOVERNMENT MEDICAL COLLEGE SRIGANGANAGAR | Rajasthan | State Govt (15% AIQ) | 7,107 | 9,183 | 5 | 11,821 | 10,558 | 67,479 | 87,766 |
| Govt Medical College Baramati Plot No P107 MIDC area Opposite Women Hospital Baramati Taluka Baramati District Pune | Maharashtra | State Govt (15% AIQ) | 5,911 | 9,314 | 7 | 10,774 | 10,290 | 46,383 | 66,674 |
| SHIMOGA INST. OF MEDICAL SCI. SHIMOGA | Karnataka | State Govt (15% AIQ) | 4,858 | 9,413 | 9 | 18,024 | 12,825 | 82,744 | 86,585 |
| Jawaharlal Nehru Medical College Bhagalpur | Bihar | State Govt (15% AIQ) | 5,905 | 9,419 | 6 | 11,716 | 10,456 | 74,652 | 99,704 |
| Govt. Medical College Karur SANAPIRATTI VILLAGE NORTH GANDHIGRAMAM KARUR TAMILNADU | Tamil Nadu | State Govt (15% AIQ) | 7,369 | 9,450 | 9 | 25,254 | 10,029 | 63,512 | 137,328 |
| SUH Maulana Mahmood Hasan Medical College Saharanpur | Uttar Pradesh | State Govt (15% AIQ) | 8,928 | 9,465 | 5 | 10,628 | 10,873 | 75,468 |  |
| Shaheed Nirmal Mahto Medical College & Hospital Dhanbad | Jharkhand | State Govt (15% AIQ) | 5,883 | 9,623 | 6 | 11,135 | 10,925 | 72,753 | 87,089 |
| Government Medical college Haridwar | Uttarakhand | State Govt (15% AIQ) | 6,592 | 9,655 | 6 | 13,189 | 13,416 | 64,598 | 94,118 |
| BUNDELKHAND MEDICAL COLLEGE SAGAR | Madhya Pradesh | State Govt (15% AIQ) | 7,759 | 9,704 | 7 | 12,542 | 10,863 | 72,047 | 96,392 |
| SHKM GMC Nalhar | Haryana | State Govt (15% AIQ) | 6,854 | 9,719 | 7 | 11,843 | 11,280 | 76,041 | 99,815 |
| MRA MEDICAL COLLEGE AMBEDKAR NAGAR UP | Uttar Pradesh | State Govt (15% AIQ) | 7,287 | 9,735 | 7 | 10,981 | 10,471 | 68,461 | 89,243 |
| CHHATTISGARH INSTITUTE OF MEDICAL SCIENCES BILASP | Chhattisgarh | State Govt (15% AIQ) | 8,830 | 9,799 | 9 | 11,511 | 11,558 | 71,211 | 99,078 |
| Thiruvannamalai MC Thiruvannamalai | Tamil Nadu | State Govt (15% AIQ) | 8,019 | 9,897 | 6 | 23,068 | 10,306 | 43,797 | 130,919 |
| MG Inst. of Medical Sciences Sevagram Wardha | Maharashtra | State Govt (15% AIQ) | 6,201 | 9,917 | 18 | 15,580 | 14,348 | 80,997 | 103,113 |
| Veer Chandra Singh Garhwali Govt. Institute of Medical Science & Research BADRINATH MARG | Uttarakhand | State Govt (15% AIQ) | 6,571 | 9,965 | 9 | 12,685 | 12,509 | 71,513 | 93,060 |
| GMC Azamgarh | Uttar Pradesh | State Govt (15% AIQ) | 7,583 | 9,989 | 6 | 12,252 | 10,733 | 68,913 | 82,489 |
| Kalyan Singh Government Medical College Bulandshahr | Uttar Pradesh | State Govt (15% AIQ) | 7,212 | 10,012 | 6 | 13,059 | 12,671 | 80,178 | 104,856 |
| Government medical College Namakkal | Tamil Nadu | State Govt (15% AIQ) | 8,516 | 10,014 | 6 |  | 10,949 | 65,150 | 139,759 |
| Govt Medical College Faizabad GANJA PARGANA- HAVELI AWADH | Uttar Pradesh | State Govt (15% AIQ) | 8,517 | 10,015 | 5 | 13,711 | 12,105 | 80,008 | 94,355 |
| BURDWAN MEDICAL COLLEGE BURDWAN | West Bengal | State Govt (15% AIQ) | 7,720 | 10,078 | 11 | 12,584 | 12,345 | 67,297 | 103,156 |
| Govt Medical College Dungarpur | Rajasthan | State Govt (15% AIQ) | 6,916 | 10,093 | 9 | 11,255 | 10,240 | 63,897 | 84,813 |
| Siddartha Medical College Vijayawada | Andhra Pradesh | State Govt (15% AIQ) | 1,496 | 10,160 | 10 | 13,471 | 13,485 | 36,798 | 92,240 |
| Rajah Muthiah Medical College Annamalai Universit | Tamil Nadu | State Govt (15% AIQ) | 8,100 | 10,207 | 9 | 24,156 | 10,727 | 58,331 | 123,915 |
| DR. VAISHAMPAYAM MEMORIAL M.C. SHOLAPUR | Maharashtra | State Govt (15% AIQ) | 7,406 | 10,285 | 13 | 12,306 | 11,871 | 76,556 | 103,016 |
| SRI KRISHNA MEDICAL COLLEGE MUZAFFARPUR | Bihar | State Govt (15% AIQ) | 8,075 | 10,324 | 8 | 11,619 | 11,096 | 78,370 | 100,741 |
| Government Medical College Dindigul | Tamil Nadu | State Govt (15% AIQ) | 7,591 | 10,362 | 9 | 25,414 | 11,474 | 56,237 | 143,103 |
| Govt Medical College Ratlam Gram Banjali | Madhya Pradesh | State Govt (15% AIQ) | 8,575 | 10,378 | 10 | 13,505 | 11,364 | 76,823 | 94,834 |
| ESIC Medical College Faridabad | Haryana | ESIC | 3,931 | 10,394 | 17 | 12,647 | 14,651 | 95,893 | 285,823 |
| GTMC THIRUVARUR | Tamil Nadu | State Govt (15% AIQ) | 10,000 | 10,400 | 5 | 24,639 | 11,030 | 62,093 | 141,327 |
| GOVERNMENT MEDICAL COLLEGE MIRAJ | Maharashtra | State Govt (15% AIQ) | 7,338 | 10,401 | 10 | 14,254 | 11,881 | 79,887 | 101,407 |
| Govt. Medical College Sirohi (rajasthan) | Rajasthan | State Govt (15% AIQ) | 8,114 | 10,476 | 7 | 11,658 | 11,449 | 71,492 | 85,339 |
| NORTH BENGAL MED.COLL DARJEELING | West Bengal | State Govt (15% AIQ) | 6,490 | 10,533 | 11 | 14,869 | 13,016 | 74,422 | 101,241 |
| Gulbarga Institute of Medical Sciences Gulbarga | Karnataka | State Govt (15% AIQ) | 3,611 | 10,554 | 8 | 18,548 | 13,440 | 82,277 | 107,916 |
| NEIGRIHMS SHILLONG | Meghalaya | State Govt (15% AIQ) | 7,414 | 10,679 | 8 |  |  |  |  |
| GOVERNMENT MEDICAL COLLEGE BUNDI | Rajasthan | State Govt (15% AIQ) | 9,411 | 10,692 | 5 | 13,942 | 11,674 | 68,952 | 86,357 |
| Government Medical College Hanumangarh | Rajasthan | State Govt (15% AIQ) | 8,669 | 10,750 | 5 | 12,972 | 11,806 | 70,064 | 89,380 |
| Government Medical College Krishnagiri | Tamil Nadu | State Govt (15% AIQ) | 7,310 | 10,780 | 8 | 25,589 | 12,018 | 64,780 | 142,895 |
| COLLEGE OF MEDICINE and JNM HOSPITAL KALYANI | West Bengal | State Govt (15% AIQ) | 8,388 | 10,895 | 8 | 12,299 | 12,926 | 70,966 |  |
| ANUGRAH NARAYAN MAGADH MEDICAL COLLEGE GAYA | Bihar | State Govt (15% AIQ) | 8,595 | 10,932 | 8 | 11,156 | 11,719 | 80,403 | 101,128 |
| Government Medical College Virudhunagar | Tamil Nadu | State Govt (15% AIQ) | 7,276 | 10,935 | 8 | 25,427 | 11,928 | 62,728 | 145,625 |
| VIJAYNAGAR INST OF MED. SC BELLARY | Karnataka | State Govt (15% AIQ) | 2,118 | 11,026 | 11 | 16,479 | 13,217 | 76,105 | 93,673 |
| Govt. Sivgangai M. C. Sivagangai MANAMADURAI MAIN ROAD | Tamil Nadu | State Govt (15% AIQ) | 7,855 | 11,038 | 6 | 21,550 | 11,634 | 63,530 | 143,700 |
| Govt Medical College Firozabad DAULATTAPUR JALESHAR ROAD NARKHI FIROZABAD | Uttar Pradesh | State Govt (15% AIQ) | 10,204 | 11,125 | 7 | 12,673 | 12,477 | 71,347 |  |
| Govt. Pudukkottai Medical College Hopt. Pudukkott | Tamil Nadu | State Govt (15% AIQ) | 9,573 | 11,149 | 9 | 25,257 | 11,457 | 63,589 | 139,163 |
| Rajarshee Chhatrapati Shahu Maharaj Government Medical College Kolhapur Rajarshee Chhatrapati Shahu Maharaj Government Medical College | Maharashtra | State Govt (15% AIQ) | 8,393 | 11,177 | 9 | 14,707 | 13,109 | 84,885 | 105,614 |
| Government Medical College Dholpur | Rajasthan | State Govt (15% AIQ) | 10,133 | 11,216 | 7 | 12,787 | 11,403 | 74,238 | 85,978 |
| DR.S.C.GOVT MEDICAL COLLEGE NANDED | Maharashtra | State Govt (15% AIQ) | 10,151 | 11,240 | 7 | 13,312 | 13,158 | 79,494 | 106,595 |
| Rajkiya Medical College Jalaun | Uttar Pradesh | State Govt (15% AIQ) | 9,600 | 11,310 | 5 | 14,066 | 11,553 | 78,141 | 98,705 |
| Rani Durgavati Medical College Banda | Uttar Pradesh | State Govt (15% AIQ) | 10,881 | 11,345 | 5 | 14,526 | 11,745 | 84,983 | 88,346 |
| Government Medical College Ariyalur | Tamil Nadu | State Govt (15% AIQ) | 9,318 | 11,373 | 8 | 24,929 | 12,199 | 67,307 | 142,071 |
| Diamond Harbour Govt Medical College New Town | West Bengal | State Govt (15% AIQ) | 9,802 | 11,448 | 6 | 12,066 | 12,358 | 80,173 | 108,951 |
| Govt Medical college Shivpuri Near Katha Mill | Madhya Pradesh | State Govt (15% AIQ) | 10,849 | 11,464 | 6 | 13,767 | 12,501 | 78,772 | 93,136 |
| Government Medical College Ramanathapuram | Tamil Nadu | State Govt (15% AIQ) | 7,000 | 11,523 | 5 | 24,911 | 12,576 | 70,909 | 137,499 |
| ASSAM MEDICAL COLLEGE DIBRUGARH | Assam | State Govt (15% AIQ) | 1,711 | 11,571 | 12 | 16,210 | 14,944 | 81,601 | 70,087 |
| Govt Medical College Badaun Gunera Wazidpur Ujhani Road Badaun U.P. 243601 | Govt Medical College Badaun | State Govt (15% AIQ) | 10,435 | 11,575 | 6 | 13,386 | 12,714 | 80,494 | 98,874 |
| GMC KARAULI mandrayal road karauli | Rajasthan | State Govt (15% AIQ) | 8,917 | 11,635 | 6 | 12,727 | 12,209 | 76,899 | 95,572 |
| Government of Medical College and Hospital Balasore | Odisha | State Govt (15% AIQ) | 9,303 | 11,639 | 5 | 13,319 | 13,131 | 62,738 | 138,033 |
| GMC Shahjhanpur | Uttar Pradesh | State Govt (15% AIQ) | 10,286 | 11,666 | 5 | 12,823 | 12,722 | 85,589 | 100,855 |
| Government Medical College Sawai Madhopur | Rajasthan | State Govt (15% AIQ) | 6,587 | 11,726 | 6 |  | 12,416 | 76,436 | 78,631 |
| Government Medical College Banswara | Rajasthan | State Govt (15% AIQ) | 7,819 | 11,845 | 6 | 14,205 | 12,790 | 73,571 |  |
| BIDAR INSTITUTE OF MEDICAL SCI. BIDAR | Karnataka | State Govt (15% AIQ) | 10,965 | 11,883 | 8 | 18,770 | 14,218 | 84,284 | 95,045 |
| BANKURA SAMMILANI MED COLL BANKURA | West Bengal | State Govt (15% AIQ) | 9,857 | 11,895 | 11 | 16,226 | 14,053 | 78,803 | 116,490 |
| SOBAN SINGH JEENA GOVERNMENT INSTITUTE OF MEDICAL SCIENCE & RESEARCH ALMORA | Uttarakhand | State Govt (15% AIQ) | 10,713 | 11,917 | 6 | 13,273 | 14,052 | 78,931 | 96,534 |
| Government Medical College Kathua | Jammu And Kashmir | State Govt (15% AIQ) | 5,622 | 11,929 | 6 | 14,377 | 13,523 | 51,060 |  |
| Govt. Medical College Khandwa | Madhya Pradesh | State Govt (15% AIQ) | 10,247 | 11,960 | 7 | 13,721 | 13,570 | 81,676 | 97,439 |
| Andaman and Nicobar Islands Institute of Medical S Director ANIIMS | Andaman And Nicobar Islands | State Govt (15% AIQ) | 6,174 | 12,014 | 5 | 21,558 | 19,826 | 104,569 | 125,622 |
| Government Medical College Kallakurichi | Tamil Nadu | State Govt (15% AIQ) | 5,717 | 12,032 | 10 | 25,511 | 12,487 | 66,279 | 138,714 |
| Govt Medical College Basti RAMPUR TAHSIL SADAR BASTI BASTI | Uttar Pradesh | State Govt (15% AIQ) | 10,318 | 12,075 | 5 | 14,389 | 12,891 | 87,588 | 96,635 |
| Kodagu Institute of Medical Sciences Kodagu | Karnataka | State Govt (15% AIQ) | 8,907 | 12,096 | 9 | 20,632 | 14,401 | 88,904 | 101,343 |
| GOVERNMENT MEDICAL COLLEGE ANANTNAG J&K | Jammu And Kashmir | State Govt (15% AIQ) | 7,193 | 12,163 | 5 | 18,738 | 17,423 | 85,055 | 82,029 |
| GOVERNMENT MEDICAL COLLEGE BARAN | Rajasthan | State Govt (15% AIQ) | 10,947 | 12,166 | 6 | 14,611 | 12,991 | 73,549 | 89,534 |
| REGIONAL INST OF MEDICAL SCI IMPHAL | Manipur | State Govt (15% AIQ) | 7,423 | 12,184 | 7 | 19,897 | 15,062 | 64,770 | 60,784 |
| SHEIKH BHIKHARI MEDICAL COLLEGE & HOSPITAL HAZARIBAG ( Formerly called as- Hazaribagh Medical College | Jharkhand | State Govt (15% AIQ) | 9,789 | 12,242 | 6 | 13,986 | 13,249 | 83,890 | 106,302 |
| Government Medical College Nagapattinam | Tamil Nadu | State Govt (15% AIQ) | 11,982 | 12,262 | 9 | 25,599 | 12,711 | 70,965 | 144,224 |
| ACSR Govt Medical College Nellore | Andhra Pradesh | State Govt (15% AIQ) | 7,462 | 12,352 | 10 | 20,208 | 13,892 | 66,395 | 112,021 |
| Autonomous State Medical College Etah | Uttar Pradesh | State Govt (15% AIQ) | 10,218 | 12,447 | 5 | 14,072 | 13,655 | 89,526 | 103,371 |
| CHIKKABALLAPURA INSTITUTE OF MEDICAL SCIENCES KARNATAKA | Karnataka | State Govt (15% AIQ) | 10,140 | 12,520 | 5 | 22,113 | 14,769 | 89,766 | 111,163 |
| SHRI BHAUSAHEB HIRE GOVT. M.C. DHULE | Maharashtra | State Govt (15% AIQ) | 10,446 | 12,677 | 9 | 16,282 | 14,510 | 84,858 | 110,678 |
| SVIMS - Sri Padmavathi Medical College for Women Tirupati | Andhra Pradesh | State Govt (15% AIQ) | 6,108 | 12,719 | 10 | 20,643 | 14,255 | 76,073 | 119,728 |
| Goverment Medical College Datia | Madhya Pradesh | State Govt (15% AIQ) | 11,036 | 12,938 | 8 | 14,277 | 13,552 | 87,423 | 82,283 |
| Rajiv Gandhi Institute Medical Sce of Adilabad MAIN ROAD | Telangana | State Govt (15% AIQ) | 5,411 | 12,965 | 6 | 19,688 | 15,996 | 68,568 | 69,858 |
| Mahatma Vidur Autonomous State Medical College Bijnor Uttar Pradesh | Uttar Pradesh | State Govt (15% AIQ) | 9,729 | 12,983 | 5 | 15,651 | 15,444 | 81,689 | 114,632 |
| Chhindwara Institute of Medical Sciences Teachers Colony | Madhya Pradesh | State Govt (15% AIQ) | 9,728 | 13,087 | 6 | 14,978 | 14,156 | 88,859 | 98,233 |
| GOVERNMENT MEDICAL COLLEGE AND GENERAL HOSPITAL SATARA | Maharashtra | State Govt (15% AIQ) | 10,664 | 13,129 | 5 | 18,612 | 15,276 | 93,364 | 121,048 |
| Barasat Government Medical College & Hospital West Bengal | West Bengal | State Govt (15% AIQ) | 9,273 | 13,148 | 6 | 18,745 | 16,780 | 73,405 | 116,504 |
| Gmc Bahraich | Uttar Pradesh | State Govt (15% AIQ) | 12,500 | 13,161 | 5 | 14,253 | 13,596 | 87,369 | 106,452 |
| Pt. Raghunath Murmu Med. College Baripada | Odisha | State Govt (15% AIQ) | 10,138 | 13,201 | 6 | 15,632 | 15,728 | 71,941 | 130,285 |
| Goverment Medical College Bettiah | Bihar | State Govt (15% AIQ) | 12,083 | 13,214 | 7 | 15,505 | 14,092 | 91,813 | 110,052 |
| GOVERNMENT MEDICAL COLLEGE LATUR | Maharashtra | State Govt (15% AIQ) | 6,343 | 13,256 | 10 | 15,523 | 14,886 | 88,273 | 105,247 |
| Employees State Insurance Corporation Medical College Alwar | Rajasthan | ESIC | 6,377 | 13,302 | 13 | 17,289 | 17,524 | 119,239 | 269,576 |
| Government Medical College and Hospital Jajpur | Odisha | State Govt (15% AIQ) | 7,401 | 13,385 | 3 | 19,125 | 17,225 | 74,418 |  |
| Karwar Institute of Medical Sciences Karwar | Karnataka | State Govt (15% AIQ) | 12,215 | 13,408 | 8 | 21,165 | 15,023 | 94,467 | 122,194 |
| Autonomous State Medical College Kanpur Dehat | Uttar Pradesh | State Govt (15% AIQ) | 8,174 | 13,409 | 7 | 13,411 | 14,958 | 83,177 | 96,527 |
| Lt. L A M Govt. Medical College Raigarh | Chhattisgarh | State Govt (15% AIQ) | 11,606 | 13,428 | 5 | 17,136 | 15,234 | 86,835 | 110,330 |
| Autonomous State Medical College Fatehpur | Uttar Pradesh | State Govt (15% AIQ) | 7,722 | 13,502 | 6 | 14,596 | 14,614 | 89,467 | 104,924 |
| Govt Medical College Shahdol GRAM CHAMPA KUDRI ROAD NEAR NEW BUS STAND SHAHDOL MP | Madhya Pradesh | State Govt (15% AIQ) | 13,178 | 13,507 | 6 |  | 13,956 | 87,702 | 99,339 |
| GOVERNMENT MEDICAL COLLEGE AKOLA | Maharashtra | State Govt (15% AIQ) | 7,660 | 13,519 | 12 | 15,562 | 15,210 | 84,167 | 109,737 |
| RAICHUR INST. OF MEDICAL SCI. RAICHUR | Karnataka | State Govt (15% AIQ) | 10,994 | 13,573 | 9 | 15,144 | 14,902 | 92,986 | 116,305 |
| MIDNAPORE MEDICAL COLLEGE MIDNAPUR | West Bengal | State Govt (15% AIQ) | 7,060 | 13,585 | 12 | 17,068 | 15,765 | 88,573 | 125,396 |
| Bhima Bhoi Medical College and Hospital Balangir | Odisha | State Govt (15% AIQ) | 7,305 | 13,609 | 6 | 20,482 | 16,234 | 60,630 | 127,876 |
| Government Medical College Quthbullapur | Telangana | State Govt (15% AIQ) | 6,208 | 13,641 | 3 | 24,686 | 20,473 | 86,163 |  |
| Autonomous State Medical College Siddharthnagar | Uttar Pradesh | State Govt (15% AIQ) | 12,807 | 13,648 | 6 | 14,051 | 14,797 | 90,491 | 104,601 |
| Sundarlal patwa Govt medical College mandsaur Dean Office | Madhya Pradesh | State Govt (15% AIQ) | 11,610 | 13,667 | 5 | 15,203 | 15,291 | 89,434 | 107,034 |
| Government Medical College Anantnag | Jammu And Kashmir | State Govt (15% AIQ) | 10,864 | 13,813 | 6 | 16,965 | 16,225 | 86,092 | 87,023 |
| MAHARSHI DEVRAHA BABA AUTONOMOUS STATE. MEDICAL COLLEGE DEORIA | Uttar Pradesh | State Govt (15% AIQ) | 10,156 | 13,815 | 7 |  | 14,957 | 88,640 | 107,291 |
| SWAMI RAMANAND TiRTH RURAL M.C AMBAJOGAI | Maharashtra | State Govt (15% AIQ) | 12,009 | 13,885 | 9 | 16,534 | 14,161 | 88,247 | 106,444 |
| Autonomous State Medical Collage Kushinagar | Uttar Pradesh | State Govt (15% AIQ) | 8,696 | 13,983 | 8 | 15,370 | 16,175 | 80,124 |  |
| Govt. Medical College Udhampur | Jammu And Kashmir | State Govt (15% AIQ) | 8,742 | 13,995 | 5 | 15,320 | 16,112 | 73,037 | 96,718 |
| Government Medical College Ananthapuram | Andhra Pradesh | State Govt (15% AIQ) | 5,177 | 14,025 | 11 | 21,311 | 16,934 | 80,867 | 108,314 |
| Govt. Medical College and Hospital Chandrapur | Maharashtra | State Govt (15% AIQ) | 11,601 | 14,150 | 8 | 17,316 | 15,666 | 91,853 | 102,566 |
| Government Medical College Satna Near Kendriya Vidyalaya No. 2 | Madhya Pradesh | State Govt (15% AIQ) | 6,914 | 14,186 | 7 | 16,684 | 14,974 | 87,788 | 108,149 |
| Autonomous State Medical college Society Hardoi Gaura Danda | Uttar Pradesh | State Govt (15% AIQ) | 13,065 | 14,227 | 7 | 14,309 | 15,616 | 87,884 | 108,144 |
| Jannayak Karpoori Thakur Medical college and Hospital Madhepura | Bihar | State Govt (15% AIQ) | 12,080 | 14,249 | 6 | 17,199 | 15,293 | 93,794 | 112,881 |
| Virendra Kumar Sakhlecha Government Medical College Neemuch | Madhya Pradesh | State Govt (15% AIQ) | 12,370 | 14,281 | 7 | 15,713 | 15,727 | 85,937 | 101,593 |
| Gadag Institute of Medical Sciences GADAG INSTITUTE OF MEDICAL SCIENCES GADAG Mallasamudra | Karnataka | State Govt (15% AIQ) | 10,473 | 14,287 | 8 | 20,274 | 15,554 | 99,128 | 94,357 |
| Government Medical College Seoni | Madhya Pradesh | State Govt (15% AIQ) | 8,098 | 14,303 | 7 | 17,567 | 15,843 | 90,279 | 100,004 |
| MALDA MED. COLLEGE MALDA | West Bengal | State Govt (15% AIQ) | 13,342 | 14,398 | 7 | 19,347 | 15,958 | 90,126 | 123,538 |
| Autonomous State Medical College Society Mirzapur | Uttar Pradesh | State Govt (15% AIQ) | 12,792 | 14,400 | 5 | 17,073 | 15,629 | 89,990 | 111,337 |
| C. Institute of Medical Sciences Chamarajanagar | Karnataka | State Govt (15% AIQ) | 4,557 | 14,419 | 10 | 22,472 | 15,745 | 86,328 | 104,491 |
| GOVERNMENT MEDICAL COLLEGE PURNEA govt.mcpurnea@gmail.com | Bihar | State Govt (15% AIQ) | 11,672 | 14,469 | 5 | 15,767 | 16,723 | 96,494 | 116,925 |
| Autonomous State Medical College Pilibhit | Uttar Pradesh | State Govt (15% AIQ) | 10,389 | 14,571 | 7 | 17,471 | 16,994 | 89,345 | 114,856 |
| Autonomous State Medical College Pratapgarh | Uttar Pradesh | State Govt (15% AIQ) | 13,441 | 14,577 | 4 | 16,768 | 15,429 | 91,457 | 109,057 |
| SH VASANT RAO NAIK GOVT.M.C. YAVATMAL | Maharashtra | State Govt (15% AIQ) | 8,335 | 14,578 | 11 | 15,782 | 15,069 | 87,513 | 109,913 |
| Government Medical College Baramulla | Jammu And Kashmir | State Govt (15% AIQ) | 12,135 | 14,647 | 6 | 21,083 | 17,373 | 84,046 | 92,877 |
| RAJIV GANDHI INSTITUTE OF MEDICAL SCIENCES KADAPA | Andhra Pradesh | State Govt (15% AIQ) | 11,877 | 14,765 | 11 | 22,662 | 17,597 | 84,095 | 124,744 |
| Goverment Medical College And Hospital Jalgaon GOVERNMENT MEDICAL COLLEGE | Maharashtra | State Govt (15% AIQ) | 7,740 | 14,860 | 10 | 17,282 | 15,816 | 91,995 | 114,432 |
| GOVERMENT MEDICAL COLLEGE NANDURBAR MAHARARASTRA DISTRICT CIVIL HOSPITAL CAMPUS SAKRI ROAD NANDURBAR | Maharashtra | State Govt (15% AIQ) | 8,378 | 15,066 | 5 | 17,163 | 16,137 | 97,338 | 114,517 |
| UNS AUTONOMOUS STATE MEDICAL COLLEGES Jaunpur | Uttar Pradesh | State Govt (15% AIQ) | 12,783 | 15,127 | 6 | 15,549 | 15,718 | 90,963 | 114,568 |
| Autonomous State Medical College Ghazipur | Uttar Pradesh | State Govt (15% AIQ) | 10,048 | 15,183 | 6 | 16,213 | 15,937 | 90,264 | 113,723 |
| Lt. B R K Government Medical College Jagdalpur | Chhattisgarh | State Govt (15% AIQ) | 11,005 | 15,184 | 7 | 18,477 | 16,283 | 89,843 | 111,624 |
| Koppal Institute of Medical Sciences DIRECTOR | Karnataka | State Govt (15% AIQ) | 14,278 | 15,274 | 10 | 20,884 | 15,999 | 93,550 | 124,471 |
| SILCHAR MEDICAL COLLEGE SILCHER | Assam | State Govt (15% AIQ) | 11,313 | 15,335 | 8 | 16,345 | 17,257 | 83,710 | 83,333 |
| GMERS Medical College Porbandar | Gujarat | State Govt (15% AIQ) | 10,293 | 15,464 | 5 | 16,335 | 18,744 | 89,070 | 132,171 |
| Government Medical College and District General Hospital Ratnagiri | Maharashtra | State Govt (15% AIQ) | 7,543 | 15,483 | 6 | 17,948 | 16,229 | 96,916 | 120,996 |
| Haveri Institute of Medical Sciences Karnataka | Karnataka | State Govt (15% AIQ) | 12,288 | 15,509 | 10 | 22,656 | 16,921 | 100,011 | 126,062 |
| Government Medcial College Gondia | Maharashtra | State Govt (15% AIQ) | 14,435 | 15,517 | 9 | 18,457 | 16,238 | 95,302 | 118,775 |
| Mursidabad M C & Hospital Mursidabad | West Bengal | State Govt (15% AIQ) | 14,561 | 15,566 | 7 | 18,344 | 17,170 | 88,409 | 127,409 |
| Phulo Jhano Medical College Dumka | Jharkhand | State Govt (15% AIQ) | 13,960 | 15,573 | 6 | 17,956 | 17,134 | 99,931 | 102,692 |
| RIMS Ongole | Andhra Pradesh | State Govt (15% AIQ) | 9,708 | 15,574 | 7 | 22,309 | 17,411 | 77,084 | 108,820 |
| Autonomous State Medical College Sultanpur | Uttar Pradesh | State Govt (15% AIQ) | 14,438 | 15,600 | 5 | 17,806 | 16,796 | 92,434 | 109,960 |
| GOVERNMENT MEDICAL COLLEGE RAJOURI | Jammu And Kashmir | State Govt (15% AIQ) | 13,572 | 15,602 | 7 | 16,757 | 17,502 | 90,851 | 96,694 |
| Saheed Laxman Nayak Med. College and Hos. Koraput | Odisha | State Govt (15% AIQ) | 9,193 | 15,676 | 7 | 20,535 | 17,984 | 71,174 | 128,137 |
| Autonomous State Medical College Lalitpur | Uttar Pradesh | State Govt (15% AIQ) | 13,603 | 15,683 | 6 | 18,487 | 16,674 | 95,676 | 112,116 |
| Government Medical College & Hospital Alibag-Raigad | Maharashtra | State Govt (15% AIQ) | 13,586 | 15,689 | 6 | 18,274 | 17,028 | 64,009 |  |
| Government Medical College Nizamabad | Telangana | State Govt (15% AIQ) | 11,152 | 15,751 | 7 | 17,052 | 16,908 | 80,061 | 59,713 |
| Autonomous State Medical College Lakhimpur Kheri | Uttar Pradesh | State Govt (15% AIQ) | 14,521 | 15,755 | 4 | 17,169 | 17,513 | 95,644 | 116,142 |
| Chandulal Chandrakar Memorial Government Medical College Durg | Chhattisgarh | State Govt (15% AIQ) | 10,601 | 15,834 | 11 | 19,738 | 17,986 | 98,965 | 122,663 |
| Government Medical college Ambernath | Maharashtra | State Govt (15% AIQ) | 10,037 | 15,846 | 5 | 17,837 | 18,031 | 79,284 | 123,743 |
| Government Medical College Rajnandgaon | Chhattisgarh | State Govt (15% AIQ) | 13,257 | 15,903 | 7 | 17,097 | 16,978 | 88,113 | 119,835 |
| Medinirai Medical College (previously Known as Palamu Medical College) Palamu | Jharkhand | State Govt (15% AIQ) | 10,270 | 15,946 | 4 | 19,273 | 17,861 | 100,039 | 122,410 |
| Chikkamagaluru Institute of Medical Sciences DIRECTOR CHIKKAMAGALURU INSTITUTE OF MEDICAL SCIENCES ARALAGUPPE MALLEGOWDA DISTRICT HOSPITAL TEG | Karnataka | State Govt (15% AIQ) | 13,274 | 15,955 | 9 | 23,078 | 16,433 | 99,928 | 122,917 |
| Government Medical College and Hospital Keonjhar | Odisha | State Govt (15% AIQ) | 13,669 | 16,017 | 3 | 21,167 | 19,116 | 85,852 | 140,433 |
| Autonomous State Medical College Gonda | Uttar Pradesh | State Govt (15% AIQ) | 15,773 | 16,046 | 5 | 18,357 | 16,860 | 92,544 | 112,771 |
| GMERS Medical College Morbi | Gujarat | State Govt (15% AIQ) | 10,609 | 16,056 | 6 | 18,907 | 17,327 | 93,826 | 118,121 |
| Government Medical College & Hospital Jalpaiguri | West Bengal | State Govt (15% AIQ) | 14,446 | 16,071 | 5 | 21,857 | 18,810 | 98,047 | 133,067 |
| Autonomous state Medical College Sehud | Uttar Pradesh | State Govt (15% AIQ) | 12,971 | 16,086 | 7 |  | 17,521 | 91,920 |  |
| Autonomous state Medical College Kaushambi | Uttar Pradesh | State Govt (15% AIQ) | 8,297 | 16,095 | 6 | 17,261 | 17,035 | 93,078 | 116,120 |
| Raiganj Government Medical College ABDULGHATA CAMPUS | West Bengal | State Govt (15% AIQ) | 13,988 | 16,264 | 4 | 20,444 | 18,300 | 97,078 | 131,714 |
| Chitradurga Medical College and Research Institute P B Road Chitradurga | Karnataka | State Govt (15% AIQ) | 14,964 | 16,313 | 8 | 22,578 | 17,154 | 102,160 | 125,638 |
| Baba Kinaram Autonomous State Medical College Chandauli | Uttar Pradesh | State Govt (15% AIQ) | 15,050 | 16,316 | 5 | 18,191 | 17,687 | 93,950 | 121,111 |
| Jorhat Medical College and Hospital JORHAT | Assam | State Govt (15% AIQ) | 11,815 | 16,465 | 8 | 19,097 | 18,742 | 102,267 | 89,396 |
| Govt Medical College Jogulamba | Telangana | State Govt (15% AIQ) | 15,950 | 16,584 | 2 |  | 20,497 | 108,752 | 141,607 |
| Autonomous State Medical College Sonebhadra | Uttar Pradesh | State Govt (15% AIQ) | 15,583 | 16,620 | 6 | 17,823 | 17,711 | 96,570 | 115,781 |
| YADGIRI INSTITUTE OF MEDICAL SCIENCES YADGIRI | Karnataka | State Govt (15% AIQ) | 14,361 | 16,640 | 10 | 20,459 | 17,557 | 101,608 | 127,896 |
| Government Medical College Mahabubangar | Telangana | State Govt (15% AIQ) | 12,208 | 16,687 | 8 | 21,758 | 18,092 | 85,262 | 105,985 |
| Government Medical College Amravati | Maharashtra | State Govt (15% AIQ) | 14,071 | 16,788 | 7 | 18,640 | 18,124 | 87,522 | 113,394 |
| Government Medical College Mahasamund Chhattisgarh In front of Sai temple raipur road village kharora Mahasamund | Chhattisgarh | State Govt (15% AIQ) | 13,052 | 16,897 | 6 | 19,764 | 18,369 | 92,487 | 124,812 |
| Government Medical College Sindhudurg | Maharashtra | State Govt (15% AIQ) | 15,990 | 16,925 | 6 |  | 17,509 | 96,743 |  |
| Government Medical College Narayanpet | Telangana | State Govt (15% AIQ) | 13,630 | 17,038 | 2 | 24,991 | 20,307 | 90,601 | 142,347 |
| GMC Jangaon gmc.jangaon@gmail.com | Telangana | State Govt (15% AIQ) | 15,413 | 17,116 | 5 | 20,808 | 19,834 | 100,443 | 126,893 |
| GOVERNMENT MEDICAL COLLEGE OSMANABAD | Maharashtra | State Govt (15% AIQ) | 13,350 | 17,216 | 6 | 19,184 | 17,566 | 92,649 | 122,369 |
| Government Medical College Doda | Jammu And Kashmir | State Govt (15% AIQ) | 9,646 | 17,315 | 6 | 19,321 | 19,533 | 101,256 | 56,076 |
| Government Medical College Parbhani | Maharashtra | State Govt (15% AIQ) | 14,594 | 17,318 | 5 | 20,687 | 18,101 | 97,428 | 119,224 |
| Government Medical College Sundargarh | Odisha | State Govt (15% AIQ) | 13,867 | 17,324 | 8 | 19,026 | 18,365 | 86,518 | 127,741 |
| Government Medical College Siddipet Survey No 54 | Telangana | State Govt (15% AIQ) | 15,128 | 17,333 | 10 | 20,415 | 18,607 | 92,458 | 110,028 |
| Tezpur Medical College Tezpur | Assam | State Govt (15% AIQ) | 12,607 | 17,344 | 5 | 21,375 | 20,306 | 105,486 | 114,020 |
| RAMPURHAT GOVT MEDICAL COLLEGE RAMPURHAT RAMPURHAT GOVERNMENT MEDICAL COLLEGE AND HOSPITAL PO RAMPURHAT PS RAMPURHAT PIN 731224 DIST BIRBHUM | West Bengal | State Govt (15% AIQ) | 14,416 | 17,392 | 6 | 19,830 | 18,283 | 90,561 | 122,224 |
| GMERS Medical College Navsari | Gujarat | State Govt (15% AIQ) | 16,016 | 17,448 | 3 | 18,734 | 19,567 | 94,348 | 132,548 |
| Rajmata shrimati devendra kumari singhdeo government medical college ambikapur | Chhattisgarh | State Govt (15% AIQ) | 14,086 | 17,455 | 7 | 19,513 | 18,613 | 94,867 | 121,735 |
| GOVERNMENT MEDICAL COLLEGE HANDWARA | Jammu And Kashmir | State Govt (15% AIQ) | 15,015 | 17,543 | 5 | 21,323 | 18,937 | 100,576 | 85,106 |
| RIMS Srikakulam Balaga Srikakulam | Andhra Pradesh | State Govt (15% AIQ) | 14,163 | 17,565 | 15 | 23,287 | 18,461 | 84,998 | 125,112 |
| Government Medical College Bhandara | Maharashtra | State Govt (15% AIQ) | 12,648 | 17,608 | 5 | 20,763 | 18,944 | 100,731 | 126,924 |
| GMERS Medical College Panchmahal Godhra | Gujarat | State Govt (15% AIQ) | 8,504 | 17,630 | 8 | 19,716 | 18,851 | 97,582 | 130,349 |
| Government Medical College Suryapet AMARAVADI NAGAR | Telangana | State Govt (15% AIQ) | 8,209 | 17,662 | 7 | 22,645 | 18,618 | 99,703 | 111,793 |
| Govt Medical College Nalgonda OFFICE OF THE PRINCIPAL | Telangana | State Govt (15% AIQ) | 15,643 | 17,800 | 7 | 22,783 | 18,976 | 97,450 | 112,609 |
| Government Medical College Nagarkurnool | Telangana | State Govt (15% AIQ) | 14,067 | 17,900 | 8 | 23,307 | 19,721 | 102,374 | 123,852 |
| Government medical College Thalarasingi village | Andhra Pradesh | State Govt (15% AIQ) | 17,598 | 17,923 | 2 | 24,545 | 20,234 | 85,153 | 139,038 |
| Sarat Chandra Chattopadhyay Govt. Medical College & Hospital Uluberia | West Bengal | State Govt (15% AIQ) | 16,828 | 17,944 | 6 | 19,261 | 19,405 | 84,981 | 124,635 |
| Govt. Medical College Rajanna Sircilla GOVERNMENT MEDICAL COLLEGE NEAR KASTURBA GIRLS SCHOOL PEDDUR SIRCILLA DISTRICT RAJANNA SIRCILLA | Telangana | State Govt (15% AIQ) | 10,826 | 17,968 | 6 | 21,384 | 19,248 | 98,635 | 63,398 |
| GMERS Medical College Rajpipla | Gujarat | State Govt (15% AIQ) | 16,307 | 18,038 | 7 | 20,692 | 19,984 | 97,658 | 134,204 |
| Saheed Rendo Majhi Medical College & Hospital Bhawanipatna | Odisha | State Govt (15% AIQ) | 15,607 | 18,070 | 7 | 20,237 | 19,326 | 86,703 | 134,635 |
| GOVERNMENT MEDICAL COLLEGE MEDAK | Telangana | State Govt (15% AIQ) | 16,850 | 18,073 | 3 | 19,796 | 20,339 | 104,671 |  |
| Maharaja Jitendra Narayan Medical College and Hospital Coochbehar Vivekananda Street | West Bengal | State Govt (15% AIQ) | 14,426 | 18,083 | 5 | 20,010 | 18,940 | 98,006 | 128,380 |
| Deben Mahata Government Medical College & Hospital Vill Hatuara PO Vivekananda Nagar PS Purulia Muffasil Dist Purulia Pin 723147 | West Bengal | State Govt (15% AIQ) | 14,580 | 18,165 | 5 | 19,558 | 19,532 | 93,051 | 127,811 |
| Government Medical College Yadadri | Telangana | State Govt (15% AIQ) | 17,976 | 18,193 | 2 | 24,618 | 20,855 | 105,026 | 129,006 |
| AGARTALA GOVT. MEDICAL COLLEGE AGARTALA | Tripura | State Govt (15% AIQ) | 12,341 | 18,254 | 6 | 23,014 | 20,221 | 101,319 | 117,645 |
| Government Medical College ESIC | Kerala | ESIC | 10,950 | 18,272 | 15 | 40,263 | 28,151 | 139,914 | 475,089 |
| Government Medical College Kanker | Chhattisgarh | State Govt (15% AIQ) | 12,797 | 18,309 | 6 | 19,977 | 18,938 | 97,250 | 119,386 |
| Government Medical College BULDHANA | Maharashtra | State Govt (15% AIQ) | 15,667 | 18,312 | 7 | 20,968 | 19,222 | 99,496 | 130,471 |
| Goverment Medical College Gadchiroli | Maharashtra | State Govt (15% AIQ) | 17,516 | 18,342 | 6 | 19,150 | 19,118 | 99,295 | 126,069 |
| Government Medical College Washim | Maharashtra | State Govt (15% AIQ) | 13,093 | 18,359 | 6 | 21,070 | 19,526 | 101,553 | 135,975 |
| Fakhruddin Ali Ahmed Medical College Barpeta | Assam | State Govt (15% AIQ) | 15,913 | 18,466 | 7 | 21,139 | 20,218 | 104,412 | 105,467 |
| Government Medical College Jalna | Maharashtra | State Govt (15% AIQ) | 16,045 | 18,468 | 5 | 21,037 | 19,458 | 99,386 | 134,712 |
| Prafulla Chandra Sen Government Medical College & Hospital Arambagh | West Bengal | State Govt (15% AIQ) | 16,676 | 18,500 | 5 | 20,938 | 19,599 | 93,574 | 109,833 |
| GOVERNMENT MEDICAL COLLEGE SANGAREDDY | Telangana | State Govt (15% AIQ) | 17,191 | 18,553 | 9 | 22,704 | 19,398 | 106,139 | 124,940 |
| Jawaharlal Nehru Medical College AMU | Uttar Pradesh | AMU | 4,040 | 18,554 | 69 |  |  |  |  |
| Government Medical College Eluru | Andhra Pradesh | State Govt (15% AIQ) | 12,712 | 18,587 | 9 | 23,264 | 19,856 | 80,839 | 137,133 |
| Government Medical College Hingoli | Maharashtra | State Govt (15% AIQ) | 16,350 | 18,639 | 5 | 21,219 | 19,403 | 101,029 | 135,062 |
| Government Medical College Korba(C.G.) | Chhattisgarh | State Govt (15% AIQ) | 17,871 | 18,665 | 8 | 19,164 | 19,269 | 100,028 | 114,749 |
| Government Medical College Maheshwaram | Telangana | State Govt (15% AIQ) | 16,248 | 18,701 | 3 | 24,918 | 21,032 | 106,467 |  |
| GOVERNMENT MEDICAL COLLEGE Karimnagar Telangana The Principal | Telangana | State Govt (15% AIQ) | 14,935 | 18,723 | 6 | 21,286 | 19,600 | 102,429 | 134,682 |
| GOVT MEDICAL COLLEGE VIZIANAGARAM Opposite Central Tribal University | Andhra Pradesh | State Govt (15% AIQ) | 11,433 | 18,762 | 10 | 24,086 | 20,200 | 92,266 | 120,297 |
| Government Medical College Narsampet Telangana | Telangana | State Govt (15% AIQ) | 14,514 | 18,763 | 2 | 22,880 | 20,374 | 104,706 | 139,117 |
| GMC Rajamahendravaram | Andhra Pradesh | State Govt (15% AIQ) | 16,488 | 18,768 | 8 | 23,873 | 19,531 | 85,380 | 119,779 |
| Tamralipto Government Medical College & Hospital West Bengal | West Bengal | State Govt (15% AIQ) | 16,381 | 18,793 | 6 | 21,290 | 19,665 | 102,110 | 132,634 |
| Government Medical College Churachandpur | Manipur | State Govt (15% AIQ) | 13,135 | 18,863 | 5 | 25,389 | 21,148 | 101,484 | 136,883 |
| GOVERNMENT MEDICAL COLLEGE NANDYAL principalgmcnandyala@gmail.com | Andhra Pradesh | State Govt (15% AIQ) | 14,619 | 18,974 | 9 | 24,454 | 19,791 | 94,142 | 120,014 |
| GOVERNMENT MEDICAL COLLEGE MACHILIPATNAM KARA AGRAHARAM NEAR RADAR STATION MACHILIPATNAM | Andhra Pradesh | State Govt (15% AIQ) | 17,914 | 18,990 | 8 | 24,175 | 20,022 | 86,954 | 136,153 |
| Tomo Riba Institute Health and Medical Sciences Naharlagun | Arunachal Pradesh | State Govt (15% AIQ) | 16,880 | 19,272 | 6 | 21,264 | 21,275 | 98,597 | 109,278 |
| Jhargram Government Medical College and Hospital West Bengal | West Bengal | State Govt (15% AIQ) | 18,367 | 19,281 | 6 | 20,542 | 19,687 | 91,235 | 125,649 |
| JLN IMS IMPHAL | Manipur | State Govt (15% AIQ) | 15,669 | 19,283 | 9 | 22,504 | 20,402 | 81,911 | 105,760 |
| Government Medical College Ramagundam | Telangana | State Govt (15% AIQ) | 18,074 | 19,450 | 7 | 24,249 | 20,489 | 107,615 | 137,439 |
| SLBS Govt. Medical College Mandi | Himachal Pradesh | ESIC | 9,041 | 19,515 | 15 | 21,839 | 21,788 | 146,564 | 441,583 |
| Government Medical College Khammam | Telangana | State Govt (15% AIQ) | 14,005 | 19,528 | 8 | 21,844 | 19,993 | 102,052 | 122,853 |
| Government Medical College Mahabubabad | Telangana | State Govt (15% AIQ) | 16,325 | 19,605 | 10 | 23,138 | 20,335 | 103,876 | 121,232 |
| Government Medical College Jagtial | Telangana | State Govt (15% AIQ) | 17,735 | 19,790 | 6 | 23,585 | 20,790 | 106,981 | 132,096 |
| GMC Kamareddy Office of the Principal | Telangana | State Govt (15% AIQ) | 19,304 | 19,972 | 7 | 24,304 | 20,348 | 104,069 | 112,712 |
| Government Medical College Mancherial | Telangana | State Govt (15% AIQ) | 18,960 | 20,063 | 5 | 24,258 | 20,955 | 107,118 | 135,567 |
| Lakhimpur Medical College North Lakhimpur | Assam | State Govt (15% AIQ) | 18,627 | 20,090 | 5 | 21,279 | 21,217 | 109,291 | 132,326 |
| Government Medical College Nirmal BESIDE DIVYA GARDEN | Telangana | State Govt (15% AIQ) | 15,766 | 20,114 | 6 | 24,815 | 20,895 | 95,860 | 108,496 |
| Govt Medical College Mulugu | Telangana | State Govt (15% AIQ) | 17,534 | 20,167 | 3 | 23,911 | 20,605 | 94,550 | 108,980 |
| Dhubri Medical College Assam | Assam | State Govt (15% AIQ) | 19,722 | 20,273 | 5 | 22,798 | 20,681 | 104,163 | 129,921 |
| Government Medical College and ESIC Hospital Coimbatore | Tamil Nadu | ESIC | 11,138 | 20,293 | 9 | 39,924 | 25,764 | 95,190 | 199,369 |
| GOVT MEDICAL COLLEGE WANAPARTHY | Telangana | State Govt (15% AIQ) | 18,717 | 20,296 | 8 | 24,438 | 20,844 | 109,044 | 133,436 |
| Government Medical College Bhadradri | Telangana | State Govt (15% AIQ) | 17,379 | 20,375 | 9 | 24,456 | 20,893 | 106,101 | 134,753 |
| Govt Medical College Vikarabad ANANTHAGIRI HILLS VIKARABAD VIKARABAD DISTRICT TELANGANA 501101 | Telangana | State Govt (15% AIQ) | 18,658 | 20,420 | 8 | 24,860 | 20,816 | 108,627 | 126,434 |
| Diphu Medical College & Hospital Assam | Assam | State Govt (15% AIQ) | 18,543 | 20,448 | 6 | 22,629 | 20,668 | 100,279 | 116,747 |
| Nagaon Medical college Dipholu | Assam | State Govt (15% AIQ) | 17,934 | 20,485 | 5 | 24,034 | 21,404 | 109,637 |  |
| Govt. Medical College Kumuram Bheem Asifabad | Telangana | State Govt (15% AIQ) | 19,735 | 20,559 | 4 | 22,654 | 20,979 | 110,389 | 140,586 |
| Govt. Medical College Jayashankar Bhupalpally Manzoor Nagar Road | Telangana | State Govt (15% AIQ) | 19,249 | 20,614 | 7 | 24,587 | 21,036 | 108,227 | 138,176 |
| Kokrajhar Medical College & Hospital Rangalikhata Rangalikhata Pt.-1 | Assam | State Govt (15% AIQ) | 19,452 | 20,679 | 6 | 24,869 | 21,330 | 105,691 | 125,887 |
| Tinsukia Medical College & Hospital Tinsukia | Assam | State Govt (15% AIQ) | 18,792 | 20,728 | 6 | 24,588 | 21,452 | 107,427 | 78,349 |
| ZORAM MEDICAL COLLEGE Falkawn Academic Block | Mizoram | State Govt (15% AIQ) | 20,524 | 20,924 | 6 | 25,440 | 21,320 | 103,767 |  |
| Nalbari Medical College & Hospital Dakhingaon Nalbari | Assam | State Govt (15% AIQ) | 18,110 | 20,989 | 7 | 24,577 | 21,232 | 93,101 | 123,013 |
| NAGALAND INSTITUTE OF MEDICAL SCIENCE AND RESEARCH PHIREBAGIE KOHIMA - 797001 | Nagaland | State Govt (15% AIQ) | 20,773 | 21,190 | 6 | 25,011 | 21,406 | 110,219 | 134,837 |
| ESI-MC&PGIMS&R Banglore | Karnataka | ESIC | 16,673 | 23,267 | 27 | 27,201 | 28,727 | 155,677 | 391,353 |
| ESIC Medical College AND PGIMSR Chennai | Tamil Nadu | ESIC | 20,331 | 24,648 | 11 | 39,589 | 28,753 | 148,246 | 474,008 |
| ESIC Medical College Hyderbad | Telangana | ESIC | 5,272 | 26,336 | 17 | 29,767 | 30,342 | 146,259 | 205,499 |
| ESIC Medical College Gulbarga | Karnataka | ESIC | 23,657 | 31,204 | 24 | 37,629 | 34,956 | 186,219 | 432,012 |
| ESIC PGIMSR Joka | West Bengal | ESIC | 16,310 | 31,648 | 24 | 38,376 | 35,494 | 190,094 | 468,396 |
| Kasturba Medical College Manipal Univ. - Manipal | Karnataka | Deemed University | 864 | 40,008 | 212 |  |  |  |  |
| SYMBIOSIS MEDICAL COLLEGE FOR WOMEN PUNE Gram Lavale Tal Mulshi Pune | Maharashtra | Deemed University | 12,004 | 47,592 | 127 |  |  |  |  |
| Kasturba Medical College Manipal Univ. - Mangalore | Karnataka | Deemed University | 1,494 | 52,466 | 161 |  |  |  |  |
| Manipal Tata Medical College Kadani Road | Jharkhand | Deemed University | 30,376 | 62,699 | 120 |  |  |  |  |
| K.S Hegde Medical Academy Mangaluru | Karnataka | Deemed University | 52,875 | 105,741 | 175 |  |  |  |  |
| JSS Medical College Mysuru | Karnataka | Deemed University | 15,142 | 117,000 | 200 |  |  |  |  |
| Rural Medical College and PIMS Loni | Maharashtra | Deemed University | 56,639 | 124,946 | 170 |  |  |  |  |
| Kalinga Institute of Medical Sciences Bhubaneswar | Odisha | Deemed University | 45,531 | 147,972 | 213 |  |  |  |  |
| MGM Medical College Navi Mumbai | Maharashtra | Deemed University | 37,102 | 160,536 | 170 |  |  |  |  |
| SDU Medical College Kolar | Karnataka | Deemed University | 76,519 | 177,905 | 170 |  |  |  |  |
| Institute of Medical Sciences & SUM Hospital Campus II | Odisha | Deemed University | 61,517 | 185,262 | 127 |  |  |  |  |
| Jagadguru Gangadhar Mahaswamigalu Moorusavirmath Medical College Hubballi | Karnataka | Deemed University | 97,664 | 198,103 | 90 |  |  |  |  |
| B.L.D.E University Bijapur | Karnataka | Deemed University | 89,923 | 207,742 | 170 |  |  |  |  |
| MGM Medical College Aurangabad | Maharashtra | Deemed University | 63,557 | 208,996 | 170 |  |  |  |  |
| Sri Siddhartha Medical College DU Tumkur | Karnataka | Deemed University | 66,842 | 217,698 | 170 |  |  |  |  |
| Mahatma Gandhi Mission Medical College Vashi | Maharashtra | Deemed University | 59,776 | 224,399 | 85 |  |  |  |  |
| Institute of Medical Sciences and SUM Host. Bhubaneswar | Odisha | Deemed University | 67,245 | 233,205 | 212 |  |  |  |  |
| Amrita Institute of Medical Science Kochi | Kerala | Deemed University | 39,878 | 233,349 | 127 |  |  |  |  |
| Mahatma Gandhi Mission Medical College Nerul | Maharashtra | Deemed University | 120,158 | 252,099 | 42 |  |  |  |  |
| Sri Siddhartha Academy T Begur SRI SIDDHARTHA INSTITUTE OF MEDICAL SCIENCES AND RESEARCH CENTRE T BEGUR NELAMANGALA TALUK BANGALOR | Karnataka | Deemed University | 119,515 | 252,684 | 127 |  |  |  |  |
| Sri Ramachandra Med. College and Res. Inst. Chennai | Tamil Nadu | Deemed University | 7,027 | 263,126 | 212 |  |  |  |  |
| MM Inst. Med. and Research Mullana | Haryana | Deemed University | 34,431 | 276,229 | 170 |  |  |  |  |
| Yenepoya Medical College Mangalore | Karnataka | Deemed University | 32,284 | 281,006 | 109 |  |  |  |  |
| Amrita School of Medicine Faridabad Mata Amritanandmayi Marg | Haryana | Deemed University | 54,768 | 283,536 | 135 |  |  |  |  |
| SRI LALITHAMBIGAI MEDICAL COLLEGE & HOSPITAL Faculty of Medicine - Sri Lalithambigai Medical College and Hospital | Tamil Nadu | Deemed University | 71,910 | 295,429 | 128 |  |  |  |  |
| Raja Rajeswari Medical College Bengaluru 202 | Karnataka | Deemed University | 74,086 | 306,923 | 212 |  |  |  |  |
| Dr. DYP Edu. Soc. Deemed Uni. Kolhapur | Maharashtra | Deemed University | 66,665 | 324,266 | 127 |  |  |  |  |
| Malla Reddy Institute of Medical Sciences Hyderabad | Telangana | Deemed University | 92,982 | 332,211 | 170 |  |  |  |  |
| SBKS Med. Inst. and Res. Centre Sumandeep Vidyapeeth | Gujarat | Deemed University | 66,113 | 340,315 | 107 |  |  |  |  |
| Malla Reddy Medical College for Women Hyderabad | Telangana | Deemed University | 159,907 | 352,435 | 170 |  |  |  |  |
| Bharati Vidyapeeth DU Medical College Dhankawadi | Maharashtra | Deemed University | 71,735 | 374,028 | 127 |  |  |  |  |
| DATTA MEGHE MEDICAL COLLEGE WANADONGRI HINGNA NAGPUR Hinaga Road Wanadongri Nagpur Maharashtra India | Maharashtra | Deemed University | 70,948 | 393,512 | 127 |  |  |  |  |
| Dr. DY Patil Medical College and Hospt. Pune | Maharashtra | Deemed University | 54,091 | 395,628 | 212 |  |  |  |  |
| Krishna Inst. of Med. Scie. Karad | Maharashtra | Deemed University | 82,145 | 396,381 | 212 |  |  |  |  |
| JLN Medical College Datta Meghe | Maharashtra | Deemed University | 116,667 | 416,757 | 212 |  |  |  |  |
| Dr. DY Patil Medical College Navi Mumbai | Maharashtra | Deemed University | 18,464 | 419,526 | 212 |  |  |  |  |
| VELS MEDICAL COLLEGE & HOSPITAL 12-123 | Tamil Nadu | Deemed University | 97,449 | 424,512 | 127 |  |  |  |  |
| Saveetha Medical College Chennai | Tamil Nadu | Deemed University | 87,900 | 432,358 | 250 |  |  |  |  |
| GITAM Institue of Med. Sce. and Res. Visakhapatnam | Andhra Pradesh | Deemed University | 45,231 | 437,866 | 127 |  |  |  |  |
| BV Deemed Uni. Med. College and Hos. Sangli | Maharashtra | Deemed University | 84,691 | 440,671 | 127 |  |  |  |  |
| Graphic Era Institute Of Medical Science Graphic Era Institute of Medical Sciences 16th Milestone Chakrata Road Dehradun Uttarakhand | Uttarakhand | Deemed University | 106,788 | 442,416 | 127 |  |  |  |  |
| Vinayaka Missions Medical College and Hospital Karaikal | Puducherry | Deemed University | 110,776 | 491,918 | 150 |  |  |  |  |
| SRM Medical College and Hospital Chennai | Tamil Nadu | Deemed University | 79,089 | 496,509 | 247 |  |  |  |  |
| Santosh Medical College and Hospital Ghaziabad | Uttar Pradesh | Deemed University | 75,601 | 499,941 | 127 |  |  |  |  |
| VMKV Medical College and Hospital Salem | Tamil Nadu | Deemed University | 37,475 | 549,662 | 150 |  |  |  |  |
| Meenakshi Medical College Hospital and Research Institute Kanchipuram | Tamil Nadu | Deemed University | 143,935 | 558,109 | 250 |  |  |  |  |
| Mahatma Gandhi Medical College Pondicherry | Puducherry | Deemed University | 82,860 | 581,782 | 225 |  |  |  |  |
| ACS Medical College and Hospital Chennai | Tamil Nadu | Deemed University | 33,108 | 587,084 | 212 |  |  |  |  |
| Aarupadai Veedu Medical College and Hospt. Puducherry | Puducherry | Deemed University | 72,493 | 593,506 | 150 |  |  |  |  |
| Chettinad Hos. and Res. Inst. Kancheepuram | Tamil Nadu | Deemed University | 96,530 | 600,008 | 250 |  |  |  |  |
| Shri Sathya Sai Medical College and Research Institute Chennai | Tamil Nadu | Deemed University | 124,660 | 640,116 | 250 |  |  |  |  |
| BHAARATH MEDICAL COLLEGE AND HOSPITAL 173 | Tamil Nadu | Deemed University | 94,750 | 657,379 | 150 |  |  |  |  |
| Sree Balaji Medical College and Hospital Chennai | Tamil Nadu | Deemed University | 40,618 | 707,998 | 245 |  |  |  |  |
| Sri Lakshmi Narayana Inst. of Med. Scien. Puducherry | Puducherry | Deemed University | 145,782 | 733,697 | 250 |  |  |  |  |
| J R MEDICAL COLLEGE AND HOSPITAL TAMIL NADU | Tamil Nadu | Deemed University | 161,603 | 734,672 | 150 |  |  |  |  |

## Section 2 — MCC AIQ + Deemed + Central Institutes — BDS — Round 1 (Provisional), 2025

All 86 institutes carrying BDS (dental) seats through MCC in 2025, same structure as Section 1.

| College | State | Type | Open Opening | Open Closing | Open Seats | EWS Closing | OBC Closing | SC Closing | ST Closing |
|---|---|---|---|---|---|---|---|---|---|
| RUHS College of Dental Science Jaipur | Rajasthan | State Govt (15% AIQ) | 13,694 | 13,694 | 1 | 18,374 | 27,912 | 133,235 | 154,776 |
| GOVT. DENTAL COLLEGE & HOSP. AURANGABAD | Maharashtra | State Govt (15% AIQ) | 11,473 | 17,519 | 3 | 44,623 | 25,483 | 84,748 | 206,111 |
| FACULTY OF DEN SCI KG MED UNIV | Uttar Pradesh | State Govt (15% AIQ) | 16,923 | 18,646 | 2 | 30,594 | 25,322 | 129,928 | 138,880 |
| GOVT. DENTAL COLLEGE & HOSP. NAGPUR | Maharashtra | State Govt (15% AIQ) | 10,886 | 19,219 | 3 | 31,500 | 33,160 | 150,005 |  |
| DC RIMS | Manipur | State Govt (15% AIQ) | 16,533 | 20,798 | 3 |  | 33,113 | 128,010 | 169,235 |
| GOVT. D.C. & RESEARCH INST BANGALORE | Karnataka | State Govt (15% AIQ) | 16,096 | 21,785 | 2 | 34,320 | 32,671 | 143,021 | 159,742 |
| GOVT. DENTAL COLLEGE TRIVANDRUM | Kerala | State Govt (15% AIQ) | 14,847 | 22,159 | 2 | 39,814 | 29,186 | 147,037 |  |
| Government Dental College Thrissur | Kerala | State Govt (15% AIQ) | 8,211 | 22,199 | 2 |  | 28,784 | 150,123 |  |
| GOVT. DENTAL COLLEGE KOTTAYAM | Kerala | State Govt (15% AIQ) | 19,836 | 22,211 | 3 |  | 23,679 | 131,550 |  |
| S.C.B. MEDICAL COLL(DENTAL) CUTTACK | Odisha | State Govt (15% AIQ) | 16,799 | 22,364 | 4 | 33,364 | 24,093 | 87,414 | 119,066 |
| NAIR HOSP DENTAL COLLEGE & HOSP MUMBAI | Maharashtra | State Govt (15% AIQ) | 20,223 | 23,139 | 4 | 31,400 | 33,900 | 155,984 | 150,701 |
| GOVT. DENTAL COLLEGE KOZIKODE | Kerala | State Govt (15% AIQ) | 23,359 | 24,900 | 3 | 36,381 | 25,837 | 138,237 | 142,016 |
| AGARTALA GOVT. DENTAL COLLEGE AGARTAL | Tripura | State Govt (15% AIQ) | 21,907 | 26,096 | 5 |  | 27,879 | 112,727 |  |
| Burdwan Dental College & Hospital Burdwan | West Bengal | State Govt (15% AIQ) | 16,449 | 26,201 | 7 | 30,420 | 31,819 | 136,525 | 172,634 |
| GOVT. COLLEGE OF DENTISTRY INDORE | Madhya Pradesh | State Govt (15% AIQ) | 16,522 | 26,651 | 4 |  | 28,365 | 145,425 | 120,444 |
| Dental Institue RIMS | Jharkhand | State Govt (15% AIQ) | 25,494 | 26,797 | 3 | 31,856 | 33,163 | 135,449 | 187,194 |
| Maulana Azad Institute of Dental Sciences New Delhi | Delhi (NCT) | Delhi University | 11,677 | 26,944 | 16 | 30,063 | 31,646 | 145,911 | 210,335 |
| Government Dental College & Hospital Srinagar | Jammu And Kashmir | State Govt (15% AIQ) | 22,671 | 27,325 | 4 | 37,759 | 37,841 | 116,222 |  |
| Government Dental College and Hospital Vijayawada | Andhra Pradesh | State Govt (15% AIQ) | 24,805 | 27,395 | 3 |  | 34,088 | 108,852 | 177,989 |
| Goverment Dental College & Hospital Jalgaon | Maharashtra | State Govt (15% AIQ) | 20,672 | 27,499 | 3 | 36,700 | 33,009 | 156,913 |  |
| TAMILNADU GOVT D.C. & HOSP CHENNAI | Tamil Nadu | State Govt (15% AIQ) | 1,456 | 27,940 | 7 | 29,880 | 34,000 | 121,650 | 191,150 |
| IMS BHU Dental Varanasi | Uttar Pradesh | Central Institute | 14,381 | 28,956 | 24 | 32,467 | 32,320 | 138,864 | 178,066 |
| Government Dental College Alappuzha | Kerala | State Govt (15% AIQ) | 25,136 | 29,369 | 4 | 47,581 | 30,159 | 156,772 |  |
| GOVT DENTAL COLLEGE Kannur Pariyaram Medical College P O | Kerala | State Govt (15% AIQ) | 22,431 | 30,556 | 3 | 46,812 | 32,327 | 139,802 | 166,717 |
| Rajah Muthiah Dental College and Hos. Annamalai | Tamil Nadu | State Govt (15% AIQ) | 22,655 | 30,682 | 4 | 48,617 | 36,696 | 133,498 | 200,828 |
| GDC PT.BDS UNIV.OF HEALTH SCI | Haryana | State Govt (15% AIQ) | 26,005 | 30,921 | 7 | 36,395 | 32,836 | 137,850 | 199,957 |
| Govt dental college Pudukkottai GOVT DENTAL COLLEGE MULLUR PUDUKKOTTAI | Tamil Nadu | State Govt (15% AIQ) | 20,517 | 31,541 | 5 |  | 32,557 | 100,049 |  |
| GOVT DEN COLL DENTAL WING PATIALA Govt.Dental College and Hospital | Punjab | State Govt (15% AIQ) | 28,945 | 31,652 | 3 | 42,615 | 36,315 | 100,310 | 130,865 |
| Faculty of Dentistry Jamia Millia Islamia | Delhi (NCT) | Central Institute | 22,966 | 32,346 | 18 |  |  |  |  |
| GOVT. DENTAL COLL.& HOSP. JAMNAGAR | Gujarat | State Govt (15% AIQ) | 8,439 | 32,396 | 6 | 39,518 | 37,300 | 146,158 | 104,061 |
| GOVT. DENTAL COLLEGE & HOSP AHMEDABAD | Gujarat | State Govt (15% AIQ) | 27,752 | 32,909 | 7 | 36,898 | 35,831 | 146,595 | 196,188 |
| GOVT. DENTAL COLLEGE & HOSP. MUMBAI | Maharashtra | State Govt (15% AIQ) | 9,094 | 33,047 | 8 | 37,507 | 35,963 | 154,379 | 200,550 |
| PATNA DENTAL COLLEGE & HOSPITAL PATNA | Bihar | State Govt (15% AIQ) | 28,343 | 33,370 | 4 |  | 34,138 | 153,918 |  |
| DR. R. AHMED DENT.COLL & HOSP KOLKATA | West Bengal | State Govt (15% AIQ) | 21,456 | 33,631 | 8 | 36,001 | 36,958 | 118,617 |  |
| NORTH BENGAL DENT.COLL SUSHRUTNAGAR | West Bengal | State Govt (15% AIQ) | 26,269 | 33,670 | 3 | 35,725 | 39,073 | 118,335 | 187,116 |
| GOVT. DC & RESEARCH INSt. BELLARY | Karnataka | State Govt (15% AIQ) | 23,133 | 33,676 | 4 | 42,780 | 36,002 | 109,870 | 178,180 |
| REGIONAL DENTAL COLLEGE GUWAHATI | Assam | State Govt (15% AIQ) | 23,095 | 33,970 | 3 | 44,671 | 37,083 | 151,292 | 157,982 |
| M.G.D.C. & HOSPITAL PUDUCHERRY | Puducherry | State Govt (15% AIQ) | 18,158 | 34,019 | 7 | 45,674 | 40,574 | 142,377 | 149,321 |
| GOA DENTAL COLLEGE & HOSPITAL GOA | Goa | State Govt (15% AIQ) | 26,541 | 34,155 | 5 |  | 34,902 | 128,784 |  |
| Government DentalCollege and Hospital Paithna Bhaganbigha Rahui Nalanda Paithna- Bhaganbigha | Bihar | State Govt (15% AIQ) | 23,486 | 34,466 | 5 | 37,599 | 38,397 | 157,338 | 188,920 |
| GOVT. DENTAL COLLEGE SHIMLA | Himachal Pradesh | State Govt (15% AIQ) | 22,527 | 34,576 | 3 | 37,924 | 36,033 | 146,316 | 190,648 |
| Dr. Ziauddin Ahmed Dental College and Hospital ALIGARH | Uttar Pradesh | Central Institute | 18,798 | 34,585 | 16 |  |  |  |  |
| PB. GOVT. DENTAL COLLEGE & HOSP AMRITSAR | Punjab | State Govt (15% AIQ) | 32,294 | 34,944 | 3 | 40,553 | 37,408 | 127,028 |  |
| Government Dental College Hyderabad GOVERNMENT DENTAL COLLEGE AND HOSPITAL | Telangana | State Govt (15% AIQ) | 28,020 | 35,615 | 5 | 40,573 | 39,328 | 148,344 | 187,445 |
| Indira Gandhi Govt. Dental College Jammu | Jammu And Kashmir | State Govt (15% AIQ) | 16,472 | 35,974 | 4 | 44,677 | 41,359 | 143,902 | 160,684 |
| Government Dental College Silchar | Assam | State Govt (15% AIQ) | 28,093 | 36,421 | 3 | 45,338 | 40,319 | 149,010 | 161,821 |
| Jawaharlal Nehru Institute of Dental Sciences Imphal | Manipur | State Govt (15% AIQ) | 31,071 | 36,801 | 3 | 45,112 | 41,398 | 134,040 |  |
| Govt Dental College RIMS Kadapa PRINCIPAL GOVT DENTAL COLLEGE | Andhra Pradesh | State Govt (15% AIQ) | 32,342 | 37,200 | 6 | 46,719 | 41,141 | 146,583 | 175,702 |
| GOVT. DENTAL COLLEGE RAIPUR | Chhattisgarh | State Govt (15% AIQ) | 25,917 | 37,526 | 5 | 40,426 | 39,237 | 153,063 | 202,317 |
| Government Dental College Dibrugarh I Lane | Assam | State Govt (15% AIQ) | 37,659 | 38,223 | 4 |  | 38,827 | 160,911 |  |
| ESIC Dental College and Hospital ESIC Hospital | Delhi (NCT) | IP University | 30,213 | 44,692 | 21 | 59,098 | 61,133 | 170,646 | 275,047 |
| ESIC Dental College Gulbarga | Karnataka | ESIC | 37,286 | 50,842 | 10 | 65,281 | 64,809 | 220,144 | 522,520 |
| Manipal College of Dental Sce. Manipal | Karnataka | Deemed University | 63,685 | 275,626 | 100 |  |  |  |  |
| Manipal College of Dental Science Mangalore | Karnataka | Deemed University | 58,634 | 359,130 | 100 |  |  |  |  |
| Amrita School of Dentistry Kochi | Kerala | Deemed University | 134,431 | 386,750 | 47 |  |  |  |  |
| AB Shetty Memorial Inst. of Dental Sce. Mangaluru | Karnataka | Deemed University | 86,348 | 484,015 | 97 |  |  |  |  |
| Saveetha Dental College Chennai | Tamil Nadu | Deemed University | 14,725 | 524,471 | 99 |  |  |  |  |
| Sri Ramachandra Dental and Hospt. Chennai | Tamil Nadu | Deemed University | 104,481 | 527,087 | 90 |  |  |  |  |
| Bharati Vidyapeeth DU Dental College and Hospt. Pune | Maharashtra | Deemed University | 79,567 | 533,032 | 85 |  |  |  |  |
| SRM Dental College Chennai | Tamil Nadu | Deemed University | 80,177 | 535,578 | 100 |  |  |  |  |
| JSS Dental College Mysuru | Karnataka | Deemed University | 146,297 | 565,318 | 100 |  |  |  |  |
| KLE VK Inst. of Dental Scie. Belagavi KLE V.K. Institute of Dental Sciences | Karnataka | Deemed University | 131,697 | 581,184 | 95 |  |  |  |  |
| Dr. DY Patil Dental College and Hosp. Pune Sant Tukaram Nagar | Maharashtra | Deemed University | 57,347 | 591,456 | 95 |  |  |  |  |
| Rural Dental College Loni | Maharashtra | Deemed University | 161,950 | 599,324 | 85 |  |  |  |  |
| SRM Katt. Dental College and Hospt. Chennai SRM NAGAR POTHERI KATTANKULATHUR KANCHIPURAM | Tamil Nadu | Deemed University | 113,821 | 617,769 | 100 |  |  |  |  |
| Sri Siddhartha DentalCollege Tumkur | Karnataka | Deemed University | 355,751 | 683,300 | 34 |  |  |  |  |
| Dr. DY Patil Dental College and Hosp. Navi Mumbai Dr. D. Y. Patil Vidyanagar | Maharashtra | Deemed University | 109,624 | 688,701 | 98 |  |  |  |  |
| BVDU Dental College and Hospital Navi Mumbai | Maharashtra | Deemed University | 204,783 | 697,340 | 90 |  |  |  |  |
| MM College of Dental Scie. and Res. Mullana | Haryana | Deemed University | 86,335 | 697,765 | 100 |  |  |  |  |
| Yenepoya Dental College Yenepoya | Karnataka | Deemed University | 161,097 | 720,900 | 50 |  |  |  |  |
| School of Dental Sciences and KIMSDU Karad | Maharashtra | Deemed University | 280,630 | 722,952 | 95 |  |  |  |  |
| Santosh Dental College and Hospital Ghaziabad | Uttar Pradesh | Deemed University | 120,037 | 731,183 | 100 |  |  |  |  |
| BVDU Dental College and Hospital Sangli | Maharashtra | Deemed University | 148,742 | 753,902 | 90 |  |  |  |  |
| Institute of Dental Sciences Bhubaneswar | Odisha | Deemed University | 124,027 | 774,006 | 100 |  |  |  |  |
| K M Shah Dental Collegel SumanDeep Vidyapeeth Vadodara | Gujarat | Deemed University | 225,736 | 788,470 | 75 |  |  |  |  |
| MANAV RACHNA DENTAL COLLEGE FARIDABAD SECTOR - 43 | Haryana | Deemed University | 71,447 | 798,698 | 98 |  |  |  |  |
| Sharad Pawar Dental College and Hospital Wardha | Maharashtra | Deemed University | 110,414 | 827,913 | 100 |  |  |  |  |
| Meenakshi Ammal Dental College and Host. Chennai1 | Tamil Nadu | Deemed University | 115,459 | 828,185 | 100 |  |  |  |  |
| Indira Gandhi Institute of Dental Sciences Pondicherry | Puducherry | Deemed University | 183,562 | 847,005 | 100 |  |  |  |  |
| Kalinga Institute of Dental Sciences Bhubaneswar | Odisha | Deemed University | 160,338 | 875,884 | 100 |  |  |  |  |
| Sree Balaji Dental College and Hospital Chennai | Tamil Nadu | Deemed University | 51,851 | 891,273 | 100 |  |  |  |  |
| Malla Reddy Institute of Dental Sciences Hyderabad | Telangana | Deemed University | 301,192 | 914,227 | 100 |  |  |  |  |
| Malla Reddy Dental College For Women Hyderabad | Telangana | Deemed University | 380,425 | 938,464 | 100 |  |  |  |  |
| SATHYABAMA UNIV. Dental College and Hospt. Chennai JEPPIAAR NAGAR RAJIV GANDHI SALAI | Tamil Nadu | Deemed University | 93,908 | 943,205 | 100 |  |  |  |  |
| VMS Dental College Salem | Tamil Nadu | Deemed University | 139,403 | 947,032 | 100 |  |  |  |  |
| Thaimoogambigai Dental College and Hsopt. Chennai Golden George Nagar | Tamil Nadu | Deemed University | 379,386 | 988,990 | 100 |  |  |  |  |

## Section 3 — Karnataka (KEA) MBBS — Round 1, Round 2-Final, 2025

All 66 KEA-counselled MBBS colleges, sorted by Round-2-Final GM (General Merit) closing rank. `R1 GM Close` lets you see how much a college's cutoff loosened between Round 1 and the final Round 2 list — typically a 2–3x jump in AIR as upgrades free up seats. `OPN`/`GMP`/`NRI` are private-college fee-tier seats (see glossary above); blank means that college has no seats of that type. The `-G` columns (CAT1-G, 2A-G, 2B-G, 3A-G, 3B-G, SC-G, ST-G) are each category's state-wide (non-regional) closing rank — see the glossary for the fuller set of regional/horizontal codes available in the raw source file.

| College | Type | R1 GM Close | R2-Final GM Open | R2-Final GM Close | R2-Final GM Seats | OPN Close | GMP Close | NRI Close | CAT1-G Close | 2A-G Close | 2B-G Close | 3A-G Close | 3B-G Close | SC-G Close | ST-G Close |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Bangalore Medical College | Government | 1,299 | 398 | 3,025 | 65 |  |  |  | 8,279 | 8,560 | 6,286 | 5,062 | 6,485 | 34,512 | 58,188 |
| Kasturba Medical College | Deemed/Private University | 3,558 | 864 | 6,786 | 17 |  |  |  | 37,727 | 34,768 | 10,894 | 16,075 | 28,530 | 130,611 | 149,851 |
| Shri Atal Bihari Vajpayee Institute of Medical Science | Government | 3,487 | 3,240 | 7,669 | 49 |  |  | 678,473 | 15,133 | 21,184 | 10,962 | 10,141 | 13,810 | 77,502 | 86,584 |
| Mysore Medical College | Government | 4,053 | 2,403 | 8,394 | 63 |  |  | 828,744 | 23,258 | 17,401 | 13,762 | 11,270 | 12,273 | 54,677 | 83,212 |
| M.S.Ramaiah Medical College | Deemed/Private University | 6,905 | 3,584 | 11,776 | 18 | 109,603 | 168,859 | 1,021,201 | 30,410 | 27,021 | 15,405 | 12,775 | 33,259 | 104,025 | 130,881 |
| ESI Medical College (Rajajinagar) | Government | 6,404 | 5,700 | 12,937 | 18 |  |  |  | 29,639 | 24,504 | 14,880 | 14,026 | 16,062 | 91,999 | 102,843 |
| Karnataka Institute of Medical Sciences | Government | 8,343 | 4,941 | 13,488 | 52 |  |  |  | 25,047 | 22,004 | 25,199 | 16,855 | 17,780 | 69,382 | 71,029 |
| Jagadguru Sri Shivarathreeswara Medical College | Deemed/Private University | 7,669 | 12,366 | 14,777 | 4 |  |  |  |  | 25,853 | 41,760 |  | 26,668 | 86,328 |  |
| Mandya Institute of Medical Sciences | Government | 11,478 | 8,509 | 15,588 | 38 |  |  |  | 27,441 | 31,310 | 22,093 | 17,139 | 24,421 | 100,335 | 101,343 |
| Kempegowda Institute of Medical Sciences | Private | 11,641 | 4,851 | 18,774 | 31 | 39,887 | 75,782 | 1,048,204 | 44,680 | 42,656 | 35,381 | 20,476 | 33,400 | 131,160 | 148,245 |
| Shimoga Institute of Medical Sciences | Government | 16,967 | 8,198 | 21,676 | 40 |  |  |  | 33,996 | 34,800 | 33,625 | 22,124 | 23,356 | 100,436 | 102,105 |
| Father Muller Institute of Med. Education & Research | Minority (Linguistic/Religious) | 13,394 | 9,062 | 21,705 | 14 | 48,544 | 87,314 | 1,098,513 | 64,620 | 59,619 | 27,608 | 28,879 | 35,402 | 178,861 | 206,841 |
| Hassan Institute of Medical Sciences | Government | 16,221 | 5,949 | 21,862 | 53 |  |  | 1,025,216 | 36,190 | 37,452 | 40,585 | 23,071 | 28,249 | 121,515 | 112,714 |
| Belgaum Institute of Medical Sciences | Government | 16,260 | 2,968 | 23,365 | 53 |  |  |  | 40,892 | 31,760 | 32,791 | 28,220 | 27,202 | 106,735 | 105,100 |
| Gulbarga Institute of Medical Sciences | Government | 17,229 | 3,611 | 23,671 | 16 |  |  |  | 49,237 | 41,621 | 39,866 | 30,756 | 37,248 | 106,446 | 106,896 |
| Vijayanagar Institute of Medical Sciences | Government | 15,845 | 13,693 | 23,690 | 21 |  |  | 445,222 | 38,301 | 36,302 | 40,115 | 24,429 | 32,646 | 93,239 | 85,547 |
| Vydehi Institute of Medical Science and Research Centre | Minority (Linguistic/Religious) | 16,640 | 13,589 | 23,885 | 19 | 48,896 | 78,764 |  |  | 50,094 |  |  | 47,098 | 156,021 | 173,716 |
| Jawaharalal Nehru Medical College | Not specified in source seat matrix (seats added later in the cycle) |  | 21,665 | 25,068 | 3 |  |  |  |  | 62,075 |  | 42,413 | 47,848 | 179,570 |  |
| ESI Medical College (Sedam Road) | Government | 18,637 | 16,911 | 28,962 | 7 |  |  |  | 48,148 | 42,607 | 35,987 |  | 37,755 | 132,887 | 111,990 |
| K.S.Hegde Medical Academy | Deemed/Private University | 20,155 | 18,182 | 29,496 | 12 |  |  |  | 42,095 | 52,241 | 52,525 | 36,952 |  | 195,611 | 169,590 |
| SDM College of Medical Sciences and Hospital | Deemed/Private University | 24,206 | 11,698 | 30,648 | 17 | 144,853 | 199,443 | 792,762 | 58,883 | 49,350 | 49,234 | 38,770 | 36,126 | 167,193 | 158,186 |
| BGS Global Institute of Medical Sciences | Private | 22,116 | 18,376 | 31,415 | 20 | 58,647 | 85,836 | 972,113 |  | 56,583 |  |  |  | 173,926 | 180,342 |
| Jaya Jagadguru Murugharajendra Medical College | Private | 24,255 | 1,577 | 31,492 | 30 | 64,695 | 89,905 |  | 69,560 | 55,030 | 48,988 | 37,833 | 33,465 | 172,200 | 174,064 |
| Chamarajanagar Institute of Medical Science | Government | 23,743 | 17,963 | 31,696 | 42 |  |  |  | 41,713 | 49,014 | 41,554 | 33,244 | 35,995 | 140,555 | 125,544 |
| Gadag Institute of Medical Sciences | Government | 27,154 | 22,891 | 32,257 | 42 |  |  |  | 50,235 | 43,592 | 49,466 | 36,750 | 34,131 | 128,129 | 124,968 |
| Bidar Institute of Medical Sciences | Government | 28,765 | 14,402 | 37,203 | 13 |  |  |  | 69,117 | 62,130 | 58,433 | 43,839 | 41,063 | 138,293 | 138,415 |
| Kodagu Institute of Medical Sciences | Government | 31,234 | 22,148 | 38,075 | 43 |  |  |  | 54,995 | 50,335 | 55,241 | 39,276 | 47,798 | 157,831 | 161,454 |
| Chikkaballapura Institute of Medical Science | Government | 29,432 | 17,051 | 38,361 | 39 |  |  | 883,348 | 48,596 | 55,837 | 47,736 | 41,412 | 43,915 | 156,848 | 159,742 |
| Koppal Institute of Medical Sciences | Government | 29,397 | 29,061 | 38,538 | 15 |  |  |  | 57,534 | 55,956 | 54,528 | 38,807 | 41,538 | 142,751 | 145,290 |
| Raichur Institute of Medical Sciences | Government | 27,935 | 12,285 | 39,240 | 19 |  |  |  | 51,554 | 53,301 | 55,042 | 40,165 | 44,204 | 136,326 | 109,357 |
| A.J.Institute of Medical Sciences | Minority (Linguistic/Religious) | 29,055 | 21,523 | 39,539 | 17 | 65,810 | 93,249 | 1,223,126 | 54,505 | 69,280 | 47,380 | 41,586 | 48,190 | 188,492 | 188,928 |
| Yenepoya Medical College | Deemed/Private University | 33,597 | 25,040 | 41,209 | 12 |  |  |  | 74,985 | 78,325 | 46,225 | 67,672 | 41,973 | 210,305 | 212,423 |
| Karwar Institute of Medical Science | Government | 34,382 | 24,187 | 41,651 | 41 |  |  |  | 64,589 | 60,034 | 57,997 | 46,312 | 44,475 | 164,172 | 159,888 |
| Dr. B.R. Ambedkar Medical College | Private | 31,037 | 16,464 | 41,969 | 20 | 60,284 | 94,573 | 502,184 | 73,046 | 70,258 | 44,899 | 47,598 | 58,044 | 161,342 | 176,846 |
| PES University Institute of Medical Sceinces and Research | Deemed/Private University | 30,688 | 24,914 | 44,066 | 19 | 243,417 | 329,680 |  | 80,276 | 72,674 | 62,147 | 50,145 | 61,566 | 191,548 | 211,218 |
| Chikkamagaluru Institute of Medical Sciences | Government | 36,665 | 23,779 | 45,629 | 41 |  |  |  | 65,561 | 63,051 | 55,781 | 46,198 | 52,229 | 168,758 | 151,347 |
| Dr. Chandramma Dayananda Sagar Institute of Medical Education | Deemed/Private University | 38,287 | 31,630 | 48,595 | 26 | 301,666 | 390,742 |  | 78,059 | 81,160 | 61,071 | 53,409 | 63,529 | 210,431 | 211,776 |
| Haveri Institute of Medical Sciences | Government | 41,063 | 38,338 | 49,827 | 41 |  |  |  | 64,736 | 67,420 | 62,178 | 52,537 | 52,768 | 172,363 | 172,444 |
| Shymanuru Shivashankarappa Institute Of Medical Sciences | Private | 41,425 | 31,990 | 51,850 | 26 | 75,388 | 98,366 | 628,262 | 76,434 | 78,872 | 53,128 | 54,297 | 54,666 | 195,029 | 197,048 |
| Yadgiri Institute of Medical Sciences | Government | 43,839 | 43,712 | 52,598 | 15 |  |  |  | 58,993 | 72,154 | 59,029 | 55,593 | 53,986 | 183,196 | 176,007 |
| Adichunchanagiri Institute of Medical Sciences | Deemed/Private University | 42,735 | 33,346 | 54,541 | 31 | 311,795 | 425,709 |  | 80,936 | 76,320 | 71,762 | 57,653 | 60,363 | 188,870 | 199,813 |
| Chitradurga Medical College and Research Institute | Government | 44,690 | 32,831 | 55,005 | 40 |  |  |  | 67,350 | 73,334 | 59,756 | 57,621 | 58,806 | 187,728 | 176,078 |
| Siddaganga Medical College and Research Institute | Private | 43,895 | 11,988 | 57,061 | 26 | 91,032 | 102,786 | 1,264,973 | 81,471 | 79,279 | 77,189 | 58,695 | 61,421 | 209,078 | 195,978 |
| Sri Madhusudan Sai Institute of Medical Sciences and Research | Deemed/Private University | 52,568 | 20,671 | 58,778 | 8 | 230,080 | 387,455 | 651,565 | 83,491 | 87,142 | 81,864 |  | 76,093 | 204,339 | 173,341 |
| M.V.J.Medical College and Research Hospital | Minority (Linguistic/Religious) | 43,416 | 26,124 | 59,196 | 16 | 69,920 | 99,030 |  |  | 76,672 |  | 59,344 | 64,623 | 211,657 | 187,442 |
| Subbaiah Institute of Medical Science | Minority (Linguistic/Religious) | 50,204 | 40,916 | 59,833 | 16 | 99,719 | 113,892 |  | 82,182 | 82,689 | 78,483 | 60,597 | 63,624 | 215,359 | 207,949 |
| BGS Medical College and Hospital(BGS MCH) Nagarur Dasanapura Hobli Banglore North | Deemed/Private University | 48,336 | 35,067 | 59,981 | 28 | 406,521 | 449,182 |  | 81,020 | 84,881 | 64,065 | 61,857 | 65,126 | 213,460 | 205,333 |
| S. Nijalingappa Medical College and Research Centre | Private | 49,342 | 16,988 | 60,347 | 32 | 91,013 | 113,628 |  | 78,706 | 77,765 | 62,751 | 61,489 | 62,410 | 211,587 | 185,762 |
| Sapthagiri Institute of Medical Sciences | Deemed/Private University | 47,164 | 15,075 | 61,306 | 33 | 350,149 | 436,420 |  | 80,496 | 85,473 | 73,725 | 63,926 | 64,897 | 210,540 | 205,609 |
| Mahadevappa Rampure Medical College | Private | 46,847 | 50,067 | 61,966 | 8 | 86,635 | 98,453 |  | 75,761 | 79,744 | 64,392 | 62,206 | 63,700 | 196,756 | 199,398 |
| Sri Basaveshwara Medical College and Hospital | Private | 54,787 | 54,787 | 63,403 | 19 | 97,622 | 120,787 |  | 89,601 | 87,739 | 76,648 | 68,916 | 66,060 | 219,567 | 205,944 |
| SRI CHAMUNDESHWARI MEDICAL COLLEGE | Minority (Linguistic/Religious) | 55,573 | 48,693 | 64,636 | 13 | 104,008 | 116,338 |  | 90,629 | 80,244 | 78,127 | 66,617 | 75,226 | 215,513 | 219,568 |
| Navodaya Medical College | Minority (Linguistic/Religious) | 55,289 | 54,651 | 65,848 | 6 | 103,797 | 125,930 | 1,151,753 |  | 84,505 | 78,120 | 72,775 | 75,988 | 209,191 | 190,403 |
| The Oxford Medical College Hospital and Research Center | Minority (Linguistic/Religious) | 52,723 | 46,239 | 66,367 | 16 | 85,712 | 109,560 |  | 88,636 | 87,683 | 74,656 | 66,713 | 72,714 | 218,168 | 214,077 |
| K.Venkataramana Gowda Medical College and Hospital | Private | 55,213 | 48,237 | 67,234 | 14 | 107,163 | 125,266 |  | 92,587 | 88,767 | 81,621 | 68,286 | 72,403 | 219,533 | 215,970 |
| East Point College of Medical Sciences and Research Center | Private | 51,850 | 51,628 | 67,539 | 26 | 92,210 | 115,621 | 1,146,921 | 90,582 | 89,937 | 76,076 | 69,668 | 71,754 | 219,262 | 209,214 |
| Shridevi Institute of Medical Sciences and Research Hospital | Private | 54,983 | 52,924 | 67,561 | 26 | 102,320 | 119,750 |  | 93,250 | 86,036 | 76,345 | 68,036 | 70,778 | 223,629 | 208,750 |
| Akash Institute of Medical Sciences and Research Centre | Minority (Linguistic/Religious) | 52,710 | 43,036 | 69,660 | 20 | 84,555 | 115,206 |  | 93,336 | 89,392 | 76,294 | 70,829 | 71,997 | 222,185 | 212,686 |
| Khaja Bande Navaz Institute Of Medical Sciences | Deemed/Private University | 58,455 | 48,590 | 70,754 | 6 | 157,512 | 209,004 |  | 97,781 | 92,397 | 72,048 |  |  | 212,769 |  |
| Kanachur Institute of Medical Sciences and Research Centre | Minority (Linguistic/Religious) | 57,790 | 50,734 | 71,059 | 16 | 105,141 | 123,624 | 1,004,653 | 98,704 | 92,825 | 78,447 | 71,976 | 76,409 | 226,772 | 219,682 |
| Srinivasa Institute of Medical Research Center Srinivas Nagar Mangalore | Deemed/Private University | 57,583 | 43,243 | 71,375 | 26 | 411,057 | 479,986 |  | 88,431 | 91,746 | 77,032 | 71,677 | 76,011 | 227,532 | 220,105 |
| S R Patil Medical College Hospital and Research Center | Private | 57,813 | 65,663 | 71,996 | 14 | 106,113 | 129,260 |  | 97,461 | 91,153 | 75,776 | 72,969 | 77,526 | 218,380 | 206,375 |
| Farookh Academy of Medical Education Hospital and Research Institute | Not specified in source seat matrix (seats added later in the cycle) |  | 41,529 | 72,690 | 13 | 109,892 | 127,996 |  | 86,475 | 91,294 | 81,263 | 73,326 | 77,967 | 225,235 | 212,386 |
| Al-Ameen Medical College | Minority (Linguistic/Religious) | 58,957 | 32,889 | 73,321 | 12 | 95,868 | 128,199 |  | 98,018 | 92,247 | 76,358 | 73,735 | 78,231 | 221,329 | 213,459 |
| Jagadguru Gangadhar Mahaswamigalu Moorusavirmath Medical College | Deemed/Private University | 60,728 | 55,809 | 73,808 | 13 |  |  |  | 99,491 | 89,450 |  |  | 76,513 | 228,284 | 229,487 |
| St John Medical College | Minority (Linguistic/Religious) |  |  |  | 0 | 13,706 | 16,608 |  |  |  |  |  |  |  |  |

## Section 4 — Karnataka (KEA) Dental / BDS — Round 2, 2025

All 39 KEA-counselled dental colleges, sorted by GM closing rank.

| College | GM Open | GM Close | GM Seats | OPN Close | GMP Close | NRI Close | SC-G Close | ST-G Close |
|---|---|---|---|---|---|---|---|---|
| Government Dental College | 64,821 | 86,982 | 16 |  |  |  | 235,796 | 256,366 |
| M.S.Ramaiah Univerisity of Applied Sciences | 79,646 | 90,359 | 6 | 288,648 | 390,981 | 1,045,091 | 255,958 | 300,317 |
| Government Dental College and Research Institute | 87,252 | 100,132 | 5 |  |  |  | 249,919 | 252,109 |
| S.B.Patil Institute for Dental Sciences and Research | 110,198 | 110,198 | 1 | 244,174 | 351,376 |  | 414,851 |  |
| Rashtreeya Vidyalaya Dental College | 84,321 | 110,729 | 6 | 337,330 | 559,699 | 1,017,892 | 258,224 | 301,660 |
| Sri Dharmasthala Manjunatheswara Dental College | 78,113 | 111,477 | 13 | 351,213 | 553,338 | 958,449 | 274,363 | 267,293 |
| Employees State Insurance Corporation Dental College | 90,941 | 112,709 | 5 |  |  |  |  | 279,761 |
| A.J. Institute of Dental Sciences | 79,726 | 118,338 | 7 | 453,698 | 948,105 | 1,180,168 | 325,925 | 375,618 |
| Dayananda Sagar College of Dental Sciences | 99,168 | 121,169 | 4 | 425,572 | 684,143 |  | 231,857 | 275,351 |
| Vokkaligara Sangha Dental College and Hospital | 88,886 | 123,491 | 11 | 422,736 | 641,719 | 549,056 | 281,978 | 312,532 |
| Bapuji Dental College and Hospital | 84,754 | 129,778 | 12 | 293,656 | 384,220 |  | 285,657 | 316,688 |
| Vydehi Institute of Dental Sciences and Research Centre | 107,720 | 130,834 | 5 | 454,047 | 825,981 |  | 274,077 |  |
| K L E S Institute of Dental Sciences | 92,708 | 133,123 | 7 | 303,812 | 451,043 |  | 290,437 | 317,340 |
| Dr.M.R.Ambedkar Dental College and Hospital | 95,551 | 133,339 | 13 | 459,403 | 642,352 | 1,239,988 | 269,606 | 332,144 |
| FAROOQUIA DENTAL COLLEGE | 85,179 | 138,745 | 3 | 328,347 | 435,976 | 839,828 | 315,721 |  |
| BGS Global Institute of Dental Sciences and Hospital | 92,309 | 142,442 | 5 | 360,987 | 577,093 |  | 235,411 | 411,989 |
| Raja Rajeshwari Dental College and Hospital | 108,740 | 142,494 | 9 | 339,816 | 695,731 | 1,036,133 | 293,145 | 449,890 |
| Bangalore Institute of Dental Sciences & Hospital | 130,734 | 142,845 | 3 | 386,658 | 733,467 |  | 239,681 | 339,143 |
| Hyderabad Karnataka Education Societies Dental College | 108,933 | 145,930 | 4 | 359,443 | 412,558 |  | 294,300 | 344,378 |
| Oxford Dental College | 132,064 | 152,310 | 8 | 523,446 | 924,009 |  | 275,032 | 457,665 |
| Sri Rajiv Gandhi Dental College | 133,332 | 155,422 | 10 | 740,460 | 926,974 |  | 294,005 | 374,355 |
| Maratha Mandal Dental College | 123,389 | 160,246 | 5 | 651,563 | 817,149 |  | 269,742 | 516,654 |
| Krishnadevaraya College of Dental Sciences | 130,037 | 161,344 | 6 | 436,175 | 629,744 | 1,011,815 | 304,416 |  |
| College of Dental Sciences | 93,185 | 162,092 | 12 | 409,902 | 586,212 |  | 348,295 |  |
| Al Badar Dental College and Hospital | 130,085 | 167,588 | 3 | 461,413 | 528,000 |  | 414,176 |  |
| Venkateswara Dental College | 115,159 | 169,729 | 7 | 700,737 | 1,005,785 | 868,007 | 310,571 | 325,535 |
| PM Nadagowda Memorial Dental College and Hospital | 115,994 | 171,469 | 13 | 480,446 | 791,528 |  | 378,435 | 346,304 |
| Coorg Institute of Dental Sciences | 111,578 | 172,103 | 5 | 642,144 | 1,130,638 | 1,047,030 | 329,327 |  |
| Srinivasa Institute of Dental Science | 133,600 | 178,152 | 7 | 1,317,693 |  |  | 363,377 | 502,737 |
| Sharavathi Dental College | 89,755 | 178,847 | 11 | 646,941 | 907,086 |  | 354,347 | 436,978 |
| Sri. Hasanamba Dental College and Hospital | 98,328 | 180,509 | 5 | 521,843 | 746,779 |  | 319,873 | 421,731 |
| Subbaiah Institute of Dental Sciences | 156,976 | 183,803 | 9 | 320,481 | 637,957 |  | 361,721 | 498,654 |
| Academy of Medical Education Dental College | 146,183 | 189,766 | 2 | 378,406 | 1,172,954 |  | 383,114 |  |
| Navodaya Dental College | 174,707 | 195,560 | 4 | 423,206 | 1,018,808 |  | 301,116 | 462,933 |
| Sri Jagadguru Murugharajendra Dental College & Hospital | 181,462 | 203,031 | 6 | 615,209 | 887,898 |  | 336,259 | 505,226 |
| HKDET`S Dental College Hospital | 173,104 | 206,045 | 3 | 441,502 | 662,208 |  | 411,774 |  |
| K.G.F. College of Dental Sciences | 192,840 | 209,596 | 4 | 412,256 | 1,265,792 |  | 319,758 |  |
| K.Venkataramana Gowda Dental College Hospital and Research Centre | 130,755 | 210,522 | 11 | 715,332 | 1,267,919 |  | 366,358 | 484,623 |
| Al-Ameen Dental College | 146,337 | 214,021 | 3 | 343,440 | 373,475 |  | 362,896 | 606,531 |

## Section 5 — Karnataka MBBS Seat Matrix: 2025 vs 2026

KEA-counselled MBBS seat counts per college (excludes minority-quota-only institutions like St John's, which run 0 seats through general KEA counselling), split by Kalyana-Karnataka (HK, Article 371(J)) vs Rest-of-Karnataka (RK) regional pools, with year-on-year delta. Useful for spotting colleges whose intake grew or shrank materially between the two cycles — a college adding 30+ seats (e.g. Mysore Medical College, Karnataka Medical College Hubballi, Mandya IMS, Hassan IMS all added 30+ seats for 2026) will likely see its closing rank loosen even if its underlying popularity is unchanged, so don't read a rank shift at these colleges as a pure demand signal without checking this table first.

**Note:** college names in this table come from a different source file than Sections 3–4 and were not cross-merged (see Caveats above) — match colleges by eye, not by exact string.

| Code | College | Type | KEA Seats 2025 | KEA Seats 2026 | Delta | HK 2025 | HK 2026 | RK 2025 | RK 2026 |
|---|---|---|---|---|---|---|---|---|---|
| M001 | Bangalore Medical College and Research Institute, Bangalore | C | 200 | 201 | 1 | 16 | 17 | 184 | 184 |
| M021 | Mysore Medical College and Research Instt. (Prev.name Government Medical College), Mysore | C | 161 | 192 | 31 | 13 | 16 | 148 | 176 |
| M041 | Vijaynagar Institute of Medical Sciences, Bellary | C | 160 | 192 | 32 | 112 | 135 | 48 | 57 |
| M031 | Karnataka Medical College and Research Institute, Hubballi, Karnataka | C | 158 | 192 | 34 | 12 | 16 | 146 | 176 |
| M082 | Shri Atal Bihari Vajapayee Medical College and Research Institute, Bengaluru, | C | 118 | 154 | 36 | 10 | 13 | 108 | 141 |
| M072 | Gulbarga Institute of Medical Sciences, Gulbarga | C | 120 | 154 | 34 | 84 | 108 | 36 | 46 |
| M044 | Bidar Institute of Medical Sciences, Bidar | C | 120 | 154 | 34 | 84 | 108 | 36 | 46 |
| M037 | Belagavi Institute of Medical Sciences, Belagavi | C | 119 | 153 | 34 | 10 | 12 | 109 | 141 |
| M073 | Koppal Institute of Medical Sciences, Koppal | C | 119 | 153 | 34 | 84 | 107 | 35 | 46 |
| M045 | Raichur Institute of Medical Sciences, Raichur | C | 120 | 153 | 33 | 84 | 107 | 36 | 46 |
| M024 | Mandya Institute of Medical Sciences, Mandya | C | 118 | 153 | 35 | 10 | 12 | 108 | 141 |
| M074 | K.H. Patil Institute of Medical Sciences (previously Gadag Institute of Medical Sciences, Mallasamudra, Mulgund Road, Gadag) | C | 121 | 152 | 31 | 9 | 12 | 112 | 140 |
| M025 | Hassan Institute of Medical Sciences, Hassan | C | 120 | 152 | 32 | 10 | 12 | 110 | 140 |
| M076 | Karwar Institute of Medical Sciences, Karwar | C | 120 | 151 | 31 | 10 | 12 | 110 | 139 |
| M087 | Yadgiri Institute of Medical Sciences, Yadgiri | C | 119 | 121 | 2 | 83 | 84 | 36 | 37 |
| M086 | Haveri Institute of Medical Sciences, Haveri | C | 119 | 121 | 2 | 10 | 10 | 109 | 111 |
| M063 | Shimoga Institute of Medical Sciences, Shimoga | C | 120 | 120 | 0 | 9 | 9 | 111 | 111 |
| M077 | Kodagu Institute of Medical Sciences, Kodagu | C | 120 | 119 | -1 | 9 | 9 | 111 | 110 |
| M085 | Chikkamagaluru Institute of Medical Sciences, Chikkamagaluru | C | 118 | 119 | 1 | 9 | 10 | 109 | 109 |
| M075 | Chamrajanagar Institute of Medical Sciences, Karnataka | C | 119 | 119 | 0 | 10 | 9 | 109 | 110 |
| M092 | Chitradurga Medical College and Research Institute | C | 119 | 118 | -1 | 10 | 9 | 109 | 109 |
| M084 | Nandi Medical College and Research Institute Chikkaballapura (Chikkaballapura Institute of Medical Sciences Chikkaballapura ) | C | 78 | 113 | 35 | 6 | 9 | 72 | 104 |
| M094 | PES University Institute of Medical Sciences and Reseach Bangalore | C | 37 | 95 | 58 | 3 | 7 | 34 | 88 |
| M069 | Shridevi Institute of Medical Sciences & Research Hospital, Tumkur | C | 56 | 95 | 39 | 4 | 7 | 52 | 88 |
| M081 | East Point College of Medical Sciences & Research Centre, Bangalore | C | 56 | 95 | 39 | 4 | 8 | 52 | 87 |
| M065 | Srinivas Institute of Medical Research Centre, Srinivasnagar, Mangalore | C | 76 | 95 | 19 | 6 | 7 | 70 | 88 |
| M035 | S. Nijalingappa Medical College & HSK Hospital & Research Centre, Bagalkot | C | 94 | 95 | 1 | 8 | 7 | 86 | 88 |
| M095 | BGS Medical College and Hospital Bengaluru, Karnataka | C | 56 | 95 | 39 | 4 | 8 | 52 | 87 |
| M042 | Mahadevappa Rampure Medical College, Kalaburagi, Gulbarga | C | 57 | 95 | 38 | 40 | 66 | 17 | 29 |
| M023 | Adichunchanagiri Institute of Medical Sciences, Bellur | C | 94 | 95 | 1 | 8 | 8 | 86 | 87 |
| M003 | Kempegowda Institute of Medical Sciences, Bangalore | C | 94 | 94 | 0 | 8 | 7 | 86 | 87 |
| M062 | S S Institute of Medical Sciences& Research Centre, Davangere | C | 76 | 94 | 18 | 6 | 8 | 70 | 86 |
| M068 | BGS Global Institute of Medical Sciences, Bangalore | C | 56 | 94 | 38 | 4 | 8 | 52 | 86 |
| M064 | Sapthagiri Institute of Medical Sciences & Research Centre, Bangalore | C | 95 | 94 | -1 | 8 | 7 | 87 | 87 |
| M090 | Siddaganga Medical College and Research Institute, Tumakuru | C | 56 | 94 | 38 | 5 | 8 | 51 | 86 |
| M061 | JJM Medical College, Davangere | C | 92 | 93 | 1 | 7 | 8 | 85 | 85 |
| M004 | M S Ramaiah Medical College, Bangalore | C | 57 | 76 | 19 | 4 | 6 | 53 | 70 |
| M083 | Dr. Chandramma Dayananda Sagar Instt. of Medical Education & Research, Harohalli, Hubli | C | 57 | 75 | 18 | 5 | 6 | 52 | 69 |
| M071 | The Oxford Medical College, Hospital & Research Centre, Bangalore | C | 47 | 60 | 13 | 4 | 5 | 43 | 55 |
| M043 | Navodaya Medical College, Raichur | C | 47 | 60 | 13 | 33 | 42 | 14 | 18 |
| M079 | Kanachur Institute of Medical Sciences, Mangalore | C | 48 | 59 | 11 | 4 | 4 | 44 | 55 |
| M009 | Vydehi Institute Of Medical Sciences & Research Centre, Bangalore | C | 59 | 59 | 0 | 5 | 5 | 54 | 54 |
| M008 | MVJ Medical College and Research Hospital, Bangalore | C | 46 | 59 | 13 | 3 | 5 | 43 | 54 |
| M010 | A J Institute of Medical Sciences & Research Centre, Mangalore | C | 48 | 58 | 10 | 3 | 4 | 45 | 54 |
| M067 | Subbaiah Institute of Medical Sciences, Shimoga, Karnataka | C | 46 | 57 | 11 | 4 | 5 | 42 | 52 |
| M054 | K V G Medical College, Sullia | C | 38 | 56 | 18 | 3 | 5 | 35 | 51 |
| M020 | Basaveswara Medical College and Hospital, Chitradurga | C | 56 | 56 | 0 | 5 | 4 | 51 | 52 |
| M036 | SDM College of Medical Sciences & Hospital, Sattur, Dharwad | C | 56 | 56 | 0 | 4 | 5 | 52 | 51 |
| M002 | Dr BR Ambedkar Medical College, Bangalore | C | 57 | 56 | -1 | 5 | 4 | 52 | 52 |
| M097 | FAROOKH ACADEMY OF MEDICAL EDUCATION HOSPITAL AND RESEARCH INSTITUTE | C | 0 | 55 | 55 | 0 | 4 | 0 | 51 |
| M070 | Employees State Insurance Corporation Medical College, Gulbarga | C | 56 | 55 | -1 | 39 | 39 | 17 | 16 |
| M066 | Employees State Insurance Corporation Medical College, Bangalore | C | 55 | 55 | 0 | 4 | 4 | 51 | 51 |
| M051 | Kasturba Medical College, Mangalore | C | 48 | 48 | 0 | 4 | 4 | 44 | 44 |
| M091 | Sri Chamundeshwari Medical College Hospital & Research Institute | C | 35 | 47 | 12 | 2 | 3 | 33 | 44 |
| M096 | SR Patil Medical College and Hospital Distt Bagalkot | C | 37 | 37 | 0 | 3 | 3 | 34 | 34 |
| M088 | G R Medical College Hospital & Research Centre | C | 0 | 36 | 36 | 0 | 3 | 0 | 33 |
| M033 | Al-Ameen Medical College, Bijapur | C | 34 | 36 | 2 | 3 | 3 | 31 | 33 |
| M050 | Father Mullers Medical College, Mangalore | C | 34 | 36 | 2 | 3 | 3 | 31 | 33 |
| M053 | K S Hegde Medical Academy, Mangalore | C | 34 | 35 | 1 | 2 | 3 | 32 | 32 |
| M005 | Khaja Bandanawaz University - Faculty of Medical Sciences, Gulbarga | C | 35 | 34 | -1 | 24 | 24 | 11 | 10 |
| M089 | Jagadguru Gangadhar Mahaswamigalu Moorusavirmath Medical College JGMMMC | C | 35 | 34 | -1 | 3 | 2 | 32 | 32 |
| M052 | Yenepoya Medical College, Mangalore | C | 35 | 34 | -1 | 3 | 3 | 32 | 31 |
| M093 | Sri Madhusudan Sai Institute of Medical Sciences & Research, Chikballapur | C | 19 | 19 | 0 | 2 | 2 | 17 | 17 |
| M022 | JSS Medical College, Mysore | C | 10 | 12 | 2 | 1 | 1 | 9 | 11 |
| M032 | Jawaharlal Nehru Medical College, Belgaum | C | 0 | 12 | 12 | 0 | 1 | 0 | 11 |
| M078 | Akash Institute of Medical Sciences and Research Centre,DEVANAHALLI,,BANGALO RE | MINORITY (L,R) | 36 | 0 | -36 | 3 | 0 | 33 | 0 |
| M011 | St John Medical College,,Bangalore | MINORITY (L,R) | 0 | 0 | 0 | 0 | 0 | 0 | 0 |

## How agents should use this file

1. **Always state the round and year** when quoting a number from here — "2025 Round 1 AIQ" or "2025 KEA Round 2 Final," never just "the cutoff." Never present a number from this file as this year's (2026) cutoff without an explicit caveat.
2. **For "what rank do I need for college X" questions:** find the college in the relevant table, quote its closing rank(s), and explain that later rounds (for MCC) typically loosen the rank further — point to the Round 1 vs Round 2-Final columns in Section 3 (KEA) as a concrete illustration of how much movement to expect, since MCC Round 2/3/mop-up data isn't in this file.
3. **For "which colleges can I get with rank Y" questions:** scan the relevant table for rows where the closing rank is at or above Y (i.e., Y would have been admitted), and present the best few options plus a couple of "safe" options with meaningfully higher closing ranks. Prefer college's own state/domicile-eligible rows for KEA-type questions (see `MD-NEET-KB.md` Section 4 for domicile rules).
4. **For "compare college A vs B" questions:** pull both rows and compare Opening/Closing rank, seats, category spread, and (for Karnataka) ownership Type and the 2025-vs-2026 seat matrix — then defer to `MD-NEET-KB.md` for fee, bond, and reputation context this file doesn't carry.
5. **For category-specific questions (SC/ST/OBC/EWS/2A/2B/3A/3B):** use the category-specific closing-rank column directly; don't extrapolate a reserved-category cutoff from the Open/GM column — the gap between categories varies widely by college and is not a fixed offset.
6. **If a college or category isn't in this file** (e.g., a state other than Karnataka's state-quota list, or a niche KEA special category), say so plainly and fall back to a web search per the sourcing workflow in `MD-NEET-KB-Prompt.txt` — don't estimate a cutoff that isn't in the data.

---

*This file is designed to be read alongside: `MD-NEET-KB.md` (narrative knowledge base) and `MD-NEET-KB-Prompt.txt` (agent instructions). Source workbooks: `MCC_R1P.xlsx`, `ALLOT_R2_copy (1).xlsx`, `KEA_Dental_R2.xlsx`, `MBBS+SEAT+MATRIX+2025_KEA.xlsx`, `MBBS_SEAT_MATRIX_COMPARISON_2025_vs_2026_Rev1.xlsx` — all 2025 admission-cycle data.*
