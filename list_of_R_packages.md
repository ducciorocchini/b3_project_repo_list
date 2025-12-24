## ✅ Repositories that are **real R packages**

These are clearly structured as R packages and intended for reuse via `install.packages()` / `remotes::install_github()`.

### **1. dissmappR**

**Repo:** [https://github.com/b-cubed-eu/dissmapr](https://github.com/b-cubed-eu/dissmapr)
**Type:** R package
**Purpose:**

* Species distribution & dissemination mapping
* Spatial analysis and visualisation in R

**Why it qualifies:**

* R package naming convention
* Focused analytical functionality
* Designed for direct use by R users

---

### **2. invasimapr**

**Repo:** [https://github.com/b-cubed-eu/invasimapr](https://github.com/b-cubed-eu/invasimapr)
**Type:** R package
**Purpose:**

* Mapping, analysing, and visualising invasive species distributions

**Why it qualifies:**

* Explicitly described as an R package
* Domain-specific analytical API

---

### **3. pdindicatoR**

**Repo:** [https://github.com/b-cubed-eu/pdindicatoR](https://github.com/b-cubed-eu/pdindicatoR)
**Type:** R package
**Purpose:**

* Computation of population and pressure indicators
* Biodiversity assessment metrics

**Why it qualifies:**

* Indicator computation library
* Typical R package role in assessment workflows

---

### **4. rgbif** *(external but relevant)*

**Repo:** [https://github.com/ropensci/rgbif](https://github.com/ropensci/rgbif)
**Type:** R package (external dependency)
**Purpose:**

* R client for the GBIF API

**Why it qualifies:**

* CRAN / rOpenSci package
* Widely reused within B3-related workflows

---

## ⚠️ Borderline / hybrid (not standalone R packages)

These may **contain R code**, but are **not primarily R packages**.

### **trias-project/indicators**

* Contains indicator implementations
* Often script- or workflow-oriented
* ❌ Not a clean, reusable R package API

---

## ❌ Not R packages (for QA/maturity alignment)

These are **software services, scripts, GUIs, infrastructure, or Python projects**:

* `b3alien`
* `b3data-scripts`
* `b3doc`
* `b3gbi`
* `b3gbi-gui`
* `binfrastructure`
* `comp-unstructured-data`
* `integrate-indicator-software`
* `occurrence-cube`
* `pygbif` (Python)
* `rsa-unstructured-data-comp`
* `virtual-suitability-cube`
* `trias`

---

## ✅ Summary table

| Repository               | Real R package?  | Notes                                 |
| ------------------------ | ---------------- | ------------------------------------- |
| dissmappR                | ✅ Yes            | Spatial / mapping R package           |
| invasimapr               | ✅ Yes            | Invasive species mapping              |
| pdindicatoR              | ✅ Yes            | Indicator computation                 |
| rgbif                    | ✅ Yes (external) | GBIF R client                         |
| trias-project/indicators | ⚠️ Partial       | R code but not package-first          |
| All others               | ❌ No             | Services, scripts, infra, Python, GUI |

---
