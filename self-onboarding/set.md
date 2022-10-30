# Sort, Filter, & Edit Objects with Sets

### Understanding Sets

Lots of people compare Sets with databases, but there's a key difference: Sets don't _store_ objects like regular databases. Rather, they provide a way to see a portion of your knowledge graph based on **Object Type** as a primary filter criterium, and several secondary filters which you can customize.

#### Sets serve two primary functions:

1. **Organizing and Accessing Objects**\
   ****\
   ****We often get requests along the lines of: _How do I find all of the Notes I've created?_One easy way is to create a Set based on Type: Note, which will display every Note you've created in Anytype. If you have specific notes you'd like to frequently access, you can filter them based on Relations you've added to these notes, for instance: Creation Date, Tags, or Priority. (In this sense, Relations behave like attributes).You can then pin your Set to your Favorites menu, where it will sit on your Anytype homescreen, acting like a folder for all Objects that meet certain criteria.
2. **Batch editing Objects**\
   ****Sets also provide a way to batch-edit Objects. You can use multi-select in Sets to delete multiple Objects at once. You can also batch-add or edit Relations for Objects from Set view, instead of entering them one-by-one.

{% embed url="https://vimeo.com/717016770" %}

### Creating Sets

You can create a Set with the + menu in the Home or bottom-left corner or using the / shortcut menu in the editor.

Next, you need to decide on the purpose of your Set. For example, project management may require Type: Project, for reading list — Book. From the Library, choose an Object Type, click "Create," and choose "Create a set."

<figure><img src="../.gitbook/assets/Create a set 2.png" alt=""><figcaption><p>Creating a Set from Types view</p></figcaption></figure>

### Adding Relations to Objects via Sets

Instead of adding Relations one-by-one to Objects, you can batch-add them to your Set by clicking the + button inside the Set's Header.&#x20;

### Adding Sort and Filters

Add Sorts and Filters by clicking the filter icon the top-right side of the Set.

<figure><img src="../.gitbook/assets/Customize set 1.png" alt=""><figcaption></figcaption></figure>

### Customizing Set View

Customize whether you want your Sets to appear in Grid, Gallery, List, or Kanban view, as well as specific filters. Tap the + button next to 'All' to add a new View and customize how you want to visualize your Objects.

<figure><img src="../.gitbook/assets/Customize set 2.png" alt=""><figcaption></figcaption></figure>

#### Grid

When you select the Grid view for a Set, you will see a tabular view of Objects with Name as mandatory first column. All other columns can be chosen by you. You can Drag and drop columsn to reorder, and use the + button at the end of the header row to add a Relation as a column. From that menu, you can also choose to add a new Relation. By clicking on the header name, you can perform actions on the column (duplicate, delete, hide), change filtering and sorting, and insert additional Relations left or right of the selected column.

#### Gallery

In the Gallery view you will see your Objects appear as cards with Relations placed on them. Using the View menu you can configure card size, to show or hide the Object icon, whether or not to show a cover image (and how).

#### List

List is the most straigforward view where Objects are listed with their name. You can only define which Relations you want to see. These Relations will be written after the name of the Object.

#### Kanban

With the Kanban view you can show your Objects as cards grouped in columns. Each column represents a value of a Relation that you select to group by. For now, you can group by Relations of type Status or Tag, and the built in Relations "Done" (being either checked or unchecked). By dragging and dropping you can reorder the columns to match your needs. You can configure whether you want the columns to have a backgroudn color (and which) and whether you want to see the icon of the Object. You can also choose to hide one or more columns via the column menu (three dots) or in the Set view menu under the Groups tab that becomes visible when you have selected the Kanban view.
