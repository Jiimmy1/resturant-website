# PizzaRestaurant

This is a small static website for a restaurant (Food Lover) — menu, offers, gallery and contact form.

How to preview locally

1. Open `index.html` in your browser (double-click or use PowerShell):

```powershell
ii .\index.html
```

How to deploy to GitHub (quick steps)

1. Create a new repository on GitHub named `pizzaresturant` (private or public).
2. On your machine, add the remote and push:

```powershell
# from project root
git remote add origin https://github.com/<your-username>/pizzaresturant.git
git branch -M main
git push -u origin main
```

Notes

- I added a responsive menu layout and a contact section at the bottom.
- Consider converting the SCSS-like nested blocks in `style.css` into valid CSS (I can do that for you).
- If you'd like GitHub Pages hosting, enable Pages in the repo settings and point the source to the `main` branch.
