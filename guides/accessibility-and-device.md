# Accessibility, reminders, and offline use

[Guide index](../README.md) · [Report an accessibility problem](https://github.com/lukaluka/savorloop-community/issues/new?template=accessibility.yml)

## Larger text and screen-reader use

The current interface uses native controls, text that can wrap, and scrolling forms. Its larger-text layout changes some horizontal groups into vertical arrangements. Use your device's preferred text-size and accessibility settings, then check the screen you need.

Do not assume the current development build has completed every physical-device or VoiceOver acceptance test. If a control is clipped, unlabeled, difficult to focus, or impossible to reach, an accessibility report is useful even if another person can use the same screen visually.

In a report, identify the screen and control, the relevant accessibility feature, the expected interaction, and what happened. Include whether larger text, VoiceOver, Reduce Motion, or another setting was enabled when relevant. You do not need to disclose a diagnosis or disability.

## Read long forms

Onboarding and preference pages scroll. If a keyboard obscures a field or a control appears below the visible area, dismiss the keyboard where possible and scroll. Use **Back** to revisit earlier setup pages. A page that remains unreachable at a supported text size is a bug worth reporting.

## Optional reminders

In **You → Gentle reminders**, the current build offers **Prep at 6 pm** and **Plan on Sunday at 10 am**. Turning one on can request system notification permission. Read any status message shown by the app.

If a reminder is missing, check whether the relevant toggle is on and whether the device allows notifications for the app. Device notification settings and focus modes can affect presentation. Reopening the app and reviewing the status message can help distinguish denied permission from an app problem.

Reminders are conveniences. They are not monitored alerts or a substitute for a separate time-critical reminder. The current UI does not offer arbitrary reminder schedules in the documented flow.

## Offline planning

Saved plans, the bundled food library, deterministic planning, and preference learning are designed to work locally. Using a public issue, opening a publisher's website, or visiting an external support page requires a network connection.

Local generative features have separate device and model availability requirements. Open **You → On-device intelligence** to read the current availability message. The app should continue to use its deterministic planning path when a qualifying local model is unavailable; a model-unavailable message does not mean that a remote language service is processing your history.

The development build does not promise that an optional model is approved on every device or that changing an operating-system setting will make it available. Do not install an unofficial model download in response to an issue comment or a message claiming to be support.

## Keep the screen awake while preparing

The **Prep** tab includes **Keep screen awake while prepping**. This setting helps while reading tasks during active use. Turn it off when finished if you do not need it. See [groceries and prep](groceries-and-prep.md) for timer limitations.
