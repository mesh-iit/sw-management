# SW Distro Management

[![Release](https://img.shields.io/badge/Launch-New_Release-informational?style=for-the-badge&logo=webpack)](../../issues/new/choose)

### 🚚 SW Distros delivery
The following are general remarks detailing our distro workflow:
- 📅 SW Distros are delivered on a **time-based workflow**.
- 4️⃣ SW Distros are released along with the **binaries at each quarter**, aligned with Program Increments + 1, **PI+1**: Feb, May, Aug, Nov.
- 🆓 The feature-freeze lasts **one month**, aligned with the **Program Increments (PI)**.
- 📛 Naming convention adheres therefore to **`YYYY.MM.0`**, where **`YYYY`** identifies the year so as **`MM`** the month of the distro. The patch number **`0`** clarifies that it is a major distro. Examples: 2021.11.0, 2022.02.0...
- 📝 Repositories stay on their usual release convention in order to enable proper **semantic versioning**. To link repos tags to SW Distro and run CI, we rely on [public tables](https://icub-tech-iit.github.io/documentation/sw_versioning_table) and the [`robotology-superbuild`](https://github.com/robotology/robotology-superbuild).
- 📦 Occasionally, we may release **feature-based distros** and/or **patches** as a collection of tags/branches (i.e., no binaries). Naming convention follows the pattern **`YYYY.MM.P`**, where **`YYYY.MM`** identifies the major release used as baseline and the patch number **`P`** is simply increased also in the case of a feature or patch distro released after YYYY/MM.
- ⚠ Distros released before `2021.11.0` may be named without the patch number **`P`** and may also be marked explicitly with `feat` or `patch` labels.
- 👨‍💼 A [**Distro Manager**](#distro-manager-) oversees the workflow, coordinates the effort of the involved developers, and guarantees that the workflow always runs smoothly and timely.

### 👨🏻‍💻 Distro Managers

| Manager | Start Date | End Date |
| :--- | :--- | :--- |
| [@Nicogene](https://github.com/Nicogene) | 2020/04 | in charge |
| [@pattacini](https://github.com/pattacini) | 2019/11 | 2020/04 |
