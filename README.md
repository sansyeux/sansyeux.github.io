# Nocturne — Music Chart Site

A community-driven music rating and discovery site, styled with the [Dracula theme](https://draculatheme.com/).

## Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage — hero, trending chart, genre grid, recent reviews, community lists |
| `charts.html` | Full chart browser with filters and pagination |
| `albums.html` | Album grid with search and genre/sort filters |
| `artists.html` | Artist grid with search and filters |
| `genres.html` | Genre directory organized by category |
| `lists.html` | Community curated album lists |
| `search.html` | Site-wide search with live skeleton loading |
| `login.html` | Login page with Google OAuth option |
| `signup.html` | Registration page |
| `style.css` | Shared Dracula theme stylesheet |

## GitHub Pages Setup

1. Push this folder to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://<username>.github.io/<repo-name>/`

## Design

- **Theme**: Dracula (official palette — `#282a36` background, `#bd93f9` purple, `#ff79c6` pink, `#8be9fd` cyan, etc.)
- **Fonts**: Syne (display/headings) + Space Mono (body/UI)
- **Framework**: Vanilla HTML/CSS/JS — no build step required

## Adding Data

The site uses skeleton placeholder states throughout. To populate with real data:
- Replace `.skeleton` elements with real content in each `.html` file
- Or wire up a backend/API and populate dynamically via JS
- Album art images go in an `/assets/` folder and can be referenced as `<img src="assets/album-name.jpg">`

## Color Reference (Dracula)

```css
--bg:      #282a36   /* Background */
--bg-alt:  #21222c   /* Alt background */
--fg:      #f8f8f2   /* Foreground */
--purple:  #bd93f9   /* Primary accent */
--pink:    #ff79c6   /* Secondary accent */
--cyan:    #8be9fd   /* Info / links */
--green:   #50fa7b   /* Success */
--yellow:  #f1fa8c   /* Ratings / warnings */
--orange:  #ffb86c   /* Highlights */
--red:     #ff5555   /* Danger */
```
