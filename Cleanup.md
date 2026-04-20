# Refactor Summary Report Template

## Overview
- **Project:** [name]
- **Date:** [date]
- **Duration:** [time]

## Results

### File Count
| Metric | Before | After | Change |
|---|---|---|---|
| Total Files | [n] | [n] | -[n] ([%]%) |
| Total Directories | [n] | [n] | -[n] |
| Total Lines of Code | [n] | [n] | -[n] ([%]%) |

### Actions Performed

#### Files Consolidated
| Merged From | Merged Into |
|---|---|
| `fileA.js`, `fileB.js` | `combined.js` |

#### Utilities Extracted
| Utility | Extracted From | New Location |
|---|---|---|
| `formatDate()` | 3 files | `src/utils/date.js` |

#### Dead Code Removed
| File/Function | Reason |
|---|---|
| `src/old-component.jsx` | Zero imports |

#### Renames Applied
| Old Path | New Path |
|---|---|
| `src/components/userCard.jsx` | `src/components/UserCard.jsx` |

### Issues Encountered & Resolved
| Issue | Resolution |
|---|---|
| Broken import in `App.jsx` after renaming | Updated path from `./userCard` to `./UserCard` |

## Verification
- [ ] All imports resolve correctly
- [ ] Build completes without errors (if applicable)
- [ ] No features removed or altered
- [ ] All edge-case handling preserved
