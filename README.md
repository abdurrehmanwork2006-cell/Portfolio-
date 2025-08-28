# Portfolio Website - Next.js

A modern, responsive portfolio website built with Next.js, TypeScript, and Tailwind CSS.

## 🚀 Features

- **Modern Design**: Clean and professional portfolio layout
- **Responsive**: Mobile-first design that works on all devices
- **Interactive**: Smooth animations and hover effects
- **Sections**: Hero, About, Projects, Skills, and Contact
- **TypeScript**: Full type safety and better development experience
- **Tailwind CSS**: Utility-first CSS framework for rapid development
- **Dark Mode Ready**: Built with dark mode support

## 📋 Prerequisites

Before running this project, you need to have Node.js installed on your system.

### Installing Node.js

1. **Download Node.js**: Visit [nodejs.org](https://nodejs.org/)
2. **Choose LTS Version**: Download the LTS (Long Term Support) version
3. **Install**: Run the installer and follow the setup wizard
4. **Verify Installation**: Open a new terminal and run:
   ```bash
   node --version
   npm --version
   ```

## 🛠️ Installation

1. **Clone or Download**: Get the project files to your local machine

2. **Install Dependencies**: Open terminal in the project directory and run:
   ```bash
   npm install
   ```

3. **Start Development Server**:
   ```bash
   npm run dev
   ```

4. **Open Browser**: Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
src/
├── app/
│   ├── globals.css          # Global styles and Tailwind imports
│   ├── layout.tsx           # Root layout component
│   └── page.tsx             # Main page component
├── components/
│   ├── Header.tsx           # Navigation header
│   ├── Hero.tsx             # Hero section with animated text
│   ├── About.tsx            # About section with experience
│   ├── Projects.tsx         # Projects showcase with filtering
│   ├── Skills.tsx           # Skills and expertise display
│   ├── Contact.tsx          # Contact form and information
│   └── Footer.tsx           # Footer with links
```

## 🎨 Customization

### Personal Information
Update the following files with your information:

- **Hero.tsx**: Change "Your Name" to your actual name
- **About.tsx**: Update experience, education, and personal details
- **Projects.tsx**: Replace sample projects with your actual work
- **Skills.tsx**: Modify skill levels and categories
- **Contact.tsx**: Update contact information and social links

### Styling
- **Colors**: Modify `tailwind.config.js` for custom color schemes
- **Fonts**: Change fonts in `layout.tsx`
- **Layout**: Adjust spacing and layout in component files

### Images
- Replace placeholder text with actual images
- Add your profile photo in the About section
- Include project screenshots in the Projects section

## 🚀 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 📱 Responsive Design

The portfolio is fully responsive and includes:
- Mobile-first design approach
- Responsive navigation with mobile menu
- Adaptive layouts for different screen sizes
- Touch-friendly interactions

## 🌙 Dark Mode

The portfolio includes dark mode support:
- Automatic dark mode detection
- Smooth transitions between themes
- Consistent color schemes

## 🔧 Technologies Used

- **Next.js 14** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS
- **React Hooks** - State management
- **CSS Animations** - Smooth transitions

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Happy Coding! 🎉**
