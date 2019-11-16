# SW Distro Management

[![Release](https://img.shields.io/badge/Launch-New_Release-informational?style=for-the-badge&logo=webpack)](../../issues/new/choose)

### SW Distros delivery 🚚
The following are general remarks detailing our distro workflow:
- 📅 SW Distros are delivered on a **time-based workflow**, rather than feature-based as we were used to.
- 4️⃣ SW Distros are released along with the **binaries at each quarter**, aligned with Program Increments + 1, **PI+1**: 01-Feb, 01-May, 01-Aug, 01-Nov.
- 🆓 The feature-freeze lasts **one month**, aligned with **PI**.
- 📛 Naming convention adheres therefore to **YYYY.MM**: e.g. 2020.02, 2020.05...
- 📝 Repositories stay on their usual release convention in order to enable proper **semantic versioning**. To link repos tags to SW Distro, we rely on public tables and the superbuild.
- 🐛 Patches are coded as **YYYY.MM.nn**.
- 📦 Exceptionally, we may deliver **feature-based releases** (only tags/branches, no binaries) as **YYYY.MM.feat-nn**.
- 👨‍💼 A [**Distro Manager**](#distro-manager-) oversees the workflow, coordinates the effort of the involved developers, and guarantees that the workflow alway runs smoothly and timely.

### Distro Manager 👨‍💼

| Manager | Start Date | End Date |
| :--- | :--- | :--- |
| [@pattacini](https://github.com/pattacini) | 2019/11 | currently in charge |
