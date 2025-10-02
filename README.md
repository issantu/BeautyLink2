# BeautyLink 💄✨

**BeautyLink** is a modern beauty services marketplace platform that connects users with skilled independent beauty professionals and established salons. Built with React and designed for scalability, BeautyLink offers a comprehensive solution for booking beauty services, managing provider businesses, and facilitating seamless transactions.

![BeautyLink Logo](public/beautylink_logo_horizontal.png)

## 🌟 Features

### For Clients
- **Service Discovery**: Browse and search beauty services by category, location, and ratings
- **Geolocation Matching**: Find providers within a 25-mile radius
- **Booking Management**: Schedule, track, and manage appointments
- **Provider Reviews**: Rate and review service providers
- **Multi-Location Options**: Services at provider's location or client's location
- **Real-time Chat**: Communicate directly with service providers

### For Service Providers
- **Business Dashboard**: Comprehensive analytics and performance tracking
- **Service Management**: Create, edit, and manage service offerings
- **Earnings Tracking**: Monitor income, commissions, and payouts
- **Supply Integration**: Order beauty supplies directly through the platform
- **Calendar Management**: Manage availability and bookings
- **Client Communication**: Built-in messaging system

### Platform Features
- **Multi-User Experience**: Separate interfaces for clients and providers
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Professional UI/UX**: Modern design with pink and purple branding
- **Search & Filtering**: Advanced search capabilities with category filters
- **Commission System**: 15% platform commission on transactions
- **AI Translation Ready**: Prepared for global expansion with translation support

## 🎨 Service Categories

- **Hair Services**: Braiding, styling, washing, conditioning, cuts
- **Nail Services**: Manicures, pedicures, nail art
- **Massage Therapy**: Relaxation, therapeutic, specialty massages
- **Makeup Services**: Professional makeup application, lessons
- **Barber Services**: Men's haircuts, beard trimming, styling
- **Tailoring**: Custom clothing alterations and fittings

## 🚀 Technology Stack

- **Frontend**: React 19, Vite, Tailwind CSS
- **UI Components**: Radix UI, shadcn/ui
- **Icons**: Lucide React
- **Routing**: React Router DOM
- **Styling**: Tailwind CSS with custom theming
- **Build Tool**: Vite
- **Package Manager**: pnpm

## 📦 Installation

### Prerequisites
- Node.js 18+ 
- pnpm (recommended) or npm

### Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/issantu/BeautyLink.git
   cd BeautyLink
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   # or
   npm install
   ```

3. **Start development server**
   ```bash
   pnpm dev
   # or
   npm run dev
   ```

4. **Open in browser**
   ```
   http://localhost:5173
   ```

## 🏗️ Project Structure

```
BeautyLink/
├── public/                     # Static assets
│   ├── beautylink_logo_*.png  # Brand logos
│   └── favicon files
├── src/
│   ├── components/            # Reusable UI components
│   │   └── ui/               # shadcn/ui components
│   ├── App.jsx               # Main application component
│   ├── App.css              # Global styles
│   ├── index.css            # Tailwind imports
│   └── main.jsx             # Application entry point
├── package.json              # Dependencies and scripts
├── vite.config.js           # Vite configuration
├── tailwind.config.js       # Tailwind CSS configuration
└── README.md                # Project documentation
```

## 🎯 Available Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm preview` - Preview production build
- `pnpm lint` - Run ESLint

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Configure build settings:
   - Build Command: `pnpm build`
   - Output Directory: `dist`
3. Add custom domain (beautylink.app)
4. Deploy automatically on push to main branch

### Netlify
1. Connect repository to Netlify
2. Set build command: `pnpm build`
3. Set publish directory: `dist`
4. Configure custom domain

### Manual Deployment
```bash
pnpm build
# Upload dist/ folder to your hosting provider
```

## 🎨 Branding

BeautyLink uses a professional pink and purple color scheme:
- **Primary Pink**: #EC4899
- **Primary Purple**: #A855F7
- **Background**: Gradient from pink-50 to purple-50

### Logo Assets
- `beautylink_logo_main.png` - Main logo for marketing
- `beautylink_logo_horizontal.png` - Header logo
- `beautylink_logo_icon.png` - Favicon and app icon

## 🔧 Configuration

### Environment Variables
Create a `.env` file for environment-specific settings:
```env
VITE_API_URL=your_api_endpoint
VITE_STRIPE_PUBLIC_KEY=your_stripe_key
VITE_GOOGLE_MAPS_API_KEY=your_maps_key
```

### Tailwind Configuration
The project uses Tailwind CSS v4 with custom theming. Modify `tailwind.config.js` for design customizations.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌐 Live Demo

Visit the live application: [beautylink.app](https://beautylink.app)

## 📞 Support

For support and questions:
- Email: support@beautylink.app
- GitHub Issues: [Create an issue](https://github.com/issantu/BeautyLink/issues)

## 🚧 Roadmap

- [ ] Backend API development (Flask/Node.js)
- [ ] User authentication system
- [ ] Payment processing integration
- [ ] Real-time messaging
- [ ] Mobile app development
- [ ] AI-powered service recommendations
- [ ] Multi-language support
- [ ] Advanced analytics dashboard

---

**BeautyLink** - Connecting beauty professionals with clients worldwide 💄✨
