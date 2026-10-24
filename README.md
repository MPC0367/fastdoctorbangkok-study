# FastDoctorBangkok — design preview

A design preview of a new English and Thai website for FastDoctorBangkok (doctor and nurse visits to
hotels and homes in Bangkok), made by [O2 Design Studio](https://o2-designstudio.com/).

**View it:** https://mpc0367.github.io/fastdoctorbangkok-study/

## What this is

- A **preview, not FastDoctorBangkok's live website** ([fastdoctorbangkok.com](https://fastdoctorbangkok.com/)).
  Every page says so in a bar at the top.
- The public website in English and Thai. The patient, clinician and operations app built alongside
  it needs a server and is not part of this preview.
- **Nothing here calls, messages or sends a request.** Call, WhatsApp and request buttons show a short
  note instead. The emergency number, 1669, still dials.
- **The AI assistant** (the chat button in the bottom-right corner) answers questions about the service
  and helps people who feel unwell find the right care. It is an AI, not a doctor: it checks for
  emergency signs first, never diagnoses or names medicines, and only suggests services from the
  catalog. Until its service is switched on it runs as a demo with scripted answers in your browser,
  and says so; with it, answers come from Claude (Anthropic) and the chat says where messages go.
  Its health information is a draft awaiting clinical review.
- Services, prices and business details come from the current public site. Anything marked
  "pending" is not yet confirmed by the business.
- Not listed on search engines (`noindex`).

The site is served from the `gh-pages` branch. This branch holds only this note and `NOTICE.md`;
the source code is kept privately by the studio.
