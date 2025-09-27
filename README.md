# UI-UX-Experiment3

## Aim:
To perform a heuristic evaluation of an existing website (OLX) by analyzing its usability issues, propose suitable design improvements, and develop a recommendation algorithm that prioritizes featured, recent, and popular listings for the Fresh Recommendations section, thereby enhancing the overall user experience.
## Algorithm:
1.Collect Data

Gather all active product listings from the database.
Each listing includes attributes such as: product name, price, location, date posted, category, number of views, and whether it is marked as featured.

2.Filter Listings

Remove any inactive or expired listings (sold, deleted, or outdated).
Keep only valid and available products.

3.Prioritize Featured Ads

Featured products are given higher priority so they appear at the top of recommendations.
This ensures that paid promotions or special items get more visibility.

4.Sort Remaining Listings

Among the non-featured items, listings are sorted using certain factors:
Recency → newer posts appear before older posts.
Popularity → items with more views or interactions are ranked higher.
Relevance → optional step, based on user’s past searches or preferences.

5.Select a Subset

From the sorted list, select the top N products (e.g., 10–20) to display under Fresh Recommendations.
This keeps the section short, relevant, and easy to browse.

6.Display Products

Present the selected products in a grid format.
Each card shows key information: product image, price, title, location, and a favorite/like button.

## Output:
<img width="1919" height="956" alt="image" src="https://github.com/user-attachments/assets/062591bd-a288-4fb9-8320-27241956ff9a" />

## Result:
succesfully analyzed and deployed .
