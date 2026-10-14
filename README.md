# Whisk & Wonder

A baking club website for young bakers (ages 8 to 12, with careers content for 10 to 18).

- **Recipe Book:** 1,008 meat-free recipes (about 110 master recipes plus variations), with filters for vegan, gluten-free, low sugar (5 g or less added sugar per portion), nut-free, sweet or savoury, season, level and festival. Diet labels and allergens are worked out from each recipe's ingredients.
- **Create my own recipe:** add your own recipes or copy any recipe and change it. Your recipes work in the planner, shopping list and bake-along.
- **Planner:** three family bakes a week, half or double batches, and a tickable shopping list grouped by aisle for Tesco, Co-op or Lidl.
- **Festivals:** 26 festivals from many faiths and cultures with dates and countdowns, plus what's in season in the UK each month.
- **Learn:** Baking School, Kitchen Safety, Maths Lab (scaling, ratios, timing, unit prices, cost and profit), Photo & Voice Diary, Bake a Business (a Somerset village bakery) and Baker Careers & CV.
- **Journal:** moods, star ratings, photos (camera on phones and tablets), voice notes and voice typing, with backup and restore.

## Files

- `index.html` is the whole website.
- `favicon.svg` is the browser tab icon.
- `fonts/` holds Bagel Fat One and Nunito (SIL Open Font License, licences included), so no outside font service is used.

## Put it on GitHub Pages

1. Create a public repository, for example `whisk-and-wonder`.
2. Upload `index.html`, `favicon.svg` and the `fonts` folder to the top level.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. The site appears at `https://<your-username>.github.io/whisk-and-wonder/` after a minute or two.

The microphone and camera need HTTPS, which GitHub Pages provides.

## Privacy

- No accounts, logins, analytics, cookies, third-party scripts or outside requests.
- Plans, recipes, the CV and business plan are saved in the browser (`localStorage`). Photos and voice notes are saved in the browser (IndexedDB). Nothing is sent to any server.
- **Voice typing** uses the browser's built-in speech service. In Chrome, Edge and Safari this may send the child's voice to the browser maker (such as Google, Microsoft or Apple) to turn it into text. The site shows a "grown-up says OK" notice before first use. Voice notes (recordings) never leave the device.
- Clearing browser data deletes everything, so the Journal page offers a backup file to save and reload.
- GitHub keeps standard server logs (such as IP addresses) for security. The site owner can't see these. See GitHub's privacy statement.

## Content notes

- Recipes are written carefully but have not been test-baked. Test them before launch.
- Business, food-safety and careers facts were checked in October 2026 against GOV.UK, Somerset Council, the NHS and apprenticeship listings. Rules change, so review them each year.
- Festival dates for moon-based festivals (such as Eid, Diwali and Lunar New Year) are listed for 2026 to 2028. Add new years to `FESTIVALS` in `index.html` before 2029.
