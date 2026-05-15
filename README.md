# Prodia QA Transformation - Agile Project Management Website

Website lengkap untuk proyek "Penguatan QA dan Testing Process" PT Prodia Widyahusada Tbk dengan pendekatan Agile Project Management.

## 📁 Struktur Website

```
├── index.html              # Homepage / Landing page with Team Info
├── timeline.html          # Project Timeline & Gantt Chart
├── burndown.html          # Sprint Planning & Burndown Charts
├── kanban.html            # Kanban Board (Interactive)
├── backlog.html           # Product Backlog Items
└── meetings.html          # Meeting Notes & Agile Ceremonies
```

## 🚀 Cara Menggunakan

### Opsi 1: Buka Langsung di Browser
1. Download semua file HTML
2. Klik 2x file `index.html` untuk membuka di browser
3. Navigasi menggunakan menu di bagian atas

### Opsi 2: Hosting Lokal (Recommended)
```bash
# Jika punya Python 3
python -m http.server 8000

# Atau jika punya Node.js
npx http-server

# Kemudian buka browser ke:
http://localhost:8000
```

### Opsi 3: Deploy ke Web Hosting
Upload semua file HTML ke hosting seperti:
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting

## 📊 Fitur Setiap Halaman

### 1. Homepage (index.html)
- **Project Overview** dengan statistik utama
- **Executive Summary** proyek
- **Quick Links** ke semua artifacts
- **Mini Gantt Chart** preview
- **Team Members** Kelompok 5 - The Luminalis Plus
- **Budget & ROI** information

### 2. Project Timeline (timeline.html)
- **Interactive Gantt Chart** untuk 12 bulan
- Visual timeline untuk 6 sprints
- Milestones dan deliverables
- Phase timeline dengan detailed view
- Toggle antara Gantt dan Phase view

### 3. Burndown Charts (burndown.html)
- **6 Sprint Burndown Charts** (interaktif)
- Ideal vs Actual velocity tracking
- Sprint goals dan deliverables
- Sprint backlog detail per sprint
- Sprint metrics dashboard

### 4. Kanban Board (kanban.html)
- **Interactive Sprint Boards** untuk 6 sprints
- Workflow: Backlog → In Progress → In Review → Done
- Story cards dengan:
  - Priority labels (High/Medium/Low)
  - Story points
  - Assignee
  - Category tags
- Sprint selector untuk navigasi antar sprints

### 5. Product Backlog (backlog.html)
- **31 User Stories** lengkap
- Filter by Sprint, Priority, atau Search
- Click story untuk detail lengkap:
  - User story description
  - Acceptance criteria
  - Story points & dependencies
- Summary statistics dashboard

### 6. Meeting Notes (meetings.html)
- **6 Agile Ceremonies Templates:**
  1. Daily Standup (15 min)
  2. Sprint Planning (4 jam)
  3. Sprint Review (2 jam)
  4. Sprint Retrospective (1.5 jam)
  5. Backlog Refinement (1 jam)
  6. Release Planning (3 jam)
- Interactive cards dengan detailed templates
- Real examples dari Sprint 1

## 🎨 Design Features

✅ **Responsive Design** - Mobile & Desktop friendly
✅ **Modern UI** - Gradient backgrounds, smooth animations
✅ **Interactive** - Charts, filters, modals
✅ **Professional** - Clean, minimalist design
✅ **Consistent Navigation** - Sticky header di semua pages

## 📈 Chart & Visualization

Website menggunakan **Chart.js** untuk data visualization:
- Burndown charts (Ideal vs Actual)
- Velocity trends
- Cumulative Flow Diagrams
- Bug trend analysis
- Team capacity charts

Semua charts **fully interactive** dengan hover tooltips dan legend controls.

## 🎯 Use Cases

### Untuk Presentasi
1. Buka di browser fullscreen
2. Gunakan untuk demo kepada stakeholders
3. Screenshot charts untuk slide deck

### Untuk Project Tracking
1. Update data di JavaScript sections
2. Track real-time progress
3. Monitor sprint metrics

### Untuk Dokumentasi
1. Referensi untuk team onboarding
2. Template untuk future projects
3. Knowledge base untuk Agile practices

## 🔧 Customization

### Update Data
Edit JavaScript sections di setiap file untuk update:
- Sprint data
- Story points
- Team members
- Metrics

### Change Colors
Modify CSS variables di `<style>` sections untuk tema custom.

### Add Content
Template mudah diperluas dengan content baru.

## 📱 Browser Compatibility

✅ Chrome/Edge (Recommended)
✅ Firefox
✅ Safari
✅ Mobile browsers

## 📝 Project Context

**Client:** PT Prodia Widyahusada Tbk
**Project:** Penguatan QA dan Testing Process
**Duration:** 12 bulan (Mei 2026 - Apr 2027)
**Approach:** Agile Scrum
**Sprints:** 6 sprints x 2 bulan
**Total Story Points:** 238 SP

### Key Objectives
- Reduce debugging time: 60% → <20%
- Deployment success rate: >95%
- Test automation coverage: >70%
- Defect rate reduction: 40%

## 👥 Team Structure

- Project Manager
- Scrum Master
- Developers (5)
- QA Engineers (3)
- DevOps Engineer (2)
- Security Engineer (1)

## 📚 Agile Artifacts Included

✅ Product Backlog (31 user stories)
✅ Sprint Backlogs (6 sprints)
✅ Burndown Charts
✅ Velocity Tracking
✅ Kanban Boards
✅ Ceremony Templates
✅ DoR & DoD
✅ Definition of Ready/Done

## 🎓 Academic Context

Dibuat untuk:
**Tugas Kelompok - Project Plan MPPTI 2025/2026**
Kelompok 5

Memenuhi requirement:
- ✅ Executive Summary
- ✅ Project Scope
- ✅ Project Schedule
- ✅ Project Cost/Budget
- ✅ Performance Measurement
- ✅ Quality Management
- ✅ Resource Management
- ✅ Communication Management
- ✅ Risk Management
- ✅ Agile Artifacts (Backlog, Kanban, Burndown)

## 💡 Tips

1. **Start from Homepage** - Overview lengkap project
2. **Use Burndown** - Track sprint progress
3. **Check Kanban** - Daily task management
4. **Reference Backlog** - Story details
5. **Review Meetings** - Ceremony templates

## 🔗 Quick Navigation

Semua halaman memiliki navigation bar yang konsisten untuk easy access ke semua sections.

## 📞 Support

Untuk pertanyaan atau feedback mengenai website ini, hubungi team Kelompok 5.

---

**Built with:** HTML, CSS, JavaScript, Chart.js
**Version:** 1.0
**Last Updated:** 2026

© 2026 Prodia QA Transformation Project - Kelompok 5 MPPTI