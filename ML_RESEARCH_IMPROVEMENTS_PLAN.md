# ML Research Scientist Website Improvement Plan

## Goals
1. Transform website to reflect ML Research Scientist identity
2. Fix individual publication pages with proper links and styling
3. Update publication information (MusiCRS → ICASSP 2026)
4. Enhance overall professional appearance

---

## Phase 1: Publication Pages Enhancement ✅

### 1.1 Add Paper URLs to All Publications
- [x] WildScore: https://aclanthology.org/2025.emnlp-main.853/
- [x] MusiCRS: https://arxiv.org/abs/2509.19469
- [x] SINR-Delay: https://ieeexplore.ieee.org/abstract/document/10877934/
- [x] Cholangiocarcinoma: https://opg.optica.org/optcon/fulltext.cfm?uri=optcon-3-8-1311

### 1.2 Update Publication Status
- [x] MusiCRS: Change from "Under review" to "ICASSP 2026"

### 1.3 Enhance Publication Page Layout
- [x] Add prominent "Download Paper" / "View Paper" buttons
- [x] Add citation section with copy button
- [x] Add abstract section
- [x] Add author list
- [x] Add venue badge/styling
- [x] Add related publications section
- [x] Improve typography and spacing

---

## Phase 2: ML Research Scientist Design Elements ✅

### 2.1 Visual Enhancements
- [x] Add research-focused color scheme (academic blue/teal accents)
- [x] Add publication badges/icons (conference logos, impact indicators)
- [x] Improve publication cards with better visual hierarchy
- [x] Add research keywords/tags
- [x] Add metrics section (citations, h-index if available)

### 2.2 Content Organization
- [x] Add research interests section prominently
- [x] Add research highlights section
- [x] Improve publication grouping (by year, by topic)
- [x] Add code/data availability badges
- [x] Add preprint/arXiv links where applicable

### 2.3 Navigation Improvements
- [x] Add "Research" tab
- [x] Add "Publications" with better organization
- [x] Consider adding "Projects" or "Code" section
- [x] Improve CV page layout

---

## Phase 3: Individual Publication Page Redesign ✅

### 3.1 Publication Header Section
- [x] Large, readable title
- [x] Author list with affiliations
- [x] Venue badge with year
- [x] Publication date
- [x] Status badges (Published, Preprint, Under Review)

### 3.2 Action Buttons
- [x] Primary: "View Paper" / "Download PDF" button
- [x] Secondary: "arXiv", "Code", "Dataset", "Slides" links
- [x] Citation copy button
- [x] BibTeX export

### 3.3 Content Sections
- [x] Abstract (expandable)
- [x] Key contributions/insights
- [x] Citation information
- [x] Related publications
- [x] Media (images, videos if available)

### 3.4 Styling
- [x] Clean, academic layout
- [x] Proper spacing and typography
- [x] Responsive design
- [x] Print-friendly styles

---

## Phase 4: About Page Enhancements ✅

### 4.1 Research Focus
- [x] Prominent research interests section
- [x] Research statement/overview
- [x] Current projects highlight

### 4.2 Publication Display
- [x] Better publication cards (already improved)
- [x] Add impact metrics if available
- [x] Group by research area
- [x] Add quick filters (by year, venue, type)

---

## Implementation Priority

**High Priority (Do First):**
1. ✅ Fix publication links (add paperurl)
2. ✅ Update MusiCRS status
3. ✅ Enhance individual publication page layout
4. ✅ Add proper buttons and links

**Medium Priority:**
5. ✅ Improve publication cards styling
6. ✅ Add research-focused design elements
7. ✅ Enhance typography and spacing

**Low Priority (Nice to Have):**
8. Add citation metrics
9. Add code/data badges
10. Add research keywords/tags
11. Add related publications algorithm

---

## Files to Modify

1. `_publications/*.md` - Add paperurl, update venue
2. `_layouts/single.html` - Enhance publication page layout
3. `_includes/archive-single.html` - Improve publication cards
4. `_sass/_publications.scss` - Add publication-specific styles
5. `_sass/_page.scss` - Enhance page layouts
6. `_pages/about.md` - Update publication info
7. Create `_includes/publication-header.html` - New component
8. Create `_includes/publication-actions.html` - Action buttons component

---

## Design Principles

1. **Clean & Professional**: Academic/research-focused aesthetic
2. **Information Hierarchy**: Important info (title, venue, links) prominently displayed
3. **Accessibility**: Clear CTAs, readable fonts, good contrast
4. **Mobile-First**: Responsive design for all devices
5. **Performance**: Fast loading, optimized images
6. **SEO**: Proper meta tags, structured data

---

## Success Metrics

- ✅ All publications have working external links
- ✅ Individual publication pages are well-designed and informative
- ✅ Website reflects ML Research Scientist identity
- ✅ Easy to find and access publications
- ✅ Professional appearance throughout
