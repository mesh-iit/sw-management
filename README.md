# SW Distro Management

[![Release](https://img.shields.io/badge/Launch-New_Release-informational?style=for-the-badge&logo=webpack)](../../issues/new/choose)

### 🚚 SW Distros delivery
The following are general remarks detailing our distro workflow:
- 📅 SW Distros are delivered on a **time-based workflow**.
- 4️⃣ SW Distros are released along with the **binaries at each quarter**, aligned with Program Increments + 1, **PI+1**: Feb, May, Aug, Nov.
- 🆓 The feature-freeze lasts **one month**, aligned with the **Program Increments (PI)**.
- 📛 Naming convention adheres therefore to **YYYY.MM**: e.g. 2020.02, 2020.05...
- 📝 Repositories stay on their usual release convention in order to enable proper **semantic versioning**. To link repos tags to SW Distro and run CI, we rely on [public tables](https://icub-tech-iit.github.io/documentation/sw_versioning_table) and the [`robotology-superbuild`](https://github.com/robotology/robotology-superbuild).
- 📦 Exceptionally, we may deliver **feature-based releases** (only tags/branches, no binaries) as **YYYY.MM.feat-nn**.
- 🐞 **Patches** are coded as **YYYY.MM.patch-nn** and, like the feature-based releases, are shipped only in terms of tags/branches.
- 👨‍💼 A [**Distro Manager**](#distro-manager-) oversees the workflow, coordinates the effort of the involved developers, and guarantees that the workflow always runs smoothly and timely.

### 👨🏻‍💻 Distro Managers

| Manager | Start Date | End Date |
| :--- | :--- | :--- |
| [@pattacini](https://github.com/pattacini) | 2019/11 | 2020/04 |
| [@Nicogene](https://github.com/Nicogene) | 2020/04 | in charge |
