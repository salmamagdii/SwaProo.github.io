# TailAdmin - Free Tailwind Admin Dashboard Template

TailAdmin is a high-quality, open-source, and **free Tailwind CSS admin template** that is perfect for creating data-rich backends,
powerful web applications and dashboard-admin projects.

![TailAdmin Dashboard Preview](./banner.png)

## Overview

TailAdmin provides essential UI components and layouts for building feature-rich, data-driven admin dashboards and control panels. It's built using:

- HTML
- Alpine.js
- Tailwind CSS
- and Webpack (for bundling)

### Quick Links

- [✨ Visit Website](https://tailadmin.com)
- [📄 Documentation](https://tailadmin.com/docs)
- [⬇️ Download](https://tailadmin.com/download)
- [🖌️ Figma Design File (Community Edition)](https://www.figma.com/community/file/1463141366275764364)
- [⚡ Get PRO Version](https://tailadmin.com/pricing)

### Demos

- [Free Version](https://free-demo.tailadmin.com/)
- [Pro Version](https://demo.tailadmin.com)

### Other Versions

- [Next.js Version](https://github.com/TailAdmin/free-nextjs-admin-dashboard)
- [React.js Version](https://github.com/TailAdmin/free-react-tailwind-admin-dashboard)
- [Vue.js Version](https://github.com/TailAdmin/vue-tailwind-admin-dashboard)

## Installation

### Prerequisites

To get started with TailAdmin, ensure you have the following prerequisites installed and set up:

- Node.js 18.x or later

### Cloning the Repository

Clone the repository using the following command:

```bash
git clone https://github.com/TailAdmin/tailadmin-free-tailwind-dashboard-template.git
```

> Windows Users: place the repository near the root of your drive if you face issues while cloning.

1. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

2. Start the development server:
   ```bash
   npm run start
   # or
   yarn start
   ```

## Components

TailAdmin is a pre-designed starting point for building a web-based dashboard using HTML, Alpine.js and Tailwind CSS. The template includes:

- Sophisticated and accessible sidebar
- Data visualization components
- Prebuilt profile management and 404 page
- Tables and Charts(Line and Bar)
- Authentication forms and input elements
- Alerts, Dropdowns, Modals, Buttons and more
- Can't forget Dark Mode 🕶️

## Feature Comparison

### Free Version

- 1 Unique Dashboard
- 30+ dashboard components
- 50+ UI elements
- Basic Figma design files
- Community support

### Pro Version

- 5 Unique Dashboards: Analytics, Ecommerce, Marketing, CRM, Stocks (more coming soon)
- 400+ dashboard components and UI elements
- Complete Figma design file
- Email support

To learn more about pro version features and pricing, visit our [pricing page](https://tailadmin.com/pricing).

## Update Logs

### Version 2.0.1 - [February 27, 2025]

#### Update Overview

- Upgraded to Tailwind CSS v4 for better performance and efficiency.
- Updated class usage to match the latest syntax and features.
- Replaced deprecated class and optimized styles.

#### Next Steps

- Run npm install or yarn install to update dependencies.
- Check for any style changes or compatibility issues.
- Refer to the Tailwind CSS v4 [Migration Guide](https://tailwindcss.com/docs/upgrade-guide) on this release. if needed.
- This update keeps the project up to date with the latest Tailwind improvements. 🚀

### Version 2.0.0 - [February 2025]

Major update with comprehensive redesign and new features.

#### Major Improvements

- Complete UI redesign of all pages and components
- Enhanced user interface with new elements
- Improved responsiveness and accessibility
- New features: collapsible sidebar, chat, and calendar
- Updated data visualization components

#### New Features

- Redesigned dashboards (Ecommerce, Analytics, Marketing, CRM)
- Enhanced navigation with improved header and breadcrumbs
- Advanced table components with sorting and filtering
- New UI components (Avatar, Alert, Ribbon)
- Full-featured calendar with drag-and-drop

#### Breaking Changes

- Updated sidebar component API
- New charting library implementation
- Revised authentication system
- **Deprecations:** SimpleTable component and legacy icon set

#### Previous Versions

For detailed changelogs of previous versions (1.0.0 - 1.3.0), visit our [documentation](https://tailadmin.com/docs/update-logs/).

## License

The community edition of TailAdmin is released under the MIT License.

## Support

If you find this project helpful, please consider giving it a star on GitHub. Your support helps us continue developing and maintaining this template.

## Deployment to GitHub Pages

This project is configured to be deployed to GitHub Pages using GitHub Actions. The deployment process is automated and will run whenever changes are pushed to the main branch.

### Prerequisites

1. A GitHub account
2. Git installed on your local machine
3. Node.js and npm installed on your local machine

### Steps to Deploy

1. Fork this repository to your GitHub account
2. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/tailadmin-dashboard.git
   cd tailadmin-dashboard
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Build the project:
   ```bash
   npm run build
   ```

5. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

6. Go to your repository settings on GitHub:
   - Navigate to Settings > Pages
   - Under "Source", select "GitHub Actions"

The site will be automatically deployed to GitHub Pages whenever you push changes to the main branch. You can find your deployed site at `https://your-username.github.io/tailadmin-dashboard`.

## Development

To run the project locally:

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

The site will be available at `http://localhost:3000`.

## Project Structure

- `src/` - Source files
  - `css/` - CSS files
  - `js/` - JavaScript files
  - `partials/` - HTML partials
- `dist/` - Built files (generated)
- `.github/workflows/` - GitHub Actions workflow files
