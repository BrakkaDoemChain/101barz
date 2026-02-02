# Images for the fabeltjes receptenboek

This directory contains image assets used in the _fabeltjes receptenboek_ project.
Use this folder for all images that are referenced from the application, documentation,
or related materials.

## Types of images stored here

Typical image types include:

- Recipe photos (finished dishes)
- Step-by-step preparation images
- Ingredient illustrations
- UI assets such as icons or decorative graphics

If you need a new type of image that does not fit one of the categories above, add a
short note to this README explaining the new category.

## Naming conventions

To keep the folder organized and avoid duplicates, follow these rules:

- Use **lowercase** file names.
- Use **hyphens** (`-`) to separate words (no spaces, no underscores).
- Keep names **descriptive** and in **English** where possible.
- Include context in the name, e.g.:
  - `recipe-lasagna-finished.jpg`
  - `step-lasagna-01-prepare-sauce.png`
  - `ingredient-tomato-illustration.svg`

When updating an existing image, keep the same file name if the semantics stay the same
(e.g., a better photo of the same recipe), so references do not break.

## Accepted image formats

Preferred formats:

- `png` for images that require transparency or sharp UI assets.
- `jpg` / `jpeg` for photos of dishes and other photographic content.
- `svg` for icons and scalable vector graphics.

Before adding a new image:

- Choose the most appropriate format from the list above.
- Avoid very large source files when a smaller version is sufficient.

## Guidelines for adding new images

- Place all images directly under this directory or, if needed, in a clearly named
  subfolder (e.g. `recipes/`, `steps/`, `icons/`).
- Ensure that the image is **licensed for use** in this project (no unlicensed or
  copyrighted images without permission).
- Optimize images for size where reasonable to reduce load times.
- Follow the naming conventions described above.
- Update any relevant documentation or code to reference the new image path.

If you are unsure whether an image belongs here or how to name it, ask the maintainers
or leave a short comment in this file describing your decision.
