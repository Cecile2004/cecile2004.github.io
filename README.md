# Astro Academia Documentation

## What is Astro Academia?

Astro Academia is a personal academic website built using Astro, a modern static site generator. The website is designed to showcase academic achievements, research papers, blog posts, and a CV. It is fast, responsive, and easy to maintain, making it an ideal platform for academics and researchers to present their work.

If you find Astro Academia useful or appreciate my work, consider supporting me! Your support helps keep this project maintained and encourages further development. 🚀✨

<a href="https://buymeacoffee.com/maiobarbero" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee" height="41" width="174"></a>
<a href="https://www.producthunt.com/products/astro-academia?embed=true&utm_source=badge-featured&utm_medium=badge&utm_source=badge-astro&#0045;academia" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1026976&theme=light&t=1760776422941" alt="Astro&#0032;Academia - Academic&#0032;website&#0032;template | Product Hunt" style="width: 189px; height: 41px;" width="189" height="41" /></a>

### Demo
You can see Astro Academia at the following link: <a href="https://maiobarbero.github.io/astro_academia/" target="_blank">demo page</a>

## How to use it

Fork this repository to create your new website starting from this template.

## How to Create a CV Using the `cv.ts` File

The `cv.ts` file located in the `src/data/` directory is used to define the structure and content of your CV. This file exports an object containing various sections of your CV, such as education, experience, publications, and more.

### Example Structure of `cv.ts`

```typescript
export const cv = {
  education: [
    {
      degree: "Ph.D. in Computer Science",
      institution: "University of Example",
      year: "2020",
    },
    {
      degree: "M.Sc. in Computer Science",
      institution: "University of Example",
      year: "2016",
    },
  ],
  experience: [
    {
      title: "Research Scientist",
      company: "Example Research Lab",
      year: "2021-Present",
    },
    {
      title: "Software Engineer",
      company: "Tech Company",
      year: "2016-2021",
    },
  ],
  // Add more sections as needed
};
```

To create or update your CV, modify the `cv.ts` file with your personal information and achievements. The CV will be automatically rendered on the CV page of your website.

## How to Use the `settings.ts` File

The `settings.ts` file located in the `src/` directory is used to configure various settings for your Astro Academia website. This file exports an object containing settings such as site title, description, social media links, and more.

### Example Structure of `settings.ts`

```typescript
export const settings = {
  siteTitle: "Astro Academia",
  siteDescription: "A personal academic website built with Astro.",
  socialLinks: {
    twitter: "https://twitter.com/yourusername",
    github: "https://github.com/yourusername",
    linkedin: "https://linkedin.com/in/yourusername",
  },
  // Add more settings as needed
};
```

To customize your website settings, modify the `settings.ts` file with your desired values. These settings will be used throughout your website to display the appropriate information.

## Where to Edit Page Content

Page content is maintained directly in the Astro files under `src/pages/`:

- `src/pages/index.astro` - About Me
- `src/pages/experience.astro` - Professional Experience
- `src/pages/moments.astro` - Moments
- `src/pages/cv.astro` - CV

Edit these files directly; there are no separate Markdown content collections.

## Deploy
The template provides a workflow to deploy the website on Github pages as a static website.
