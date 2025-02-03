# New Inventory Adjustments Dashboard Features

## Table of Contents

- [Overview](#overview)
- [Navigation Bar](#navigation-bar)
- [Filters](#filters)
- [Tabs](#tabs)
- [Statistics Cards](#statistics-cards)
- [Table](#table)
- [Data Manipulation](#data-manipulation)

# Overview

![overview](screenshots/image-17.png)
The Inventory Adjustments Dashboard is a web application designed to manage and track inventory adjustments across different branches. This documentation provides an overview of the new features available on this page.

### Purpose

- Monitor and manage inventory adjustments
- Review and approve adjustment entries
- Track COGS (Cost of Goods Sold) changes
- Generate insights through metrics and statistics
  </br></br></br></br>

# Navigation Bar

![full nav bar](screenshots/image-11.png)

## Information Section

![information section](screenshots/image-30.png)

- Title of Page
- Current Date (NOT the date of the data being viewed)
- Last Refreshed (Updates every 30 minutes)

## Logo Button

![logo button expanded](screenshots/image-29.png)

- Triggers dropdown menu containing all available filters
- Quick access to date selection
- Region/Branch selection interface

## Menu/Settings

![menu/settings](screenshots/image-31.png)

- Triggers dropdown menu containing page options
- Toggle Theme (dark/light mode)
- Export options
- Future features planned:
  - User profiles
  - Bug reporting
  - PDF exports
    </br></br></br></br>

# Filters

![filter section](screenshots/image-15.png)

## Date Filter

![date button](screenshots/image-32.png)
</br>

![date filter](screenshots/image-3.png)

- If only one date is selected by the user, a dropdown will appear beneath the calendar to provide quick range selections. (see picture)
- Single date or date range selection
- Quick range selection dropdown

> [!WARNING]
> Date changes trigger data refresh and clear selections.

## Location Filters

![location filters](screenshots/image-14.png)
**Filter options:**

1. Complete region selection
2. Specific branches within a region
3. Custom branch combinations across regions

## Inventory Specific Filters

![inventory data filter](screenshots/image-12.png)
Available filters:

1. COGS minimum value
2. Buy Line
3. Price Line
4. Adjuster
5. GL Product Type
6. Primary Code (Reviewed Tab only)

## Clearing Filters

![clear filters](screenshots/image-18.png)

- Date filter clear: Refreshes data pool from server
- Other filters clear: Resets currently applied filters to dataset view
  </br></br></br></br>

# Statistics Cards

## Static Cards

![static cards](screenshots/image-9.png)

- MTD/YTD toggle
- Refresh on initial page load only
- Not affected by filters

## Dynamic Cards

![dynamic cards (reviewed)](screenshots/image-10.png)

- Tab-specific metrics
- Filter-sensitive calculations
- Selection-aware updates
- Real-time data reflection
  </br></br></br></br>

# Tabs

![tabs](screenshots/image-8.png)

- There are two tabs that completely separate the data based on their adjustment status.
- As items are reviewed or sent back to unreviewed, they will immediately be removed from the current tab, and appear in their new tab.
  </br></br></br></br>

# Table

![alt text](screenshots/image-19.png)

## Pagination Controls

![rows per page](screenshots/image-23.png)
![pagination](screenshots/image-22.png)

- Adjustable rows per page
- Page navigation
- Total entries counter
- Selection count indicator

## Core Features

![view columns buttons](screenshots/image-33.png)
</br>

![column reorder](screenshots/image-20.png)

- Column Customization

  - Show/hide columns
  - Reorder columns via drag-and-drop

- Data Organization

  - Sort by any column (click column header)
  - Global search across all columns
  - Per-column filtering

- Row Operations
  ![row operations](screenshots/image-21.png)
  - Single row selection
  - Multi-row selection
  - Bulk actions on selected rows
  - Row hover previews
    </br></br></br></br>

# Data Manipulation

## Single Entry Editing

![edit button](screenshots/image-34.png)
</br>

![single entry](screenshots/image-25.png)

- Edit button triggers modal form
- Required fields validation
- Field-specific rules and constraints
- Real-time validation feedback

## Bulk Operations

![bulk edit button](screenshots/image-35.png)
</br>
![bulk entry](screenshots/image-26.png)

- Select multiple entries
- Available bulk actions:
  - Status updates
  - Limited primary code assignment
  - Notes addition
  - Group operations

## Group Entry Management

![group management](screenshots/image-28.png)
<br>

> [!IMPORTANT]
> Feature only present in Offsetting and Previous adjustments

- Create entry groups
- Add/remove entries from groups
- Group validation rules
- Offset ledger functionality
