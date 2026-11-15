# Collection and coding method

Version: 1.0.1. Release date: November 15, 2026. Pages frozen November 13, 2026.

This document restates only the collection, coding and limits recorded in the frozen source pages. It does not introduce a new search, validation experiment or numerical calculation. CSVs are published-table copies; `V4_fda_records.csv` is the supplied public-record export. The underlying cell-level archive, review IDs and raw discussion records are not included. The package contains no review text, no usernames and no personal data. V5 supplies approach labels, helpful-report counts and guideline context only.

The V1 and PR tables reuse the same captured listing set. Their rows are not independent additional samples. The complaint-language records and archived reviews in V3 are separate collections. Regulatory measures are not a pooled incident dataset.

## How are unsupported listing details handled?

Listing evidence is classified as supported, missing, conflicting or unsupported. Only supported statements enter the counts. The wide CSV tables do not include the original status columns. Partial information may qualify; a supported statement can still describe restrictive terms.

## `PR_t01_which_11_written_details_should_i_check.csv`

- **Source type:** Written-information criterion definitions
- **Collection/counting period:** Same captured set as the index: October 22–November 12, 2026; some dates missing
- **Observation unit:** A criterion definition
- **Coding rule:** Keep the 11 check definitions used in the source scoring method.
- **Excluded or withheld:** Favorable conditions are not separately scored.
- **Known limits:** A check definition is not an effectiveness measure.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massagers-scored-written-terms; sections: “Which 11 written details should I check?”; “How did you score the listings?”

## `PR_t02_how_many_written_details_does_each_listing_have.csv`

- **Source type:** Captured listing evidence and canonical Welnexx return terms
- **Collection/counting period:** October 22–November 12, 2026; some source dates missing
- **Observation unit:** A listing record scored across written criteria
- **Coding rule:** One point per supported check, at most one per category. Welnexx uses current return terms and excludes K7. Return trio requires delivery-based timing, used acceptance and seller-paid shipping.
- **Excluded or withheld:** Missing, conflicting and unsupported checks receive no point; favorable-condition counts are excluded.
- **Known limits:** 363 cells across 33 records and 11 checks describe evidence availability, not quality, comfort or lifespan.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massagers-scored-written-terms; sections: “How many written details does each listing have?”; “How did you score the listings?”

## `PR_t03_will_it_fit_and_how_hot_will_it_feel.csv`

- **Source type:** Selected captured fit/temperature statements
- **Collection/counting period:** Same source-capture register, October 22–November 12, 2026
- **Observation unit:** A selected product/channel record
- **Coding rule:** Retain measurement location and upper/lower or strap distinctions from the captured wording.
- **Excluded or withheld:** Do not substitute a circumference promise for a strap measurement.
- **Known limits:** Written dimensions and unspecified temperature locations do not establish actual fit or skin temperature.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massagers-scored-written-terms; sections: “Will it fit, and how hot will it feel?”; “How did you score the listings?”

## `PR_t04_can_i_try_it_and_return_it_without_postage_costs.csv`

- **Source type:** Selected return-policy captures and canonical Welnexx terms
- **Collection/counting period:** Source register October 22–November 12, 2026; Welnexx return terms updated November 12
- **Observation unit:** A selected product return-policy record
- **Coding rule:** Preserve return clock, required condition and postage/deductions as separate fields.
- **Excluded or withheld:** Missing or conflicting evidence does not earn a supported check; no favorable assumption is added.
- **Known limits:** The selection is a condition comparison, not a completed-refund record or return-rate estimate.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massagers-scored-written-terms; sections: “Can I try it and return it without postage costs?”; “How did you score the listings?”

## `PR_t05_what_if_the_battery_stops_charging_within_a_year.csv`

- **Source type:** Selected captured coverage statements
- **Collection/counting period:** Same source register, October 22–November 12, 2026
- **Observation unit:** A selected product/channel coverage record
- **Coding rule:** Keep general product coverage separate from explicit battery coverage.
- **Excluded or withheld:** Missing, conflicting or unsupported coverage is not scored as supported.
- **Known limits:** The source contains no device tests or lifespan follow-up.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massagers-scored-written-terms; sections: “What if the battery stops charging within a year?”; “How did you score the listings?”

## `PR_t06_which_captured_pages_support_the_tables.csv`

- **Source type:** Published capture register
- **Collection/counting period:** October 22–November 12, 2026; some dates missing
- **Observation unit:** A source-register entry or grouped record reference
- **Coding rule:** Retain product and policy source descriptions and separate technical/policy dates.
- **Excluded or withheld:** Archive-only marketplace rows have no published marketplace links.
- **Known limits:** The exported register is grouped and does not supply a complete per-cell audit trail.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massagers-scored-written-terms; sections: “Which captured pages support the tables?”; “How did you score the listings?”

## `V1_t01_what_should_i_check_before_buying_a_heated_knee_ma.csv`

- **Source type:** Captured seller/supplier listings and policy pages
- **Collection/counting period:** October 22–November 12, 2026; some source dates are missing
- **Observation unit:** A written criterion, aggregated across 32 comparison records
- **Coding rule:** Count only statements with retained support; Welnexx is outside the comparison denominator. Partial or restrictive information can count.
- **Excluded or withheld:** Missing, conflicting and unsupported cells do not count as supported.
- **Known limits:** A supported statement is not a favorable condition or verified feature.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-index; sections: “What should I check before buying a heated knee massager?”; “How did we check the listings and handle missing information?”

## `V1_t02_which_specifications_did_each_product_put_in_writi.csv`

- **Source type:** Captured listings
- **Collection/counting period:** October 22–November 12, 2026; R00 technical capture October 23
- **Observation unit:** One listing record, with technical checks K1–K6
- **Coding rule:** Preserve separate channel observations and condition-level wording.
- **Excluded or withheld:** Do not invent evidence for missing, conflicting or unsupported cells.
- **Known limits:** The convenience sample includes heating pads and stimulation/gel-pad alternatives. It is not a device-performance test.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-index; sections: “Which specifications did each product put in writing?”; “How did we check the listings and handle missing information?”

## `V1_t03_what_do_the_warranties_and_return_policies_actuall.csv`

- **Source type:** Captured product and policy pages, with canonical Welnexx policy update
- **Collection/counting period:** Comparison captures October 22–November 12, 2026; Welnexx policy updated November 12
- **Observation unit:** One listing record, with policy checks K7–K11
- **Coding rule:** Use current Welnexx K9–K11 terms; retain unresolved conditions as not stated rather than selecting a favorable interpretation.
- **Excluded or withheld:** No unsupported coverage or return condition is asserted.
- **Known limits:** Historical captured terms are not a current policy check.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-index; sections: “What do the warranties and return policies actually say?”; “How did we check the listings and handle missing information?”

## `V1_t04_do_more_advertised_features_mean_a_higher_price.csv`

- **Source type:** Historical brand-site offer captures
- **Collection/counting period:** October 22–23, 2026
- **Observation unit:** A group of retained offers by extracted feature-category count
- **Coding rule:** Use only recorded feature categories and numeric retained offers; preserve the published median and range.
- **Excluded or withheld:** Exclude marketplace prices captured November 9, records without numeric prices, and the extracted Nooro amount assigned to a bonus e-book.
- **Known limits:** Mixed devices and unstandardized offer quantities cannot establish the value of an extra feature. No recalculation was performed for this package.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-index; sections: “Do more advertised features mean a higher price?”; “How did we check the listings and handle missing information?”

## `V1_t05_which_source_captures_support_the_product_and_poli.csv`

- **Source type:** Source-capture register
- **Collection/counting period:** October 22–November 12, 2026; R12 lacks retained supporting evidence
- **Observation unit:** A listing-record reference or group in the source register
- **Coding rule:** Keep source addresses and separate technical/policy dates as published.
- **Excluded or withheld:** Marketplace source links and recommendations are not published in those archival rows.
- **Known limits:** A grouped register row is not a complete per-cell provenance archive.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-index; sections: “Which source captures support the product and policy cells?”; “How did we check the listings and handle missing information?”

## `V3_t01_what_are_the_most_common_knee_massager_complaints.csv`

- **Source type:** Customer-language bank
- **Collection/counting period:** Counted November 12, 2026; collection start/end not stated
- **Observation unit:** Distinct source-record IDs assigned to device-issue groups
- **Coding rule:** Join each selected record to its merged group once; complaint column selects complaint codes only. The wider people column includes other codes.
- **Excluded or withheld:** Wishes, solutions, fears and questions are excluded from the complaint denominator, but retained in the wider group counts.
- **Known limits:** 134 complaints and 162 language records are different denominators; the people convention does not verify purchaser identity.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-complaints-counted; sections: “What are the most common knee massager complaints?”; “How were the complaints and review topics counted?”

## `V3_t02_why_does_it_stop_working_or_fail_to_hold_a_charge.csv`

- **Source type:** Star-filtered archived-review coding
- **Collection/counting period:** Coding completed and counted November 12, 2026; collection start/end not stated
- **Observation unit:** Review with a primary charging/battery or stopped-working topic and stated time
- **Coding rule:** The selected timing subset contains 45 reviews. The coded 2–3-month interval uses the stated midpoint of 2.5 months.
- **Excluded or withheld:** Reviews without a stated time are outside this timing subset.
- **Known limits:** Other-product reviews remain in the archive. The reported median of 3 months is not service life or a failure rate.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-complaints-counted; sections: “Why does it stop working or fail to hold a charge?”; “How were the complaints and review topics counted?”

## `V3_t03_why_does_it_not_fit_stay_fastened_or_feel_strong_e.csv`

- **Source type:** Welnexx product/supplier record
- **Collection/counting period:** October 23, 2026
- **Observation unit:** A requested fit or control detail
- **Coding rule:** Record the available written information for strap/circumference and independent vibration-off instructions.
- **Excluded or withheld:** Do not infer fit or control instructions from adjustable-mode wording.
- **Known limits:** Supplier statements do not establish independently verified fit or operation.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-complaints-counted; sections: “Why does it not fit, stay fastened, or feel strong enough?”; “How were the complaints and review topics counted?”

## `V3_t04_how_can_i_tell_whether_reviews_belong_to_a_differe.csv`

- **Source type:** Listing-history audit
- **Collection/counting period:** November 9, 2026
- **Observation unit:** Review-date comparison within an anonymized listing
- **Coding rule:** Compare archived review dates with listing first availability; retain the displayed subset and Total row.
- **Excluded or withheld:** Listing identities and ratings are omitted. The displayed listings are a subset of the inspected listings.
- **Known limits:** A pre-availability date is a continuity signal, not proof of an invented review.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-complaints-counted; sections: “How can I tell whether reviews belong to a different product?”; “How were the complaints and review topics counted?”

## `V3_t05_how_were_the_complaints_and_review_topics_counted.csv`

- **Source type:** Star-filtered archived-review coding
- **Collection/counting period:** Coding completed and counted November 12, 2026; collection start/end not stated
- **Observation unit:** Distinct archived review ID
- **Coding rule:** Across all 10 completed slices, assign each of 1,184 distinct review IDs one primary topic; the source reports matching input/coded IDs with no missing or duplicate IDs.
- **Excluded or withheld:** Secondary topic labels are excluded; positive, neutral and other-product reviews remain included.
- **Known limits:** Country and listing histories differ. Topic shares are not complaint, defect or return rates.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-massager-complaints-counted; sections: “How were the complaints and review topics counted?”

## `V4_fda_records.csv`

- **Source type:** Public CPSC/FDA records and a published MAUDE analysis
- **Collection/counting period:** Official records captured November 12, 2026. The study uses FDA receipts January 1, 2016–December 31, 2025 and extraction September 8, 2026
- **Observation unit:** Exported public source/measure row, not one injured person
- **Coding rule:** Preserve source class, public reference, device scope, date meaning, event code and original quantity. The English schema uses source, record_id, date, device_type, event, count and url. Source classes are CPSC, FDA_MAUDE, STUDY_MAUDE and FDA_RECALL_NOTICE. Recalled devices, event reports and injuries remain separate measures.
- **Excluded or withheld:** The export includes the official records and the published powered-heating-pad analysis total. No exposed-user denominator or completed matching across sources is supplied.
- **Known limits:** Date meanings depend on source type. A MAUDE event date differs from its FDA receipt date; the study interval covers FDA receipts. Reports do not establish causation, and the measures cannot produce a combined injury rate.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-device-burn-safety-records; sections: “What do the CPSC recall records actually count?”; “Does a MAUDE report prove a device caused an injury?”; “Which sources and dates support this review?”

## `V4_t01_what_do_the_cpsc_recall_records_actually_count.csv`

- **Source type:** Official CPSC notices and individual FDA MAUDE records
- **Collection/counting period:** Captured November 12, 2026; displayed dates have source-specific meanings
- **Observation unit:** Public record with one or more recorded measures
- **Coding rule:** Keep recall units, report counts, injury counts, device categories and event dates separate.
- **Excluded or withheld:** Do not relabel neck wraps, handheld massagers or combined blanket/pad records as knee-only incidents.
- **Known limits:** No completed overlap-matching process is stated; reported counts must not be summed into a burn rate.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-device-burn-safety-records; sections: “What do the CPSC recall records actually count?”; “Which sources and dates support this review?”

## `V4_t02_how_many_product_listings_advertise_heat_above_113.csv`

- **Source type:** Temperature criterion of captured written-information records
- **Collection/counting period:** Reviewed November 12, 2026; captures October 22–23 and November 12
- **Observation unit:** Included supplier/seller listing record
- **Coding rule:** Start with 33 product records; exclude 10 Amazon records, retaining 23. Count each once, even with multiple settings or power options.
- **Excluded or withheld:** A level count without a numerical temperature does not enter the numerical-temperature groups.
- **Known limits:** 9 records exceed 113°F; this is an advertised-temperature count, with no independent measurement or safety-cutoff interpretation.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-device-burn-safety-records; sections: “How many product listings advertise heat above 113°F?”; “Which sources and dates support this review?”

## `V4_t03_how_many_product_listings_advertise_heat_above_113.csv`

- **Source type:** Seller/supplier captures with numerical temperatures
- **Collection/counting period:** October 22–23 and November 12, 2026
- **Observation unit:** One listing record with numerical temperature evidence
- **Coding rule:** Retain each numerical record once; multiple power options belong to one listing.
- **Excluded or withheld:** The nonnumerical captured records are not reproduced in this detail table.
- **Known limits:** Advertised settings do not establish skin-contact temperatures or individual suitability.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-device-burn-safety-records; sections: “How many product listings advertise heat above 113°F?”; “Which sources and dates support this review?”

## `V4_t04_does_113_f_tell_me_when_heat_will_burn_skin_over_6.csv`

- **Source type:** Evidence-gap summary of listing and incident records
- **Collection/counting period:** October 22–23 and November 12, 2026
- **Observation unit:** Device-specific evidence question
- **Coding rule:** Mark the requested independently measured or age-specific evidence as not stated.
- **Excluded or withheld:** No age-specific temperature/time experiment is provided by these records.
- **Known limits:** The comparison cannot yield a burn probability or personal-use limit.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-device-burn-safety-records; sections: “Which sources and dates support this review?”

## `V4_t05_does_a_maude_report_prove_a_device_caused_an_injur.csv`

- **Source type:** FDA recall announcement and recall update
- **Collection/counting period:** Captured November 12, 2026; notice dates October 24, 2022 and March 25, 2026
- **Observation unit:** FDA announcement with its source-specific recorded measure
- **Coding rule:** Retain recalled units separately from serious injuries and keep the injury as-of date distinct from notice date.
- **Excluded or withheld:** Do not recode all serious injuries as burns or label dated announcement titles as official recall numbers.
- **Known limits:** A recalled-unit count and a broader injury count do not share a denominator.
- **Source page and sections:** https://welnexx.com/blogs/guides/heated-knee-device-burn-safety-records; sections: “Does a MAUDE report prove a device caused an injury?”; “Which sources and dates support this review?”

## `V5_t01_which_everyday_approaches_did_people_say_helped_mo.csv`

- **Source type:** Selected public discussion records and a seller-hosted review
- **Collection/counting period:** Counted November 12, 2026; collection start/end not stated; guideline captures November 11
- **Observation unit:** Each recorded person once per approach, aggregated by named approach
- **Coding rule:** The selected collection has 34 people: 33 Reddit records and 1 seller-hosted review. Preparation removed 3 duplicates and 3 outside-selection entries from 40 candidates. Positive and negative codes were counted separately.
- **Excluded or withheld:** The displayed named-approach table excludes the mixed other category. A blank approach field is not a failed attempt.
- **Known limits:** A person can occur in several approaches. Accounts include relatives and different surgery circumstances; diagnoses, severity and follow-up are not independently matched. The export contains counts and guideline context without reproducing individual accounts.
- **Source page and sections:** https://welnexx.com/blogs/guides/bone-on-bone-knee-what-helped; sections: “Which everyday approaches did people say helped most?”; “How were these bone-on-bone reports counted?”
