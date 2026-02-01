# Radiant Space Nuclear BD Hub

## Project Overview
A comprehensive business development resource hub for Radiant Nuclear, focused on space nuclear contract opportunities and technology. The main deliverable is a single-page web application (`space-nuclear-hub.html`) that serves as an internal BD tool.

## Project Files
- **space-nuclear-hub.html** - Main website (~256KB, self-contained HTML/CSS/JS)
- **space-nuclear-contracts.html** - Earlier/alternate version
- **Radiant_BD_Research.docx** - Background research
- **Specific contract related info.docx** - Contract details
- **otas : other contracting stuff.docx** - OTA information
- **Radiant-Master-Plan-Atoms-for-Prosperity.pdf** - Company master plan
- **future strategic options for space nuclear leadership.pdf** - Strategy document

## Website Structure

### Navigation Tabs
1. **Contract Hub** (priority tab) - Active opportunities, contract types, alert setup
2. **Agencies** - NASA, DARPA, Space Force/SpaceWERX, DIU, DOE guidance
3. **Strategy & Playbook** - BD strategy and capture planning
4. **Technical** - Technical specifications and requirements
5. **History** - Space nuclear history
6. **Programs & Timeline** - Key programs and milestones
7. **Radiant Nuclear** - Company-specific information
8. **Contract Deep Dive** - Detailed contract analysis
9. **Glossary** - Terms and definitions

### Key Features
- Global search across all content
- Sidebar with quick links to government portals (SAM.gov, SBIR.gov, DARPA, etc.)
- Downloadable templates (checklists, RFI templates, capture plans)
- Key dates timeline
- Interactive checklist for alert setup
- Responsive design (mobile-friendly)
- Dark theme with purple/cyan accent colors

### Contract Opportunities Tracked
- NASA Fission Surface Power (FSP) RFI - 40-100+ kWe lunar reactors, 2030 goal
- DARPA TTO On-Orbit Nuclear Power - Workshop Feb/Mar 2026
- DARPA DRACO Program - Nuclear thermal propulsion demo ~2027
- DoD SBIR/STTR - Monthly releases
- SpaceWERX - Space Force innovation (SBIR paused as of Oct 2025)
- DIU Janus Program - Army nuclear microreactors
- DOE/National Labs - CRADAs, INL DOME facility

### Key Dates (from sidebar)
- 2026: Radiant Kaleidos Test (INL)
- 2027: DRACO Flight Demo
- 2028: Radiant First Delivery
- 2030: NASA Lunar Reactor Goal
- Mid-2030s: China/Russia Lunar Power

## Technical Details

### Styling
- CSS variables for theming (--bg-primary, --accent, etc.)
- Inter font family
- Glassmorphism header with backdrop blur
- Gradient accents (purple to cyan)
- Custom scrollbar styling

### JavaScript Features
- Tab navigation system
- Global search with fuzzy matching
- Accordion components
- Checklist toggle functionality
- PDF download generation (planned)

## Development Notes

### To Run Locally
Simply open `space-nuclear-hub.html` in a browser - it's fully self-contained.

### Future Enhancements (TODO)
- [ ] Add actual PDF generation for download templates
- [ ] Implement contract deadline notifications
- [ ] Add data persistence for checklist state (localStorage)
- [ ] Consider breaking into separate CSS/JS files for maintainability
- [ ] Add print stylesheet improvements
- [ ] Real-time contract data from SAM.gov API (if available)

## Contact Context
- Matthew Evans - NASA Agreements Officer
- Linda Nabors - NASA Agreements Officer
- DARPA TTO contact: DARPA-SN-26-21@darpa.mil

---
*Last updated: January 2026*
