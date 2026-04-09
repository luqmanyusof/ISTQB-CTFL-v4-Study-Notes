# Visual Resources for ISTQB CTFL v4.0

## Recommended Diagram Sources

### Chapter 1: Fundamentals of Testing

| Topic | Suggested Visual | Source |
|-------|------------------|--------|
| Testing vs Debugging | Flowchart showing testing finds failure, debugging finds cause | Draw: Testing → Failure → Debugging → Fix → Confirmation Test |
| Error-Defect-Failure Chain | Linear flow diagram | Error (human) → Defect (code) → Failure (runtime) |
| 7 Testing Principles | Numbered list infographic | Create simple icons for each principle |

### Chapter 2: Testing in SDLC

| Topic | Suggested Visual | Source |
|-------|------------------|--------|
| V-Model | Classic V-shape diagram | https://www.getsoftwareservice.com/v-model-of-testing/ |
| Test Levels | Pyramid or stacked boxes | Component → Integration → System → Acceptance |
| Agile Testing | Sprint cycle with testing | Show testing within each iteration |
| Shift Left | Timeline arrow with testing moved left | Before vs After shift left comparison |

### Chapter 3: Static Testing

| Topic | Suggested Visual | Source |
|-------|------------------|--------|
| Static vs Dynamic | Two-column comparison | Side-by-side: No execution vs Execution |
| Review Process | 5-step flowchart | Planning → Initiation → Individual → Communication → Fixing |
| Review Types | Formality scale | Informal ← → Inspection (low to high) |

### Chapter 4: Test Techniques

| Topic | Suggested Visual | Source |
|-------|------------------|--------|
| Equivalence Partitioning | Number line with partitions | Valid partition, Invalid partitions marked |
| Boundary Value Analysis | Number line with boundary points | Min-1, Min, Max, Max+1 marked |
| Decision Table | Grid/table format | Conditions rows, Actions rows, Rules columns |
| State Transition | State diagram with arrows | States as circles, transitions as arrows |
| Statement/Branch Coverage | Code flowchart | Highlight executed paths |

### Chapter 5: Test Management

| Topic | Suggested Visual | Source |
|-------|------------------|--------|
| Test Planning | Mind map or document structure | Scope, Approach, Resources, Schedule |
| Risk Matrix | 2x2 or 3x3 grid | Likelihood vs Impact |
| Defect Lifecycle | State diagram | New → Open → Fixed → Verified → Closed |
| Test Metrics | Dashboard/charts | Progress bars, pie charts |

### Chapter 6: Test Tools

| Topic | Suggested Visual | Source |
|-------|------------------|--------|
| Tool Categories | Icon grid | Management, Execution, Static Analysis, Performance |
| CI/CD Pipeline | Pipeline flowchart | Code → Build → Test → Deploy |

---

## Free Diagram Tools

| Tool | URL | Best For |
|------|-----|----------|
| Draw.io | https://app.diagrams.net | Flowcharts, diagrams |
| Canva | https://canva.com | Infographics |
| Miro | https://miro.com | Mind maps |
| Lucidchart | https://lucidchart.com | Technical diagrams |

---

## Quick Sketch Ideas (Draw Yourself)

### V-Model (Chapter 2)
```
Requirements ─────────────────── Acceptance Testing
    Design ───────────────── System Testing
        Architecture ───── Integration Testing
            Coding ─── Unit Testing
```

### Test Levels Pyramid (Chapter 2)
```
        /\
       /  \  Acceptance
      /────\
     /      \  System
    /────────\
   /          \  Integration
  /────────────\
 /              \  Component
/────────────────\
```

### Defect Lifecycle (Chapter 5)
```
[New] → [Open] → [In Progress] → [Fixed] → [Verified] → [Closed]
                       ↓                        ↓
                  [Rejected]              [Reopened]
```

### Review Formality Scale (Chapter 3)
```
Low ◄─────────────────────────────────────────► High

Informal → Walkthrough → Technical Review → Inspection
```
