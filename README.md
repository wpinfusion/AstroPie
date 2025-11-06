# LLMCD2025 >>> DO NOT USE, THIS IS AN EXPERIMENT 20251106 JRF

AstroPie is a free theme for the Astro framework, designed to provide a beautiful and functional starting point for your next restaurant or bistro website. Whether you're running an Italian restaurant, a cozy bistro, or any other type of dining establishment, AstroPie has you covered with its clean design and easy-to-use components.

## 🌟 About AstroPie

AstroPie is perfect for restaurant owners, developers, and designers who want to quickly set up a stylish and responsive website. It leverages modern web technologies to ensure a smooth and performant user experience.

## 🛠️ Technologies Used

-   **Astro**: The core framework for building fast, content-focused websites.
-   **TailwindCSS**: A utility-first CSS framework for rapid UI development.
-   **Alpine.js**: A lightweight JavaScript framework for adding interactivity.
-   **Swiper**: A modern slider library for creating responsive sliders.
-   **GLightbox**: A pure JavaScript lightbox for displaying images and videos.

## 🚀 Installation and Deployment

To get started with AstroPie, follow these steps:

1. **Clone AstroPie**:

    ```sh
    git clone https://github.com/wpinfusion/AstroPie.git
    ```

2. **Install Dependencies**:

    ```sh
    npm install
    ```

3. **Run Development Server**:

    ```sh
    npm run dev
    ```

4. **Build for Production**:

    ```sh
    npm run build
    ```

## 📂 Project Structure

Inside of your AstroPie project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   ├── components/
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── about-us.astro
│   │   ├── menu.astro
│   │   ├── gallery.astro
│   │   ├── contact.astro
│   │   └── book.astro
│   └── styles/
└── package.json
```

## 📄 Premade Pages

-   Home: index.astro
-   About Us: about-us.astro
-   Menu: menu.astro
-   Gallery: gallery.astro
-   Contact: contact.astro
-   Book a Table: book.astro

## 🧩 Available Components

-   Article: Article.astro
-   Badge: Badge.astro
-   Button: Button.astro
-   ButtonCallUs: ButtonCallUs.astro
-   Card: Card.astro
-   Footer: Footer.astro
-   FormBook: FormBook.astro
-   FormContact: FormContact.astro
-   Grid: Grid.astro
-   Header: Header.astro
-   Heading: Heading.astro
-   Hero: Hero.astro
-   Menu: Menu.astro
-   ReviewSlider: ReviewSlider.astro
-   Section: Section.astro
-   WideImage: WideImage.astro

## 📚 Component Documentation

### Article

A component for displaying articles.

```astro
<Article contain={true}>
  <h1>Title</h1>
  <p>Content goes here...</p>
</Article>
```

### Badge

A component for displaying badges.

```astro
<Badge color="green" title="New" />
```

### Button

A component for displaying buttons.

```astro
<Button color="green" url="/contact">Contact Us</Button>
```

### ButtonCallUs

A component for displaying a call-to-action button.

```astro
<ButtonCallUs />
```

### Card

A component for displaying cards.

```astro
<Card>
  <h2>Card Title</h2>
  <p>Card content goes here...</p>
</Card>
```

### Footer

A component for displaying the footer.

```astro
<Footer />
```

### FormBook

A component for displaying a booking form.

```astro
<FormBook />
```

### FormContact

A component for displaying a contact form.

```astro
<FormContact />
```

### Grid

A component for displaying a grid layout.

```astro
<Grid>
  <div slot="grid-content-1">Content 1</div>
  <div slot="grid-content-2">Content 2</div>
  <div slot="grid-content-3">Content 3</div>
</Grid>
```

### Header

A component for displaying the header.

```astro
<Header />
```

### Heading

A component for displaying headings.

```astro
<Heading>
  <h1 slot="heading-title">Title</h1>
  <p slot="heading-content">Content goes here...</p>
</Heading>
```

### Hero

A component for displaying the hero section.

```astro
<Hero>
  <div slot="hero-content-left">Left Content</div>
  <div slot="hero-content-right">Right Content</div>
</Hero>
```

### Menu

A component for displaying a menu.

```astro
<Menu />
```

### ReviewSlider

A component for displaying a review slider.

```astro
<ReviewSlider />
```

### Section

A component for displaying a section.

```astro
<Section>
  <p>Section content goes here...</p>
</Section>
```

### WideImage

A component for displaying a wide image.

```astro
<WideImage src={importedImage} alt="alt description" />
```

## 👀 Stuck?

If you have any questions or need help with AstroPie, feel free to reach out to me at info@wpinfusion.com, or open an issue on the [AstroPie GitHub repository](https://github.com/wpinfusion/AstroPie)
