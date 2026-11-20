
# TutorHelper — Beta Tester Bug & Feature Requests Tracker

Welcome to the TutorHelper Beta Testing Programme!

This document tracks functionality, bug reports, feature requests and their development progress across the TutorHelper plugin suite.

**Last reviewed:** 20 November 2026  
**Contact:** holly@teachallaboutit.uk

> **Important:** Bug fixes and security updates take priority over new features. Some requests affect several plugins and may require additional development and testing.

## Status guide

| Status | Badge | Meaning |
|---|---|---|
| Implemented | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | Functionality is present in the latest merged `main` branch |
| Reported | ![Reported](https://img.shields.io/badge/Reported-DC3545) | A bug has been reported and requires investigation |
| Requested | ![Requested](https://img.shields.io/badge/Requested-FFD700) | A new feature or improvement has been suggested |
| Testing | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | A fix is being verified |
| Complete | ![Complete](https://img.shields.io/badge/Complete-28A745) | Implementation has been merged and verified |
| Deferred | ![Deferred](https://img.shields.io/badge/Deferred-6C757D) | Planned for a later development batch |

**Priorities:** P1 = High, P2 = Medium, P3 = Low.

*Implemented does not necessarily mean that a feature has passed beta testing.*

---

## 1. TutorHelper Bookings Core

| ID | Feature / Request | Type | Status | Priority | Notes |
|---|---|---|---|---|---|
| BC-001 | Tutor availability and exclusions | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Availability calendar, booking restrictions and date exclusions |
| BC-002 | Booking types | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Manage different lesson types and booking options |
| BC-003 | Student booking interface | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Student-facing booking experience and availability |
| BC-004 | Student dashboard | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Booking information, account controls and lesson access |
| BC-005 | Booking Hub | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Tutor administration and booking management |
| BC-006 | Student and parent account relationships | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Canonical parent/student links used by add-ons |
| BC-007 | Tutor reporting dashboard | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Core reporting and booking analytics |
| BC-008 | Cross-plugin student details integration | Testing | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | P2 | Confirm LMS enrolments and Pro extensions remain compatible |

---

## 2. TutorHelper Bookings Pro

| ID | Feature / Request | Type | Status | Priority | Notes |
|---|---|---|---|---|---|
| BP-001 | Finance management | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF)| — | Payment ledger, finance records and adjustments |
| BP-002 | Stripe payments and refunds | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Payment and refund integration |
| BP-003 | Tutor-issued account credit | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Credit allocation and refund recording |
| BP-004 | Tutor financial statements | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | PDF statement generation |
| BP-005 | Recurring bookings | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Recurring lesson and booking management |
| BP-006 | Attendance tracking | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Tutor records lesson attendance |
| BP-007 | Lesson follow-up and homework setting | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Homework and feedback associated with lessons |
| BP-008 | Student notes and communications | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Student history and communication tools |
| BP-009 | Progress reporting | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Student reporting and feedback |
| BP-010 | Account-credit and refund reconciliation | Regression | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | P1 | Verify balances and statuses after credit/refund transactions |
| BP-011 | Homework maximum marks passed to LMS | Bug / Integration | ![Reported](https://img.shields.io/badge/Reported-DC3545) | P2 | Tester reports that the marks available for homework do not appear in the LMS marking interface; see LP-007 |

---

## 3. TutorHelper LMS Core

| ID | Feature / Request | Type | Status | Priority | Notes |
|---|---|---|---|---|---|
| LC-001 | Learning Hub | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Learning content management |
| LC-002 | Levels, Subjects, Courses and Topics | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Reusable academic structures |
| LC-003 | Lesson Builder | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Lesson content and learning resources |
| LC-004 | Reusable Question Bank | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Questions and immutable versions |
| LC-005 | Quiz Builder | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Reusable Quizzes with ordered Questions |
| LC-006 | Quiz attempts and automatic marking | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Objective attempts, saved answers and results |
| LC-007 | Import Preview | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | CSV/JSON preview and import infrastructure; full LearnDash execution remains a separate development workstream |
| LC-008 | Preserve Course Builder position when saving | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Saving or adding Lesson/Topic content should refresh only the affected section, not reload the entire page |
| LC-009 | Custom learner-facing Quiz labels | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Allow tutor to choose Quiz, Assignment, Mock Exam, Exam or a custom title |
| LC-010 | Learning Hub enrolled-student count | Bug | ![Reported](https://img.shields.io/badge/Reported-DC3545) | P1 | Students enrolled via Booking Hub Student Details do not appear in the Learning Hub Students card or tab |
| LC-011 | H5P interactive lesson activities | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Support embedded interactive activities within Lessons without treating them as LMS Quizzes |
| LC-012 | LearnDash image-based Question import | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P1 | Preserve images in Question text and answers, including image-to-image Matching Pairs |
| LC-013 | Historical Quiz attempt integrity | Regression | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | P1 | Verify editing a Question does not change previously completed attempts |
| LC-014 | LearnDash Fill-in-the-Blanks/Cloze import fails audit for valid source syntax | Bug / Migration blocker | ![Reported](https://img.shields.io/badge/Reported-DC3545) | **P1** | Import Preview displays blue crosses when LearnDash embeds `{answer}` directly into the prompt; IM3 must parse and convert to TutorHelper's `{{1}}` placeholder model without losing text or content. |
| LC-015 | Multiple accepted answers per Cloze gap | Feature Request / Compatibility | ![Requested](https://img.shields.io/badge/Requested-FFD700) | **P1** | Support LearnDash `{[love][hate]}` alternatives for a single gap; import, edit, deliver and automatically mark any accepted alternative. |
| LC-016 | Configurable mark allocation per Cloze gap and alternative | Feature Request / Compatibility | ![Requested](https://img.shields.io/badge/Requested-FFD700) | **P1** | Preserve LearnDash `{play|2}` and weighted alternatives such as `{[love|2][hate|5]}` when the source scoring flags activate those semantics. Tutor should be able to review/override marks; update totals, marking and attempt snapshots. |
| LC-017 | Scientific HTML and Unicode preservation in imported Questions and answers | Regression / Import compatibility | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | **P1** | Verify subscript, superscript, chemical equations, arrows, rich feedback and safe HTML survive preview correction, creation, editing, player and results. Do not treat HTML tags as gap syntax. |

### LC-014 to LC-017 — Priority LearnDash Cloze and scientific-content migration

**Reported:** 20 November 2026, by a beta tester importing a real LearnDash Biology Question export. **Development workstream:** existing IM3 (confirmed LearnDash Question import), with dependencies in IM1 (Question model/editor) and IM6 (regression).

**Observed issue:** Import Preview correctly finds Question titles, prompts and maximum marks, but reports blue crosses in the *Fill-in placeholders `{{1}}`, `{{2}}` and matching blank answers* column. The preview correction currently presents the original LearnDash prompt in a field intended for blank answers. LearnDash embeds accepted text in single braces; TutorHelper currently expects numbered double-brace placeholders and a separate answer list.

**LearnDash examples supplied by tester** (illustrative source syntax, not TutorHelper syntax):

```text
I {play} soccer.
I {[love][hate]} soccer.
I {play|2} soccer.
I {[love|2][hate|5]} soccer.
```

**Required conversion and review:**

1. Detect LearnDash Cloze tokens within Question HTML and convert each *gap* into `{{1}}`, `{{2}}`, etc. in its original position, while extracting accepted answers and keeping the complete surrounding prompt text.
2. Preserve alternatives **within the same gap** instead of incorrectly creating multiple gaps. Provide tutor-facing preview/edit controls for answers and marks per gap; do not force tutors to hand-rewrite imported source prompts.
3. Handle source mark values and answer-point modes according to **verified LearnDash 5.1.7 grading semantics**. Do not assume a per-answer weight is active simply because source text includes a number. If alternate correct answers can earn different scores, extend the answer/marking model or flag for explicit tutor approval rather than silently reducing it to one mark.
4. Keep the existing TutorHelper-native `{{n}}` import format working, and maintain backward compatibility with previously saved Cloze Questions and historical attempt snapshots.
5. Verify source and destination rich text, including `<sub>`, `<sup>`, entities, Unicode arrows and chemical formulae, survives HTML sanitisation, edit/save cycles, student rendering and feedback. Unsupported or ambiguous patterns remain **Draft / Needs Review** rather than being published incorrectly.
6. Use the real tester's LearnDash export only as a **private** regression fixture. Add sanitised synthetic tests for single gaps, several gaps, multiple accepted answers, weighted variants, malformed braces, mixed HTML and repeats. No historical student attempts should be imported.

**Acceptance tests:** A LearnDash Question such as `Animal cells have a {nucleus|1} that controls the cell and contains {DNA|1}.` previews as two correctly positioned gaps with the right answers and score, and no false missing-field cross; `{[love][hate]}` gives one gap with two valid answers; weighted alternatives are awarded exactly according to verified source semantics; scientific HTML remains rendered correctly. Re-import is idempotent.

**Work instruction:** Update the existing **TutorHelper LMS Development Tracker** IM3 definition of done, its IM1 dependencies, IM6 tests, change log and decisions. Keep this beta-facing issue register aligned without claiming a fix until the PR is merged and sandbox-tested.

### LC-008 — Course Builder partial refresh

**Reported by:** Holly

Currently, saving Course/Topic/Lesson changes can reload the entire Course Builder.

**Requested behaviour:**

- Save changes without a full page refresh.
- Preserve expanded and collapsed Topic sections.
- Preserve scroll position.
- Refresh only the changed Lesson, Topic or activity.
- Keep existing unsaved work in other panels intact.

**Acceptance test:** Collapse several Topics, edit a Lesson, save it and confirm the page remains in the same position with the same Topics collapsed.

### LC-009 — Custom Quiz labels

**Reported by:** Holly

Add a tutor-configurable display label for each Quiz:

- Quiz
- Assignment
- Mock Exam
- Exam
- Custom label

The selected label should replace the generic word "Quiz" throughout the relevant learner-facing experience, including links, instructions, submissions, attempts, feedback and results.

Internal Question/Quiz identifiers and marking behaviour must remain unchanged.

### LC-010 — Enrolled students missing

**Reported by:** Holly

Students enrolled on Courses through Booking Hub Student Details are not correctly reflected in the Learning Hub Students card or tab.

**Code investigation:** In the audited LMS Core `main` branch, the Learning Hub's student-count helper methods return zero, and the Students workspace contains placeholder content.

**Expected behaviour:** Display accurate student enrolment counts and a useful Students workspace, respecting tutor permissions and the existing student/Course relationships.

### LC-011 — H5P activities

**Reported by:** Holly

Tutors should be able to embed interactive activities into Lessons, for example H5P activities.

**Requested behaviour:**

- Embed supported interactive content within a Lesson.
- Display activities responsively on desktop and tablets.
- Keep interactive resources distinct from LMS Quizzes.
- Allow students to work through activities without requiring a separate Quiz.
- Consider completion tracking as a later extension.

---

## 4. TutorHelper LMS Pro / Premium

**Tester feedback — 18 November 2026**

The tester reported positive PDF and image-marking experiences on desktop and iPad, including smooth continuation between devices.

The following issues and requests were identified.

| ID | Feature / Request | Type | Status | Priority | Notes |
|---|---|---|---|---|---|
| LP-001 | Homework file submissions | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Student submissions with protected file storage |
| LP-002 | Tutor homework marking | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Marks, feedback and submission status |
| LP-003 | PDF annotations | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Pen, stamps, multi-page editor and saved annotations |
| LP-004 | Image annotations | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Image marking with pen and stamps |
| LP-005 | Marked PDF/image storage | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Protected marked-file derivative generation and delivery |
| LP-006 | **Marked PDF rejected on save/release** | Bug | ![Reported](https://img.shields.io/badge/Reported-DC3545) | **P1** | Displays "The marked file could not be accepted" |
| LP-007 | **Homework maximum marks missing** | Bug | ![Reported](https://img.shields.io/badge/Reported-DC3545) | P2 | Maximum marks from assigned homework not displayed |
| LP-008 | **Marked image preview not updated** | Bug | ![Reported](https://img.shields.io/badge/Reported-DC3545) | **P1** | Annotations saved, but do not appear in the subsequent marking preview |
| LP-009 | Preview every PDF page by scrolling | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Preview currently renders the first page only |
| LP-010 | Open homework in enlarged/fullscreen view | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Larger marking workspace should be available from initial opening |
| LP-011 | Redo last annotation | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Confirm intended behaviour; existing code already includes Undo last for PDF and image |
| LP-012 | Custom stamp colours | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P3 | Allow changing stamp colours independently of pen colour |
| LP-013 | Straight-line / ruler tool | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Draw lines for graphs, labels and lines of best fit |
| LP-014 | Previous / Next submission navigation | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Move between submissions after successful Save Marking |
| LP-015 | Released marked PDF and original-file access | Regression | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | P1 | Verify flattened marked derivative and original download |
| LP-016 | Adaptive Practice | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Mastery-based Question selection |
| LP-017 | Timed Quizzes | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Timed Quiz delivery |
| LP-018 | Premium written/file Questions | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Manual marking and feedback |
| LP-019 | Gradebook and released feedback | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Academic progress and released assessment results |

### LP-006 — Marked file could not be accepted

**Reported by:** Beta tester  
**Date:** 18 November 2026  
**Priority:** P1

**Observed behaviour:**

The tutor can annotate a PDF and see purple annotations in the preview. However, saving or releasing the marking displays:

> The marked file could not be accepted.

The supplied screenshot shows this error alongside the Feedback editor and Submission Status controls.

**Code investigation:**

The message comes from:

`packages/tutorhelper-lms-premium/includes/class-tutorhelper-lms-marked-files.php`

Specifically, the initial validation in:

`TutorHelper_LMS_Marked_Files::ajax_store()`

Possible failed checks include tutor context, required file identifiers, missing upload, PHP upload error or temporary-file validation.

These are investigation targets, not a confirmed root cause.

**Required resolution:**

1. Capture safe diagnostic information for the failing request.
2. Confirm the browser generates and submits a valid marked PDF.
3. Check request identifiers, nonce, upload error and file metadata.
4. Ensure marked-file storage succeeds before claiming release completion.
5. Test on desktop and iPad.
6. Verify the student can view the marked file and download the original.

**Acceptance test:** Annotate and save a multi-page PDF, release feedback, reopen it and confirm that the marked derivative is available without an error.

### LP-008 — Image annotations missing from preview

**Reported by:** Beta tester  
**Priority:** P1

**Observed behaviour:**

The tutor clicks **Mark image**, adds annotations and selects **Save annotations**.

On returning to the Feedback and Submission Status screen, the preview on the left does not display the saved annotations.

**Expected behaviour:** The left preview immediately displays the latest saved annotations, without requiring a manual refresh.

Investigate saved annotation data, preview refresh, canvas redraw and marked-image derivative handling.

### LP-009 — All-page PDF preview

**Reported by:** Beta tester

**Current code finding:** The PDF preview function currently renders page 1 only.

**Requested behaviour:**

- Scroll through all PDF pages before opening the annotation editor.
- Display saved annotations on every relevant page.
- Preserve readable zoom and scrolling.
- Avoid excessive loading time for large PDFs.

### LP-010 — Fullscreen homework review

**Reported by:** Beta tester

The enlarged Mark PDF interface works well, but the tutor would prefer the same spacious view immediately when opening homework.

This should work for both PDFs and images, including tablet layouts.

### LP-011 — Redo / Undo

**Reported by:** Beta tester

The tester requested a "redo last" control.

**Code finding:** Both the PDF and image annotation editors already include **Undo last** buttons.

Confirm whether the tester needs:

- Better visibility of the existing Undo control.
- A true Redo action to restore an undone annotation.
- Both controls.

Do not add a second Undo button without checking the existing implementation.

### LP-012 — Custom stamp colours

**Reported by:** Beta tester

Allow tutors to select the colour of stamps, not just freehand ink.

Stamp colour should be preserved when saving and flattening marked files.

### LP-013 — Straight-line tool

**Reported by:** Beta tester

Add a tool for drawing straight lines, particularly for:

- Graph axes.
- Lines of best fit.
- Label lines.
- Highlighting corrections.
- Diagram annotations.

Support mouse, stylus and touch input.

### LP-014 — Previous / Next submission

**Reported by:** Beta tester

Allow tutors to navigate directly between submissions from the marking interface.

Navigation should:

1. Save the current marking.
2. Confirm successful completion.
3. Load the previous or next submission.
4. Preserve the current filters/order.
5. Prevent accidental loss of unsaved changes.

---

## 5. TutorHelper Group Bookings Add-On

| ID | Feature / Request | Type | Status | Priority | Notes |
|---|---|---|---|---|---|
| GB-001 | Group Lesson blocks | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Reusable scheduled group sessions |
| GB-002 | Student group enrolment | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Group membership and enrolment management |
| GB-003 | Group lesson bookings | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Linked individual Core bookings |
| GB-004 | Group pricing and deposits | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Upfront, deposit and manual payments |
| GB-005 | Group Stripe payments | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Group checkout and balance collection |
| GB-006 | Group finance reconciliation | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Credits, refunds and payment-state updates |
| GB-007 | Shared group calendar events | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Shared joining links and session management |
| GB-008 | Group attendance | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Per-student attendance recording |
| GB-009 | Student cancellation and rescheduling | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Identified in repository roadmap as unfinished |
| GB-010 | Finance reversal regression tests | Regression | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | P1 | Verify refunded/credited bookings update enrolment balances and place state |

---

## 6. TutorHelper Parent / Child

| ID | Feature / Request | Type | Status | Priority | Notes |
|---|---|---|---|---|---|
| PC-001 | Parent/student relationships | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Multiple parents and students supported |
| PC-002 | Parent Accounts administration | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Manage linked parents |
| PC-003 | Parent dashboard | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Parent-specific dashboard and child selection |
| PC-004 | Attendance and lesson history | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Read-only reporting |
| PC-005 | Feedback and homework view | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Parent visibility of tutor follow-up |
| PC-006 | Parent finance dashboard | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Statements, invoices and payment options |
| PC-007 | Account-credit refund request | Regression | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | P2 | Verify that parents can request refunds from their dashboard and tutors can process requests correctly |
| PC-008 | Financial visibility settings | Regression | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | P2 | Confirm parent-only finance visibility and credited lesson transactions |
| PC-009 | Delegated parent booking actions | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P3 | Future parent cancellation/rescheduling and booking permissions |

---

## 7. TutorHelper Agency

| ID | Feature / Request | Type | Status | Priority | Notes |
|---|---|---|---|---|---|
| AG-001 | Agency activation and licence | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Dependency and licensing system |
| AG-002 | TH Tutor role | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Restricted tutor permissions |
| AG-003 | Tutor/student assignments | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Many-to-many assignment relationships |
| AG-004 | Agency administration | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Administrators assign tutors and students |
| AG-005 | Tutor Hub | Feature | ![Implemented](https://img.shields.io/badge/Implemented-007BFF) | — | Read-only assigned-student dashboard |
| AG-006 | Tutor Hub booking management | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Future booking and calendar tools |
| AG-007 | Tutor Hub student management | Feature Request | ![Requested](https://img.shields.io/badge/Requested-FFD700) | P2 | Future assigned-student editing and reporting |
| AG-008 | Multi-tutor booking permissions | Regression | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | P1 | Confirm Core tutor resolver permits authorised TH Tutor bookings without exposing unrelated records |
| AG-009 | Assignment-based access | Regression | ![Testing](https://img.shields.io/badge/Testing-A8E6A3) | P1 | Test permission checks, removed assignments and cross-tutor data access |

---

## 8. Current development priorities

| Priority order | Issue IDs | Development focus |
|---|---|---|
| **1 — migration blocker** | **LC-014, LC-015, LC-016, LC-017** | Correct LearnDash Cloze conversion, multiple accepted answers, verified marks and scientific HTML; integrate with IM3 before the tester's bulk Question import |
| **1 — marking blocker** | **LP-006, LP-015** | Fix marked PDF acceptance and verify reliable release/storage; schedule in parallel or according to tester impact |
| 2 | LP-008 | Fix image annotation preview after saving |
| 3 | LC-010 | Fix Learning Hub enrolled-student counts and student list |
| 4 | LP-007, BP-011 | Display configured homework maximum marks |
| 5 | LP-009, LP-010, LP-011 | Improve PDF preview, fullscreen opening and Undo/Redo |
| 6 | LC-008 | Course Builder partial refresh |
| 7 | LC-009 | Custom learner-facing Quiz labels |
| 8 | LC-011 | H5P interactive lesson activities |
| 9 | LP-012, LP-013, LP-014 | Annotation tool and navigation enhancements |
| 10 | Other regression rows | Cross-plugin beta verification |

The LMS LearnDash migration and Learning Journey work is continuing to be managed through a separate **TutorHelper LMS Development Tracker**, for initial development, but beta tester feedback will be added here as the main LMS features are released.

---

## 9. Reporting a bug or requesting a feature

Please email **holly@teachallaboutit.uk** with:

1. Plugin name and version.
2. Description of the problem or requested feature.
3. Steps to reproduce the problem.
4. Expected behaviour.
5. Actual behaviour.
6. Screenshot, if useful.
7. Device/browser and WordPress/PHP versions, if known.

Please **remove student names, personal information, licence keys and confidential files** from screenshots or logs *before* sharing them.

### How the tracker is maintained

- Each request receives a unique issue ID.
- Confirmed fixes are linked to their GitHub PRs.
- A change is not marked Complete until it has been merged and tested.
- Existing requests remain visible for development history.
- New feedback is added to the appropriate plugin table.
- After each beta release, verified changes should be reflected in the tracker.

---

## 10. GitHub source audit — 20 November 2026

The implementation baseline was checked against the latest available `main` branches. The LMS branch was rechecked on 20 November; other plugin SHAs below are from the 18 November audit:

| Repository | Main commit |
|---|---|
| TutorHelper-Bookings | `b7e60565` |
| TutorHelper-Pro | `86ab56af` |
| TutorHelper-Group-Bookings | `a0e53235` |
| TutorHelper-Parent-Child | `d96c8d52` |
| TutorHelper-Agency | `c5a67939` |
| Tutorhelper-LMS Core and Premium | `4c8f9ab7` |

Source files provide evidence of implementation, not confirmation that every workflow works correctly in a live WordPress environment.

---

**TutorHelper — Built for tutors, by tutors.**
