# Your preferences, restrictions, and targets

[Guide index](../README.md) · [Getting started](getting-started.md)

Open **You → Edit preferences** to revisit the four setup pages. Complete the flow and choose **Save and rebuild plan**. Review the rebuilt plan before relying on an earlier grocery list or prep checklist.

## Firm boundaries and softer preferences

Allergies, explicit ingredient exclusions, excluded recipes, and required restrictions constrain what the planner can use. Likes, dislikes, cuisine choices, and repetition preferences influence which eligible meals it favors. Liking a meal must not override a hard exclusion.

In **Foods you love, dislike or never eat**, the choices have different purposes:

- **Love** is a positive preference signal.
- **Dislike** asks the planner to favor other eligible choices where it can.
- **Exclude** is a firm ingredient boundary.

Recipe-level **Never again** is separate from ingredient-level **Exclude**. Reversing a recipe exclusion does not remove an allergy or an ingredient exclusion from your profile.

## Allergies and strict restrictions

Select all applicable supported allergies. If a strict requirement is not represented by a listed choice, use **Other allergy or strict restriction**. An unsupported entry may prevent a plan; that is preferable to having the requirement silently ignored.

Review ingredient labels and preparation conditions yourself. The app's catalog and filters cannot verify manufacturing, substitutions made outside the app, or kitchen cross-contact. A record in the general food library has not automatically been approved for your meal plan or assessed for your allergy needs.

If a meal appears inconsistent with an exclusion, stop relying on that recommendation and submit a [food-data or safety-behavior report](https://github.com/lukaluka/savorloop-community/issues/new?template=food_data.yml) using a fictional profile and the recipe name. Do not post your personal allergy or medical history.

## Planning estimates

The current build collects adult planning inputs and can accept optional manual calorie and protein targets. It validates values before proceeding. Selecting a manual target does not bypass eligibility or safety checks.

The current product does not generate a standard plan for unsupported ages or for the clinical situations identified in its setup flow, including pregnancy/breastfeeding, a need for clinical nutrition guidance, or an eating-disorder history. Community maintainers cannot select clinical targets for you or tell you to bypass those checks.

Targets and nutrient totals are planning estimates. They are not a diagnosis, treatment, prescription, or promised outcome. This guide intentionally provides no personal calorie or protein recommendation.

## Household, equipment, and timing

Choose the equipment that is actually available. Set the household size and maximum cooking time for your routine. Fewer available tools, less time, and more restrictions can leave fewer eligible recipes.

The meal-detail amounts describe one planned portion. Household scaling is applied to groceries and prep. Do not multiply the grocery totals by the household size a second time.

The repetition slider ranges from **More variety** to **Keep it familiar**. The leftovers setting records whether leftovers fit your plans; it does not guarantee an optimal batch-cooking schedule or provide a food-storage safety assessment.

## Budget and meals out

The optional weekly budget is a preference. Current local prices, package sizes, checkout totals, and savings are not supplied by the app.

Under **Plan around a busy day**, the current flow offers dinner-out choices for the seven plan days. Nutrition for those meals is unknown and excluded from planned totals. Recording **Ate out** later is a behavior entry, not a restaurant calorie calculation.

If the resulting plan cannot be created, read [troubleshooting](troubleshooting.md) and report the general constraint combination without personal details.

## A taste profile that develops over time

**You → Your Taste** starts with what you told the app and develops from feedback across different meals. Open **Why this sounds like you** to inspect and correct learned patterns. Saved food preferences take priority over inferred patterns; edit those through **Edit preferences**. Your allergies, restrictions, and exclusions remain firm boundaries. See [Your Taste and feedback](feedback.md#your-taste) for the controls and how learning works.


## Measurement units

Choose **Metric** or **Imperial** during target setup, or open **You → Measurements** to switch at any time. Metric uses centimeters and kilograms for body measurements, and grams/kilograms for food. Imperial uses total inches for height (5 feet 10 inches = 70 inches), pounds for body weight, and ounces/pounds for food weights.

The choice is saved on your iPhone and included in your data export. Switching from You updates displayed quantities without rebuilding your week or resetting checked groceries and prep tasks. Existing profiles start in Metric. Quantities are rounded for display only; nutrition calculations stay unchanged. Nutrition labels and food-source nutrient bases retain grams/milligrams and the source’s stated basis. Ounces here are weight, not fluid ounces; cups and spoons are not inferred from weight.
## Tell us how you like to eat (optional)

Open **You → How you like to eat**, or expand the optional section on the last setup page. Write a short blurb, choose **Review my blurb**, then correct the breakfast, lunch and dinner choices before saving. You can also choose a routine directly or skip it entirely.

The current offline English phrase recognizer supports smoothies, preparing ahead/reheating, simple protein-carb-vegetable meals, quick meals and no-cook meals. It does not understand every sentence. Only the displayed choices affect suggestions; unrecognized text stays saved as your wording. Review again after changing the text, or adjust the choices yourself. No allergies or nutrition targets are inferred from this field.

Two independent switches start off: **Personalize my weekly meal plans** and **Personalize my recipe recommendations**. Choose either, both or neither. Recommendations currently means the alternatives shown when swapping a meal. With both off, this saved routine has no influence; the app's existing meal feedback and saved food preferences still work as before.

Saving here keeps your current week. Plan changes apply when you generate another plan; recommendation changes apply when you next view meal alternatives. Cancel discards unsaved edits. **Clear my blurb and routine**, followed by **Save**, removes the text and choices and turns both switches off. Your routine stays on your iPhone and is included in the existing export and local deletion controls.

Routine choices are gentle preferences, not guarantees. The app shows a notice when no eligible recipe matches a choice. Four breakfast smoothies are available: berry banana yogurt, banana peanut yogurt, berry avocado chia, and apple banana peanut. The last two use plant ingredients only. Select Blender in your kitchen equipment if you have one, choose Smoothies for breakfast, then enable weekly plans, recipe recommendations, or both. Plan changes apply when you create your next plan; recipe recommendations appear when you swap a breakfast. Smoothies include measured ingredients, nutrition, preparation steps and grocery quantities. Allergies and exclusions may reduce the available options. Rate meals as usual to help the app learn what you like. Preparing ahead favors suitable existing cooking templates; it does not create a batch-cooking schedule or certify storage/reheating safety. Allergies, restrictions, equipment limits and exclusions always apply.
### Cuisine preferences

Use **Other cuisines** to save additional cuisines, separated by commas. These tastes do not prevent planning if matching recipes are not available yet. Keep allergies and strict restrictions in their separate field. If you accidentally entered a cuisine as a restriction, clear that field and enter it under Other cuisines to continue.


### Explore your taste

In **You**, choose **Explore your taste** on the green Your Taste card. Each pattern shows whether it comes from saved preferences, meal feedback, or your own adjustment. Expand **Meals behind this pattern** to see the supporting meals. Use **Adjust this pattern** to ask for more, less, ignore it, or resume learning.
