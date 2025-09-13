# 🧠 Freelance Experience

## Almost Two Decades of Technical Experience & Creative Problem Solving

With almost two decades of learning and coding, Igor's work spans full-stack freelance work and developer tools, each built with reliability and performance in mind. He has created solutions in various sectors such as healthcare, HR, media, automation and luxury beverage retail. From full-stack builds to SEO, from UI/UX enhancements to API development, from systems architecture to server security, Igor's work reflects breadth and attention to details.

<br>

## 📃 Table of Contents

- [**WordPress & WooCommerce Solution**](#-sissis)
- [**End-to-End Mortuary Management System**](#-ezmm)
- [**Healthcare E-Commerce Platform**](#-sensomed)
- [**Other Projects**](#-other-projects)
  - [**ASP.NET Site Recovery**](#-aspnet-site-recovery)
  - [**Custom Front-End for URL Shortener**](#-custom-front-end-for-url-shortener)
  - [**Drag-and-Drop WPF API**](#-drag-and-drop-wpf-api)
  - [**HR Technical Quiz Authoring**](#-hr-technical-quiz-authoring)
  - [**Responsive Redesign for Movie Website**](#-responsive-redesign-for-movie-website)
  - [**Bootstrap Template Cleanup**](#-bootstrap-template-cleanup)
  - [**Multilingual Video Transcription**](#-multilingual-video-transcription)
  - [**Custom Sorting Algorithm**](#-custom-sorting-algorithm)
- [**Work Principles**](#-work-principles)
- [**Client Testimonials**](#-client-testimonials)

<br>

### 🍷 SissiS

#### WordPress and WooCommerce Solution

Developed a custom `WordPress` and `WooCommerce` solution for a luxury beverage retail. The solution handled automated orders export to a 3rd-party fulfillment provider, `FTP`-based tracking updates via `Cron`, dynamic invoice generation, tracking number fetching and customer notification. The solution was multilingual - `English`, `German`. All of the components were built from scratch and used modern `PHP` features and custom `HTTP security headers` to harden server security. Also, the client did not ask for a configuration page but one was provided to the client, to give them full control.

#### 💻 Tech Stack

This solution was built from the ground up with no frameworks. The only external dependency was the `FTP` client. The stack that was used was:

- `PHP`, a language that powers `WordPress`, `WooCommerce` and all custom plugin logic. `WordPress` is the `CMS` with tailored post types and admin tools
- `WooCommerce` was chosen as the e-commerce engine, extended with client-requested features
- `Custom order workflow plugin` - built for export, tracking, invoicing, and automation, using the following `data formats`: `CSV`, `XML`, and `JSON` for 3rd-party integrations
- `Security` was increased with custom `HTTP` headers and other security measures
- `Multilingual support` was a client's need, native English and German was implemented, with no external translation plugins
- `Admin UX` was enhanced by implementing dynamic interactions via `AJAX`
- `Email marketing` powered by `KlickTipp` (email marketing platform) was integrated in order to increase customer `conversions`
- `Shared logic` - reusable helpers for `FTP`, `email`, `caching`, `debugging`, and `scheduling` were used for performance and non-repeating code.

#### 🔧 Backend

- `Setup` - setup configuration of `WordPress` and `WooCommerce` with a custom database schema
- `Plugin` for order export in `XML` and `JSON` formats was built to match the client's needs
- `CSV` import/export pipelines with validation, tracking, and result logging were built for migration of previous customers on the legacy website
- Dynamic invoice generation with editable templates
- `PayPal` integration, and footer customization were created, per client needs
- `Meta-boxes` were implemented for custom post metadata and admin-side editing
- Reusable helpers for `FTP`, `AJAX`, `email`, `caching`, and `debugging` were used to avoid code-bloat and ensure atomic functioning
- `Cron` was used as a `scheduler` for `automated` tasks and background operations, orders `import`/`export`, `CSV` importing and parsing
- `Secure HTTP headers` and custom `security` logic was implemented to mitigate security attacks.

##### 🚚 Fulfillment & Tracking Integration

- `WooCommerce` orders are exported to a 3rd-party fulfillment provider via automated `XML` feed
- Periodically connect to the provider's `FTP` server to retrieve shipped order data via a `Cron` task
- Parse incoming `CSV` files to extract `tracking numbers` and deduct carrier info from the tracking numbers
- Update `WooCommerce` orders with tracking numbers and carrier-specific tracking `URLs`
- Display `tracking info` in the admin dashboard for staff visibility
- Send automated emails to customers with personalized tracking links based on carrier

#### 🖥️ Frontend & Admin UX

- Customized frontend templates and styles for WooCommerce pages
- Built dynamic admin tables with pagination, sorting, and filtering
- Added custom admin bar entries and plugin settings pages
- Enabled tracking uploads and order status management via AJAX
- Integrated multilingual support with English and German translations

#### 📈 SEO, Performance & Accessibility

- Applied high-security headers and sanitized all plugin inputs
- Optimized frontend markup and metadata for SEO visibility
- Audited accessibility across templates and admin interfaces

#### 🌟 Highlights

- Built the plugin suite from scratch - no reliance on 3rd-party frameworks
- Delivered production-grade code with modular architecture and clean separation of concerns with maintainable logic
- Solved complex export and import challenges with elegant, maintainable solutions
- No external translation plugins, native multilingual support
- Automated fulfillment and tracking, no missed orders

#### 🧭 Ongoing Platform Evolution

- Assisted in migrating admin layout workflows to Visual Composer
- Adapted plugin output and content structure to align with new builder logic
- Added new content blocks and ensured compatibility with multilingual and SEO requirements
- Provided support and refinements during transition to ensure smooth editorial experience

<br>

> 🌍 URL: [**SissiS.com**](https://sissis.com)

---

### 🧠 EZMM

#### End-to-End Mortuary Management System

Designed and developed the entire EZMM application from scratch, delivering a robust, modular, and user-friendly desktop solution tailored for mortuary operations. The system integrates data management, billing, scheduling, inventory, and multimedia handling - all wrapped in a custom tabbed UI.

#### 💻 Tech Stack

- `C#` – core language for backend logic and data operations
- `WPF` – desktop UI framework with custom controls and tabbed layouts
- `MVVM` – architectural pattern for clean separation of logic and presentation
- `DataGrid` – used for sortable, filterable record views
- `Custom Forms` – dynamic input fields for deceased records, services, and billing
- `Local Database` – structured storage for mortuary data and client records
- `Validation Logic` – built-in rules for form integrity and data consistency
- `Navigation System` – tabbed interface with contextual routing
- `Modular Components` – reusable UI elements and backend utilities
- `Role-Based Access` – permission layers for staff and admin workflows

#### 🔧 Backend

- Built a modular control system with reusable components for staff, visitors, relatives, memberships, and organizations
- Designed a custom drag-and-drop API for WPF controls with binary export/import support
- Implemented dynamic dashboard sections, separators, and item containers with animated transitions
- Created a flexible caching layer and global config system for runtime settings
- Engineered migration utilities for database, filesystem, and config upgrades
- Integrated network utilities for remote data sync and service communication
- Built a centralized data fetcher and document retriever with fallback logic
- Authored utility libraries for strings, forms, images, paths, and app-wide helpers
- Built a robust storage system with safe read/write operations and fallback recovery
- Engineered database utilities for query abstraction, migration, and schema evolution
- Developed configuration management with runtime overrides and version tracking
- Implemented app data handling with secure serialization and environment awareness

#### 🖥️ UI & UX Engineering

- Designed the entire tabbed UI from scratch using WPF - intuitive, responsive, and domain-specific
- Created custom controls for caption bars, combo boxes, scrollers, and draggable elements
- Developed document and image viewers with dynamic layout and metadata support
- Built a music track component for multimedia handling
- Implemented inventory and billing controls with expandable detail views
- Added billing modules for informant and service details with export-ready formatting
- Integrated status indicators, to-do tasks, and notification logic
- Created profile and contact management interfaces with validation and role-based access

#### 🧠 System Integration

- Connected external Excel/Word viewers via custom launchers
- Added support for dynamic tab switching and context-aware navigation
- Designed expandable search bars and custom filtering logic across modules

#### 🌟 Highlights

- Built the entire system solo - from UI to backend
- Delivered a fully operational, domain-specific desktop app with high maintainability
- Solved complex problems with zero prior domain experience
- Created a scalable architecture ready for future modules and integrations

---

### 🏥 Sensomed

#### Healthcare E-Commerce Platform

Delivered a full-stack WordPress + WooCommerce solution for a medical supplier, transforming a static Photoshop design into a dynamic, secure, and accessible online store.

#### 💻 Tech Stack

- `PHP` – backend logic for WordPress and WooCommerce
- `WordPress` – CMS foundation with custom theme and post templates
- `WooCommerce` – e-commerce engine with product variations and filters
- `HTML/CSS` – frontend styling and responsive layout from PSD
- `JavaScript` – dynamic UI elements and expandable search bar
- `Google Translate` – integrated multilingual support
- `Gutenberg` – custom blocks for flexible content publishing
- `Security Headers` – applied for enhanced protection and SEO
- `Video Templates` – custom layout for embedded media
- `Custom Theme` – built from scratch based on static design

#### 🔧 Backend

- Installed and configured WordPress and WooCommerce with custom database setup
- Developed a bespoke theme from PSD, including custom post loop templates and Gutenberg blocks
- Built a custom shop page with product variations, category filters, and dynamic sorting
- Implemented Google Translate integration and multilingual support
- Advised on accessibility improvements and design corrections
- Added high-security HTTP headers and SEO enhancements
- Created a custom video page template and expandable search bar
- Enabled selectable post templates for flexible content publishing

<br>

> 🌍 URL: [**Sensomed.eu**](https://sensomed.eu)

---

### ✨ Other Projects

<br>

#### ✅ ASP.NET Site Recovery

> Diagnosed and resolved critical issues on a legacy ASP.NET platform - without prior ASP experience - restoring full functionality through rapid adaptation and reverse engineering.

#### 🎯 Custom Front-End for URL Shortener

> Designed and implemented a lightweight jQuery + CSS interface for a URL shortening service, optimized for responsiveness and minimal load time.

#### 🧩 Drag-and-Drop WPF API

> Engineered a custom API for dynamic WPF controls with drag-and-drop support, including binary export/import logic for persistent layout storage.

#### 🧠 HR Technical Quiz Authoring

> Reviewed and authored a senior-level developer quiz for HR screening, ensuring technical accuracy, relevance, and challenge balance.

#### 🎬 Responsive Redesign for Movie Website

> Refactored layout and styles to ensure mobile compatibility across devices, improving accessibility and user retention.

#### 🧼 Bootstrap Template Cleanup

> Audited and corrected layout inconsistencies in a 3rd-party Bootstrap template, streamlining the DOM and improving maintainability.

#### 🎧 Multilingual Video Transcription

> Transcribed and subtitled video content in English and Spanish, ensuring timing precision and linguistic clarity.

#### 🧮 Custom Sorting Algorithm

> Designed a performant sorting algorithm for large datasets (thousands of lines), praised by the client for its speed and adaptability.

---

<br>

## 🏆 Work Principles

- `Resourcefulness` - solving unfamiliar problems with speed and precision
- `Technical Depth` - from low-level APIs to high-level UI polish
- `Cross-Platform Versatility` - web, desktop, mobile, and beyond
- `Client-Centric Design` - every solution tailored to real-world and client's needs
- `Security & Performance` - always optimized, always protected

<br>

#### 💡 Client Testimonials

Client testimonials for these projects are available on the [**Testimonials**](https://github.com/igorskyflyer/igorskyflyer/blob/main/TESTIMONIALS.md) page.
