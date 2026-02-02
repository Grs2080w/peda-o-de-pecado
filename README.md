# 🍰 Piece of Sin - Landing Page

This is the official landing page of Pedaço de Pecado, an artisanal sweet shop and café located in Presidente Prudente - SP. The project was developed with a focus on conversion via WhatsApp, user experience (UX) and responsive design.

## 🚀 Technologies Used 

- React.js: Main library for the interface. 
- Tailwind CSS: Utility framework for fast and responsive styling. 
- Lucide React: Lightweight and elegant icon library. 
- Shadcn/UI: Interface components (Button, Card) for visual consistency.


## ✨ Features
- Fixed Header: Navigation always visible with quick access to the order button.

- Product Gallery: Grid display of sweets and coffees with zoom effects on hover.

- Integration with WhatsApp: Strategic buttons that open a direct conversation with a personalized message.

- Testimonials: Social proof with customer reviews.

- Location: Dedicated section with address information, opening hours and integrated map.

- Responsive Design: Fully adapted for mobile devices, tablets and desktops.

## 📁 Folder Structure

```Plaintext
src/
├── components/
│ └── ui/ # Base components (Buttons, Cards)
├── pages/
│ └── Home.jsx # Main component of the Landing Page
├── public/ # Images and logos (SVG/JPG)
└── index.html # Application entry point
```

## 🛠️ How to Execute the Project

1. Clone the repository:

```Bash
git clone https://github.com/seu-usuario/pedaco-de-pecado.git
```

2. Install dependencies:
```Bash
npm install
# or
yarn install
```
Make sure you have the images in the /public folder: The code references images as /1.jpg, /fora.jpg, etc. Make sure these files exist in the public directory.

3. Start the development server:

```Bash
npm run dev
```

### 🎨 Color Customization

The project uses a custom palette in Tailwind. Make sure your tailwind.config.js file contains the definitions for:

- cream: Soft background.
- chocolate: Texts and main elements.
- rose-dusty: Highlights and action buttons.
- gold: Rating stars and footer details.