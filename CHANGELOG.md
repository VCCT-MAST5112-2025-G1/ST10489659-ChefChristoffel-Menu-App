# Changelog

## [1.0.0] - 2025-10-10

### Added

- Project scaffold with Expo + React Native and TypeScript
- Screens:
  - Home (menu display and analytics)
  - Manage (add/remove menu items)
  - Filter (course-based filtering)
- Components:
  - MenuCard — displays a menu item
  - AddMenuItemForm — add new items with validation
  - AnalyticsCard — shows average prices and counts
  - EmptyState — informative empty-screen UI
- Utilities:
  - menuUtils.ts — calculation helpers (average price, filters)
  - storage helpers — AsyncStorage wrappers for persistence
- Design:
  - Light and dark theme support
  - Simple, consistent color tokens and typography

### Improved
- TypeScript coverage and explicit types for menu data
- Form validation and user-friendly error messages
- Defensive error handling around local storage and JSON parsing

### Technical notes
- Data persisted using AsyncStorage for offline-first usage
- Simple analytics: average price calculated per course
- Localized price display in South African Rands (R)

---

## [2.0.0] - 2025-10-22

Initial stable release

- Core features implemented:
  - Add, view, and remove menu items
  - Course categories: Starter, Main, Dessert
  - Filtering by course
  - Real-time statistics (counts and average prices)
  - Pull-to-refresh and confirmation dialogs
- Supabase integration for persistent storage
- Sample data button for quick demos
- TypeScript with React Context for state management
- Basic error handling and loading/empty states

---

### [3.0.0] - 2025-11-7

### Fix

- Updated Readme.md file.

### Removed

- Removed unnecessary  imformation here.
