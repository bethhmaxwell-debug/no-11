# Beth & Rich Family Hub

This repo contains the public GitHub Pages version of our family planning hub.

The site is a simple home base for practical planning tools:

- Finance Forecast
- Balanced Working Week
- Dinner Rota

The live site is published with GitHub Pages from this repository.

## What Each File Does

```text
index.html
```

The homepage for the family hub. It links to the planning tools and shows the latest published update time.

```text
balanced-working-week.html
```

The working week planner. This is a standalone page for viewing family work, childcare, and weekly rhythm.

```text
family-dinner-rota.html
```

The dinner rota planner. It shows one week at a time, supports a two-week rhythm, lets meals be changed, and includes a local meal bank.

```text
finance-forecast/
```

The public-safe built version of the finance forecast app. This is generated from the separate public finance app source copy and should not be edited by hand unless making a very small static-file fix.

## Editing And Publishing Flow

Use this basic workflow:

1. Make or request changes locally.
2. Review the changed files in GitHub Desktop.
3. Commit the changes with a short clear message.
4. Push to GitHub.
5. Wait for GitHub Pages to rebuild.
6. Check the live site.

GitHub Pages usually updates within a minute or two, but it can sometimes take longer.

## Suggested Commit Messages

Use short messages that describe the visible change:

```text
Update family hub homepage
Polish dinner rota layout
Add meal to dinner rota
Update working week planner
Refresh finance forecast build
Add project notes
```

## Public Safety Notes

This GitHub Pages site is public.

Do not add:

- Real bank balances
- Real salaries
- Account numbers
- Passwords or passcodes
- Private documents
- Sensitive family, medical, school, or childcare information
- Anything that would be uncomfortable if shared outside the family

For the finance app, keep using a public-safe demo dataset on the published site. Private finance data should stay local and should only be imported by the user into their own browser if needed.

## How Data Is Stored

Some tools may save changes in the browser using local storage.

That means:

- Changes may only exist on that device/browser.
- Clearing browser data may remove saved local changes.
- Local saved data is not automatically committed back to GitHub.
- Public default data should still be changed in the repo files if it needs to be part of the published site.

## Current Design Direction

The hub should feel:

- Warm
- Simple
- Modern
- Family-specific
- Calm rather than busy
- Easy to navigate on mobile

Avoid making it feel like a corporate dashboard or a test project page.

## Future Ideas

Possible improvements:

- Add export/import for Dinner Rota data.
- Add a shopping list generator.
- Add recipe notes or links.
- Improve mobile navigation across all tools.
- Add a private version later if needed.
- Move repeated styles into shared CSS if the project grows.

## Notes For Future Codex Sessions

When returning to this project:

1. Work in the local repo folder:

```text
/Users/elizabethmaxwell/Documents/Codex/no-11
```

2. Check the current git status before editing.
3. Avoid overwriting user changes.
4. Keep the site public-safe.
5. Prefer small, understandable changes.
6. After edits, tell the user exactly what GitHub Desktop should show and suggest a commit message.

