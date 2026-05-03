---
title: Documentation
---

# 📚 Documentation Overview

Welcome to the documentation section! Here you'll find notes, guides, and reference
materials organized by topic.

<hr class="section-divider">

## 📂 Available Documents

<!-- ============================================================
     INSTRUCTIONS: Each doc-card uses a background image.
     Replace YOUR_FILE_ID with your Google Drive image File ID.
     To get the File ID: Share image → "Anyone with link" → copy
     the ID from the URL after /d/
     ============================================================ -->




<div class="doc-card" style="background-image: url('https://drive.google.com/thumbnail?id=YOUR_FILE_ID&sz=w800');" markdown>

### 🚀 3D Designing

Your first 3D design project.

[:octicons-arrow-right-24: Read Guide](mooncamp1st.md)

</div>

</div>

---

## ➕ How to Add New Documents

!!! info "Adding a New Page"

    1. **Create** a new `.md` file in the `docs/documentation/` folder  
       _(e.g., `my-new-topic.md`)_

    2. **Copy** the content from `template.md` as a starting point

    3. **Add** your new page to `mkdocs.yml` under the `Documentation` section:

        ```yaml
        nav:
          - Documentation:
              - Overview: documentation/index.md
              - Getting Started Guide: documentation/getting-started.md
              - "📝 Blank Template": documentation/template.md
              - My New Topic: documentation/my-new-topic.md    # ← add here
        ```

    4. **Save** and run `mkdocs serve` to see your changes!
