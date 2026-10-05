# Café Delight Website

A fully functional multi-page café website with shopping cart functionality, contact form, and modern UI design. Ready for online deployment!

## Project Structure

```
ProjectHyper/
├── index.html          # Landing page with auto-redirect
├── home.html           # Home page with hero, carousel, and testimonials
├── products.html       # Products/Menu page with 9 items
├── about.html          # About page with company info and team
├── services.html       # Services page with catering and offerings
├── contact.html        # Contact page with form and map
├── privacy.html        # Privacy policy page
├── terms.html          # Terms of service page
├── css/
│   └── styles.css      # Custom styles
├── js/
│   └── script.js       # JavaScript functionality
└── README.md           # Project documentation
```

## Features

### 🎨 **Modern UI Design**
- Responsive layout using Bootstrap 5
- Custom CSS with smooth animations
- Hero section with gradient overlay
- Product cards with hover effects
- Professional color scheme

### 🛒 **Shopping Cart System**
- Add items to cart
- View cart with item details
- Remove items from cart
- Real-time cart count updates
- Checkout process with form validation
- Order confirmation with unique order ID

### 📝 **Contact Form**
- Form validation (name, email, message)
- Email format validation
- Success feedback modal
- Form reset after submission

### 🧭 **Navigation**
- Smooth scrolling to sections
- Navbar with scroll effects
- Mobile-responsive menu
- Cart badge showing item count

### 🎠 **Image Carousel**
- Auto-playing carousel
- Manual navigation controls
- High-quality Unsplash images

## How to Use

1. **Open the website**: Open `index.html` in a web browser (auto-redirects to home.html)
2. **Navigate**: Use the navbar to switch between Home, Products, About, Services, and Contact pages
3. **Browse products**: Visit the Products page to see the full menu with 9 items
4. **Add to cart**: Click "Add to Cart" on any product
5. **View cart**: Click the cart icon in the navbar
6. **Checkout**: Fill in the checkout form to place an order
7. **Contact**: Use the contact form on the Contact page to send messages

## Deployment Guide

### 🚀 Deploy to Netlify (Recommended)

1. **Create a Netlify account** at [netlify.com](https://www.netlify.com)
2. **Drag and drop** the `ProjectHyper` folder to Netlify dashboard
3. **Your site will be live** in seconds with a free SSL certificate

### 🌐 Deploy to GitHub Pages

1. **Create a GitHub repository** and upload all files
2. **Go to Settings** > Pages
3. **Select main branch** as source
4. **Your site will be live** at `https://yourusername.github.io/repository-name`

### ☁️ Deploy to Vercel

1. **Install Vercel CLI**: `npm i -g vercel`
2. **Navigate to project folder**: `cd e:\HTML\ProjectHyper`
3. **Run**: `vercel`
4. **Follow the prompts** to deploy

### 📦 Deploy to Traditional Hosting

1. **Upload all files** to your hosting provider's public_html folder
2. **Ensure folder structure** is maintained (css/, js/ folders)
3. **Access via your domain**

### 🔧 Pre-Deployment Checklist

- ✅ All pages have proper SEO meta tags
- ✅ All navigation links work correctly
- ✅ Images are loading from reliable sources
- ✅ Contact form has proper validation
- ✅ Shopping cart functionality is tested
- ✅ Privacy policy and terms of service are included
- ✅ Social media links are updated with real URLs
- ✅ Footer links point to correct pages
- ✅ Responsive design works on mobile devices

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with animations
- **JavaScript (ES6+)**: Interactive functionality
- **Bootstrap 5**: Responsive framework
- **Wikipedia Commons**: High-quality genuine images

## JavaScript Functions

### Core Functions
- `showAlert()`: Displays welcome message
- `orderItem(productId)`: Adds product to cart
- `viewCart()`: Displays cart modal
- `removeFromCart(productId)`: Removes item from cart
- `checkout()`: Initiates checkout process
- `processCheckout(event)`: Handles order submission
- `submitForm(event)`: Validates and submits contact form

### Utility Functions
- `updateCartCount()`: Updates cart badge
- `showOrderModal(itemName)`: Shows order confirmation
- `setupSmoothScrolling()`: Enables smooth scroll
- `setupNavbarScroll()`: Adds navbar scroll effects
- `setupScrollAnimations()`: Adds scroll-based animations

## Customization

### Adding New Products
Edit the `products` array in `js/script.js`:
```javascript
const products = [
    { id: 1, name: 'Coffee', price: 120, image: 'url' },
    { id: 2, name: 'Burger', price: 150, image: 'url' },
    // Add more products here
];
```

### Modifying Styles
Edit `css/styles.css` to customize:
- Colors
- Fonts
- Spacing
- Animations
- Responsive breakpoints

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

- User authentication
- Order history
- Payment gateway integration
- Admin panel for product management
- Real-time order tracking
- Email notifications
- Product reviews and ratings

## License

This project is open source and available for educational purposes.
