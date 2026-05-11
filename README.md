# EconomIA - Lumina Landing Page

A modern, responsive landing page for **Lumina**, a personal finance application that helps users manage their money with predictive insights and gentle guidance.

## 🚀 Features

- **Hero Section** - Eye-catching title and value proposition
- **Interactive Animations** - Smooth Framer Motion transitions
- **iPhone Mockup** - Visual representation of the app dashboard
- **Feature Cards** - Three key benefits highlighted
- **Call-to-Action Buttons** - Waitlist signup and download prompts
- **Responsive Design** - Mobile-first approach with Tailwind CSS
- **French Localization** - All content in French

## 📦 Tech Stack

- **Next.js 14** - React framework for production
- **React 18** - UI library
- **Framer Motion** - Animation library
- **Tailwind CSS** - Utility-first CSS framework
- **TypeScript** - Type safety

## 🎯 Getting Started

### Prerequisites

- Node.js 16.x or higher
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/king636ar-cpu/EconomIA.git
   cd EconomIA
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## 🎨 Customization

### Colors

Modify the color scheme by editing `tailwind.config.js`:

```javascript
theme: {
  colors: {
    // Add your custom colors here
  },
}
```

### Content

Edit `pages/index.tsx` to update:
- Headlines and descriptions
- Feature list items
- Button labels
- Call-to-action text

### Animations

Adjust Framer Motion animations in the component:

```jsx
<motion.div
  initial={{ opacity: 0, y: 40 }}
  animate={{ opacity: 1, y: 0 }}
  transition={{ duration: 1 }}
>
  {/* Content */}
</motion.div>
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

Created by [king636ar-cpu](https://github.com/king636ar-cpu)

## 📞 Contact

For questions or support, please open an issue on GitHub.

---

**Lumina** - *Less stress. More projects.* 💡
