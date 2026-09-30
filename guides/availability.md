# Availability and known limitations

[Guide index](../README.md) · [Documentation changes](../CHANGELOG.md)

**Reviewed: September 17, 2026.** SavorLoop is in development. A public production or TestFlight release is not announced here. This support hub can be linked publicly without implying that the app is already available for download.

## What these guides describe

The current implementation includes four-step preferences, a local meal planner, Today and weekly plan views, meal instructions and portions, eligible meal swaps, feedback and explicit exclusions, household groceries, prep tasks and a timer, local reminders, data export/deletion, and an offline food-reference library.

These are descriptions of the development implementation. They are not a certification that every device, operating-system version, accessibility mode, or release configuration has completed acceptance testing. Your installed test build may differ; include its version when requesting help.

## Limits to understand

| Area | Current boundary |
| --- | --- |
| Distribution | No public download, enrollment link, or release date is promised here |
| Nutrition | Adult consumer planning estimates; clinical needs and unsupported eligibility are outside the standard plan |
| Allergies | Filters do not verify packaging or cross-contact; unsupported requirements may block planning |
| Planning variety | Limited by the reviewed recipe catalog and your constraints |
| Food search | A reference library, not automatic admission into meal planning |
| Barcode lookup | Exact matches in a bounded bundled sample; no universal live lookup or camera scanning |
| Budget | Stored preference; no verified local prices or checkout totals |
| Personal data | Local storage; no account-based cross-device sync or general import/restore interface |
| On-device generation | Subject to availability and evaluation requirements; deterministic planning is the fallback |
| Timers | Do not assume multiple concurrent timers or guaranteed background alarm delivery |
| Purchases | Production purchases disabled; Free daily planning and the Plus weekly-plan structure are implemented in development, with no subscription availability or release announced |
| Accessibility | Further device acceptance remains necessary; reports are welcome |
| Support | Public GitHub tickets and private security reporting; no private general-support inbox or response-time guarantee |

## Version information in reports

An app/build version and a food-reference version describe different things. Include the app/build version if known, and separately include the catalog or library version when reporting food-data behavior. If the app does not expose the information you need, say it is unavailable rather than guessing.

## Follow changes

Read [CHANGELOG.md](../CHANGELOG.md) for user-facing documentation updates and [existing issues](https://github.com/lukaluka/savorloop-community/issues) for reported problems. An issue being accepted or closed is not an announcement that a fix is present in your installed build. Look for an explicit released-version statement when distribution begins.

Do not treat a roadmap idea, third-party comment, or proposed documentation change as a promised feature or release date. Only maintainer-published availability information should be used as the basis for installation or purchase decisions.
