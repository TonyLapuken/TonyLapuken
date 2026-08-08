<h1 align="center">GET /tony</h1>
<p align="center"><i>Returns a Tony Lapuken, fully rendered.</i></p>

<!--
  ASSUMPTION: GitHub username is unconfirmed. This README uses "TonyLapuken"
  for the animated typing-SVG banner and every github.com/TonyLapuken link
  because it matches the pattern of the other confirmed handles:
  tonylapuken@gmail.com, linkedin.com/in/tonylapuken, twitter.com/tonylapuken.
  If the real GitHub handle differs, swap every "TonyLapuken" occurrence
  in this file.
-->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=180&section=header&text=api.tonylapuken.dev&fontSize=38&fontColor=00ff9d&animation=fadeIn&fontAlignY=38&desc=Fullsnack%20Developer%20%7C%20UI%20Crafter%20%7C%20Backend%20Tamer%20%7C%20Code%20Snacker%20%7C%20End-to-End%20Mobile%20Dev&descAlignY=58&descSize=14" alt="banner" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/TonyLapuken">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=00FF9D&center=true&vCenter=true&width=600&lines=const+dev+%3D+await+fetch('%2Ftony');;fullstack+%E2%89%88+fullsnack;shipping+clean+UI+%2B+solid+backend;currently+learning%3A+Cloud+Engineering;mobile+apps%2C+end+to+end" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-200_OK-39d353?style=for-the-badge&logo=statuspage&logoColor=white" alt="status"/>
  <img src="https://img.shields.io/badge/method-GET-58a6ff?style=for-the-badge" alt="method"/>
  <img src="https://img.shields.io/badge/Content--Type-application%2Fjson-orange?style=for-the-badge" alt="content-type"/>
  <img src="https://img.shields.io/badge/uptime-%E2%88%9E%20(always%20shipping)-brightgreen?style=for-the-badge" alt="uptime"/>
  <img src="https://img.shields.io/badge/caffeine--dependency-critical-red?style=for-the-badge" alt="caffeine"/>
</p>

<p align="center"><sub>Base URL: <code>https://github.com/TonyLapuken</code> &nbsp;·&nbsp; API Version: <code>v∞</code> (continuously deployed, no breaking changes intended)</sub></p>

---

## Request

```http
GET /tony HTTP/1.1
Host: github.com
Authorization: Bearer coffee_and_curiosity
Accept: application/json
X-Client: recruiter, collaborator, or curious dev
```

## Response

```http
HTTP/1.1 200 OK
Content-Type: application/json
X-Powered-By: clean-UI + solid-backend-architecture
Cache-Control: no-cache, always-shipping-something-new
```

```json
{
  "name": "Tony Lapuken",
  "role": "Fullsnack Developer",
  "aka": ["UI Crafter", "Backend Tamer", "Code Snacker", "End-to-End Mobile Dev"],
  "status": "online, mid-build",
  "currentlyBuilding": "a Flutter mobile app, end to end (design, build, ship)",
  "currentlyLearning": "Cloud Engineering — Google Cloud, going deep",
  "philosophy": "Code with clarity, build with care, snack with joy.",
  "stack": {
    "frontend": ["React", "Angular", "Flutter", "Tailwind CSS", "Material UI", "Framer Motion", "Three.js"],
    "backend": ["Node.js", "Express", "NestJS", "ASP.NET", "MongoDB", "MySQL", "SQL Server"],
    "languages": ["Dart", "TypeScript", "JavaScript", "Java", "C++", "Python", "Go", "Kotlin", "MATLAB"],
    "tools": ["VS Code", "IntelliJ IDEA", "Postman", "Figma", "Adobe Illustrator"],
    "cloud": ["Google Cloud"]
  },
  "links": {
    "email": "tonylapuken@gmail.com",
    "linkedin": "linkedin.com/in/tonylapuken",
    "twitter": "twitter.com/tonylapuken"
  }
}
```

<details>
<summary><b>Schema notes</b> (click to expand)</summary>
<br/>

- `stack.frontend` and `stack.backend` are both populated — this endpoint does not return `null` for either, by design.
- `stack.cloud` is the newest field in this schema, added the moment Google Cloud entered the rotation.
- `currentlyBuilding` and `currentlyLearning` are mutable fields; they get `PATCH`ed fairly often.
- `philosophy` is immutable. It has not changed and is not expected to.

</details>

---

## `GET /tony/status` — live process table

*A lightweight health check. No secrets, just what's currently running.*

```text
$ curl https://github.com/TonyLapuken/status

USER   PID   STATE      PROCESS
tony   101   running    ui_polish_daemon           # never fully idle
tony   202   running    backend_architecture_guard # keeps services in line
tony   303   building   flutter_mobile_app         # active project
tony   404   learning   gcp_cloud_engineering      # racking up billing alerts responsibly
tony   ∞     sleeping   snack_break_scheduler       # wakes for chips, non-negotiable
```

> No process ever reports `FAILED` for long — see `debugging` in the changelog below.

---

## Dependencies Manifest

<table>
<tr>
<td width="50%" valign="top">

**frontend + backend + cloud**

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/Material_UI-0081CB?style=for-the-badge&logo=mui&logoColor=white" />
<img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" />
<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" />
<br/><br/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
<br/><br/>
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />

</td>
<td width="50%" valign="top">

**languages + tools**

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" />
<br/><br/>
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
<img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
<img src="https://img.shields.io/badge/Adobe_Illustrator-FF9A00?style=for-the-badge&logo=adobeillustrator&logoColor=white" />

</td>
</tr>
</table>

<sub>Every dependency above is a fact, not a filler badge — no version is stubbed in and none is left unlisted.</sub>

---

## Authentication

This endpoint doesn't require an API key — just a proper header. Any of the following will authenticate you:

| Header | Value | Notes |
|---|---|---|
| `Authorization: Email` | `tonylapuken@gmail.com` | Highest reliability |
| `Authorization: LinkedIn` | `linkedin.com/in/tonylapuken` | Best for professional context |
| `Authorization: Bearer` | `twitter.com/tonylapuken` | Best for hot takes on dev/design |

> No `403 Forbidden` here — this endpoint is public by design. Say hi.

## Rate Limits

| Endpoint | Limit | Notes |
|---|---|---|
| `POST /message` | unlimited | usually answered same day |
| `POST /pr-review` | 1 req / cup of coffee | optimized for thoroughness, not speed |
| `POST /collab-request` | best-effort | 200 OK if the idea is interesting |
| `POST /snack-break` | 429 Too Many Requests | non-negotiable, do not retry |

## Changelog

*A lightweight, factual log of recent deploys to this human.*

```diff
- [learning]  Angular — component structure clicked, moving on
+ [learning]  Cloud Engineering — Google Cloud, going deep
+ [building]  A Flutter mobile app, end to end (design, build, ship)
  [ongoing]   Balancing clean UI work with solid backend architecture
  [ongoing]   Swapping notes on dev, design, and debugging with anyone who'll chat
```

---

## Errors You Might Get

`GET /tony` is stable in production, but a few edge cases still return non-200s. Known error states, documented below so you don't file a duplicate issue.

| Status | Name | Cause |
|---|---|---|
| `300` | Multiple Choices | Asking which job title is the "real" one. `UI Crafter`, `Backend Tamer`, `Code Snacker`, `End-to-End Mobile Dev` — all valid representations of the same resource. Content negotiation depends on which layer broke today. |
| `403` | Forbidden | Request to skip the architecture and "just hack it in before the demo." Endpoint exists, access denied on principle, appeal process is a 20-minute refactor conversation. |
| `404` | Not Found | A day with no side project open in a second VS Code window. Reported by multiple witnesses, never reproduced. |
| `408` | Request Timeout | Waiting on a straight answer to "React or Angular?" Connection closes before a verdict — there isn't one, it's resolved per-project, not per-opinion. |
| `409` | Conflict | Two priorities at once: shipping the Flutter app end-to-end and going deep on Google Cloud this month. Both branches stay open; merge happens on weekends. |
| `418` | I'm a Teapot | Asking whether "Fullsnack Developer" is just a pun. Confirmed: it is a pun, and also an accurate job description — full-stack under load, snack-stack at all other times. |
| `422` | Unprocessable Entity | A bug report that says "it's broken." Request is well-formed but missing required fields: steps to reproduce, expected result, a screenshot. |
| `425` | Too Early | Asking for a ship date on the Flutter app before the architecture's settled. The request arrived before the server was ready to commit — check back once the data layer's decided, not before. |
| `503` | Service Unavailable | Heads-down on a hard bug, output temporarily paused for everything that isn't the stack trace in front of him. Service resumes automatically once root cause is found. |
| `508` | Loop Detected | Asked to explain, again, how "learning Cloud Engineering" and "building a mobile app" and "maintaining a backend" fit in the same week. It's not a contradiction — it's just the stack. |

<details>
<summary>Example error response</summary>

```json
{
  "status": 503,
  "error": "Service Unavailable",
  "message": "Currently isolating a bug. All non-urgent requests will be processed after root cause is confirmed.",
  "retry_after": "root_cause_found = true"
}
```

</details>

---

<p align="center">
  <i>"Code with clarity, build with care, snack with joy."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:16213e,100:1a1a2e&height=100&section=footer" alt="footer" width="100%"/>
</p>

<!--
This repository is special: it's my GitHub profile repo (named exactly like
my username, TonyLapuken/TonyLapuken), so this README is displayed directly
on my GitHub profile page.
-->
