# Angelos Tsiatsis Project Portfolio

## Web projects

### Synapse CMS – Multi-Tenant Headless Content Management System

Synapse is an API-first headless CMS built to manage content across multiple organizations and sites from one instance.
Built with Next.js and Supabase, leveraging PostgreSQL RLS for secure data isolation.

#### Key Features

- Multi-tenancy with full isolation
- Flexible modeling (12 field types)
- Granular role-based access control (RBAC) permissions
- Multi-language (i18n) UI and content with graceful fallbacks
- Supabase-backed asset management
- Draft/Publish/Archive lifecycles
- Auto REST API endpoint generation
- User API key generation
- Dashboard branding and theming

#### Tech Stack

- Supabase
- Next.js
- Tailwind CSS

#### Skills

- Postgres RLS (row-level security), triggers, functions, indexes, and views
- Database security testing using pgTAP to validate RLS policies
- Supabase Migrations, Seeds, Auth, Storage, Vault, and Edge Functions
- API key system with Supabase Vault
- CI/CD pipeline with GitHub Actions
- Version control with semantic-release
- Responsive frontend design using React and Tailwind CSS
- next-intl for multi-language UI
- Embedded API Playground using Scalar

---

### Label Designer App

A browser-based, WYSIWYG label design application built with Next.js. It lets users compose, configure, and export labels containing text, barcodes, QR codes, images, and shapes. The project ships both as a full web application and as a standalone exportable TypeScript library (label-converter) for embedding label rendering into other products.

#### Key Features

- Drag-and-drop canvas with text, barcodes (1D/QR), images, and shapes
- Multi-object alignment, undo/redo, clipboard operations, and keyboard shortcuts
- Export to PNG, SVG, PDF, and ZPL (Zebra thermal printers)
- Unit-aware rulers (mm, cm, inch) and dark/light theme

#### Tech Stack

- Next.js
- React 18
- Fabric.js
- Zustand
- Material UI
- Tailwind CSS
- Zod
- Rollup

#### Skills

- Building a WYSIWYG canvas editor with Fabric.js
- Scalable state management with Zustand + Immer
- DPI-aware multi-format export pipeline
- Packaging and obfuscating a TypeScript library with Rollup

---

### Full-Stack Websites with Next.js

Built various Full-stack websites with Next.js (App Router), TypeScript, and Tailwind CSS including internationalization and accessibility features.

#### Key Features

- URL-based locale switching
- CMS interconnection via Next.js API routes for dynamic content
- Server-side email delivery via Nodemailer
- Google reCAPTCHA v2 verification
- Theme selection
- Responsive design
- Accessibility features
- Animated UI using Framer Motion
- SEO optimization

#### Tech Stack

- Next.js
- React
- Radix UI primitives, shadcn/ui
- Framer Motion
- next-intl
- Tailwind CSS
- next-themes
- Nodemailer

#### Skills

- Building full-stack applications with Next.js App Router
- TypeScript for type-safe development
- Internationalization using next-intl
- Implementing accessibility best practices (a11y)
- Responsive UI design with Tailwind CSS
- Integrating CMS via API routes
- Server-side email delivery with Nodemailer
- Google reCAPTCHA v2 integration
- Theme management with next-themes
- UI animation with Framer Motion
- SEO optimization techniques
- Using Radix UI primitives and shadcn/ui for accessible components

---

### Static Business Websites with HTML, CSS & Bootstrap

Built various responsive business landing pages using vanilla HTML, CSS, and JavaScript with Bootstrap, including third-party API integrations and SEO optimization.

#### Key Features

- Responsive design
- CSS animations & transitions
- SEO optimization
- Dual theme support

#### Tech Stack

- HTML5 / CSS3
- Bootstrap 4
- Vanilla JavaScript (ES6+)

#### Skills

- Semantic HTML5 structure
- Responsive layouts using Bootstrap
- CSS animations and transitions
- DOM manipulation with vanilla JavaScript
- SEO and social sharing meta tags

---

### I/O Controller Real-Time Status Monitor

A lightweight web application built with ASP.NET Core, SignalR, and React to provide real-time monitoring of an industrial I/O controller. The system displays the current status of digital inputs/outputs, updating instantly as values change, and the webpage can be viewed in a browser.

#### Key Features

- Real-time status updates using SignalR
- React-based web interface for monitoring I/O controller state
- Visualization of digital and analog input/output channels
- Lightweight and responsive design for industrial use

#### Tech Stack

- ASP.NET Core
- SignalR
- React
- .NET
- HTML5 / CSS3

#### Skills

- Implementing real-time web communication with SignalR
- Developing React-based interfaces for industrial hardware monitoring
- Integrating ASP.NET Core with hardware controllers
- Designing secure and responsive status pages
- Application development with ASP.NET Core, React, and .NET

## Desktop applications

### Custom Multi-Department ERP System

The software was built to integrate multiple company departments such as service, secretarial, procurement, sales, and production, significantly improving operational efficiency. It focuses on ease of use and simplicity, while integrating the company's procedures and ensuring ISO 9001 compliance.

#### Key Features

- Create entries for each relevant procedure
- Convert entries to documents using RDLC reports
- IP phone center integration using a custom-made service so that users can insert the phone number they are speaking to, without typing
- Service ticket management
- User login with role-based permission assignment
- Customized open production orders form with priority indication for each entry
- Conversion between entry types (e.g., sales offer to production order)
- Integration with accounting software to display customer invoices on search
- File attachment support to add files to entries
- Entry search for each department, as well as combined search

#### Tech Stack

- Microsoft .NET Framework
- Windows Forms
- SQL Server

#### Skills

- Designing and implementing multi-department ERP systems
- Business process analysis and workflow integration
- Custom report generation with RDLC
- Integrating telephony systems with desktop applications
- Service ticket and production order management
- Database design
- Implementing authentication and role-based access control (RBAC) systems
- Data integration with accounting and file management systems
- Ensuring ISO 9001 compliance in software workflows
- User experience design for business applications
- Database design and management with SQL Server
- Application development with Microsoft .NET Framework

---

### Weighing Bridge Management Application

#### Key Features

- Integration with multiple types of weighing indicators by implementing their communication protocols
- Perform weighing bridge measurements using the vehicle's plate number as key information
- Store several additional fields per measurement (customer, product, supplier, etc.)
- Modular complementary field system, where each field title can be tailored to each installation
- Peripheral equipment integration such as traffic lights, barriers, LED matrix displays
- IP camera integration for live streaming, as well as for capturing screenshots and connecting them to the measurements
- Extensive printer support (dot matrix, laser, thermal) with easily modifiable format
- Comprehensive reporting system
- User login with role-based permission assignment
- SQL views for integrating external ERP system with the software
- Custom browser-like UI for easy navigation across windows
- Support for multiple weighing bridge connections, as well as multiple installations
- Multi-language UI support

#### Tech Stack

- Microsoft .NET Framework
- Windows Forms
- SQL Server

#### Skills

- Implementing custom communication protocols for industrial devices
- Integrating multiple types of weighing indicators and peripheral equipment (traffic lights, barriers, LED matrix displays)
- Developing modular and customizable data entry systems
- Managing and associating multimedia (IP camera streaming, screenshots) with business records
- Advanced printer integration and dynamic report formatting
- Designing comprehensive reporting systems
- Implementing authentication and role-based access control (RBAC) systems
- Database design
- Creating SQL views for external ERP integration
- Multi-language UI development
- Application development with Microsoft .NET Framework and SQL Server

---

### Weighing and Labeling System

The application was designed for installation on industrial touch-screen computers, enabling direct use in production environments. The computer is connected to weighing indicators and label printers, allowing it to save measurements and print labels that are affixed to the final products. It features a modular design, allowing customization to each project's specific needs. The system has been deployed in various industries, including food, pharmaceuticals, and metallurgy. Usually, the measurements along with the complementary data are imported to the company's ERP system for traceability purposes.

#### Key Features

- Complementary fields to mark each weighing, such as procedure, product, lot number, running number, and production date
- Additional numerical, alphanumerical, and list fields that can be tailored to each installation need
- Support for packing list generation
- User login
- Barcode scanner integration
- Calculation of gross, net, and tare weights, price, and glaze
- Enable or disable features from UI configuration
- Print total labels by product, box, pallet, and grand totals
- Additionally print total receipt to separate printer with weighing analysis
- Generate and print customized reports
- Custom label WYSIWYG designer utility that can also be used as a standalone application
- SQL views for integrating external ERP system with the software
- Interconnection with industrial automation equipment using Open Platform Communications Unified Architecture (OPC UA) and Modbus

#### Tech Stack

- Microsoft .NET Framework
- Windows Forms
- SQL Server

#### Skills

- Integrating industrial hardware (weighing indicators, label printers, barcode scanners) with software systems
- Designing modular and customizable production software for touch-screen environments
- Implementing user authentication and access control
- Developing dynamic label generation and WYSIWYG label designer utilities
- Generating and printing customized reports and packing lists
- Data acquisition and traceability integration with ERP systems
- Industrial automation communication using OPC UA and Modbus protocols
- Multi-industry deployment and adaptation
- Application development with Microsoft .NET Framework and SQL Server

---

### Dosing Control Application

The application was designed to automate and monitor the dosing process in industrial production lines. It controls a series of weighing tanks that sequentially add materials to a mixer, ensuring precise formulation of the final product. Users can create and manage recipes for each product, specifying ingredients, dosing order, and acceptable tolerances. The system supports both percentage-based and weight-based recipes, integrates with PLCs and network I/O modules, and provides real-time feedback and control for efficient and accurate batching.

#### Key Features

- Integration with network I/O modules
- Communication with PLCs
- Defining recipes by percentage or by weight
- Multiple weighing units supported
- Weighed tank or material flow control
- Mixer control

#### Tech Stack

- Microsoft .NET Framework
- Windows Forms
- SQL Server

#### Skills

- Automating industrial dosing and batching processes
- Integrating and communicating with PLCs and network I/O modules
- Designing recipe management systems with flexible ingredient and order configuration
- Implementing real-time process monitoring and control
- Supporting multiple weighing units and dosing strategies
- Developing user interfaces for industrial control applications
- Application development with Microsoft .NET Framework and SQL Server

## Windows service

### Weighing Bridge Control Service

The service controls all aspects of an automated weighing bridge and its peripherals, including weighing indicators, RFID and barcode readers, driver terminals, network cameras, photocells, LED matrix displays, traffic barriers, and buttons. Moreover, it displays the status in the browser using a web server and exposes a customized TCP interface for communication with other applications.

#### Key Features

- Modular design using DLLs
- Integration with Windows event log
- Configuration through UI interface
- Flexible, object-oriented codebase for easy integration of new features
- Any number of weighing bridges with separate configurations can be controlled from a single point
- Coordination between peripherals
- Web-based page for real-time status display
- Storage of measurements and logs to the database

#### Tech Stack

- Microsoft .NET Framework
- Windows Services
- .NET
- ASP.NET Core
- SQL Server

#### Skills

- Designing modular and extensible Windows services
- Integrating and controlling industrial peripherals
- Implementing real-time monitoring and web-based dashboards
- Developing custom TCP interfaces for inter-application communication
- Event logging and diagnostics using Windows event log
- Database design and data logging for traceability
- Coordinating multiple devices and managing concurrent operations
- Applying object-oriented programming for maintainability and scalability
- Application development with Microsoft .NET Framework, .NET Core, ASP.NET, and SQL Server
