# Karnataka (KEA) MBBS Cutoffs — 2026 Mock Allotment Round

## Purpose & scope

This is a **data reference companion** to `MD-NEET-KB.md` and `MD-NEET-Cutoffs-KB.md`, covering the **2026 KEA Mock Allotment round** for Karnataka MBBS — the earliest look at where the *current* NEET UG 2026 cohort is likely to land, ahead of the real KEA Round 1/Round 2. It complements, rather than replaces, `MD-NEET-Cutoffs-KB.md`'s 2025 actual-outcome data (MCC nationwide + KEA Karnataka).

**Use this file to answer:** "Based on this year's mock round, where do I roughly stand?", "Which Karnataka colleges look most competitive in the current cycle?" — always paired with the Mock-round caveat below. For India-wide MCC/AIQ data, or Karnataka's last completed real cycle (2025), use `MD-NEET-Cutoffs-KB.md` instead. For process, dates, fees, and general context, use `MD-NEET-KB.md`.

## ⚠️ This is a MOCK round — read this before anything else

A **Mock Allotment round is a simulation KEA runs on the option-entries candidates have already locked in, before the real (binding) round** — it lets candidates preview where their entered choices would land and revise them before the real round closes. It is **not a binding allotment and nobody is actually admitted based on it.** Specifically:

- Mock-round ranks are a **snapshot of current option-entry behavior**, not a stable prediction — they will move, sometimes substantially, once the real Round 1 runs (candidates revise choices, new candidates enter/exit, seat-matrix corrections happen).
- This file reflects **one mock round only**, dated in its own source filename (17-08-2026). It will be superseded by KEA's real Round 1 provisional allotment once published — always check whether a newer round's data is available before treating this as current.
- Do not present a mock-round rank to a parent as "the cutoff" — always call it what it is: a **mock/provisional preview rank**, likely to loosen or tighten before the real result.

## Data provenance & methodology

| Source file | What it is | Rows analyzed |
|---|---|---|
| `UGNEET_ALLOT_2026_MEDICAL_MOCK_17082026english.xlsx` | KEA's Karnataka MBBS **Mock Allotment round**, 2026 cycle, dated 17-08-2026 | 11,774 candidate-level rows, all `Allotted`, across 68 colleges |

**Aggregation method:** identical to `MD-NEET-Cutoffs-KB.md` — source candidate-level rows were grouped by college + category, and the minimum/maximum All-India Rank (AIR) within each group taken as the Opening/Closing rank. College **ownership type** (Government / Minority / Private / Deemed) is cross-referenced from the same verified 68-college mapping used in `MD-NEET-KB.md` Section 5's official 2026-27 KEA fee table — all 68 colleges in this mock-round file matched that mapping exactly, which is itself a useful consistency check across all three 2026 KEA sources (fee structure, mock allotment, and — once published — the real allotment).

## How to read the table

- **Opening/Closing Rank** — same definition as `MD-NEET-Cutoffs-KB.md`: Closing Rank is the highest (worst) AIR that still got a seat in the mock round; that's conventionally what "cutoff" means, but remember this is a mock, not real, cutoff.
- **Category codes** follow the same KEA pattern as `MD-NEET-Cutoffs-KB.md`: `GM` = General Merit; `1/2A/2B/3A/3B/SC/ST` = Karnataka's reservation ladder; `-G` suffix = state-wide (non-regional) variant of that category; `OPN` = private-college management/open-fee seat; `GMP` = government-fee seat inside a private/deemed college; `NRI` = NRI quota. This 2026 file's raw category list also includes `S1`–`S4` (G/H/K/KH/R/RH) codes not seen in the 2025 files and not decoded here — treat these as a KEA special-category ladder distinct from the main one, and verify exact eligibility against KEA's 2026 information bulletin before quoting one. Course-type labels changed slightly too: this file uses `MBBS-MNG` where 2025 files used `MBBS- OTHERS` — both appear to mean the same private-management seat-type bucket.
- Blank cells mean no seat was allotted in that college+category combination in this mock round — not necessarily zero capacity.

## "Which colleges look most preferred?" — this mock round's signal

Same logic as `MD-NEET-Cutoffs-KB.md`: in a merit-based allotment, the colleges with the *lowest* GM closing rank are the ones better-ranked candidates are choosing first. Read this as "current option-entry demand," not a confirmed outcome.

**Top 15, GM category, 2026 Mock Round:**

1. **Bangalore Medical College** (Government) — GM closing rank **1,833**
2. **Mysore Medical College** (Government) — GM closing rank **5,788**
3. **Shri Atal Bihari Vajpayee Institute of Medical Science** (Government) — GM closing rank **6,307**
4. **Kasturba Medical College** (Deemed/Private University) — GM closing rank **7,124**
5. **ESI Medical College (Rajajinagar)** (Government) — GM closing rank **9,966**
6. **M.S. Ramaiah Medical College** (Deemed/Private University) — GM closing rank **11,028**
7. **Karnataka Institute of Medical Sciences** (Government) — GM closing rank **11,253**
8. **Jagadguru Sri Shivarathreeswara Medical College** (Deemed/Private University) — GM closing rank **12,456**
9. **Mandya Institute of Medical Sciences** (Government) — GM closing rank **17,516**
10. **Kempegowda Institute of Medical Sciences** (Private) — GM closing rank **18,358**
11. **Vijayanagar Institute of Medical Sciences** (Government) — GM closing rank **20,613**
12. **Jawaharlal Nehru Medical College, Belgaum** (Deemed/Private University) — GM closing rank **21,274**
13. **Shimoga Institute of Medical Sciences** (Government) — GM closing rank **23,120**
14. **Belgaum Institute of Medical Sciences** (Government) — GM closing rank **23,126**
15. **Hassan Institute of Medical Sciences** (Government) — GM closing rank **23,693**

**By college type (GM category, 2026 Mock Round):**
- **Government (24 colleges):** GM closing rank spans **1,833 to 68,263**, median **34,316**.
- **Deemed/Private University (17 colleges):** GM closing rank spans **7,124 to 91,769**, median **66,108**.
- **Private (13 colleges):** GM closing rank spans **18,358 to 92,286**, median **74,662**.
- **Minority — Linguistic/Religious (14 colleges):** GM closing rank spans **25,148 to 93,679**, median **84,400**.

**Comparing against 2025:** `MD-NEET-Cutoffs-KB.md` Section 3 has the 2025 actual Round 1/Round 2-Final KEA figures for the same 68 colleges. Do **not** subtract or ratio the two directly to "predict" a final 2026 number — one is a real final-round outcome from a prior, harder-qualifying-cutoff cycle, and this one is a single mock round from a cycle with an easier paper and a higher qualifying-mark band (see `MD-NEET-KB.md` Section 7). At most, use both together to describe a *plausible band* for a college, clearly labeling which figure came from which file and round.

## Full 2026 Mock Round college-wise GM & category closing ranks (all 68 colleges)

| College | Type | GM Open | GM Close | GM Seats | OPN Close | GMP Close | NRI Close | CAT1-G Close | 2A-G Close | 2B-G Close | 3A-G Close | 3B-G Close | SC-G Close | ST-G Close |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Bangalore Medical College | Government | 48 | 1,833 | 76 |  |  |  | 10,857 | 6,917 | 3,582 | 3,847 | 3,605 |  | 16,356 |
| Mysore Medical College | Government | 432 | 5,788 | 71 |  |  | 212,495 | 16,498 | 14,141 | 12,867 | 7,844 | 8,750 |  | 30,409 |
| Shri Atal Bihari Vajpayee Institute of Medical Science | Government | 631 | 6,307 | 57 |  |  | 197,890 | 19,382 | 17,000 | 12,243 | 8,178 | 11,418 |  | 36,486 |
| Kasturba Medical College | Deemed/Private University | 1,812 | 7,124 | 18 |  |  |  | 25,097 | 37,254 | 9,098 | 9,731 | 23,067 |  | 52,112 |
| ESI Medical College (Rajajinagar) | Government | 5,147 | 9,966 | 20 |  |  |  | 27,371 | 20,884 | 12,289 | 11,368 | 13,556 |  | 54,884 |
| M.S.Ramaiah Medical College | Deemed/Private University | 1,267 | 11,028 | 31 | 77,099 | 154,943 | 1,051,159 | 29,042 | 40,538 | 23,837 | 14,000 | 26,800 |  | 86,116 |
| Karnataka Institute of Medical Sciences | Government | 190 | 11,253 | 72 |  |  | 317,314 | 25,382 | 20,146 | 19,440 | 16,478 | 13,104 |  | 42,754 |
| Jagadguru Sri Shivarathreeswara Medical College | Deemed/Private University | 8,450 | 12,456 | 5 |  |  |  | 39,829 | 39,679 |  |  |  |  | 85,883 |
| Mandya Institute of Medical Sciences | Government | 6,502 | 17,516 | 61 |  |  | 335,104 | 33,381 | 32,368 | 28,834 | 18,243 | 26,871 |  | 60,576 |
| Kempegowda Institute of Medical Sciences | Private | 6,305 | 18,358 | 37 | 34,710 | 88,654 | 1,155,793 | 38,421 | 52,483 | 27,646 | 27,992 | 31,917 |  | 90,289 |
| Vijayanagar Institute of Medical Sciences | Government | 4,606 | 20,613 | 31 |  |  | 407,662 | 42,075 | 33,019 | 22,738 | 24,510 | 28,105 |  | 52,991 |
| Jawaharalal Nehru Medical College | Deemed/Private University | 13,299 | 21,274 | 5 |  |  |  |  | 62,550 |  |  |  |  |  |
| Shimoga Institute of Medical Sciences | Government | 4,450 | 23,120 | 48 |  |  |  | 42,704 | 34,426 | 38,348 | 26,769 | 27,440 |  | 56,302 |
| Belgaum Institute of Medical Sciences | Government | 1,268 | 23,126 | 60 |  |  | 401,853 | 35,311 | 33,322 | 32,353 | 30,953 | 27,475 |  | 46,817 |
| Hassan Institute of Medical Sciences | Government | 8,425 | 23,693 | 63 |  |  | 448,771 | 43,443 | 37,182 | 42,063 | 24,926 | 31,894 |  | 66,065 |
| Father Muller Institute of Med. Education & Research | Minority (Linguistic/Religious) | 10,053 | 25,148 | 16 | 37,256 | 86,600 | 1,122,845 | 45,411 | 71,034 | 30,675 | 44,255 | 29,854 |  | 104,394 |
| Vydehi Institute of Medical Science and Research Centre | Minority (Linguistic/Religious) | 14,468 | 27,041 | 26 | 36,906 | 94,796 | 991,879 | 54,167 | 67,128 | 43,634 | 36,208 | 43,958 |  | 120,983 |
| Gulbarga Institute of Medical Sciences | Government | 3,528 | 28,530 | 24 |  |  | 530,727 | 53,901 | 42,154 | 36,520 | 31,315 | 33,854 |  | 73,912 |
| ESI Medical College (Sedam Road) | Government | 13,678 | 29,686 | 7 |  |  |  |  | 44,342 | 34,756 | 30,892 | 33,667 |  | 95,561 |
| SDM College of Medical Sciences and Hospital | Deemed/Private University | 396 | 32,655 | 23 | 117,501 | 163,881 | 1,074,451 | 61,159 | 53,569 | 51,523 | 50,774 | 37,940 |  | 117,443 |
| K.S.Hegde Medical Academy | Deemed/Private University | 24,927 | 34,491 | 16 |  |  |  | 46,348 | 49,189 | 37,703 | 53,902 |  |  | 118,821 |
| Chamarajanagar Institute of Medical Science | Government | 16,163 | 38,945 | 50 |  |  |  | 61,692 | 54,329 | 55,694 | 40,812 | 43,088 |  | 94,947 |
| Jaya Jagadguru Murugharajendra Medical College | Private | 17,055 | 40,280 | 38 | 50,336 | 108,615 |  | 52,056 | 69,289 | 41,771 | 52,295 | 49,381 |  | 114,368 |
| K.H. Patil Institute of Medical Sciences (previously Gadag Institute of Medical Sciences | Government | 24,076 | 41,241 | 62 |  |  | 775,237 | 55,106 | 51,650 | 51,241 | 46,318 | 43,680 |  | 90,804 |
| BGS Global Institute of Medical Sciences | Private | 18,617 | 41,737 | 40 | 48,699 | 104,206 | 1,096,984 | 69,463 | 72,317 | 62,060 | 45,200 | 54,692 |  | 116,337 |
| Raichur Institute of Medical Sciences | Government | 21,098 | 43,120 | 26 |  |  | 722,206 | 45,916 | 53,654 | 47,932 | 46,808 | 43,633 |  |  |
| A.J.Institute of Medical Sciences | Minority (Linguistic/Religious) | 25,742 | 45,376 | 24 | 50,550 | 109,269 | 946,133 | 67,951 | 77,749 | 59,274 | 56,366 | 56,977 |  | 111,461 |
| Bidar Institute of Medical Sciences | Government | 25,735 | 46,827 | 25 |  |  | 829,970 |  | 55,402 |  |  | 48,652 |  | 72,930 |
| Nandi Medical College and Research Institute Chikkaballapura (Chikkaballapura Institute of Medical Sciences Chikkaballapura ) | Government | 21,283 | 47,973 | 44 |  |  | 425,700 | 75,733 | 68,174 | 58,221 | 50,600 | 55,269 |  | 105,111 |
| Dr. B.R. Ambedkar Medical College | Private | 25,040 | 49,045 | 22 | 44,518 | 108,104 | 1,045,362 | 84,453 | 78,804 | 57,058 | 52,926 | 64,934 |  | 119,920 |
| Kodagu Institute of Medical Sciences | Government | 25,185 | 49,462 | 50 |  |  |  | 73,666 | 64,599 | 62,435 | 50,377 | 55,846 |  | 92,381 |
| Yenepoya Medical College | Deemed/Private University | 25,658 | 50,394 | 15 |  |  |  | 73,292 | 87,822 | 57,138 | 64,236 | 68,074 |  |  |
| Koppal Institute of Medical Sciences | Government | 37,992 | 52,004 | 27 |  |  | 865,819 | 66,919 | 58,178 | 54,386 | 55,758 | 52,511 |  | 101,627 |
| Karwar Institute of Medical Science | Government | 25,037 | 55,776 | 64 |  |  | 783,915 | 74,972 | 68,985 | 68,168 | 58,329 | 57,645 |  | 82,572 |
| PES University Institute of Medical Sceinces and Research | Deemed/Private University | 24,139 | 57,236 | 40 | 170,532 | 211,095 | 681,588 | 65,112 | 86,483 | 72,413 | 64,172 | 65,469 |  | 129,595 |
| Chikkamagaluru Institute of Medical Sciences | Government | 29,479 | 58,516 | 52 |  |  |  | 74,590 | 73,721 | 68,727 | 60,655 | 60,337 |  | 103,065 |
| Shymanuru Shivashankarappa Institute Of Medical Sciences | Private | 41,596 | 63,402 | 40 | 62,822 | 121,169 |  | 82,742 | 87,728 | 79,762 | 71,176 | 68,272 |  | 122,900 |
| Haveri Institute of Medical Sciences | Government | 31,381 | 63,822 | 51 |  |  |  | 75,184 | 77,110 | 73,992 | 65,175 | 65,275 |  | 106,781 |
| Yadgiri Institute of Medical Sciences | Government | 47,749 | 66,032 | 21 |  |  |  | 81,227 | 77,767 | 76,662 | 66,582 | 66,568 |  | 106,755 |
| Dr. Chandramma Dayananda Sagar Institute of Medical Education | Deemed/Private University | 35,224 | 66,108 | 32 | 206,147 | 244,399 | 279,187 | 97,607 | 90,318 | 80,872 | 70,041 | 72,617 |  | 132,977 |
| Adichunchanagiri Institute of Medical Sciences | Deemed/Private University | 33,371 | 66,984 | 41 | 191,080 | 237,937 |  | 84,649 | 90,389 | 85,165 | 67,690 | 71,110 |  | 132,727 |
| Chitradurga Medical College and Research Institute | Government | 29,285 | 68,263 | 49 |  |  |  | 82,099 | 80,390 | 78,464 | 70,404 | 69,403 |  | 113,617 |
| Sri Madhusudan Sai Institute of Medical Sciences and Research | Deemed/Private University | 15,013 | 69,205 | 8 | 130,546 | 214,443 |  | 111,350 | 81,253 |  | 77,233 | 69,896 |  |  |
| M.V.J.Medical College and Research Hospital | Minority (Linguistic/Religious) | 49,730 | 72,323 | 25 | 52,667 | 114,283 |  | 89,387 | 95,491 | 79,132 | 72,943 | 75,720 |  | 132,584 |
| Siddaganga Medical College and Research Institute | Private | 11,155 | 72,439 | 40 | 74,866 | 129,743 | 1,077,419 | 93,355 | 96,323 | 79,192 | 73,382 | 76,485 |  | 127,871 |
| BGS Medical College and Hospital | Deemed/Private University | 47,775 | 74,130 | 39 | 193,398 | 258,187 | 945,432 | 92,335 | 101,589 | 86,244 | 74,909 | 82,871 |  | 126,896 |
| Mahadevappa Rampure Medical College | Private | 60,214 | 74,662 | 16 | 64,717 | 126,418 | 936,324 | 87,972 | 85,700 | 86,026 | 76,530 |  |  | 131,096 |
| Sapthagiri Institute of Medical Sciences | Deemed/Private University | 34,960 | 77,205 | 40 | 193,093 | 263,430 |  | 98,636 | 96,072 | 87,146 | 78,219 | 85,026 |  | 133,477 |
| S. Nijalingappa Medical College and Research Centre | Private | 27,516 | 78,569 | 40 | 74,844 | 137,289 |  | 89,299 | 91,223 | 86,360 | 83,651 | 82,002 |  | 130,981 |
| Subbaiah Institute of Medical Science | Minority (Linguistic/Religious) | 53,574 | 79,321 | 24 | 83,843 | 136,094 | 902,765 | 97,822 | 89,051 | 95,526 | 80,711 | 84,510 |  | 129,780 |
| The Oxford Medical College Hospital and Research Center | Minority (Linguistic/Religious) | 67,433 | 82,588 | 23 | 60,575 | 131,879 |  | 104,398 | 104,593 | 94,847 | 88,308 | 88,718 |  |  |
| East Point College of Medical Sciences and Research Center | Private | 33,291 | 83,846 | 40 | 65,917 | 138,191 | 520,191 | 102,339 | 107,267 | 91,409 | 88,227 | 85,594 |  | 141,751 |
| Akash Institute of Medical Sciences and Research Centre | Minority (Linguistic/Religious) | 52,573 | 84,400 | 25 | 56,822 | 132,674 |  | 104,153 | 109,392 | 93,076 | 84,875 | 85,990 |  | 140,109 |
| Sri Basaveshwara Medical College and Hospital | Deemed/Private University | 60,815 | 84,532 | 23 | 88,858 | 168,819 |  | 112,400 | 106,317 | 97,011 | 86,082 | 85,743 |  | 115,797 |
| Navodaya Medical College | Minority (Linguistic/Religious) | 64,360 | 85,612 | 10 | 82,113 | 148,059 |  | 104,531 | 99,766 | 92,470 | 85,809 | 87,803 |  |  |
| SRI CHAMUNDESHWARI MEDICAL COLLEGE | Minority (Linguistic/Religious) | 49,037 | 86,411 | 20 | 87,314 | 136,733 |  |  | 101,653 |  | 90,190 | 87,841 |  | 144,145 |
| Khaja Bande Navaz Institute Of Medical Sciences | Deemed/Private University | 57,303 | 87,025 | 5 | 117,390 | 171,109 |  |  | 95,178 |  |  |  |  |  |
| K.Venkataramana Gowda Medical College and Hospital | Private | 67,543 | 88,449 | 25 | 89,861 | 148,359 | 1,053,090 | 108,886 | 103,564 | 97,606 | 89,181 | 90,168 |  |  |
| ALVAS INSTITUTE OF MEDICAL SCIENCES AND RESEARCH CENTRE | Minority (Linguistic/Religious) | 59,910 | 88,451 | 15 | 94,389 | 142,703 | 939,261 | 111,209 | 112,422 | 102,147 | 89,367 | 93,911 |  | 144,138 |
| Shridevi Institute of Medical Sciences and Research Hospital | Private | 74,614 | 88,886 | 40 | 83,778 | 147,423 | 1,166,654 | 109,879 | 110,279 | 96,158 | 91,493 | 91,976 |  | 139,375 |
| Srinivasa Institute of Medical Research Center Srinivas Nagar Mangalore | Deemed/Private University | 45,841 | 90,743 | 39 | 234,187 | 294,967 | 303,787 | 111,156 | 112,615 | 100,790 | 93,791 | 92,811 |  | 143,068 |
| S R Patil Medical College Hospital and Research Center | Private | 84,499 | 91,411 | 16 | 88,894 | 149,792 |  | 113,541 | 106,475 | 95,429 | 91,696 |  |  | 132,725 |
| Kanachur Institute of Medical Sciences and Research Centre | Minority (Linguistic/Religious) | 51,674 | 91,589 | 25 | 72,627 | 144,500 | 510,110 | 114,238 | 112,117 | 98,346 | 92,711 | 92,329 |  |  |
| Jagadguru Gangadhar Mahaswamigalu Moorusavirmath Medical College | Deemed/Private University | 71,841 | 91,769 | 14 |  |  |  | 108,884 | 114,549 | 98,927 | 94,637 | 95,778 |  | 157,457 |
| Al-Ameen Medical College | Minority (Linguistic/Religious) | 54,550 | 91,792 | 14 | 77,471 | 132,878 |  | 115,886 | 112,314 | 96,480 | 94,719 |  |  | 139,188 |
| Farookh Academy of Medical Education Hospital and Research Institute | Private | 38,664 | 92,286 | 23 | 93,980 | 152,863 | 745,718 | 115,678 | 113,438 | 96,134 | 94,089 | 94,654 |  |  |
| G R Medical College Hospital and Research Centre Mangalore D.K | Minority (Linguistic/Religious) | 65,725 | 93,679 | 15 | 92,285 | 161,798 |  | 117,742 | 113,881 | 101,803 | 94,521 | 95,676 |  |  |
| St John Medical College | Minority (Linguistic/Religious) |  |  | 0 | 9,127 | 20,740 |  |  |  |  |  |  |  |  |

## How agents should use this file

1. **Always call it a "2026 Mock Round" figure, every time** — never drop the word "mock." This is the single most important labeling rule for this file, more so than for `MD-NEET-Cutoffs-KB.md`'s real-round data.
2. **Prefer this file over `MD-NEET-Cutoffs-KB.md` when the question is about the current (2026) cycle's likely standing**, and prefer `MD-NEET-Cutoffs-KB.md` when the question is about the last completed (2025) cycle's actual outcome, or needs India-wide MCC/AIQ data (which this file doesn't have — Karnataka/KEA only).
3. **When a real KEA round for 2026 is published**, treat it as superseding this mock file for anything about the current cycle — check with the user or a web search whether a newer round exists before relying solely on this file for a live decision.
4. **For category-specific questions**, use that category's own column — don't extrapolate a reserved-category rank from GM.
5. **If a college isn't in this file**, it isn't a KEA-participating college for 2026 (all 68 KEA colleges are covered) — say so and don't guess.

---

*This file is designed to be read alongside: `MD-NEET-KB.md` (narrative knowledge base) and `MD-NEET-Cutoffs-KB.md` (2025 actual MCC + KEA cutoffs). Source workbook: `UGNEET_ALLOT_2026_MEDICAL_MOCK_17082026english.xlsx` — 2026 KEA Mock Round, dated 17-08-2026.*
