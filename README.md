# junior-test

Task: Build a Bookmark Management App using store management

Pages Required:
1. Home Page - Display welcome message and a summary of bookmarks i.e. total bookmarks, total liked bookmarks, total categories.
2. Bookmarks Page - Display a list of bookmarks. Also allow user to add, edit, complete and delete bookmark.
3. Category Page - Display a list of categories.
4. Settings Page - Let user toggle a dark mode theme.

Bookmark Data Pattern:
[{ id: '1', title: 'VueJs Basics', desciption: 'This is description', url: 'https://vuejs.org/guide/introduction.html', category: "[INSERT CATEGORY ID]", liked: true, created_at: "", updated_at: "" }]

Requirements:
- State Management(Pinia):
  Create stores for bookmarks and settings to store it locally in store.
  Bookmarks should be stored in a Pinia store with persistent state (via localStorage) to retain bookmarks between page reloads.
- VueJs's Lifecycle and Events:
  Use computed to display derived data i.e. total bookmarks, total completed bookmarks. etc.
  Use other events and lifecycle according to your needs.
- Bookmark Management:
  Bookmark must have relation with categoru.
  Allow users to create bookmarks with title, url, description, category and liked status.
  created_at and updated_at must be change based on create or edit function.
  Paginate data with dropdown to select items to show per page.
  Users can mark a task "completed" using a checkbox.
  Search bookmark by title.
  Filter by liked status.
  Inputs must have validation logic based in the item before submitting.

Evaluation Criteria
- Code Quality
- Proper usage of Pinia
- Both Options API and Composition API are valid

Plus points
- Proper documentation
- Visually appealing UI/UX

Please contact us if you have any question.
