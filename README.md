# Ittipat Pattum (Pu)

## Flutter & Mobile Application Developer

Flutter specialist with native Android and iOS experience and a strong record of independently delivering complex, cross-platform products. Experienced in citizen-service applications, identity and biometric workflows, secure document processing, OCR, marketplace platforms, and full-stack product development. Comfortable owning application architecture, responsive UI, state management, navigation, REST integrations, authentication, notifications, local persistence, file and media workflows, and mobile release configuration.

**Location:** Bang Rak Yai, Bang Bua Thong, Nonthaburi, Thailand<br>
**Email:** [pu.van.intania@gmail.com](mailto:pu.van.intania@gmail.com)<br>
**Phone / LINE:** 065-145-1565<br>
**WhatsApp:** +66 65 145 1565<br>
**GitHub:** [Richard-Van-Intania](https://github.com/Richard-Van-Intania)<br>
**Pronouns:** He/Him/His<br>
**Year of birth:** 1990

---

## Professional Summary

- Mobile developer specializing in Flutter and Dart, with hands-on native development in Kotlin, Jetpack Compose, Android Views, Swift, and SwiftUI.
- Independently delivered mobile and web applications containing 60–70+ screens and long, multi-step business workflows.
- Experienced with Riverpod, Flutter Hooks, GoRouter, Freezed, JSON code generation, GetX, secure storage, Firebase services, deep links, and responsive phone/tablet UI.
- Built document and identity workflows involving OCR, MRZ, NFC, facial liveness, face matching, camera capture, PDF generation, uploads, e-signatures, and privacy masking.
- Full-stack experience with Rust, Axum, Tokio, SQLx, PostgreSQL, JWT authentication, S3-compatible storage, and React/Next.js.
- Comfortable working independently across application architecture, implementation, API integration, native configuration, deployment, and maintenance.

## Education & English Proficiency

### Chulalongkorn University

**Bachelor of Engineering — Metallurgical and Materials Engineering**<br>
Graduated 2014 · GPA 2.68

### Mukdahan School

High School Diploma

### English

**TOEIC:** 700

## Core Competencies

### Mobile Engineering

Flutter, Dart, Kotlin, Java, Swift, SwiftUI, Jetpack Compose, Android Views, Material Design, responsive mobile/tablet interfaces, platform permissions, app lifecycle, localization, accessibility-aware UI, and Android/iOS configuration.

### Architecture & State Management

Riverpod, Flutter Hooks, GetX, StateFlow, Kotlin Coroutines and Flow, ViewModel, GoRouter, Navigation Compose, NavigationStack, Android Navigation Component, Freezed, json_serializable, Kotlin Serialization, and modular reusable components.

### APIs, Security & Device Integrations

REST APIs, HTTP/JSON, multipart upload, JWT access and refresh tokens, secure credential storage, SSO/deep links, Firebase Cloud Messaging, Crashlytics, CameraX, NFC, MRZ, OCR, QR scanning, biometrics, LocalAuthentication, PDF/image processing, and connectivity handling.

### Full-Stack & Data

Rust, Axum, Tokio, Tower, SQLx, PostgreSQL, Node.js, NestJS, Express.js, Go, MongoDB, MySQL, Elasticsearch, AWS S3, CloudFront, Docker, Nginx, and Firebase Hosting.

### Web Engineering

React, Next.js, Vue.js, Nuxt.js, TypeScript, JavaScript, Material UI, Tailwind CSS, TanStack Query, Zustand, Pinia, Flutter Web, and WebAssembly.

---

# Selected Projects

## DPT Town Square — Citizen Services Mobile Application

### Client / Project Context

Department of Public Works and Town & Country Planning (DPT), Thailand<br>
กรมโยธาธิการและผังเมือง

### Role

Independent Flutter Developer — solo project

### Date

March 2024 – December 2025

### Project Description

Independently developed a cross-platform citizen-services application from provided product requirements and UI/UX designs, bringing DPT services into one Flutter experience. The application covers construction-material testing requests, complaints and appeals, public-information search, chatbot and officer support, service-status tracking, digital documents, payments, notifications, and citizen account management.

### Key Contributions

- Developed 60+ screens for Android and iOS, including responsive phone and tablet layouts.
- Built an end-to-end material-testing workflow covering center selection, delivery information, samples, test items, attachments, submission, status tracking, payment evidence, and downloadable results.
- Implemented complaint, corruption-report, suggestion, planning-appeal, and building-appeal workflows with witnesses, evidence, previews, replies, and case histories.
- Created categorized public-information search with popular topics, filters, history, view tracking, document metadata, and HTML/PDF previews.
- Integrated chatbot and live-officer conversations with paginated history, recurring message updates, images, files, quick replies, carousels, and authenticated handoff.
- Integrated SSO/ThaiD-style authentication, secure token storage, session-expiration handling, REST APIs, and deep-link return flows.
- Connected Firebase push and local notifications to route-specific deep links for requests, complaints, appeals, and chat.
- Organized complex asynchronous state with Riverpod and 80+ nested routes with GoRouter’s stateful navigation shell.
- Added multipart uploads, camera/gallery input, PDF/image/video previews, downloads, sharing, offline handling, and Thai-language validation.
- Created typed, immutable API contracts with generated serialization to make a large government-service data model safer to maintain.
- Built reusable Thai-language form components and consistent loading, empty, validation, retry, and failure states across unrelated service domains.
- Implemented secure persistence, connectivity monitoring, token registration, notification badges, and session recovery.
- Configured Firebase initialization, crash reporting, Android/iOS permissions, splash screens, launcher assets, and native platform settings.

### Key Features

- Central directory of public and authenticated DPT citizen services.
- Construction-material testing requests with center, delivery, sample, and test-item configuration.
- Digital waybill preview, supporting-document uploads, submission, payment slips, and result documents.
- Status tracking across review, delivery, payment, testing, analysis, approval, and completion.
- Complaints, Damrongdhama Center cases, corruption reports, planning/building appeals, suggestions, witnesses, and evidence.
- Searchable case histories with status badges, officer replies, attachment previews, and downloads.
- Public-information discovery with categories, popular topics, keywords, filters, history, view counts, and document details.
- Chatbot and officer conversations with text, images, files, quick replies, carousels, external links, and pagination.
- SSO/ThaiD-style authentication, citizen profiles, saved addresses, and administrative-area selection.
- Push/local notifications, badges, deep links, offline detection, and responsive Thai phone/tablet UI.

### Technologies

- **Application:** Flutter, Dart, Material UI, responsive phone/tablet layouts, Android, iOS.
- **Architecture:** Riverpod, Flutter Hooks, GoRouter stateful navigation shell, Freezed, json_serializable, build_runner.
- **Integration:** REST APIs, HTTP/JSON, multipart requests, authenticated endpoints, SSO/ThaiD-style login, deep links, WebView.
- **Firebase:** Core, Cloud Messaging, Crashlytics, Analytics, token registration, foreground/background notification handling.
- **Security and persistence:** Flutter Secure Storage, SharedPreferences, protected routes, credential/session lifecycle management.
- **Media and reliability:** File Picker, Image Picker, cached images, PDF viewer, video player, downloads, sharing, local notifications, connectivity monitoring.

---

## E-Passport Mobile Application

### Client / Project Context

Ministry of Foreign Affairs of Thailand — bidding and demonstration prototype<br>
กระทรวงการต่างประเทศ

### Role

Independent Flutter Developer — solo project

### Date

March 2025 – July 2026

### Project Description

Developed a cross-platform e-passport prototype from provided product requirements and UI/UX designs for a bidding presentation. The application demonstrates digital passport enrollment, identity-document capture, MRZ and NFC reading, biometric verification, portrait-quality checks, payment and receipt workflows, passport retrieval, QR verification, parental consent, and passport validation. This was a functional demonstration prototype, not a claimed public production deployment.

### Key Contributions

- Delivered 70+ Flutter screens across five role-based user journeys on Android and iOS.
- Built remote enrollment covering Thai ID/passport registration, OCR extraction, data review, document uploads, liveness, face matching, portrait capture, ABIS verification, payment, receipt generation, and submission.
- Integrated document and biometric SDKs for MRZ scanning, NFC e-passport reading, smile/eye liveness, facial comparison, and photo-quality evaluation.
- Designed typed REST integrations for enrollment, KYC, OCR, face comparison, photo enhancement, ABIS, passport preview, receipts, retrieval, and completion.
- Added digital-passport retrieval, NFC ownership verification, selfie-to-passport matching, QR sharing and verification, parental consent, and MRZ validation.
- Managed long asynchronous workflows with Riverpod and immutable Freezed/json_serializable models.
- Implemented camera/gallery capture, QR scanning and generation, file upload, PDF invoice preview/download, local application history, bilingual UI, and reusable interface components.
- Coordinated identity data from document scans, NFC chips, biometric capture, manual forms, uploaded evidence, and backend responses across long workflows.
- Implemented loading, validation, success, retry, and hardware/API failure experiences for camera, MRZ, NFC, QR, facial capture, and payment steps.
- Created reusable Thai/English interface components, custom typography, local history, persisted passport records, and configurable API environments.
- Configured Firebase, crash reporting, platform permissions, launch assets, and Android/iOS project settings for demonstration builds.

### Key Features

- End-to-end remote passport application and enrollment management.
- Thai national ID/existing-passport registration, OCR extraction, data review, and supporting documents.
- MRZ scanning and validation plus NFC reading of electronic-passport chips.
- Smile, facial, and eye-liveness checks with document-to-selfie comparison.
- Portrait capture, enhancement, quality analysis, and ABIS identity verification.
- Passport configuration, preview, QR PromptPay/debit flows, payment, and final submission.
- PDF invoice/receipt generation, preview, download, and local application history.
- Digital-passport retrieval with NFC ownership confirmation and selfie matching.
- QR passport sharing and verifier scanning, parental consent, and standalone validation.
- Bilingual Thai/English UI with clear recovery states for hardware-dependent operations.

### Technologies

- **Application:** Flutter, Dart, Material UI, custom typography, Thai/English localization, Android, iOS.
- **Architecture:** Riverpod, generated providers, Flutter Hooks, GoRouter, Freezed, json_serializable, build_runner.
- **Identity and biometrics:** OCR, MRZ, NFC, facial/eye-liveness SDKs, face comparison, ABIS integration, portrait-quality analysis.
- **Camera and QR:** Camera APIs, Mobile Scanner, gallery capture, QR scanning/generation, image/file pickers.
- **Integration and media:** REST APIs, HTTP/JSON, typed models, uploads, PDF preview/download, FFmpeg, image processing.
- **Platform:** Firebase Core, Firebase Crashlytics, SharedPreferences, permissions, splash screens, launcher icons, native build configuration.

---

## Thai.ID by FINEMA — Secure Certified Document Creator

### Client / Project Context

FINEMA — privacy-focused digital document utility

### Role

Independent Mobile Developer / Native Platform Reengineering

### Date

April 2023 – October 2025

### Project Description

Independently implemented the original Flutter application for Android and iOS from provided product requirements and UI/UX designs, then reengineered the product through native SwiftUI and Jetpack Compose implementations. Thai.ID creates certified copies of identity cards and personal documents with editable layouts, signatures, bilingual certification, privacy masking, secure local storage, and PDF/image export.

### Key Contributions

- Built camera, gallery, cropping, and PDF-rasterization input pipelines for card and A4 document layouts.
- Implemented five document formats with reusable saved layouts and responsive editing interfaces.
- Developed drag, resize, and rotation controls for signatures, certification text, dates, cross-card markings, and redaction areas.
- Added selective masking for Thai ID numbers, barcodes, names, birth dates, religion, addresses, and photographs.
- Created handwritten signature capture, reusable signature libraries, high-resolution composition, PDF/image output, native sharing, export history, re-editing, and deletion.
- Implemented offline persistence with Isar in Flutter, Room and Proto DataStore in Android, and AppStorage-backed state in SwiftUI.
- Added six-digit application locks and platform biometrics with secure hashing and platform-native authentication APIs.
- Rebuilt the main Android workflow with Jetpack Compose, CameraX, PdfRenderer, Room, DataStore, Coroutines, and Flow.
- Built the iOS application foundation in SwiftUI with NavigationStack, localization, profile/settings flows, BCrypt passcodes, and Face ID/Touch ID.
- Created an Android Views proof of concept using XML, Fragments, View Binding, ViewPager, Safe Args, and Navigation Component.
- Translated one product across Flutter, SwiftUI, Jetpack Compose, and Android Views while adapting navigation, persistence, authentication, media, and lifecycle patterns.
- Implemented provided UI/UX designs for Thai/English onboarding, editable profiles, terms/privacy, support, settings, permissions, and native interface components.
- Managed local image files and reusable signature/layout records with previews, usage tracking, re-editing, and deletion.
- Configured Flutter analytics/crash reporting plus Xcode, Gradle, SDK, resource, font, and package settings for the native rewrites.

### Implementation Status

- **Flutter:** Most complete version, including certification, redaction, export, sharing, and editable history.
- **Jetpack Compose:** Main native Android workflow plus security, profile, persistence, camera, PDF, crop, certification, and signature features; some Flutter capabilities remain in migration.
- **SwiftUI:** Native application shell, onboarding, profile, settings, localization, passcode, and biometric flows; advanced document composition is not yet fully represented.
- **Android Views:** Architecture proof of concept for onboarding and Fragment/XML navigation.

### Key Features

- Camera, gallery, crop, and PDF-page import/rasterization.
- Single/double-sided cards, half-A4, full A4, and reusable named layouts.
- Drag, resize, and rotation controls for document images and annotations.
- Thai/English certification, dates, cross-card markings, and handwritten e-signatures.
- Signature library with preview, selection, usage tracking, and local file management.
- Privacy masking for ID number/barcode, name, birth date, religion, address, and photograph.
- High-resolution PDF/image output, previews, gallery save, sharing, export history, re-editing, and deletion.
- Offline storage for profiles, settings, signatures, layouts, preferences, and history.
- Six-digit PIN/passcode protection using salted hashing or BCrypt by platform.
- Face ID, Touch ID, Android biometrics, localization, onboarding, profiles, settings, and support.

### Technologies

- **Flutter product:** Flutter, Dart, GetX, Isar, Firebase Analytics, Firebase Crashlytics, PDF/image rendering, native sharing, signature capture.
- **Native iOS:** Swift, SwiftUI, NavigationStack, AppStorage, LocalAuthentication, BCryptSwift, WebKit, String Catalogs, Xcode.
- **Android Compose:** Kotlin, Jetpack Compose, Material 3, Navigation Compose, CameraX, PdfRenderer, Room, KSP, Proto DataStore, Coroutines, Flow, BiometricPrompt.
- **Android Views:** Kotlin, XML, ConstraintLayout, Fragments, View Binding, ViewPager, Safe Args, Navigation Component.
- **Security and data:** Salted SHA-256, BCrypt, native biometrics, Isar, Room, DataStore, AppStorage, local image-file management.
- **Document pipeline:** Camera/gallery input, PDF rasterization, cropping, bitmap composition, redaction overlays, PDF/image generation, Android, iOS.

---

## Thai OCR WebAssembly Demo

### Client / Project Context

FINEMA document OCR and identity-document analysis demonstration

### Role

Independent Flutter Developer — solo project

### Date

August 2025 – September 2025

### Project Description

Developed, configured, and deployed a browser-based Flutter WebAssembly demonstration from provided product requirements and UI/UX designs for FINEMA’s document-analysis APIs. It supports general-document OCR, passport MRZ extraction and validation, Thai national ID extraction, and physical-card liveness detection.

### Key Contributions

- Built four independent analysis workflows with responsive Material 3 interfaces and nested navigation.
- Implemented browser uploads for JPG, JPEG, PNG, and PDF with in-memory byte handling, extension checks, a 5 MB limit, per-service queues, and deletion controls.
- Integrated REST endpoints using Base64 document payloads, UTF-8 JSON decoding, typed responses, and clear server/application error states.
- Presented page-by-page OCR previews and copyable text, structured passport fields and MRZ status, Thai/English national ID data and imagery, and card-liveness pass/fail results.
- Modeled responses with Freezed and json_serializable and managed login, files, navigation, loading, and response state with Riverpod.
- Added persistent demo sessions, SHA-256 credential comparison, Flutter WASM build configuration, Firebase setup, SPA rewrites, Hosting, and deployment workflow.
- Isolated all four tools with independent file managers and asynchronous providers so documents and pending results cannot leak between workflows.
- Decoded Base64 document and face imagery beside structured response data while retaining browser file bytes in memory.
- Implemented consistent empty, loading, validation, API-error, and unexpected-error states for live demonstrations.
- Defined a clear system boundary: WebAssembly delivers the browser client while FINEMA APIs perform OCR and liveness inference.

### Key Features

- Four dedicated tools for general OCR, passport analysis, Thai ID analysis, and physical-card liveness.
- JPG, JPEG, PNG, and PDF uploads with extension checks and a 5 MB limit.
- In-memory browser file handling with separate service queues, single deletion, and bulk clearing.
- Base64 encoding, service-specific REST requests, UTF-8 JSON decoding, and typed responses.
- Page-by-page source previews with extracted text and one-click clipboard copying.
- Structured passport identity fields, formatted dates, optional data, and MRZ validation status.
- Thai/English ID names, dates, religion, address, processed card image, and extracted face image.
- Immediate physical-card liveness pass/fail presentation with the analyzed image.
- Persistent demo login, responsive Material 3 layout, nested navigation, and Firebase deployment.

### Technologies

- **Web application:** Flutter, Dart, Flutter Web, WebAssembly, Material 3, responsive wide-screen UI.
- **Architecture:** Riverpod, generated providers, Flutter Hooks, Freezed, json_serializable, build_runner, nested navigation.
- **API and data:** REST APIs, HTTP, Base64, UTF-8/JSON, immutable typed service responses.
- **Browser capabilities:** File Picker, in-memory bytes, image/PDF validation, clipboard integration, Base64 image decoding.
- **Authentication and hosting:** SHA-256 credential comparison, SharedPreferences, Firebase Core, Firebase Hosting, SPA rewrites, WASM build workflow.

---

## ETMS e-Seal Android Application — QR Usage-Cycle Lookup

### Client / Project Context

Post-production feature enhancement for an existing Excise Department e-Seal Android application.

### Role

Android Developer — QR Scan and Usage Cycle Feature

### Date

March 2025 – September 2025

### Project Description

Contributed a focused engineering enhancement to an application that was already in production, implementing the existing product and UI/UX requirements for the feature. It recognizes e-Seal device codes and IMEI-formatted QR values from a live camera or gallery image, requests the device’s total usage-cycle count from a protected API, and presents it in a new Jetpack Compose screen. The original ETMS application was not developed by me.

### Key Contributions

- Extended CameraX and Google ML Kit scanning while preserving the existing QR login workflow.
- Parsed and normalized IMEI payloads and 12-character numeric or alphanumeric device codes.
- Added conditional routing so device codes open the usage details flow and other payloads retain their existing behavior.
- Built a Jetpack Compose result screen with loading, failure, and successful response states.
- Integrated an authenticated REST endpoint using OkHttp and Kotlin Serialization.
- Managed asynchronous data with ViewModel and StateFlow and passed the device code through Navigation Compose.
- Prepared required dependency, API environment, Android SDK, Firebase, version, and release-build updates.
- Applied identical identifier rules to live frames and gallery images for predictable operator behavior.
- Normalized valid alphanumeric values to uppercase and surfaced HTTP errors and connection failures clearly.
- Integrated the enhancement with targeted detection and conditional routing instead of replacing established scanner logic.

### Key Features

- Live CameraX QR analysis and barcode extraction from gallery images.
- Recognition of IMEI, 12-digit, and 12-character alphanumeric identifiers.
- Input validation, normalization, and uppercase conversion for supported codes.
- Content-aware routing that separates e-Seal lookups from the existing QR authentication path.
- Device-code transfer through a Navigation Compose route argument.
- Protected API lookup for an e-Seal device’s total usage-cycle count.
- Compose details screen displaying the seal number and total usage count.
- ViewModel/StateFlow loading, success, unsuccessful HTTP, and connection-error states.
- Dependency, SDK, Firebase, API-environment, version, and release-build updates.

### Technologies

- **Android UI:** Kotlin, Jetpack Compose, Material 3, Navigation Compose, Android SDK 36.
- **Scanning:** CameraX, Google ML Kit Barcode Scanning, live image analysis, gallery-image decoding.
- **State:** Android ViewModel, Kotlin Coroutines, StateFlow, lifecycle-aware Compose collection.
- **Networking and data:** OkHttp, protected REST API, authorization headers, Kotlin Serialization, typed JSON mapping.
- **Delivery:** Firebase, Gradle, dependency/SDK upgrades, environment configuration, release versioning and build preparation.

---

## TB789 — Thai License Plate Marketplace

### Client / Project Context

Independent full-stack side project, formerly named 789plates

### Role

Founder, Product Designer, and Full-Stack Developer

### Date

May 2024 – Present

### Project Description

Conceived and developed a specialized marketplace for discovering, listing, and collecting Thai vehicle registration plates. The actively developed prototype combines a responsive Flutter client with a Rust/Axum backend, PostgreSQL persistence, pattern-aware search, seller storefronts, inventory tools, likes and saves, authentication, and S3/CloudFront media infrastructure.

### Key Contributions

- Modeled Thai plate prefixes, character groups, numbers, provinces, vehicle categories, visual styles, prices, quantities, sellers, and reactions.
- Implemented pattern-aware search for number-text-number, number-text, text-number, text-only, and number-only queries, returning exact and suggested matches.
- Built filters for plate type, province, vehicle category, maximum price, virtual inventory, sorting, pagination, and list/grid layouts.
- Developed seller listing, validation, image crop/upload, inventory, pricing, pinning, storefront, and engagement workflows.
- Built email verification, account creation, sign-in, session restoration, refresh-token rotation, password recovery/change, and account deletion.
- Developed a 40+ route Rust/Axum REST API with SQLx/PostgreSQL, middleware, request limits, timeouts, tracing, and graceful shutdown.
- Integrated S3 presigned media operations, CloudFront delivery, transactional email through Lettre, and secure mobile credential storage.
- Added Thai/English localization, light/dark themes, responsive layouts, custom plate typography, and realistic plate previews.
- Built detailed plate and store views with inventory totals, pinned listings, seller data, reactions, saved state, and collection counts.
- Added middleware for API keys, normalized email validation, uniqueness checks, bearer tokens, request limits, timeouts, tracing, and graceful shutdown.
- Generated typed Flutter models and Riverpod providers and organized nested tab/drawer navigation with GoRouter.
- Created Node.js utilities to generate and transform Thai plate-pattern data during domain research.

### Project Status

Authentication, profiles, listings, marketplace search, filters, likes/saves, seller queries, and media infrastructure are implemented. Real-time chat and ownership-transfer workflows remain incomplete or partially connected; the project is not presented as a public production deployment.

### Key Features

- Email-verified registration, sign-in, session restoration, token renewal, password recovery/change, and account deletion.
- User profiles, seller/store information, ratings/data, inventory totals, and pinned listings.
- Listing creation with province, category, Thai characters/numbers, price, quantity, sale status, and validation.
- Camera/gallery listing images with crop and S3 presigned upload operations.
- Domain-specific parsing of mixed Thai text/number queries into five plate structures.
- Exact and suggested results when no perfect inventory match exists.
- Filters for type, province, vehicle category, maximum price, virtual listings, sorting, pagination, and list/grid display.
- Realistic plate previews with official-style colors, formats, province data, and custom Thai typography.
- Plate/store details, likes, saved plates/stores, reaction totals, and seller-specific inventory.
- Thai/English localization, light/dark themes, secure storage, cached media, and responsive UI.
- Transactional verification email, S3 presigned media operations, and CloudFront delivery.

### Technologies

- **Client:** Flutter, Dart, Material UI, Riverpod, Flutter Hooks, GoRouter, Freezed, json_serializable, HTTP/JSON.
- **Mobile:** Flutter Secure Storage, SharedPreferences, Image Picker, Image Cropper, cached images, localization, Android, iOS.
- **Backend:** Rust, Axum, Tokio, Tower, Tower HTTP, Serde, Validator, middleware, structured tracing, graceful shutdown.
- **Database:** PostgreSQL, SQLx, migrations, typed queries, relational marketplace/search/reaction data.
- **Security:** JWT access/refresh tokens, rotation, BLAKE3, API-key and bearer-token middleware, request validation/limits.
- **Email and media:** Lettre/SMTP, expiring codes, AWS SDK for Rust, Amazon S3, presigned URLs, object removal, CloudFront.
- **Research:** Node.js scripts for Thai registration-plate pattern generation and transformation.

---

## Taengmo — Full-Stack Recruitment Platform

### Client / Project Context

Independent side project; two-sided recruitment platform

### Role

Founder, Product Designer, and Full-Stack Developer

### Date

2025 – Present

### Project Description

Conceived, designed, and developed a recruitment platform connecting candidates with employers and hiring personnel. Originally created with Vue.js, the frontend was redesigned and rewritten with React, TypeScript, and Next.js and organized into a unified application, reusable UI library, shared utilities, and a Rust/Axum REST API.

### Key Contributions

- Built candidate profiles covering personal data, education, employment, skills, languages, certifications, awards, résumés, documents, applications, and saved jobs/employers.
- Developed employer workflows for organizations, locations, sectors, benefits, personnel, jobs, applicants, application statuses, and saved candidates.
- Rewrote the original Vue.js frontend using React, TypeScript, and Next.js and extracted reusable component and utility packages.
- Engineered an Axum/PostgreSQL API with role-specific endpoints, SQLx relational operations, email verification, password recovery, and authorization.
- Implemented JWT access/refresh flows, API-key validation, password hashing, verification codes, and protected routes.
- Integrated S3-compatible object storage and presigned uploads for profile imagery, résumés, certificates, and candidate documents.
- Added Leaflet location selection, PDF résumé viewing, rich-text job content, image cropping, server-state synchronization, and application state stores.
- Designed international reference data for countries, languages, currencies, CEFR levels, education, contracts, workplace modes, and proficiency scales.
- Consolidated earlier employer and candidate portals into a unified application while retaining clear role-specific boundaries.
- Created reusable React UI and TypeScript packages for forms, dialogs, validation, badges, models, enumerations, reference data, and styling.
- Implemented organization administration with multilingual names, multiple locations, sectors, benefits, personnel onboarding, and activation controls.
- Added structured tracing, graceful shutdown, environment configuration, transactional email, and object-removal endpoints.

### Project Status

Actively developed side project rather than a claimed production deployment. Candidate, employer, authentication, profile, storage, and application-management foundations are implemented; chat, subscription, advanced search, and some routes require further integration or production hardening.

### Key Features

- Candidate registration, email verification, authentication, token refresh, password reset, and protected dashboards.
- Professional profiles with personal data, summaries, education, employment, skills, interests, and CEFR languages.
- Licenses, certifications, awards, social links, résumés, supporting files, and portfolio documents.
- Job discovery, job details, applications, application history, saved jobs, and saved employers.
- Employer accounts and organization profiles with images, multilingual names, sectors, size, currency, benefits, and verification state.
- Multiple organization/job locations with interactive Leaflet map selection.
- Personnel invitation, onboarding, activation, profile, and administrative-access workflows.
- Job management, applicants, candidate details, résumé viewing, status workflows, and saved candidates.
- JWT sessions, email verification, role authorization, API-key checks, and protected client/server routes.
- Presigned uploads for profile images, covers, résumés, certificates, and candidate documents.
- Reusable component and utility packages plus international recruitment reference data.

### Technologies

- **Frontend:** React 19, Next.js 16, TypeScript, Material UI, Tailwind CSS, Emotion, Vite.
- **State and data:** TanStack Query, Zustand, reusable TypeScript models/utilities, validation, protected routes.
- **User experience:** next-intl, Leaflet/React Leaflet, React PDF, React Quill, React Easy Crop, responsive role-specific interfaces.
- **Backend:** Rust 2024, Axum, Tokio, Tower, Serde, Validator, structured tracing, graceful shutdown.
- **Database:** PostgreSQL, SQLx, migrations, transactions, typed relational operations.
- **Authentication:** JWT access/refresh tokens, API keys, BLAKE3, verification codes, password recovery, role authorization.
- **Email and storage:** Lettre, S3-compatible storage, AWS SDK for Rust, presigned uploads, object removal.
- **Architecture:** Unified app, earlier employer/candidate portals, shared React UI library, TypeScript utilities, Rust REST API.

---

# Professional Experience

## Flutter Developer — FINEMA Co., Ltd

**March 2023 – Present**

- Develop cross-platform mobile and web applications with Flutter and Dart.
- Work on identity, certified-document, OCR, biometric, government-service, and demonstration applications.
- Own UI implementation, state management, navigation, API integration, device features, local persistence, Firebase configuration, and Android/iOS setup across assigned projects.
- Apply native Android and iOS technologies where platform-specific implementation or product reengineering is required.

## Flutter Developer — Relationship Republic Co., Ltd

**September 2022 – March 2023**

- Developed and maintained Flutter application features for Android and iOS.
- Collaborated within the product-development lifecycle on UI, application logic, integrations, testing, and delivery.

## Junior Java Developer — Skytizens (ThaiTizens Co., Ltd)

**March 2022 – September 2022**

- Contributed to Java-based software development and gained experience working with production code, team processes, and business requirements.

---

# Technical Skills

## Languages

Dart, Kotlin, Java, Swift, Rust, TypeScript, JavaScript, Go, HTML, CSS, SQL.

## Mobile

Flutter, Flutter Hooks, Riverpod, GetX, GoRouter, Freezed, SwiftUI, Jetpack Compose, Android Views, CameraX, Navigation Compose, NavigationStack, Fragments, Firebase, secure storage, local notifications, deep links, biometric APIs, app publishing, TestFlight.

## Frontend

React, Next.js, Vue.js, Nuxt.js, Pinia, Material UI, Tailwind CSS, Emotion, TanStack Query, Zustand, Flutter Web, WebAssembly.

## Backend

Rust, Axum, Tokio, Tower, SQLx, Node.js, Express.js, NestJS, Go, REST APIs, WebSockets, Openfire XMPP, Apache Pulsar.

## Databases & Storage

PostgreSQL, MySQL, MongoDB, Mongoose, Elasticsearch, Isar, Room, SharedPreferences, Proto DataStore, AppStorage, Amazon S3, CloudFront.

## Tools, Cloud & Delivery

Git, Docker, Linux command line, Nginx, Postman, Jira, Figma, VS Code, Android Studio, Xcode, Firebase App Distribution, Firebase Hosting, Firebase Cloud Messaging, Firebase Remote Config, Firebase Realtime Database, Firebase Crashlytics, AWS EC2, app-store publishing, Google Play publishing.

## Automation & Other Platforms

Selenium, Cheerio, web scraping, Microsoft Power Automate, Joget.

---
