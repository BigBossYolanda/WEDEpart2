WEDE POE_PART_TWO

Feedback from Part 1: Navigation was fixed to be consistent across all 5 pages, contact page expanded to include 2 distinct locations with full address/phone/email/hours, semantic tags corrected (header, nav, main, section, article, footer), and all images now have alt attributes and documented sources in content ZIP.
## Part 2 - CSS Styling & Responsive Design (2026-09-18)

 Changes Made
Created external style.css with CSS reset, base styles, typography scale, Flexbox nav and Grid for services/locations
Applied color scheme: #111111 black, #D4AF37 gold, #FFF0F5 soft pink - for luxury hair salon feel
Added pseudo-classes :hover, :focus, :active for all interactive elements
Implemented responsive design

 Breakpoints Used
Desktop: >768px (3-column services, 2-column locations)
Tablet: max-width 768px (2-column services, 1-column locations, nav stacks)
Mobile: max-width 480px (single column all sections, vertical nav, font-size 90%)

 Relative Units
rem for font-sizes, em for padding/margins, % for widths (main 90%, images 100%)

 Testing - DevTools
Tested in Chrome DevTools:
Desktop 1920x1080: Multi-column layout works
Tablet iPad 768x1024: Grid switches to 2 columns
Mobile iPhone 12 390x844: Single column, hamburger not needed as nav stacks vertically

 Screenshots Evidence
 /screenshots/desktop-home.png

 References Part 2
- www.w3schools.com. (n.d.). CSS Comments. [online] Available at: https://www.w3schools.com/css/css_comments.asp [Accessed 18 Sept. 2026].
- W3Schools (2019). CSS Media Queries. [online] W3schools.com. Available at: https://www.w3schools.com/css/css3_mediaqueries.asp [Accessed 18 Sept. 2026].
