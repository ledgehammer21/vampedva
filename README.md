# Vamped site revisions

Static HTML mockups for the revised vampedva.com. Each page is self-contained (CSS, JS, images and the HV Cocktail font are inlined; only Bricolage Grotesque loads from Google Fonts), and the pages link to each other with relative paths.

| Page | File |
| --- | --- |
| Home | `index.html` |
| Roles & Pricing | `roles-pricing.html` |
| How It Works | `how-it-works.html` |
| About | `about.html` |
| For Virtual Assistants | `for-virtual-assistants.html` |
| Referral Partners | `referral-partners.html` |
| Book a Discovery Call | `book-a-call.html` |

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Notes

- The inner pages carry `<meta name="robots" content="noindex">` because they are previews. Remove it before launch.
- Links to the blog, login, privacy and terms pages go to the live vampedva.com.
