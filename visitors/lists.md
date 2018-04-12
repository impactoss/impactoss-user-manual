### Lists: Filter, group & more

> _Available for: [Visitors](/visitors/visitor.md) and registered users ([Guests](/guests/guest.md), [Contributors](/contributors/contributor.md), [Managers](/managers/manager.md), and [Administrators](/admins/admin.md))_

On any list view, including for [Actions](/visitors/actions.md), [Indicators](/visitors/indicators.md), [Recommendations ](/visitors/recommendations.md), and optionally also [SDG Targets ](/visitors/sdg-targets.md), you can use several features to customise your view:

* **group list items** (except Indicators),
* **sort list items**,
* **filter list items** by keyword, attribute and/or associated categories and related elements
* **change pagination** (number of items on page),
* **change view mode** to see (Implementation View) or hide (Liust View) nested elements such as Indicators and Progress Reports

> Note: [Managers](/managers/manager.md) can use the filter function to select the entities they wish to edit individually or in bulk. They must be logged in to do so. For more details on how to edit multiple entities from the list view please see [Batch edit](/managers/batch-edit.md).

#### Grouping

List items can be grouped by any category group (or taxonomy) that is applicable. It additionally allows to subgroup items.

> Depending on the specific configuration, items can be grouped by default, e.g. by Recommendation Cluster and/or by Organisation as pictured below

![](/assets/v-actions-grouping.png)
_Screenshot from demo site ([demo.impactoss.org](https://demo.impactoss.org)) - all content for demo purposes only_

You can change the grouping by selecting a different taxonomy from the dropdown and ungroup by clicking on the cross next to the grouping.

#### Sorting

List items can also be sorted by creation date (often default), title, reference (where applicable) and last update.

![](/assets/v-action-list-sorting.png)

> Depending on the specific configuration, sorting options and default sorting can vary for different list types

#### Filtering

Lists can be filtered by keyword or any associated category, related element or attribute. This can help you narrow down the number of list items according to personal preferences or areas of interest.

> Please note: for a full text search that includes descriptons use the [Search feature](/visitors/search.md)

Any active filter will appear in the search field at the top of the list views:

![](/assets/v-action-list-seach.png)
_Screenshot from demo site ([demo.impactoss.org](https://demo.impactoss.org)) - all content for demo purposes only_

##### Filtering by keyword (Reference or Title)

By typing into the search field you can filter list items by keyword, targeting each list item's title, and unique reference (sometime database id). The list will auto update and the number of matching items will accordingly reduce immediately.

In the example pictured below, the list of actions was filtered by 'children':

![](/assets/v-list-search.png)
_Screenshot from demo site ([demo.impactoss.org](https://demo.impactoss.org)) - all content for demo purposes only_

> The keyword filter function can also be used to find specific entities, e.g. by entering a UPR recommendation reference number.

##### Filtering by Category, Connected Category, Connection or Attribute

Other filter options for specific associations can be found in the list side bar on the left hand side.

Filter options includes
* **Filter by Category**: allows filtering the list items by any Category they are tagged with, grouped by taxonomy
* **Filter by Connected Category** (where applicable): you can also filter items by a Category a connected element is tagged with, this allows for example filtering Actions by Human Rights Mechanisms that a Recommendation they address is tagged with
* **Filter by Connection** (where applicable): you can filter items by any other element they are related with, this allows for example filtering Actions by a specific Recommendation
* **Filter by Attribute** (where applicable): you can filter items by specific attributes and characteristics, for example if Recommendations have been accepted or not accepted and (if authorised) also by assigned user.

> Note: you can toggle (expand and collapse) filter option groups. Default toggle state may depend on the specific configuration

**Example: how to filter a list of actions by Education category (of Thematic CLuster taxonomy)**

![](/assets/v-list-filter.png)
_Screenshot from demo site ([demo.impactoss.org](https://demo.impactoss.org)) - all content for demo purposes only_

Clicking on the 'Thematic Cluster' taxonomy in the filter list will bring out all Thematic Cluster  categories, including the number of list Actions each category 'tags'. From the cluster list you can simply select the cluster you are interested in and the filter will be applied. If the list of options is long you can also filter the list of filters using the search box above the filter options.

For instance, if we select 'Education' then we are presented with the 5 actions associated with that cluster of Recommendations:

![](/assets/v-list-filtered.png)
_Screenshot from demo site ([demo.impactoss.org](https://demo.impactoss.org)) - all content for demo purposes only_

The filter the user has applied now appears in the seacrh field above the list (circled in red). You can remove the filter by clicking on the cross on the tag or you can choose additional filters (including keyword filters) to further reduce the number of list items.

---

### Pagination

You can change the number of items per page or navigate to additional pages by using the options below the list.

> Please note: the default number of search results can vary depening on the specific configuration

---

#### Change view mode: expanding the Implementation Plan

The National Action Implementation Plan (Action List), as well as Indicator and SDG Target list views, can be viewed in either 'List View' or 'Implementation View'.

**List View**:

The default 'List View' gives the user a condensed overview with the a summary of associated Indicators and Progress Reports only.

![](/assets/v-impl-list-view.png)
_Screenshot from demo site ([demo.impactoss.org](https://demo.impactoss.org)) - all content for demo purposes only_

From the list view you can activate the Implementation View either clicking on 'Implementation View' towards the top right-hand corner of the screen (see screenshots). You can also drill down one level at a time by clicking on the respective column headers or summary boxes within each column.

**Implementation View**

The 'Implementation View' gives a more detailed view with direct access to any associated Indicators and Progress Reports

![](/assets/v-impl-extended-view.png)
_Screenshot from demo site ([demo.impactoss.org](https://demo.impactoss.org)) - all content for demo purposes only_

Once selected the user can revert to the List View by clicking on 'List View' or on the column headers.
