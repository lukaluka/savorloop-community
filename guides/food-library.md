# Explore the food library

[Guide index](../README.md) · [Report a food-data issue](https://github.com/lukaluka/savorloop-community/issues/new?template=food_data.yml)

Open **You → Explore food library**. The library is an offline reference collection. Its records are not automatically eligible planning ingredients, and a search result has not automatically been assessed for your allergy needs.

## Search by name or exact barcode

Search the combined library or open one of the listed sources. Enter a food name or exact barcode in the search field. If a search returns many matches, refine the name; the screen may show only the first group of results.

If there are no matches, try a shorter name or another source. Barcode lookup covers the bundled Open Food Facts sample. It is not a universal product lookup, camera barcode scanner, or live request to a retailer. A missing barcode does not establish that a product does not exist or that its label is invalid.

## Read a record from top to bottom

1. **Food identity:** check the name and brand, when present.
2. **Food state:** distinguish raw, cooked, dry, ready-to-eat, or the publisher's other description.
3. **Quantity basis:** read what amount the nutrient values refer to. Per 100 g and per 100 ml are not interchangeable.
4. **Source and record:** note the publisher, release, record identifier, and available record date.
5. **Common nutrients:** read the values that have a recognized definition.
6. **All nutrient fields:** expand the section for additional fields and definitions.
7. **Publisher portions and notes:** read any reported portion weights and qualifications.

Some fields use specialized bases, such as a percentage of fatty acids, rather than the food's standard 100 g basis. Read the label next to the field before comparing it with another record.

## Missing, trace, and differently defined values

Missing means unavailable, not zero. Trace values and values below a measurement limit are shown as qualified values. A blank field must not be used as evidence that a food contains none of that nutrient.

Definitions can differ between publishers, including carbohydrate, fiber, energy, edible portion, and quantity basis. Two records with similar names may describe different foods, states, methods, or measurement dates. A dataset's publication date does not mean every food was measured that year.

## Current coverage

The documented development build includes 28,538 records in eight attributed packs: USDA Foundation Foods, USDA SR Legacy, FNDDS, the Canadian Nutrient File, Ciqual, CoFID, the Australian Food Composition Database, and a bounded Open Food Facts sample. The Open Food Facts pack contains 1,000 sampled products; it does not represent the full service.

Check the source and library versions shown in your installed build. This count describes the reviewed development snapshot, not a promise of live coverage or proof that every provider has released no newer data.

The meal planner uses a smaller reviewed ingredient catalog. Searching the larger library does not add a record to your meal plan or remove the need for food-state, quantity, and allergy review.

## Attribution and reference-pack exports

Open **Source & reuse terms** to read the publisher attribution, license information, notices, and source links. If you export a reference pack, its reuse terms still apply. That export contains public reference data; it is separate from **Export my data**, which contains personal app information.

This community repository does not redistribute the food databases. In-app publisher links and notices are the appropriate starting point for data provenance and reuse questions.

## Report a questionable value

Provide the source name, record identifier, field name, displayed value and unit, quantity basis, food state, and the relevant public publisher link. Explain the discrepancy precisely. A report that compares cooked food with raw food, or 100 ml with 100 g, may describe different measurements rather than an error. Use the food-data form and leave personal nutrition history out of the ticket.
