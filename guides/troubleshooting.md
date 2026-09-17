# Troubleshooting

[Guide index](../README.md) · [Open a support ticket](../SUPPORT.md)

Start with the exact screen and message. Avoid repeated resets, app deletion, or sharing personal exports. If you can reproduce the issue with fictional data in a separate test context, report those steps instead of private information.

## A plan cannot be created

1. Read the message and any planning notes.
2. Review your saved preferences for unsupported or mutually incompatible constraints.
3. Check equipment and cooking-time choices against what you actually have available.
4. Distinguish a soft preference from an allergy or other firm requirement.
5. If the catalog cannot satisfy a necessary restriction, report the gap without removing that restriction just to force a result.

A blocked plan can be an intentional safety boundary. Include the general constraint combination and message in a ticket. Do not request clinical target selection through support.

## My week disappeared after a rating

If you chose **Never again** for a recipe in the active week, the app can deactivate that week so it stops recommending the excluded meal. Create a fresh plan. Historical records are retained locally. To reverse the exclusion, use **You → What SavorLoop is learning → Allow this meal again** before rebuilding.

## Preferences changed but the menu looks familiar

Finish the preference flow with **Save and rebuild plan**, or use **Rebuild this week** after appropriate feedback. A preference changes selection among eligible recipes; it does not guarantee a completely different menu. A narrow catalog and restrictive constraints can limit variety.

## A swap offers no suitable meal

The alternatives still have to satisfy the current restrictions and planning requirements. Do not use a swap as a way to bypass an allergy. Report the absence of an expected eligible alternative with a fictional setup and the meal name.

## Grocery quantities seem too large or too small

Check the household size, food state, ingredient's meal-usage breakdown, and whether the active plan recently changed. Meal-detail quantities describe a planned portion; grocery quantities already include the household. Package sizes and raw-to-cooked yields are not interchangeable with plan usage in grams.

## A grocery check or prep completion did not persist

Record the sequence: create a plan, check the item, leave the tab, return, close/reopen the app. Note whether you swapped a meal, rebuilt a plan, or changed preferences in between. Those details distinguish lost persistence from a regenerated list.

## Prep won't let me complete a task

Look for **Complete the earlier steps first**. Some tasks depend on earlier work. Review preceding tasks and complete the necessary ones. If a task remains blocked after its prerequisites are complete, report the task title and fictional sequence.

## A timer or reminder did not alert me

Separate the visible Prep countdown from the optional reminders in **You**. Check the active countdown and the app's notification status message. Verify device permission and notification presentation settings. The current countdown should not be assumed to guarantee an alarm in every background or locked-device state.

## A food or barcode is missing

Try a shorter food name or a different source. Refine a very broad search if only the first matches are shown. Barcode lookup is limited to a bundled product sample; it is not a complete live product database.

## A nutrient value differs from another source

Compare the record identifier, food state, quantity basis, nutrient definition, unit, and date. A missing or trace value is not necessarily zero. Report the exact field and a public publisher reference using the food-data form.

## The library cannot open

Leave and reopen the library once. The app may state that the meal-planning catalog remains available even if reference-library loading failed. Report the exact message and whether ordinary planning still works. Do not erase personal data to attempt to repair a bundled reference-library problem.

## On-device intelligence is unavailable

Read the availability message in **You**. Device, operating-system, model readiness, and app evaluation requirements affect this feature. Core deterministic planning is the fallback. A request for a remote-model API key or an unofficial model installation is not part of this support flow.

## Saved data cannot be opened after an update

Keep the app and its local data in place. Record the version before and after the update if known, the OS, and the exact non-sensitive message. Avoid repeated deletion/reinstallation. A historical plan may be preserved while its active recommendation is disabled if current requirements no longer match it.

## Export or purchase controls are confusing

**Export my data** produces a personal copy via the share sheet; it does not provide an import feature or automatically send a support ticket. **Remove temporary export** does not delete copies saved elsewhere. Purchases are disabled in the documented development build. Do not send payment to a person in an issue comment or reveal purchase credentials.

## What makes a useful ticket

Provide one problem per ticket, the affected screen, app/build version if available, device/OS version, numbered steps, expected result, actual result, and a redacted screenshot only if needed. Say “unknown” if a version is unavailable. In **You**, a value labeled as the food-data version is not necessarily the app build number.

Open the [issue chooser](https://github.com/lukaluka/savorloop-community/issues/new/choose) after checking [existing tickets](https://github.com/lukaluka/savorloop-community/issues). For security or unintended disclosure, use the [private route](../SECURITY.md).
