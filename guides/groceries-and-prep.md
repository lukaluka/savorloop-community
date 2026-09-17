# Groceries and prep

[Guide index](../README.md) · [Plans and meals](plans-and-meals.md)

Both tabs derive their quantities from the active saved plan. Review them again after changing preferences, swapping a meal, or rebuilding a week.

## Use the grocery list

1. Open **Groceries** after creating a plan.
2. Check the household count displayed above the list.
3. Browse the ingredients by aisle.
4. Expand an ingredient's meal usage when you want to see which recipes contribute to its total.
5. Tap its check control when you have it. Tap again to uncheck it.

The app saves the checkoff state locally. If an item unexpectedly becomes unchecked, note whether the plan changed first. A rebuilt list can represent a different set of plan items. If checks disappear after reopening an unchanged plan, include that distinction in a bug report.

## Interpret quantities correctly

The list describes exact plan usage in grams. It is not a supermarket cart, a package-size calculator, or a price quote. You may need to buy more than the displayed amount because packages come in fixed sizes.

Read the food state. A cooked ingredient is listed as cooked: use ready-cooked food or measure the amount after cooking, as appropriate to the recipe. The app does not automatically translate every cooked weight into a raw shopping quantity.

Meal-detail amounts are for a planned portion. Grocery totals include the configured household. Do not multiply the already-scaled grocery amount by the household size again. If totals look unexpected, compare the household setting, meal usage breakdown, food state, and active plan before filing a report.

## Work through Prep

1. Open **Prep**.
2. Read the estimated work time, storage note, and task details.
3. Work through the tasks in order. Some tasks depend on earlier steps.
4. Choose **Mark complete** after finishing a task.
5. Use **Undo completion** if you checked it by mistake.

If the app says **Complete the earlier steps first**, inspect the preceding tasks rather than treating the control as broken. Quantities shown alongside a task correspond to the current prep plan.

Preparation notes are planning aids. They do not assess the actual temperature, freshness, storage conditions, or safety of food in your kitchen.

## Timers and the screen-awake option

Tasks with a timer offer a duration button, such as a number of minutes. Starting it shows the current countdown in Prep. **Clear timer** stops or clears that timer. Use the displayed state to confirm which task the timer belongs to.

Starting a timer can request notification permission and schedule a local “Kitchen timer finished” notification. If scheduling fails, the app can tell you that the on-screen countdown is still running but its notification could not be scheduled. Check that message and the device's notification settings; notification presentation is not guaranteed in every device state.

Enable **Keep screen awake while prepping** if you want the prep screen to remain visible during active use. This is a convenience setting and may use more battery. Turn it off when you no longer need it.

The current timer UI presents a single active countdown. Do not assume a guaranteed background alarm, multiple simultaneous timers, or delivery while the device is unavailable. Check the actual behavior of your build before relying on it for time-sensitive cooking.

## A practical sequence

Review the week's meals, shop from the household list, then open Prep for the current plan. Mark tasks as you complete them and return to each meal for its full instructions. If you swap or regenerate meals midway through the process, review the updated ingredients and tasks before continuing.

For list mismatches, timer behavior, or lost checkoffs, see [troubleshooting](troubleshooting.md).
