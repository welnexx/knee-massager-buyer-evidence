---
kanal: dataset
kaynak: V1, V3, V4, V5, PR
baslik: "Data dictionary: Welnexx buyer evidence"
baglanti: https://welnexx.com/blogs/guides/heated-knee-massager-index?utm_source=dataset&utm_medium=dataset&utm_campaign=dagitim-2026-11
bicim: B5
fiyat: evet
---

# Data dictionary

Version: 1.0.0. Release date: {TARIH}. Source-page freeze: November 13, 2026.

Each table below describes an existing CSV without renaming, recoding or changing it. Logical types describe values inside CSV text fields. Ratio, percentage, currency, range and mixed-date fields retain their published formatting. A Total row is a summary, not an additional person, listing or event.

No empty cells were observed in the supplied files. If a field is empty in another copy, it means no exported value is available; do not substitute zero, No or a negative outcome. The literal `not stated` is an evidence marker, not an empty cell. The table-specific meanings below take precedence over a numerical interpretation.

The package contains no review text, no usernames, no personal data and no review IDs.

These are presentation-table exports, not the underlying cell-status or review-level archives. Join V1 and PR listing tables by the R-number within the label; do not merge cross-channel records solely because product names resemble one another. Provenance rows can cover a range of records. The same evidence appears in several tables and must not be added across files.

## `PR_t01_which_11_written_details_should_i_check.csv`

Source: PR. Exported table rows: 11.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Check | criterion code | Check identifier K1 through K11 used by the written-information score. | K1 | Empty: no exported value; not zero. |
| Information counted | text | Information counted for that check; favorable conditions are not extra points. | Heat levels or temperature information | Empty: no exported value; not zero. |

## `PR_t02_how_many_written_details_does_each_listing_have.csv`

Source: PR. Exported table rows: 33.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Record and product | record label | Listing record identifier and product label; sales channels remain distinct records. | R25 Bob and Brad ThermoRed | Empty: no exported value; not zero. |
| Channel | category text | Recorded sales channel, such as Brand site, Marketplace or Retailer site. | Brand site | Empty: no exported value; not zero. |
| Written criteria /11 | ratio text | Supported written criteria out of 11; not a quality or performance score. | 6/11 | Empty: no exported value; not zero. |
| Return trio | Yes/No text | A Yes entry confirms three supported terms: the period starts at delivery, use is allowed, and the seller covers return postage. No indicates that this full combination lacks support. | No | Empty: no exported value; not zero. |
| Stated checks | comma-separated criterion numbers or missing marker | Numbers of supported checks; match the K-number definitions, not product quantities. | 1,3,7,9,10,11 | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| Not stated checks | comma-separated criterion numbers | Checks not established as supported, including missing, conflicting or unsupported evidence. | 2,4,5,6,8 | Empty: no exported value; not zero. |

## `PR_t03_will_it_fit_and_how_hot_will_it_feel.csv`

Source: PR. Exported table rows: 4.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Product and channel | product/channel label | Product and sales channel selected for this fit/temperature comparison. | Comfytemp K1006, brand site | Empty: no exported value; not zero. |
| Written measurement | text with units | Captured strap or circumference measurement, retaining upper/lower locations where supplied. | 19-inch strap/extension | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| Temperature measurement location | text | Whether the advertised temperature is identified as skin or element temperature. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |

## `PR_t04_can_i_try_it_and_return_it_without_postage_costs.csv`

Source: PR. Exported table rows: 5.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Product | product label | Product selected for the return-condition comparison. | Bob and Brad ThermoRed | Empty: no exported value; not zero. |
| Return window and start | text | Return period and starting event as captured or canonically updated for Welnexx. | 30 days from purchase | Empty: no exported value; not zero. |
| Required return condition | text | Captured condition required for returns, including used-item acceptance where stated. | Unused; original packaging | Empty: no exported value; not zero. |
| Return shipping or deductions | text | Captured postage payer or deductions; absence of wording is not a free-return promise. | Customer pays postage; $10 fee for nondefective returns | Empty: no exported value; not zero. |

## `PR_t05_what_if_the_battery_stops_charging_within_a_year.csv`

Source: PR. Exported table rows: 5.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Product and channel | product/channel label | Product and channel selected for the coverage comparison. | Bob and Brad ThermoRed, brand site | Empty: no exported value; not zero. |
| Product warranty | text | Captured general product-coverage statement; not automatically battery-specific. | 2-year limited | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| Explicit battery warranty | text | Explicit battery-coverage wording; not stated is an evidence gap. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |

## `PR_t06_which_captured_pages_support_the_tables.csv`

Source: PR. Exported table rows: 24.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Record | record reference | Listing identifier or identifier range covered by this provenance row. | R00 | Empty: no exported value; not zero. |
| Source URLs supporting the cells | text with URLs | Captured source descriptions and URLs supporting the score and condition cells. | Welnexx product <https://welnexx.com/products/welnexx-knee-massager>; canonical product/policy record | Empty: no exported value; not zero. |
| Capture date | date description text | Capture date or separate technical/policy dates; some rows describe missing dates. | Technical: 2026-10-23; policy: 2026-11-12 | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |

## `V1_t01_what_should_i_check_before_buying_a_heated_knee_ma.csv`

Source: V1. Exported table rows: 11.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Criterion | criterion code | Identifier for the written-information check, K1 through K11. | K1 | Empty: no exported value; not zero. |
| What we looked for | text | Information sought for that check. | Heat settings or temperature range | Empty: no exported value; not zero. |
| Comparison entries with a supported written statement | ratio text | Supported comparison entries divided by 32; Welnexx is excluded from this denominator. | 22/32 | Empty: no exported value; not zero. |

## `V1_t02_which_specifications_did_each_product_put_in_writi.csv`

Source: V1. Exported table rows: 33.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Record and product | record label | Listing record identifier followed by product and channel wording; channels are separate observations. | R00 Welnexx Version A | Empty: no exported value; not zero. |
| K1: heat | text | Captured heat-setting or temperature statement; supplier wording is identified where applicable. | 4 levels; 42–57°C | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| K2: skin or element? | text | Whether the temperature is located at the skin or heating element in the captured statement. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| K3: timer/shutoff | text | Recorded timer or automatic-shutoff information; one does not establish the other. | 10-minute timer; supplier-stated automatic shutoff | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| K4: separate control | text | Captured information about separate controls; this does not establish heat-only operation. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| K5: fit information | text | Captured knee, circumference or strap measurement; a strap measurement is not a complete fit range. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| K6: testing/identifier | text | Captured testing, regulatory statement or identifier; a statement does not verify certification. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |

## `V1_t03_what_do_the_warranties_and_return_policies_actuall.csv`

Source: V1. Exported table rows: 33.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Record and product | record label | Listing record identifier and product label, matching the specification table. | R00 Welnexx Version A | Empty: no exported value; not zero. |
| K7: product warranty | text | Supported product-coverage wording; unresolved or unsupported conditions are not asserted. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| K8: battery warranty | text | Explicit battery-specific coverage, kept separate from general product coverage. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| K9: return window/start | text | Return period and its starting event, with any captured qualification. | 60 days from delivery; used OK; free return label | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| K10: required condition | text | Captured condition required for a return, including used-product acceptance when stated. | Used accepted | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| K11: return costs/location | text | Captured postage responsibility, deductions or return location conditions. | Prepaid US return label if requested back | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |

## `V1_t04_do_more_advertised_features_mean_a_higher_price.csv`

Source: V1. Exported table rows: 3.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Advertised feature categories | integer | Number of extracted advertised feature categories for the grouped offers. | 1 | Empty: no exported value; not zero. |
| Dated offers retained | integer | Number of dated numeric offers retained in this group; offer quantities are not standardized. | 2 | Empty: no exported value; not zero. |
| Median listed USD | USD currency text | Published median listed price within this retained historical group. | $143.50 | Empty: no exported value; not zero. |
| Listed USD range | USD range text | Published minimum and maximum listed prices in the group; not current quotes. | $37.99–$249.00 | Empty: no exported value; not zero. |

## `V1_t05_which_source_captures_support_the_product_and_poli.csv`

Source: V1. Exported table rows: 24.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Record | record reference | Listing identifier or identifier range covered by this provenance row. | R00 | Empty: no exported value; not zero. |
| Source URLs supporting the cells | text with URLs | Captured source descriptions and URLs supporting the published cells; may identify archive-only records. | Welnexx product <https://welnexx.com/products/welnexx-knee-massager>; canonical product/policy record | Empty: no exported value; not zero. |
| Capture date | date description text | Capture date or separate technical and policy dates; wording is retained as exported. | Technical: October 23, 2026; policy: November 12, 2026 | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |

## `V3_t01_what_are_the_most_common_knee_massager_complaints.csv`

Source: V3. Exported table rows: 14.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Issue type | category text | Device-issue group, or the published Total row. | Stopped working / will not start | Empty: no exported value; not zero. |
| Complaint-coded reports | integer | Complaint-coded source records in the issue group; denominator for shares is 134. | 26 | Empty: no exported value; not zero. |
| People in issue group | integer | Distinct source-record IDs in the group, including non-complaint codes; not verified purchasers. | 27 | Empty: no exported value; not zero. |
| Share of 134 complaints | percentage text | Published complaint share using 134 complaint-coded records; not all buyers. | 19.40% | Empty: no exported value; not zero. |

## `V3_t02_why_does_it_stop_working_or_fail_to_hold_a_charge.csv`

Source: V3. Exported table rows: 2.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Fault-timing evidence | text | Timing subset or unestablished service-life measure described by this row. | Charging or stopped-working reviews with a stated time | Empty: no exported value; not zero. |
| Review count | integer or missing marker | Reviews with a stated time within the selected fault-topic subset; not a sales denominator. | 45 | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |
| Reported time to problem | text | Published timing summary, with month units; not independently observed service life. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |

## `V3_t03_why_does_it_not_fit_stay_fastened_or_feel_strong_e.csv`

Source: V3. Exported table rows: 2.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Welnexx fit or control detail | text | Welnexx fit or control detail sought in the supplier record. | Strap length and knee-circumference range | Empty: no exported value; not zero. |
| Written information | text | Written evidence for the requested detail; not stated records an evidence gap. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |

## `V3_t04_how_can_i_tell_whether_reviews_belong_to_a_differe.csv`

Source: V3. Exported table rows: 4.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Anonymized listing | anonymized label | Listing-history label A, B or C, or Total; no reviewer identity. | A | Empty: no exported value; not zero. |
| Review records checked | integer | Review records examined for the listing-history date comparison. | 194 | Empty: no exported value; not zero. |
| Predating first availability | integer | Examined reviews dated before the listing first-available date; not a finding about authenticity. | 187 | Empty: no exported value; not zero. |

## `V3_t05_how_were_the_complaints_and_review_topics_counted.csv`

Source: V3. Exported table rows: 14.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Primary review topic | category text | Primary topic assigned once to each archived review, or Total. | Reported comfort / relief | Empty: no exported value; not zero. |
| Review count | integer | Distinct review IDs assigned to that primary topic; includes positive and neutral topics. | 352 | Empty: no exported value; not zero. |
| Share of 1,184 coded reviews | percentage text | Published topic share using 1,184 coded review IDs; not a complaint rate. | 29.73% | Empty: no exported value; not zero. |

## `V4_fda_records.csv`

Source: V4. Exported table rows: 14.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| source | source code | Record origin: CPSC, FDA_MAUDE, STUDY_MAUDE or FDA_RECALL_NOTICE. This file is not limited to FDA sources. | CPSC | Empty: no exported value; not zero. |
| record_id | identifier text | Public record reference or an analysis label. An analysis label is not an individual FDA report number. | 16-762 | Empty: no exported value; not zero. |
| date | ISO date or interval text | Source-specific date: a recall publication, an event, or the receipt interval used by the analysis. FDA receipt dates can differ from event dates. | 2022-10-24 | Empty: no exported value; not zero. |
| device_type | text | English device description. The category identifies the scope of the source record. | Neck-and-shoulder heated wrap | Empty: no exported value; not zero. |
| event | measure code | English label identifying what count measures. Approximation and injury-scope qualifiers are part of the label; definitions follow below. | units_recalled_approximately | Empty: no exported value; not zero. |
| count | integer | Quantity for the measure named by event. Units, submissions and injuries are different quantities; overlapping counts must remain separate. | 10000 | Empty: no exported value; not zero. |
| url | URL text | Address of the official notice, public submission or published analysis supporting this row. | https://www.cpsc.gov/Recalls/2016/Emson-Recalls-UComfy-Heat-Wraps | Empty: no exported value; not zero. |

## `V4_t01_what_do_the_cpsc_recall_records_actually_count.csv`

Source: V4. Exported table rows: 5.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Source | source label | Public record authority and source class. | CPSC | Empty: no exported value; not zero. |
| Date and date type | date description text | Date with its explicit meaning: recall notice or event date, not necessarily FDA receipt date. | July 27, 2016; recall notice | Empty: no exported value; not zero. |
| Device type | text | Device category recorded in that source; not necessarily a knee device. | Neck-and-shoulder heated wrap | Empty: no exported value; not zero. |
| Event type and recorded count | text | Source-specific reports, injuries or recalled-unit quantities with their original units and qualifiers. | 1 report coded for third-degree burn | Empty: no exported value; not zero. |
| Record number | identifier with URL | Public record reference plus source URL; not a personal identifier. | 16-762 <https://www.cpsc.gov/Recalls/2016/Emson-Recalls-UComfy-Heat-Wraps> | Empty: no exported value; not zero. |

## `V4_t02_how_many_product_listings_advertise_heat_above_113.csv`

Source: V4. Exported table rows: 4.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Included listing records | category text | Temperature-information category, or Total included. | At least one advertised temperature above 113°F | Empty: no exported value; not zero. |
| Count | integer | Listing-record count in that category; included denominator is 23. | 9 | Empty: no exported value; not zero. |
| Counting rule | text | Numerical comparison or inclusion rule; 113°F is not a safety threshold. | Numerical temperature greater than 45°C or 113°F | Empty: no exported value; not zero. |

## `V4_t03_how_many_product_listings_advertise_heat_above_113.csv`

Source: V4. Exported table rows: 10.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Listing reference | listing reference with URL | Published listing reference and source URL; one record can have multiple power options. | 1: heated knee device <https://levidecupp.com/products/levide%E2%84%A2-red-light-therapy-panel> | Empty: no exported value; not zero. |
| Advertised temperature information | text with units | Captured advertised temperatures and qualifications; not measured skin temperatures. | 105, 120 and 140°F | Empty: no exported value; not zero. |
| Capture date, 2026 | partial date text | Month and day of capture; the column header supplies the year 2026. | October 22 | Empty: no exported value; not zero. |

## `V4_t04_does_113_f_tell_me_when_heat_will_burn_skin_over_6.csv`

Source: V4. Exported table rows: 3.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Question about a specific device | text | Device-specific evidence question for which the comparison supplies no measured answer. | Independently measured skin-contact temperature | Empty: no exported value; not zero. |
| Evidence in this comparison | text | Evidence available in the comparison; not stated does not establish safety. | not stated | Empty: no exported value; not zero. not stated: detail not established in the captured evidence. |

## `V4_t05_does_a_maude_report_prove_a_device_caused_an_injur.csv`

Source: V4. Exported table rows: 2.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Source | source label | FDA announcement or update class, rather than an individual MAUDE submission. | FDA recall announcement | Empty: no exported value; not zero. |
| Notice date | date text | Announcement or update date; an as-of date for injuries can differ. | October 24, 2022 | Empty: no exported value; not zero. |
| Device type | text | Product category and model context retained from the source table. | Electric heating pads, three models | Empty: no exported value; not zero. |
| Recorded measure | text with units | Recalled-device quantity or serious-injury count, preserving distinctions from burn-only counts. | 544,212 recalled devices | Empty: no exported value; not zero. |
| Source identifier | identifier with URL | Dated announcement label and URL; the label is not an official recall number. | Dated FDA announcement <https://www.fda.gov/safety/recalls-market-withdrawals-safety-alerts/whele-llc-announces-national-voluntary-recall-mighty-bliss-electric-heating-pad-due-product-safety> | Empty: no exported value; not zero. |

## `V5_t01_which_everyday_approaches_did_people_say_helped_mo.csv`

Source: V5. Exported table rows: 6.

| Column | Logical type | Meaning | Example from this CSV | Empty / missing meaning |
|---|---|---|---|---|
| Reported approach | category text | Approach label used for the discussion count. The mixed other category is outside this table. | Exercise, strengthening or physical therapy | Empty: no exported value; not zero. |
| People reporting help | integer | People whose accounts were coded as helpful for this approach in the selected group of 34. The same person may also count under another approach. | 6 | Empty: no exported value; not zero. |
| Guideline counterpart | text | Guideline position for a related intervention. A recommendation may apply to only part of a grouped approach label. | ACR 2026: locally applied heat conditionally recommended | Empty: no exported value; not zero. |

## Measure codes in `V4_fda_records.csv`

| Exported `event` value | Meaning and unit |
|---|---|
| units_recalled_approximately | Approximate number of devices covered by the recall; no injured-user count is implied. |
| overheating_reports | Overheating accounts recorded in the CPSC notice. |
| burn_reports | Burn accounts recorded in the CPSC notice. |
| exposed_wire_spark_smoke_or_flame_reports | Accounts involving wiring or electrical/fire symptoms. These are not all heating-surface incidents. |
| smoke_melting_or_burning_reports | Reports categorized by the notice as smoke, melting or burning. |
| burn_injuries | Injuries identified as burns in the notice. |
| report_coded_third_degree_burn | Individual MAUDE submission coded for a third-degree burn. The code does not establish verified causation. |
| reports_all_event_types_not_a_burn_count | Report count for the analysis group, covering all event categories. It must not be labeled a burn total. |
| devices_recalled | Device count covered by the FDA notice; the export does not mark it as approximate. |
| serious_injuries_as_of_2026_03_10_burns_not_stated_separately | Serious injuries reported by March 10, 2026. The source supplies no separate burn-only total. |

A STUDY_MAUDE row describes the published powered-heating-pad group. Its report total and the official recall measures have different scopes and cannot be pooled.
