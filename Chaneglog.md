# Academic Website Development Changelog

Last updated: 2026-11-01

## Completed

### Collections
- Added `guest_lectures` collection.
- Organized teaching materials into dedicated course pages.
- Added guest lecture entries separate from conference talks.

### Navigation
- Renamed Portfolio → Projects (planned transition in navigation structure).

### Teaching
- Teaching page organized into:
  - Courses Taught
  - Guest Lectures

---

## Planned Improvements

### Publications

Expand publication categories beyond the default Academic Pages structure.

```yaml
publication_category:
  manuscripts:
    title: "Journal Articles"

  conferences:
    title: "Conference Papers"

  reviews:
    title: "Review Articles"

  book-chapters:
    title: "Book Chapters"

  preprints:
    title: "Preprints"

  patents:
    title: "Patents"

  theses:
    title: "Theses"
```

### Projects

Maintain a dedicated Projects section.

Planned structure:

```
Projects
├── Research Projects
├── Outreach
└── Educational Resources (optional)
```

### Outreach

Create a dedicated Outreach subsection under Projects for:

- Public science communication
- Community outreach activities
- STEM workshops
- Educational demonstrations
- Open-source educational resources
- Public engagement initiatives
- Science festival participation

### Teaching

Maintain separate records for:

#### Courses Taught

- ENGPHYS 3ES3 – Introduction to Energy Systems
- ENGPHYS 3PN4 – Semiconductor Junction Devices
- ENGPHYS 4UM2 – Modern and Applied Physics Laboratory
- ENGPHYS 4Z04 – Semiconductor Manufacturing Technology

#### Guest Lectures

Examples:

- Colloidal QDs and Their Applications
- Iron Oxide Nanoparticles for Water-Splitting
- An Engineer's Guide to the Sensor-alaxy

### Talks

Reserve the Talks collection exclusively for:

- Conference presentations
- Invited talks
- Seminars
- Poster presentations
- Keynotes

Do not include guest lectures in the Talks collection.

### Future Collections to Consider

#### Supervision

Potential collection:

```
_supervision/
```

for:

- Undergraduate students
- Graduate students
- Postdoctoral trainees

#### Awards

Potential collection:

```
_awards/
```

for:

- Scholarships
- Fellowships
- Academic awards
- Teaching awards
- Research recognitions

---

## Long-Term Vision

### Main Navigation

- Home
- Publications
- Projects
- Teaching
- Talks
- CV

### Site Organization Philosophy

Collections represent major activity categories:

- Publications
- Projects
- Teaching
- Guest Lectures
- Talks

Categories and tags are used within collections for finer organization.

```

Next time, you can simply tell me:

> "Continue from the website changelog"

and I'll pick up from this roadmap and help implement the next items.