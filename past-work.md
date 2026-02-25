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

Developed a custom **WordPress** and **WooCommerce** solution for a luxury beverage retail. The solution handled automated orders export to a 3rd-party fulfillment provider, **FTP**-based tracking updates via **Cron**, dynamic invoice generation, tracking number fetching and customer notification. The solution was multilingual - **English**, **German**. All of the components were built from scratch and used modern **PHP** features and custom **HTTP security headers** to harden server security. Also, the client did not ask for a configuration page but one was provided to the client, to give them full control.

<br>

#### 💻 Tech Stack

This solution was built from the ground up with no frameworks. The only external dependency was the **FTP** client.  
The stack that was used was:

- **PHP** - backend language
- **WordPress** - CMS foundation
- **WooCommerce** - e-commerce engine
- **HTML** - markup for frontend templates and admin views
- **CSS** - custom styles and layout refinements across themes
- **JavaScript** - custom settings page for the plugin
- **AJAX** - dynamic frontend/backend interactions
- **FTP** - protocol for external data exchange
- **Cron** - task scheduler for automation
- **PayPal** - payment gateway
- **KlickTipp** - email marketing platform
- **Visual Composer** - page builder for admin layout (later in the project, read below)

<br>

## 🧩 Functional Capabilities

These are implementation domains and architectural patterns built on top of the stack:

- **Data Formats** - **CSV**, **XML**, **JSON** for **import**/**export** and integrations
- **Security** - custom **HTTP** headers and logic to mitigate attacks
- **Multilingual Support** - native **English** and **German** implementation
- **Admin UX** - dynamic admin tables, **AJAX**-powered interactions
- **Shared Logic** - reusable helpers for **FTP**, **email**, **caching**, **debugging**, **scheduling**

<br>

## 🔧 Backend Architecture

- Custom **database** schema for **WooCommerce**
- Plugin suite for:
  - Order **export** (**XML**/**JSON**)
  - **CSV** migration with validation and logging
  - Dynamic **invoice** generation
  - Meta-boxes for post **metadata**
- **Cron**-based automation:
  - **Scheduled** imports/exports
  - CSV **parsing**
  - **Fulfillment** sync
- **Secure** HTTP **headers** and custom logic for threat **mitigation**

<br>

## 🚚 Fulfillment & Tracking Integration

- Automated **XML** feed export to 3rd-party fulfillment provider
- Periodic **FTP** sync to retrieve shipped order data
- **CSV** parsing to extract **tracking numbers** and carrier info
- **WooCommerce** order **updates** with **tracking** URLs
- Admin **dashboard** display for tracking visibility
- **Automated** customer **emails** with **personalized** tracking links

<br>

## 🖥️ Frontend & Admin UX

- Customized **WooCommerce** templates and styles
- Dynamic admin tables with **pagination**, **sorting**, **filtering**
- Custom **admin** bar entries and plugin **settings** pages
- **AJAX**-powered tracking **uploads** and order status **management**
- Native **multilingual** support (**EN**/**DE**) without external plugins

<br>

## 📈 SEO, Performance & Accessibility

- **High-security** headers and input sanitization
- Optimized **frontend** markup and **metadata** for **SEO**
- **Accessibility** audit across templates and admin interfaces

<br>

## 🌟 Highlights

- **Plugin suite** built from scratch - no 3rd-party frameworks
- **Modular architecture** with clean **separation** of concerns
- Elegant solutions for complex **import**/export **challenges**
- Native **multilingual** support - no **translation** plugins
- Fully **automated fulfillment** and tracking - zero **missed** orders

<br>

## 🧭 Ongoing Platform Evolution

- Migrated admin layout workflows to **Visual Composer**
- Adapted plugin output to align with **builder** logic
- Added new content blocks with **multilingual** and **SEO** compatibility
- Provided **support** and **refinements** during the **Gutenberg** &rarr; **Visual Composer** transition

<br>

> 🌍 URL: [**SissiS.com**](https://sissis.com)

---

### 🧠 EZMM

#### End-to-End Mortuary Management System

Designed and developed the entire **EZMM** application from scratch, delivering a robust, modular, and user-friendly **desktop** solution tailored for mortuary operations. The system integrates data **management**, **billing**, **scheduling**, **inventory**, and **multimedia** handling - all wrapped in a custom tabbed UI.

<br>

## 💻 Tech Stack

These are the core technologies and platforms used to build the system:

- **C#** – core language for backend logic and data operations
- **WPF** – desktop UI framework with custom controls and tabbed layouts
- **MVVM** – architectural pattern for separation of logic and presentation
- **Local Database** – structured storage for mortuary data and client records

<br>

## 🧩 Functional Capabilities

These are implementation domains and architectural patterns built on top of the stack:

- **DataGrid** – **sortable**, filterable record **views**
- **Custom Forms** – **dynamic** input fields for deceased records, services, billing
- **Validation Logic** – built-in rules for form **integrity** and data **consistency**
- **Navigation System** – tabbed **interface** with contextual routing
- **Modular Components** – reusable **UI** elements and backend utilities
- **Role-Based Access** – **permission** layers for staff and **admin** workflows

<br>

## 🔧 Backend

- **Modular control** system for staff, visitors, relatives, memberships, organizations
- Custom **drag-and-drop API** for WPF controls with binary **export**/**import**
- **Dynamic** dashboard sections, separators, item containers with animated **transitions**
- Flexible **caching** layer and global **config** system for **runtime** settings
- **Migration** utilities for **database**, **filesystem**, and **config** upgrades
- **Network** utilities for remote data **sync** and service communication
- Centralized data **fetcher** and **document** retriever with fallback logic
- Utility **libraries** for strings, forms, images, paths, and app-wide **helpers**
- Robust **storage** system with safe read/write operations and fallback recovery
- **Database** utilities for query abstraction, migration, schema evolution
- **Configuration** management with runtime overrides and version **tracking**
- App data handling with **secure** serialization and **environment** awareness

<br>

## 🖥️ UI & UX Engineering

- **Tabbed** UI designed from scratch using **WPF**
- **Custom controls** for caption bars, combo boxes, scrollers, draggable elements
- **Document** and **image** **viewers** with dynamic layout and metadata support
- **Inventory** and **billing** controls with expandable detail views
- **Billing** modules for informant and service details with **export-ready** formatting
- Status **indicators**, to-do **tasks**, and **notification** logic
- **Profile** and contact management interfaces with validation and **role-based** access

<br>

## 🧠 System Integration

- External **Excel**/**Word** viewers via custom launchers
- Dynamic **tab switching** and context-aware **navigation**
- Expandable **search** bars and custom **filtering** logic across modules

<br>

## 🌟 Highlights

- Built the entire system solo – from **UI** to **backend**
- Delivered a fully **operational**, domain-specific desktop app with high **maintainability**
- Solved **complex** problems with zero prior domain experience
- Created a **scalable** architecture ready for future modules and integrations

---

### 🏥 Sensomed

#### Healthcare E-Commerce Platform

Delivered a full-stack `WordPress` + `WooCommerce` solution for a medical supplier, transforming a static `Photoshop` design into a dynamic, `secure`, and accessible online `store`.

<br>

- **PHP** – backend logic for WordPress and WooCommerce
- **HTML/CSS** – frontend styling and responsive layout from PSD
- **JavaScript** – dynamic UI elements and expandable search bar
- **WordPress** – CMS foundation with custom theme and post templates
- **WooCommerce** – e-commerce engine with product variations and filters
- **Gutenberg** – block editor for flexible content publishing
- **Google Translate** – integrated multilingual support
- **Security Headers** – applied for enhanced protection and SEO

<br>

## 🧩 Functional Capabilities

These are implementation domains and architectural patterns built on top of the stack:

- **Custom Theme** – built from scratch based on static design
- **Video Templates** – custom layout for embedded media
- **Custom Post Templates** – selectable layouts for flexible publishing
- **Multilingual Support** – English and German via Google Translate
- **Accessibility Enhancements** – advised improvements for inclusive design

<br>

## 🔧 Backend

- Installed and configured WordPress and WooCommerce with custom database setup
- Developed bespoke theme from PSD, including custom post loop templates and Gutenberg blocks
- Built custom shop page with product variations, category filters, and dynamic sorting
- Implemented Google Translate integration and multilingual support
- Added high-security HTTP headers and SEO enhancements
- Created custom video page template and expandable search bar
- Enabled selectable post templates for flexible content publishing

<br>

## 🖥️ Frontend & Admin UX

- Created frontend templates and styles from provided Photoshop design
- Added custom admin bar entries and plugin settings pages
- Integrated multilingual support with English and German translations

<br>

> 🌍 URL: [**Sensomed.eu**](https://sensomed.eu)

---

### ✨ Other Projects

<br>

#### ✅ ASP.NET Site Recovery

> Diagnosed and resolved critical issues on a legacy ASP.NET platform - without prior ASP experience - restoring full functionality through rapid adaptation and reverse engineering.

<br>

#### 🎯 Custom Front-End for URL Shortener

> Designed and implemented a lightweight jQuery + CSS interface for a URL shortening service, optimized for responsiveness and minimal load time.

<br>

#### 🧩 Drag-and-Drop WPF API

> Engineered a custom API for dynamic WPF controls with drag-and-drop support, including binary export/import logic for persistent layout storage.

<br>

#### 🧠 HR Technical Quiz Authoring

> Reviewed and authored a senior-level developer quiz for HR screening, ensuring technical accuracy, relevance, and challenge balance.

<br>

#### 🎬 Responsive Redesign for Movie Website

> Refactored layout and styles to ensure mobile compatibility across devices, improving accessibility and user retention.

<br>

#### 🧼 Bootstrap Template Cleanup

> Audited and corrected layout inconsistencies in a 3rd-party Bootstrap template, streamlining the DOM and improving maintainability.

<br>

#### 🎧 Multilingual Video Transcription

> Transcribed and subtitled video content in English and Spanish, ensuring timing precision and linguistic clarity.

<br>

#### 🧮 Custom Sorting Algorithm

> Designed a performant sorting algorithm for large datasets (thousands of lines), praised by the client for its speed and adaptability.

---

<br>

## 🏆 Work Principles

- **Resourcefulness** - solving unfamiliar problems with speed and precision
- **Technical Depth** - from low-level APIs to high-level UI polish
- **Cross-Platform Versatility** - web, desktop, mobile, and beyond
- **Client-Centric Design** - every solution tailored to real-world and client's needs
- **Security & Performance** - always optimized, always protected

<br>

#### 💡 Client Testimonials

Client testimonials for these projects are available on the [**Testimonials**](https://github.com/igorskyflyer/igorskyflyer/blob/main/client-testimonials.md) page.
