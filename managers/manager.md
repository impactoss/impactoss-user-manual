## 4. Manager overview

> _Available for: Managers and [Administrators](/admins/admin.md))_

#### Who are Managers?

Managers are responsible for developing and updating the National Implementation Plan. Some managers can also become "Category managers" and are responsible for an area of the National Implementation Plan (e.g. UPR recommendations, CRC recommendations, SDG targets, etc.) and thus for sets of recommendations. Category Managers play an oversight role to ensure that data is entered when required - thus providing the second safeguard against non-entry of data.

#### What can I do as a Manager?

* Everything a Contributor can do (see [Contributor overview](/contributors/contributor.md))
* [Create Implementation Plan](managers/create-implementation-plan.md)
* [Monitor Implementation Plan](managers/monitor-implementation-plan.md)
* Become a "Category Manager" and oversee reporting (see [Oversee Reporting](/managers/oversee-reporting.md))
* Promote Guest to Contributor (see [Promote Users](/managers/users-admin.md))
* Manage all content (except Pages)
  * [Manage Categories](/managers/categories.md)
  * [Manage Actions](/managers/actions.md)
  * [Manage Indicators](/managers/indicators.md)
  * [Manage Recommendations](/managers/recommendations.md)
  * [Manage SDG Targets (optional)](/managers/sdg-targets.md)
  * [Import content](/managers/import.md)
  * [Batch editing](managers/batch-edit.md)  
  * [Delete content](/managers/delete-content.md)

---

### Specific functions and responsibilities of a Manager

#### Function: Implementation Plan Manager

As an **Implementation Plan Manager**, a user can be responsible for developing and updating the National Implementation Plan. This functional role is not explicitly assigned but is expected to be assigned by the overseeing organisation (e.g. NMRF).

##### Responsibilities

The responsibilities of an **Implementation Plan Manager** are:
* Create and update Recommendations, Actions and Indicators, as well as Categories
* Categorise and cluster Recommendations, Actions and SDG Targets, and associate Recommendations with Actions

Also see [Create Implementation Plan](managers/create-implementation-plan.md) and [Monitor Implementation Plan](managers/monitor-implementation-plan.md)

---

#### Function: Category Manager

The Manager can as **Category Managers** be explicitly made responsible for an area of the National Implementation Plan, thus for sets of Recommendations, commonly by Human Rights Mechanism (depends on application configuration). Category Managers play an oversight role to ensure that data is entered when required.

> For each 'Human Rights Body' Mechanism, as well as for each SDG, a 'Category Manager' should be assigned by one of the Administrators.

##### Prerequisites

* A Manager requiress to be assigned to suitable category (by Admininistrator, see [Assign Category Manager](/admins/assign-category.md))

##### Responsibilities

The responsibilities of an **Category Managers** are:
* Assign users to indicators (see [Oversee Reporting](/managers/oversee-reporting.md))
* Oversee and follow-up data collection (see [Oversee Reporting](/managers/oversee-reporting.md))
* Review and publish progress reports added by **Guest Contributors** (see [Reporting as Guest](/guests/reporting.md))

##### Email reminders

**Category Managers** will receive automated email reminders when a reporting due date for Indicators in their area have lapsed ('overdue') so that they can follow-up with the responsible [Contributors](/contributors/contributor.md). 'Indicators in their area' are all **Indicators** that are associated with **Actions** that are targeting **Recommendations** that are tagged with the **Category** the **Manager** has been assigned to:

```
Manager ---- Category ---- Recommendation 1 ---- Action 1 ---- Indicator 1.1
                        |
                        -- Recommendation 2 ---- Action 2 ---- Indicator 2.1
                        |
                        -- Recommendation 3 ---- Action 3 ---- Indicator 3.1
                                              |
                                              -- Action 4 ---- Indicator 4.1
                                                            |
                                                            -- Indicator 4.2
```

> Please note: if Recommendations are part of tagged with Categories or if Actions are associated with Recommendations of multiple Categories, it is possible that multiple Managers receive email reminders for the same Indicator

> Also note that the frequency of email reminders may vary dependoing on configuration - default is **weekly** (compare [Contributor overview](/contributors/contributor.md))