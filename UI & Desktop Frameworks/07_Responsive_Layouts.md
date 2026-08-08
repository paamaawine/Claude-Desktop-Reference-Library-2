# Responsive Layouts

Search

Responsive PySide6

Responsive Qt

Qt Splitter

Qt Layout

Qt Grid Layout

Study

Adaptive resizing

High DPI

Window scaling

Responsive forms

Responsive dashboards

# Verified Responsive Layout Standards

Desktop applications should remain usable across different window sizes and screen resolutions.

## Layout Management

Prefer Qt layout managers instead of fixed widget positions.

Use:

- QVBoxLayout
- QHBoxLayout
- QGridLayout
- QFormLayout
- QStackedLayout

Avoid hard-coded coordinates where possible.

## Window Resizing

Important screens should remain usable when the user:

- Resizes the window
- Maximises the window
- Restores the window
- Uses a smaller display

## Size Policies

Use appropriate Qt size policies to control how widgets respond to available space.

Avoid unnecessarily fixed widths and heights.

## Stretch Factors

Use stretch factors where appropriate so important content receives suitable space as the window changes size.

## Tables

Tables should adapt to available space.

Important columns should remain visible, while less important columns may use flexible sizing.

## Sidebar Layouts

A dashboard sidebar should support:

```text
Expanded
    ↓
Navigation labels + icons

Collapsed
    ↓
Icons
