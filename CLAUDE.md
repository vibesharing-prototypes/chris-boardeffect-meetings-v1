# BoardEffect Meetings v1

## What this is
A React-based prototype for managing board meetings within the BoardEffect platform. Users can view a list of meetings with status indicators, create new meetings from templates, edit meeting details, duplicate existing meetings, and perform row-level actions like delete and status updates.

## Key pages and components

- HomePage - Landing/dashboard view
- MeetingsPage - Main meetings list with filtering and row actions
- MeetingDetailView - Display and edit individual meeting details
- MeetingFormPage - Form for creating/editing meetings
- MeetingRowActions - Inline actions for each meeting row
- ConfirmDialog, DuplicateMeetingDialog, TemplatePickerDialog - Modal dialogs
- StatusChip - Visual status indicator

## Tech stack
React (TypeScript), Vite, CSS

## Current state
Core meeting CRUD operations and UI components are implemented with mock data. No backend integration yet.