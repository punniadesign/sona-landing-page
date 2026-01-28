# Implementation Plan - Footer & Navigation

I will completely redesign the footer to match the user's reference image and update the top navigation links.

## Proposed Changes

### HTML
#### [MODIFY] [index.html](file:///c:/Users/hp/.gemini/antigravity/scratch/sona-landing-page/index.html)
- **Footer**: Replace existing footer with a 4-column layout:
    1.  **Brand**: Logo + "Your trusted co-sleeping partner..."
    2.  **Product**: Links (How It Works, Features, Pricing, FAQ)
    3.  **Support**: Links (Help Center, Contact Us, Shipping Info, Returns)
    4.  **Company**: Links (About Sona, Our Story, Safety Standards, Press Kit)
    -   Add bottom divider and copyright text.
- **Nav**:
    -   Update links to: "Company", "Reviews", "Product", "Support".
    -   Add "Buy Now" button (pill-shaped) on the right.

### CSS
#### [MODIFY] [f1.css](file:///c:/Users/hp/.gemini/antigravity/scratch/sona-landing-page/css/f1.css)
- **Footer**:
    -   Grid layout for 4 columns.
    -   Soft warm background (using `var(--color-pal-cream)` or similar).
    -   Typography styling: Clean sans-serif, varying weights for headers vs links.
    -   Divider line minimal styling.
- **Nav**:
    -   Adjust flex layout to accommodate new prominent button.
    -   Style "Buy Now" button (distinct from other buttons, premium look).

## Verification Plan
### Manual Verification
- **Footer**: Check 4-column layout on desktop, stacking on mobile. Verify background color and text readability.
- **Nav**: Check new menu items order. Verify "Buy Now" button appearance and hover state.
