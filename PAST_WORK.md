# 🧠 Freelance Experience

## Almost Two Decades of Technical Experience & Creative Problem Solving

Across nearly two decades of learning and writing code, Igor has consistently delivered high-performance, user-centric solutions for global clients across industries, including healthcare, HR, media, and infrastructure. His work spans full-stack engineering, UI/UX refinement, API design, and systems architecture, with a reputation for solving complex problems under pressure and delivering elegant, maintainable results.

<br>

### 🌍 Global Reach

Worked with clients from:

- 🇩🇪 Germany
- 🇵🇰 Pakistan
- 🇦🇺 Australia
- 🇷🇸 Serbia
- 🇰🇷 South Korea
- 🇭🇷 Croatia
- 🇺🇸 United States
- 🇯🇲 Jamaica
- 🇳🇱 Netherlands
- 🇬🇧 United Kingdom

<br>

### 🔧 Selected Projects & Highlights

#### 🛍️ SissiS: WordPress + WooCommerce (Web)

> Developed a custom multi-faceted solution for a WooCommerce storefront, handling automated order export, `FTP`-based tracking integration with a 3rd-party fulfillment provider, multilingual support, and dynamic invoice generation. All built from scratch with secure, maintainable backend logic. More about it in the [**detailed breakdown**](#️-sissis).

#### ⚰️ EZMM: Mortuary Management System (Desktop)

> Developed a full-featured desktop application for mortuary management, including custom scheduling, record management, and secure data handling. Extensive `UI` customization and domain-specific logic tailored to client workflows and input. More about it in the [**detailed breakdown**](#-ezmm).

#### 🏥 Sensomed: Healthcare E-Commerce Platform (Web)

> Delivered a full-stack `WordPress` and `WooCommerce` site for a medical supplier, converting a static `Photoshop` design into a secure, multilingual storefront with custom `Bootstrap`-powered templates, `SEO` enhancements, and accessibility improvements. More about it in the [**detailed breakdown**](#-sensomed).

#### ✅ ASP.NET Site Recovery

> Diagnosed and resolved critical issues on a legacy `ASP.NET` platform (without prior `ASP.NET` experience) restoring full functionality through rapid adaptation and reverse engineering. Fixed `Bootstrap` layout misalignments.

#### 🎯 Custom Front-End for URL Shortener

> Designed and implemented a lightweight `jQuery` + `CSS` interface for a URL shortening service, optimized for responsiveness and minimal load time.

#### 🧩 Drag-and-Drop WPF API

> Engineered a custom `API` with drag-and-drop support for system `WPF` controls, including a custom binary file export/import for persistent layout storage.

#### 🧠 HR Technical Quiz Authoring

> Reviewed and authored a senior-level developer quiz for HR screening, ensuring technical accuracy, relevance and challenge balance.

#### 🎬 Responsive Redesign for Movie Website

> Refactored layout and styles to ensure mobile compatibility across devices, i.e. implemented responsive design, improving accessibility and user retention.

#### 🧼 Bootstrap Template Cleanup

> Audited and corrected layout inconsistencies in a 3rd-party Bootstrap template and in the process improved user experience and project maintainability.

#### 🎧 Multilingual Video Transcription

> Transcribed and subtitled video content in English and Spanish, ensuring timing precision and correctness.

#### 🧮 Custom Sorting Algorithm

> Designed a performant sorting algorithm (in `C#`) for large datasets (`1000s` of lines), praised by the client for its speed and adaptability.

---

### 🛍️ SissiS

#### Custom WordPress + WooCommerce Solution

Delivered a deeply customized e-commerce solution for SissiS, combining WordPress and WooCommerce. The project focused on backend extensibility, data automation, multilingual support, and secure, SEO-optimized performance, all tailored to real-world operational and client needs.

#### Tech Stack

- `PHP` - core language powering WordPress and custom plugin logic
- `WordPress` - CMS foundation with custom post types and admin tooling
- `WooCommerce` - e-commerce engine with deep plugin integration
- `Custom Plugins` - built from scratch for export, tracking, invoicing, and automation
- `CSV/XML/JSON` - data formats used for import/export and third-party integration
- `Security Headers` - custom HTTP headers and endpoint protection
- `Multilingual Support` - English and German translations with dynamic content handling
- `HTML/CSS` - frontend templates and styling for WooCommerce pages
- `AJAX` - dynamic admin interactions and tracking updates
- `Visual Composer` - layout builder used in later platform evolution
- `Reusable Helpers` - FTP, email, caching, debugging, and scheduler logic

#### 🔧 Plugin Architecture & Backend Engineering

- Installed and configured WordPress and WooCommerce with custom database setup
- Engineered a full-featured WooCommerce plugin for order export in XML and JSON formats
- Built custom data models for customers, salutations, titles, and metadata
- Developed CSV import/export pipelines with validation, tracking, and result logging
- Created dynamic invoice generation with editable templates, PayPal integration, and footer customization
- Implemented meta-boxes for custom post metadata and admin-side editing
- Designed reusable helpers for FTP, AJAX, email, caching, and debugging
- Built a scheduler for automated tasks and background operations
- Added secure HTTP headers and custom security logic for plugin endpoints
- Developed a hook system for extensibility and third-party integration

#### 🚚 Fulfillment & Tracking Integration

- Exported WooCommerce orders to a third-party fulfillment provider via automated XML feed
- Periodically connected to the provider's FTP server to retrieve processed order data via a Cron task
- Parsed incoming CSV files to extract tracking numbers and carrier info
- Updated WooCommerce orders with tracking numbers and carrier-specific tracking URLs
- Displayed tracking info in the admin dashboard for staff visibility
- Sent automated emails to customers with personalized tracking links based on carrier
