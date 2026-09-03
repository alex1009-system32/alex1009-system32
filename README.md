# Alex Kerschbamer

`ALTO ADIGE` &nbsp;·&nbsp; [alex1009-system32.github.io](https://alex1009-system32.github.io)

Java and JavaFX on the desktop, React and TypeScript on the web, C++ and Raylib for
the graphics work.

---

## 01. About

Everything here is personal work: small, self-contained programs, mostly desktop
tools and one web frontend.

The portfolio site is where the structure is deliberate: strict TypeScript,
dependencies that only point one way (`sections → features → lib`), and a test suite
split into characterization, edge cases and security — with MSW sitting in front of
it, so a test that reaches for the real network fails instead of quietly passing.

Its README also lists what the site still gets wrong: unauthenticated API rate
limits, an external asset host, section headings that aren't headings.

## 02. Stack

| | |
|---|---|
| **Languages** | `Java` &nbsp;`TypeScript` &nbsp;`JavaScript` &nbsp;`C++` |
| **Web** | `React` &nbsp;`Tailwind CSS` &nbsp;`TanStack Query` &nbsp;`Vite` |
| **Backend & data** | `Spring Boot` &nbsp;`Node.js` &nbsp;`Express` &nbsp;`PostgreSQL` |
| **Desktop & graphics** | `JavaFX` &nbsp;`Raylib` |
| **Testing & tooling** | `Vitest` &nbsp;`MSW` &nbsp;`Git` &nbsp;`Docker` |

## 03. Selected work

### [alex1009-system32.github.io](https://github.com/alex1009-system32/alex1009-system32.github.io)

`TypeScript` `React` `Tailwind` &nbsp;·&nbsp; [live](https://alex1009-system32.github.io)

Single-page portfolio that reads the profile and repository list from the GitHub API
at runtime; only the skills list is kept in code. Every push to `main` builds and
publishes it through GitHub Actions.

### [CalcettoManagementSystem](https://github.com/alex1009-system32/CalcettoManagementSystem)

`Java`

Runs a school calcetto tournament: team management and the UI that visualizes the
standings.

### [GameOfLive](https://github.com/alex1009-system32/GameOfLive)

`C++` `Raylib`

Conway's Game of Life running in a Raylib window.

### [Subnet-Calculator](https://github.com/alex1009-system32/Subnet-Calculator)

`Java` `JavaFX`

Subnet math in a JavaFX window, and nothing else.

---

<sub>The rest is in the repository tab.</sub>
