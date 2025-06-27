# AcademicWritingWeb

‎I need to design a smart, unique and fantastic dynamic web application simply meant for sharing and providing academic writing tips and also materials like notes among other materials and tips.
‎These website should have about 5 pages.
‎1. Homepage
‎2. Writingstyles 
‎3. WritingTools
‎4. WritingTests
‎5. AccountPage
‎6. FAQs
‎
‎A user should be able to sign in the web application by using an email and a password. Once signed in, every user should be able to access all the features and materials as necessary. 
‎The landing page at home should be nice and contain texts, images and other features related to Academic writing. The home page should be nice and dynamically interactive having great resources to amaze the user and explain everything in details. 
‎
‎The header containing the navigations for the pages, should remain fixed at the left side of  all the pages even during scrolling.
‎All the pages should contain a fixed footer containing privacy policy or terms. 
‎
‎The writing styles page should contain notes on all the main and most used academic styles and show guides of each style notes dynamically. Like apa, MLA, havards, among others. Good and nice content. 
‎The writing tools page should show and teach the user of all available academic writing tools used to do assignments and how to approach tasks. These tools are like Ai and plagiarism checking tools, grammar checking tools, paraphrasing tools and proofreading tools. Nice features and styles making the page dynamic. 
‎
‎The writing tests page should show and alert the user of any writing good standards and what to observe. Then this page should contain tests for the user with choices. The user will use the test to check their writing understanding. 
‎
‎FAQs page should show in style and dynamically using great features all FAQs and their answers or solutions. 
‎
‎I need a smart and nice web application you know. Easy to use one. 
‎With good data. 
‎
‎
‎
‎Excellent—let’s finalize the feature list and requirements for your **dynamic academic writing web application** project.

Below is a **complete, structured document** you can use as your formal requirements/spec.

---


## 🎯 Goal

Build a smart, modern, dynamic web application for sharing and providing academic writing tips, materials, and tools. The app enables registered users to access notes, guides, writing tools, tests, and FAQs—all in a user-friendly, engaging format.

---

## ✅ General Features

* Modern, responsive design (works on mobile, tablet, desktop)
* Left-side fixed navigation header on desktop
* Collapsible sidebar or hamburger menu on mobile
* Fixed footer on all pages with Privacy Policy / Terms
* User authentication (register/login/logout)
* User profile management
* Access control: only logged-in users can view materials
* Dynamic, rich content (text, images, videos where needed)
* Clean, accessible UI/UX

---

## ✅ Pages (with details)

### 1️⃣ Homepage

* Hero section with engaging banner image and welcome text
* Sections describing:

  * What the site offers
  * Benefits of academic writing skills
  * How to use the site
  * Call to action (Register/Login)
* Highlight top writing styles, tools, and tests
* Testimonials or example student feedback (optional)
* Visual elements (images, icons, animations)

---

### 2️⃣ Writing Styles Page

* Dynamic, filterable or tabbed list of major academic writing styles:

  * APA
  * MLA
  * Harvard
  * Chicago
  * IEEE
  * Vancouver
  * Others as desired
* Each style section includes:

  * Overview/Description
  * Formatting rules
  * In-text citation guide
  * Reference list guide
  * Example templates
* Optional: Downloadable PDFs

---

### 3️⃣ Writing Tools Page

* List and description of common academic writing tools:

  * AI writing assistants
  * Plagiarism checkers
  * Grammar checkers
  * Paraphrasing tools
  * Proofreading tools
  * Citation generators
* For each tool:

  * Brief explanation of what it does
  * How to use it effectively
  * Pros and cons
  * Link to external website if available
  * Screenshots or video demos (optional)

---

### 4️⃣ Writing Tests Page

* Introduction to academic writing standards:

  * Clarity
  * Structure
  * Referencing
  * Academic tone
* Interactive quiz/test system:

  * Multiple-choice questions
  * Immediate feedback on each question
  * Score summary at end
  * Optional: Save results to user profile
* Alerts/tips about good writing habits

---

### 5️⃣ FAQs Page

* List of common questions and answers
* Dynamic, interactive layout:

  * Accordion (expand/collapse answers)
  * Search bar to filter FAQs
  * Optional: Categories or tags
* Example FAQs:

  * How do I cite sources correctly?
  * How do I avoid plagiarism?
  * Which writing style should I use?

---

### 6️⃣ Account Pages

* Sign Up

  * Email, password fields
  * Validation
  * Optional: Terms acceptance
* Login

  * Email and password
  * "Forgot password?" link
* Profile

  * View/update email
  * Change password
  * View saved materials or quiz results (if implemented)
  * Logout button

---

### 7️⃣ Fixed Sidebar Navigation

* Always visible on desktop (fixed left)
* Contains links to:

  * Home
  * Writing Styles
  * Writing Tools
  * Writing Tests
  * FAQs
  * Account/Profile
  * Logout
* Collapses into hamburger on mobile

---

### 8️⃣ Fixed Footer

* Small, unobtrusive footer on all pages
* Links to:

  * Privacy Policy
  * Terms and Conditions
  * Contact/Support (optional)

---

## ✅ Optional / Advanced Features

(For MVP or future expansion)

* Search across all site content
* Bookmark/save notes or tests
* Admin dashboard to add/edit content
* User analytics (which styles/tests are popular)
* Email verification on signup
* Password reset via email
* Social login (Google, Facebook)
* Dark mode toggle
* Notifications for new tests or materials

---

**
text-based wireframe / layout sketch plan**

---

## 🎨 GENERAL DESIGN SYSTEM

✅ Fixed **LEFT SIDEBAR** navigation on desktop
✅ Collapsible hamburger menu on mobile
✅ Fixed **FOOTER** on all pages
✅ Consistent header, typography, colors

---

# 📐 GLOBAL LAYOUT

```
---------------------------------------------------
| Sidebar |           Main Content Area          |
| (fixed) |                                       |
|         |                                       |
|         |                                       |
---------------------------------------------------
|                 Fixed Footer                   |
---------------------------------------------------
```

✅ Sidebar:

* Always visible on desktop
* Links:

  * Home
  * Writing Styles
  * Writing Tools
  * Writing Tests
  * FAQs
  * Account/Profile
  * Logout

✅ Footer:

* Privacy Policy
* Terms
* Contact

---

# 1️⃣ HOMEPAGE

## Wireframe sections

**Hero Section**

```
-------------------------------------------------
| Banner Image / Illustration                   |
| "Welcome to [Site Name]"                      |
| "Your Academic Writing Companion"             |
| [Get Started Button]                          |
-------------------------------------------------
```

**Features Section**

```
-------------------------------------------------
| "Why use this platform?"                      |
| Icon + Text Grid:                             |
| - Styles Guidance                             |
| - Writing Tools                               |
| - Interactive Tests                           |
| - Expert Tips                                 |
-------------------------------------------------
```

**How It Works Section**

```
-------------------------------------------------
| "How It Works" Steps                          |
| 1. Sign Up                                    |
| 2. Explore Guides                             |
| 3. Practice Tests                             |
| 4. Improve Writing                            |
-------------------------------------------------
```

**Highlights Section**

```
-------------------------------------------------
| "Popular Styles"                             |
| Cards with APA, MLA, Harvard, etc.           |
| Click to go to Writing Styles page           |
-------------------------------------------------
```

**Testimonials / Example Use**

```
-------------------------------------------------
| "What Students Say"                           |
| Carousel of testimonials                      |
-------------------------------------------------
```

**Call To Action**

```
-------------------------------------------------
| "Ready to Improve Your Writing?"              |
| [Sign Up / Login Button]                      |
-------------------------------------------------
```

---

# 2️⃣ WRITING STYLES PAGE

**Page Intro**

```
-------------------------------------------------
| "Academic Writing Styles"                     |
| Brief description                             |
-------------------------------------------------
```

**Styles Selector**

```
-------------------------------------------------
| Tabs or Accordion                             |
| [APA] [MLA] [Harvard] [Chicago] [IEEE] etc.   |
-------------------------------------------------
```

**Style Content (on select)**

```
-------------------------------------------------
| Style Name: APA                               |
| Overview Text                                 |
| Formatting Rules                              |
| In-Text Citation Guide                        |
| Reference List Guide                          |
| Example Template / Download                   |
-------------------------------------------------
```

✅ Optional:

* Search bar to find styles
* Sidebar with style links

---

# 3️⃣ WRITING TOOLS PAGE

**Intro Section**

```
-------------------------------------------------
| "Essential Academic Writing Tools"            |
| Brief explanation                             |
-------------------------------------------------
```

**Tools List (Cards or Accordions)**

```
-------------------------------------------------
| Tool Name: Grammarly                          |
| Short description                             |
| How to Use                                    |
| Pros / Cons                                   |
| Link / Screenshot                             |
-------------------------------------------------
| Tool Name: Turnitin                           |
| ...                                           |
-------------------------------------------------
```

✅ Optional:

* Category filters (AI, Plagiarism, Grammar, etc.)
* Demo videos

---

# 4️⃣ WRITING TESTS PAGE

**Intro**

```
-------------------------------------------------
| "Test Your Writing Knowledge"                 |
| Brief explanation of academic standards       |
-------------------------------------------------
```

**Guidelines Section**

```
-------------------------------------------------
| - Clarity                                     |
| - Structure                                   |
| - Referencing                                 |
| - Academic Tone                               |
-------------------------------------------------
```

**Quiz Section**

```
-------------------------------------------------
| [Start Quiz Button]                           |
-------------------------------------------------
| Question 1                                    |
| What is APA citation format?                  |
| ( ) Option A                                  |
| ( ) Option B                                  |
| ( ) Option C                                  |
| [Next Button]                                 |
-------------------------------------------------
```

**Results Page**

```
-------------------------------------------------
| "Your Score: 8/10"                            |
| Feedback on incorrect answers                 |
| Tips for improvement                          |
| [Retake Quiz]                                 |
-------------------------------------------------
```

✅ Optional:

* Save user scores to profile

---

# 5️⃣ FAQs PAGE

**Intro**

```
-------------------------------------------------
| "Frequently Asked Questions"                  |
| Brief intro                                   |
-------------------------------------------------
```

**Search Bar**

```
-------------------------------------------------
| [Search FAQs]                                 |
-------------------------------------------------
```

**FAQ Accordion List**

```
-------------------------------------------------
| Q1: How do I cite sources correctly?          |
| [Expand for Answer]                           |
-------------------------------------------------
| Q2: Which style should I use?                 |
| [Expand for Answer]                           |
-------------------------------------------------
```

✅ Optional:

* Categories or tags

---

# 6️⃣ ACCOUNT PAGES

**Login Page**

```
-------------------------------------------------
| "Login to Your Account"                       |
| Email: [____]                                 |
| Password: [____]                              |
| [Login Button]                                |
| [Forgot Password?]                            |
| [Register Instead]                            |
-------------------------------------------------
```

**Register Page**

```
-------------------------------------------------
| "Create an Account"                           |
| Email: [____]                                 |
| Password: [____]                              |
| Confirm Password: [____]                      |
| [Register Button]                             |
| [Login Instead]                               |
-------------------------------------------------
```

**Profile Page**

```
-------------------------------------------------
| "Your Profile"                                |
| Email: [user@example.com]                     |
| Change Password                               |
| View Saved Materials (optional)               |
| View Test Results (optional)                  |
| [Logout Button]                               |
-------------------------------------------------
```

---

# 7️⃣ FIXED SIDEBAR NAVIGATION

**Example Layout**

```
-------------------------------------------------
| [Site Logo]                                   |
-------------------------------------------------
| [Home]                                        |
| [Writing Styles]                              |
| [Writing Tools]                               |
| [Writing Tests]                               |
| [FAQs]                                        |
| [Account/Profile]                             |
| [Logout]                                      |
-------------------------------------------------
```

✅ Collapsible on mobile (hamburger icon)

---

# 8️⃣ FIXED FOOTER

**Example Layout**

```
-------------------------------------------------
| [Privacy Policy]  |  [Terms of Service]       |
| [Contact/Support]                             |
-------------------------------------------------
```

✅ Small, low-profile, always visible




---

## ⚡ FINAL TABLE LIST

We’ll define these 8 tables:

1. users
2. writing\_styles
3. writing\_tools
4. faqs
5. writing\_tests
6. test\_questions
7. test\_options
8. user\_test\_results

---

## ✅ FULL MYSQL SCHEMA

```sql
-- 1️⃣ USERS TABLE
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    email VARCHAR(255) NOT NULL UNIQUE,
    password_hash VARCHAR(255) NOT NULL,
    name VARCHAR(100),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);

-- 2️⃣ WRITING_STYLES TABLE
CREATE TABLE writing_styles (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    description TEXT,
    formatting_rules TEXT,
    intext_guide TEXT,
    reference_guide TEXT,
    example_template TEXT,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);

-- 3️⃣ WRITING_TOOLS TABLE
CREATE TABLE writing_tools (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    description TEXT,
    how_to_use TEXT,
    pros TEXT,
    cons TEXT,
    external_link VARCHAR(255),
    image_url VARCHAR(255),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);

-- 4️⃣ FAQS TABLE
CREATE TABLE faqs (
    id INT AUTO_INCREMENT PRIMARY KEY,
    question TEXT NOT NULL,
    answer TEXT NOT NULL,
    category VARCHAR(100),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);

-- 5️⃣ WRITING_TESTS TABLE
CREATE TABLE writing_tests (
    id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    description TEXT,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);

-- 6️⃣ TEST_QUESTIONS TABLE
CREATE TABLE test_questions (
    id INT AUTO_INCREMENT PRIMARY KEY,
    test_id INT NOT NULL,
    question_text TEXT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
    FOREIGN KEY (test_id) REFERENCES writing_tests(id) ON DELETE CASCADE
);

-- 7️⃣ TEST_OPTIONS TABLE
CREATE TABLE test_options (
    id INT AUTO_INCREMENT PRIMARY KEY,
    question_id INT NOT NULL,
    option_text TEXT NOT NULL,
    is_correct BOOLEAN DEFAULT FALSE,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
    FOREIGN KEY (question_id) REFERENCES test_questions(id) ON DELETE CASCADE
);

-- 8️⃣ USER_TEST_RESULTS TABLE
CREATE TABLE user_test_results (
    id INT AUTO_INCREMENT PRIMARY KEY,
    user_id INT NOT NULL,
    test_id INT NOT NULL,
    score INT,
    taken_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    FOREIGN KEY (user_id) REFERENCES users(id) ON DELETE CASCADE,
    FOREIGN KEY (test_id) REFERENCES writing_tests(id) ON DELETE CASCADE
);
### 9 `admins` table

CREATE TABLE admins (
    id INT AUTO_INCREMENT PRIMARY KEY,
    email VARCHAR(255) NOT NULL UNIQUE,
    password_hash VARCHAR(255) NOT NULL,
    name VARCHAR(100),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## ✅ EXPLANATION (TABLE BY TABLE)

### 🟣 1. `users`

* Stores user accounts
* `email` is unique
* `password_hash` stores hashed password (never plain text!)

---

### 🟣 2. `writing_styles`

* Holds all style notes (APA, MLA, etc.)
* Rich text fields for rules and guides

---

### 🟣 3. `writing_tools`

* Describes AI, plagiarism checkers, etc.
* Includes optional external link and image URL

---

### 🟣 4. `faqs`

* Question/answer pairs
* Optional `category` for grouping

---

### 🟣 5. `writing_tests`

* Metadata for each quiz/test
* Descriptive title and instructions

---

### 🟣 6. `test_questions`

* Links to `writing_tests`
* Each question belongs to one test

---

### 🟣 7. `test_options`

* Links to `test_questions`
* Stores multiple-choice options
* Marks correct answer with `is_correct`

---

### 🟣 8. `user_test_results`

* Links users to test attempts
* Stores scores and timestamp

---






**Admin Dashboard** 

# ✅ CORE FEATURES OF THE ADMIN DASHBOARD

## 1️⃣ Authentication for Admins

* Separate login page for admins
* Role-based access (admin vs regular user)
* Password management

✅ Purpose: Only authorized admins can edit content.

---

## 2️⃣ Admin Home Page / Dashboard Overview

* Quick stats / KPIs

  * Total users
  * Total writing styles
  * Total writing tools
  * Total tests / quizzes
* Recent activity
* Links to all management sections

✅ Purpose: Fast snapshot of the platform

---

## 3️⃣ Manage Users

* List all users
* Search/filter by email
* View user details
* Disable / enable accounts
* Reset passwords (optional)

✅ Purpose: User moderation and support

---

## 4️⃣ Manage Writing Styles

* View all styles in a table
* Add new style
* Edit existing style
* Delete style

✅ Fields:

* Name
* Description
* Formatting rules
* In-text guide
* Reference guide
* Example template link

✅ Purpose: Keep style guides up to date

---

## 5️⃣ Manage Writing Tools

* View all tools
* Add new tool
* Edit existing tool
* Delete tool

✅ Fields:

* Name
* Description
* How to use
* Pros / cons
* External link
* Image URL

✅ Purpose: Recommend and update tools dynamically

---

## 6️⃣ Manage FAQs

* View all FAQs
* Add new FAQ
* Edit existing FAQ
* Delete FAQ

✅ Fields:

* Question
* Answer
* Category

✅ Purpose: Keep FAQ relevant

---

## 7️⃣ Manage Writing Tests

✅ Parent/child relationship management:

* **Tests List View**

  * Title
  * Description
  * # of questions
* Add new test
* Edit/delete test

✅ When editing a test:

* Add/Edit/Delete questions

  * Question text
  * Add/Edit/Delete answer options

    * Option text
    * Mark correct

✅ Purpose: Build and maintain quizzes interactively

---

## 8️⃣ View User Test Results

* Search by user/email
* View past scores
* Filter by test
* Export to CSV (optional)

✅ Purpose: See how users perform




# ✅ EXAMPLE ADMIN WIREFRAME LAYOUT (TEXTUAL)

## Admin Dashboard Sidebar

```
---------------------------------
|  [Site Logo]                  |
---------------------------------
| [Dashboard Overview]          |
| [Users]                       |
| [Writing Styles]              |
| [Writing Tools]               |
| [FAQs]                        |
| [Writing Tests]               |
| [User Test Results]           |
| [Logout]                      |
---------------------------------
```

✅ Sidebar always visible (or collapsible on mobile)

---

## Example Admin Home Page

```
-------------------------------------------------
| "Admin Dashboard"                             |
| Stats Cards:                                  |
| - Total Users                                 |
| - Total Writing Styles                        |
| - Total Writing Tools                         |
| - Total Tests                                 |
-------------------------------------------------
| Recent Activity Feed                          |
-------------------------------------------------
```

---

## Manage Writing Styles Page

```
-------------------------------------------------
| [Add New Style Button]                        |
-------------------------------------------------
| Table/List View:                              |
| - Name                                        |
| - Actions: Edit / Delete                      |
-------------------------------------------------
```

✅ Add/Edit Form

```
-------------------------------------------------
| Name                                          |
| Description                                   |
| Formatting Rules                              |
| In-Text Guide                                 |
| Reference Guide                               |
| Example Template Link                         |
| [Save Button]                                 |
-------------------------------------------------
```

---

## Manage Writing Tests Page

✅ Master/Detail UI

```
-------------------------------------------------
| Test List:                                    |
| - Title                                       |
| - # of Questions                              |
| - Actions: Edit / Delete                      |
-------------------------------------------------
| When Editing Test:                            |
| - Edit title/description                      |
| - Questions Table:                            |
|   - Question Text                             |
|   - Edit / Delete                             |
|   - Add New Question                          |
| - For Each Question:                          |
|   - Option List (with is_correct toggle)      |
|   - Add/Edit/Delete Options                   |
-------------------------------------------------

