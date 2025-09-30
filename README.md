# Admin Dashboard Template

A modern, responsive admin dashboard template built with Astro and Tailwind CSS, inspired by the Spike Tailwind template from Wrappixel.

## Features

- **Modern Design**: Clean and professional interface with a modern color scheme
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Charts**: Beautiful charts powered by Chart.js for data visualization
- **Sidebar Navigation**: Collapsible sidebar with smooth animations
- **Statistics Cards**: Key metrics displayed in attractive card layouts
- **Recent Activities**: Real-time activity feed with icons and timestamps
- **Top Clients Table**: Sortable table with client information and status indicators
- **Product Showcase**: Featured products with pricing and discount information
- **Mobile Friendly**: Optimized for mobile devices with hamburger menu

## Components

### Core Components
- `Sidebar.astro` - Navigation sidebar with menu items
- `Header.astro` - Top header with search, notifications, and user profile
- `StatsCards.astro` - Key performance metrics cards
- `Charts.astro` - Interactive charts for analytics
- `RecentActivities.astro` - Activity feed component
- `TopClients.astro` - Client management table
- `ProductShowcase.astro` - Product display grid

### Layout
- `Layout.astro` - Main layout with Tailwind CSS and external libraries
- `index.astro` - Main dashboard page
- `add.astro` - Example secondary page

## Technologies Used

- **Astro** - Modern static site generator
- **Tailwind CSS** - Utility-first CSS framework
- **Chart.js** - JavaScript charting library
- **Font Awesome** - Icon library
- **Alpine.js** - Lightweight JavaScript framework for interactions

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:4321`

## Project Structure

```
src/
├── components/
│   ├── Sidebar.astro
│   ├── Header.astro
│   ├── StatsCards.astro
│   ├── Charts.astro
│   ├── RecentActivities.astro
│   ├── TopClients.astro
│   └── ProductShowcase.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   ├── index.astro
│   └── add.astro (Add User)
|   └── view.astro (View the User entry)
└── styles/
    └── global.css
```

## Customization

### Colors
The dashboard uses a consistent color palette:
- Primary: Indigo (600, 700)
- Success: Green (500, 600)
- Warning: Yellow (500, 600)
- Error: Red (500, 600)
- Neutral: Gray (50-900)

### Charts
Charts are configured in the `Charts.astro` component. You can modify:
- Chart types (line, bar, doughnut)
- Data sources
- Colors and styling
- Animation options

### Navigation
Update the sidebar navigation in `Sidebar.astro`:
- Add/remove menu items
- Change icons (Font Awesome)
- Update links and routes

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- Design inspiration from [Wrappixel Spike Template](https://bootstrapdemos.wrappixel.com/spike-free-tailwind/dist/index.html)
- Icons by [Font Awesome](https://fontawesome.com/)
- Charts by [Chart.js](https://www.chartjs.org/)
- Built with [Astro](https://astro.build/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)