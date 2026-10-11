# PayCalculator AU — Web Beta v1.3

Live test calculator: https://goldman-stanley.github.io/paycalculatorau/

Independent browser implementation of the native v1.3 calculator, with responsive desktop/mobile layouts and English/Chinese UI.

- Salary and PAYG regular withholding; one-off bonus, purchased leave and employer super.
- Annual after-tax-return estimate, deductions, Medicare/MLS and HELP.
- Financial years 2023–24 through 2029–30. Official PAYG available through 2026–27; future years show annual scenarios with explicit carried-forward parameter notes.
- ABS median and approximate percentile, tax tables and interactive tax explorer.
- Effective Work Value, state/regional public holidays, daily records, weekly/monthly summaries and actual savings goals.
- Purple, Blue and Big 4-inspired themes; light/dark appearance.

Calculations run locally. Work records, deposits, appearance and saved scenarios use this browser's local storage. No account, analytics, salary upload, native app sync, reminders or backup/restore. Clearing browser storage removes saved data.

The browser engine was compared with native Swift outputs across 588 salary scenarios and 112 state/year work projections (24,108 numeric comparisons). Rules and assumptions intentionally match the app. Estimates are not a guarantee of employer withholding or final ATO assessment.

Serve the directory over HTTP to develop (ES modules and JSON resources require an HTTP server). No runtime dependencies or build step.

Support / privacy: https://goldman-stanley.github.io/paycalculator-au-pages/#support
Feedback: https://github.com/goldman-stanley/paycalculator-au-pages/issues/new/choose

Public holidays retain attribution in `holidays.json`, also available from the holiday browser. Theme names reflect brand inspiration only; no affiliation or endorsement.
