# Sign-Up Form

A sign-up page for an imaginary service, recreated from a design file using only HTML and CSS. It's the first project after The Odin Project's Foundations course, built to practise layout, web fonts, and native form validation.

- 🔗 [Live demo](https://unstoppable-aj-limitsnotfound.github.io/sign-up-form/)
- 📂 [Repo](https://github.com/Unstoppable-AJ-LimitsNotFound/sign-up-form)

## Features

- Two-column layout with an image sidebar and a form panel, built with Flexbox
- Logo area on a semi-transparent dark band so it stays readable over the busy background photo
- Custom Norse and Montserrat fonts loaded with `@font-face`
- Native form validation: required fields, email format check, and an 8-character minimum on passwords
- Password inputs turn red when invalid (`:user-invalid`); focused inputs get a blue border and soft shadow (`:focus`)
- "Create Account" button placed outside the form but still wired to it

## Built With

- HTML5
- CSS3 (Flexbox, `@font-face`, pseudo-classes, box-shadow)

## What I Learned

- **Flexbox came back fast.** After a break from projects, I expected it to feel fuzzy, but the layouts came together without much second-guessing.
- **Web fonts.** First proper use of `@font-face` to load and apply custom fonts from local files.
- **Backgrounds and shadows.** Using `background-image` with sizing and positioning for the sidebar, and learning that a `box-shadow` spread radius also shows up on sides you didn't intend.
- **Forms are their own world.** Input types, `required`, `minlength`, labels tied to inputs with `for`/`id`, and how the browser validates natively.
- **Pseudo-classes for state.** `:focus` for the active input and `:user-invalid` for password errors, which only fires after the user has interacted with the field.
- **A button doesn't have to live inside its form.** It wasn't submitting until I linked it with the `form` attribute.
- **Refreshing through docs.** MDN and W3Schools got me through forgotten properties, with no major roadblocks.

## Odin Requirements

- [x] Git repository set up, with regular commits
- [x] HTML and CSS files linked and structured to match the design
- [x] Background image sourced and credited to its creator
- [x] External font used for the logo section
- [x] Odin logo used in the sidebar
- [x] Semi-transparent dark background behind the logo
- [x] "Create Account" button uses `#596D48`
- [x] Inputs use a `#E5E7EB` border by default
- [x] Invalid password inputs get a red border via `:user-invalid`
- [x] Focused inputs get a blue border and subtle box-shadow via `:focus`
- [x] Each field validated separately (matching passwords needs JavaScript, which comes later)

## Known Limitations

- Not responsive: the layout is designed for desktop only, as the assignment states
- Password and confirm-password fields aren't compared, since that needs JavaScript
- The form doesn't submit anywhere, because it's a demo with no backend

## Running Locally

```bash
git clone https://github.com/Unstoppable-AJ-LimitsNotFound/sign-up-form.git
cd sign-up-form
```

Then open `index.html` in your browser. There's no build step.

## Credits

- Background photo by [Halie West](https://unsplash.com/@haliewestphoto) on [Unsplash](https://unsplash.com/photos/green-leaf-plant-in-close-up-photography-25xggax4bSA)
- Logo font: [Norse Bold](https://www.joelcarrouche.com/fonts/norse)
- Design and Odin logo by [The Odin Project](https://www.theodinproject.com/)