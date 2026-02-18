# Basel Omar - Professional QS Consultant & Civil Engineer Web Application

A comprehensive, mobile-optimized web application designed for Basel Omar, a Civil Engineer and QS Consultant based in Dubai, UAE.

## 🌟 Features Overview

This single-page application includes 5 integrated features:

### 1. **Dashboard**
- Real-time statistics display
- Memory test progress tracking
- Jobs viewed counter
- Documents created counter
- Recent activity timeline
- Abu Dhabi time (UTC+4) display

### 2. **Memory Test System**
- 150 structural engineering exam questions
- Hourly question delivery system (2:00 PM - 2:00 AM Abu Dhabi time)
- 2 questions per hour, 20 questions per day
- Multiple choice format with explanations
- Progress tracking and accuracy calculation
- Mistake tracking by topic
- Countdown timer for next test
- Browser notifications support
- LocalStorage persistence

### 3. **Freelance Jobs Finder**
- 50+ sample jobs from 10+ platforms:
  - Upwork, Fiverr, Freelancer.com, Toptal
  - PeoplePerHour, Guru, and more
- Match percentage algorithm (70-96%)
- Color-coded match badges:
  - Green: 85%+ (High match)
  - Yellow: 70-84% (Medium match)
  - Red: <70% (Low match)
- Filter by platform, match %, and keywords
- Customized proposal generator
- Save jobs functionality
- Budget range display

### 4. **Invoice Generator**
- Professional invoice creation
- Dark blue header with company branding
- Dynamic item rows (add/remove)
- Real-time total calculation
- Live preview panel
- Save draft functionality
- Print to PDF (browser print dialog)
- Client information management
- Payment terms and notes

### 5. **Quotation Generator**
- Professional quotation creation
- Navy and blue theme
- Validity period setting (default 30 days)
- Project-based quotations
- Dynamic service items
- Terms & conditions customization
- Real-time calculations
- Live preview
- Print to PDF capability

## 🎨 Design Specifications

### Color Scheme
- **Primary:** Dark Blue (#003366)
- **Secondary:** Navy Blue (#003d7a)
- **Accent:** Light Gray (#f5f5f5)
- **Text:** Dark Gray (#333333)
- **Success:** Green (#28a745)
- **Warning:** Yellow (#ffc107)
- **Danger:** Red (#dc3545)
- **NO PINK COLORS** ✓

### Typography
- Primary Font: Arial, Roboto
- Clean, professional sans-serif
- Responsive font sizes

### Responsive Design
Tested and optimized for:
- 📱 **Mobile:** 320px - 480px (iPhone, Android)
- 📱 **Tablet:** 480px - 1024px (iPad, tablets)
- 💻 **Desktop:** 1024px+ (laptops, desktops)

## 🚀 Technical Details

### Technology Stack
- **HTML5:** Semantic markup
- **CSS3:** Modern styling with flexbox/grid
- **Vanilla JavaScript:** No framework dependencies
- **LocalStorage API:** Client-side data persistence
- **Browser Print API:** PDF generation

### Key Features
- ✅ Single HTML file (83KB)
- ✅ 100% client-side (no server required)
- ✅ Offline functionality
- ✅ Mobile-first responsive design
- ✅ Touch-friendly (48px+ buttons)
- ✅ Abu Dhabi timezone (UTC+4)
- ✅ Browser notifications
- ✅ Data persistence
- ✅ Professional UI/UX

## 📦 Installation & Usage

### Method 1: Direct File Open
1. Download `basel_system.html`
2. Double-click to open in any modern browser
3. That's it! No installation needed.

### Method 2: Web Server
1. Host on any static web server:
   - GitHub Pages
   - Netlify
   - Vercel
   - AWS S3
   - Simple HTTP server: `python3 -m http.server`

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile Safari (iOS 14+)
- ✅ Chrome Mobile (Android)

## 💾 Data Storage

All data is stored locally in your browser using LocalStorage:
- Memory test progress and answers
- Question history (to avoid repeats)
- Saved jobs
- Invoice drafts
- Quotation drafts
- Daily statistics

**Note:** Data persists across browser sessions but is device-specific.

## 🔧 Features in Detail

### Memory Test System
**Operating Hours:** 2:00 PM - 2:00 AM (Abu Dhabi Time)
- Delivers 2 questions every hour
- Tests retention from previous hour
- Tracks mistakes by topic
- Shows explanations after answering
- Generates end-of-day reports
- Never repeats questions until all 150 are used

### Jobs Finder Algorithm
**Matching Criteria:**
- User skills: QS, BOQ, Civil Engineering
- UAE/Dubai experience: 10+ years
- Project count: 300+ projects
- Budget alignment
- Skill requirements

**User Profile (Embedded):**
- Name: Basel Omar
- Title: Civil Engineer & QS Consultant
- Certifications: SOE member, Dubai Municipality (G+4)
- Experience: 10+ years UAE
- Projects: 300+
- Specialties: QTO, BOQ, Cost Estimation
- Contact: +971 54 547 2423
- Email: basel.omar.qs@gmail.com
- Website: baselomar.site

### PDF Export
Uses browser print functionality:
1. Click "Download PDF" button
2. Browser print dialog opens
3. Select "Save as PDF" destination
4. Save the file
5. Professional formatting maintained

## 📱 Mobile Experience

### Touch Optimization
- Large tap targets (48px minimum)
- Swipe-friendly cards
- Responsive grids
- Single-column mobile layout
- No horizontal scrolling
- Optimized form inputs

### Mobile Navigation
- Sticky header
- Full-width buttons
- Stack vertically
- Easy thumb navigation

## 🔐 Security & Privacy

- ✅ No data sent to servers
- ✅ No external API calls (except blocked CDN)
- ✅ All data stays on your device
- ✅ No tracking or analytics
- ✅ Client-side only
- ✅ No sensitive data storage

## 📊 Sample Data Included

- **150 structural engineering questions** with:
  - Question text
  - 4 multiple choice options
  - Correct answer
  - Detailed explanation
  - Difficulty level
  - Topic category

- **50 freelance job listings** with:
  - Platform information
  - Job titles and descriptions
  - Budget ranges ($300-$4000)
  - Match percentages (70-96%)
  - Custom proposals
  - Skills required
  - Deadlines

## 🎯 Use Cases

1. **Daily Memory Training:** Structural engineering exam preparation
2. **Job Hunting:** Find and track freelance opportunities
3. **Business Operations:** Generate professional invoices
4. **Client Quotations:** Create project quotations quickly
5. **Performance Tracking:** Monitor daily progress and accuracy

## 📞 Contact Information

**Basel Omar**
- 📧 Email: basel.omar.qs@gmail.com
- 📱 Phone: +971 54 547 2423
- 🌐 Website: [baselomar.site](https://baselomar.site)
- 🏆 Certifications: SOE Member, Dubai Municipality Certified (G+4)
- 💼 Experience: 10+ Years in UAE
- 📊 Projects: 300+ Delivered

## 🆘 Support & Troubleshooting

### Common Issues

**Q: Notifications not working?**
A: Allow notifications when prompted by the browser.

**Q: Data not saving?**
A: Ensure LocalStorage is enabled in browser settings.

**Q: PDF download not working?**
A: Use browser print dialog to save as PDF (Ctrl+P or Cmd+P).

**Q: Mobile view not responsive?**
A: Clear browser cache and reload.

### Browser Settings Required
- ✅ JavaScript enabled
- ✅ LocalStorage enabled
- ✅ Notifications allowed (optional)
- ✅ Pop-ups allowed (for print dialog)

## 📝 Version History

**v1.0.0** (February 2026)
- Initial release
- All 5 features implemented
- 150 questions database
- 50 job listings
- Full responsive design
- LocalStorage persistence
- Print-to-PDF functionality

## 🙏 Credits

Built specifically for Basel Omar - QS Consultant & Civil Engineer
Designed for UAE construction industry professionals

---

© 2026 Basel Omar - All Rights Reserved
