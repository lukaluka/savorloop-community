# Frequently asked questions

[Guide index](../README.md) · [Support](../SUPPORT.md)

### Where can I download SavorLoop?

No public App Store or TestFlight release is announced in this repository. Check [availability](availability.md). This repository contains documentation, not an installable app. Do not install an attachment offered by an unknown commenter.

### Do I need an account?

The current app does not require a SavorLoop account for local planning. A GitHub account is needed to submit or comment on a public ticket here.

### Does it work offline?

Core planning, saved plans, feedback, and the bundled library work locally. GitHub support and external publisher pages need internet access. Optional on-device generative features have separate availability requirements.

### Does the app send my nutrition history to an AI service?

The documented build does not use a remote meal-planning language-model service. Information you choose to export or post to GitHub is separate and leaves the app's local storage boundary.

### Can I use it across multiple devices?

The current build does not provide account-based cross-device sync. Its personal database is excluded from device backups. Review [data controls](privacy-and-data.md) before assuming a plan can be recovered on another device.

### Is an export a restorable backup?

It is a copy of your information. The current interface does not include a general import/restore workflow. Keep exports private and do not assume a one-tap restore.

### Can support recover deleted data?

Do not assume that it can. Local deletion is described as irreversible in the app, and support does not have a server copy of your local database. Copies you exported elsewhere are managed separately.

### Can it plan around every allergy or dietary requirement?

No. Unsupported strict requirements or insufficient eligible recipes can prevent planning. Filters cannot verify packaging, manufacturing, or kitchen cross-contact. Do not omit a necessary restriction to get a result.

### Does it provide a medically appropriate diet or target?

It provides consumer meal-planning estimates, not clinical care. The app blocks unsupported situations described in setup. Community support cannot choose personal clinical targets or override those boundaries.

### Why is a liked meal absent next week?

Feedback informs selection among eligible meals. Other restrictions, timing, equipment, variety, and the available catalog also matter. A positive rating does not reserve a slot in the next plan.

### Is “Never again” the same as “less often”?

No. It excludes the recipe until you explicitly allow it again in **You**. It can also require rebuilding a current week containing that recipe.

### Why does the grocery quantity differ from the meal quantity?

The meal shows your planned portion; groceries cover the configured household and can combine usage across meals. Read raw/cooked food states before comparing weights.

### Are prices and budget totals current?

No live local price feed or reliable checkout estimate is included in the current build. Your optional budget is stored as a preference.

### Can I add any food-library result to a plan?

The reference library is broader than the reviewed planning catalog. A search result is not automatically approved for meal planning or allergy safety.

### Does a missing nutrient mean zero?

No. It means the value is unavailable. Trace values, measurement limits, quantity bases, and nutrient definitions need to be read as reported.

### Does deleting local data cancel billing?

No. Local deletion and Apple billing are separate. Purchases are disabled in the documented development build; no price or paid-release date is promised here.

### Are support tickets private?

No. Issues and ordinary pull requests are public. Use fictional data and redacted screenshots. Private vulnerability reporting is available for security issues; it is not a private general-support inbox.

### When will my ticket be answered?

Maintainers triage tickets as capacity allows. There is no published response-time guarantee, 24-hour service, or emergency-support commitment. Add useful detail to your existing ticket rather than opening duplicates.

### Is the app open source because this repository is public?

No. This is a public documentation and support repository. It does not contain the private application code or grant a license to it. Read [content and reuse](../NOTICE.md).


### How many recipes are in development?
The current development catalog contains 252 recipes, including two new no-cook compositions. This count excludes food-library records and portion variants. Availability in your installed release can differ. Recipes have engineering checks; kitchen testing and professional nutrition review are separate and are not claimed. Check all ingredient labels and your necessary exclusions; no app can certify kitchen cross-contact.
