# sw-distro-management

### When SW Distro is delivered
The following are general remarks detailing our distro workflow:
- 📅 SW Distros are delivered on a **time-based workflow**, rather than feature-based as we were used to.
- 4️⃣ SW Distros are released along with the **binaries** at each quarters, aligned with Program Increments + 1, **PI+1**: 01-Feb, 01-May, 01-Aug, 01-Nov.
- 🆓 The feature-freeze lasts one month, aligned with **PI**.
- 📛 Naming convention adheres therefore to **YYYY.MM**: e.g. 2020.02, 2020.05... Repos will stay on their usual tags convention in order to enable proper semantic versioning.
- 🐛 Patches are coded as **YYYY.MM.nn**.
- 📦 Exceptionally, we may deliver **feature-based releases** (only tags/branches, no binaries) as **YYYY.MM.feat-nn**.
- 👨‍💼 A **Distro Manager** oversees the workflow guaranteeing that it will alway run smoothly and timely coordinating, the effort of the involved developers.
