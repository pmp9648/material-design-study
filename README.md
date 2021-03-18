# Material Design Study

## Overview

Utilizing the ideas from Material IO to be implemented into our current app-stack

## Design

### Layout

#### Principles
- **Predictable** - Use predictable layouts with consistent UI regions and spatial organization.
- **Consistent** - Layouts should be consistent in the use of grids, keylines, and padding
- **Responsive** - Layouts are adaptive and they react to input from a user, device, and screen elements.

#### Measurements
![measurements](/pictures/layout-measurements-1.jpg)

### Pixel Density

Screen density = Screen width / Screen Height

### Responsive Layout

@360 dp (Mobile Device)
- 4 Columns
- 16dp gutter size
- 16dp margins

@600 dp (Tablet)
- 8 Columns
- 24dp gutter size
- 24dp margins

**Gutter**: the space between a column

**Margins**: the space between content and the left and right edges of the screen

8dp gutter size may equate to items beings related in a layout

32dp perceived as individual entities within a collection

Don't use too much space

The ideal length of legibility of body copy is 40-60 characters per line

Gutter and Margin widths can be different

Material Layout Idea
https://material.io/design/layout/responsive-layout-grid.html#ui-regions

### Spacing

![layout-spacing](/pictures/layout-spacing-1.jpg)
Icons, type, and some elements within components can align to a 4dp grid.

![layout-spacing](/pictures/layout-spacing-2.jpg)
1. Status bar height: 24dp
2. App bar height: 56dp
3. List item height: 88dp

### Aspect Ratios

![layout-aspect-ratio](/pictures/layout-aspect-ratio.jpg)

## Applying Colors to UI

### Top and Bottom App Bars
Top and Bottom app bar uses primary color
System bar uses a lighter of dark variant of the primary color

![color-primary](/pictures/color-1.png)

To Emphasize the difference between app-bars and other surfaces, use a secondary color 

![color-secondary](/pictures/color-2.png)

Do: Apply a secondary color to a floating action button.  If you are going to apply a primary color to an action button, make sure it has a shadow

