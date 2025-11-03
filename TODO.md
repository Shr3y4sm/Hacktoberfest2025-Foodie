# TODO: Add Advanced Search and Filtering (Cuisine and Rating Filters)

## Pending Tasks
- [x] Update products.json: Add "cuisine" field to each of the 21 products based on names/descriptions (e.g., Italian for pizza/lasagna, Indian for biryani, etc.)
- [x] Edit html/menu.html: Add cuisine custom-select dropdown (All Cuisines, Italian, Indian, Chinese, American, Thai, Vietnamese, Japanese, Mexican, Greek) in filter-bar after priceSelector
- [x] Edit html/menu.html: Add rating custom-select dropdown (All Ratings, Above 4.0, Above 3.0, Below 3.0) in filter-bar after cuisine selector
- [ ] Edit js/app.js: Add currentCuisineFilter and currentRatingFilter variables (default 'all')
- [ ] Edit js/app.js: Add event listeners for cuisineSelector and ratingSelector similar to priceSelector
- [ ] Edit js/app.js: Update applyFilters function to include matchesCuisine and matchesRating checks with AND logic
- [ ] Test: Load menu.html, apply individual filters, combine filters, verify results and existing functionality intact

## Completed Tasks
- [x] Create TODO.md file with plan steps
