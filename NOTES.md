# NOTES

## Proposed changes

Reorder the steps to focus on key React functionality (like updating `state`) before dealing with API calls. Also incorporate styling earlier so what we look at looks better earlier since half-day sessions don't make it to step 10.

- 07-delete-email
  * delete email by doing `.filter`
  * style delete button by adding "status" element + CSS classes for layout
- 08-fetch
  * in `componentDidMount` `GET` emails + polling
  * in `_handleFormSubmit` `POST` new email + optimistic update
  * in `_handleItemDelete` `DELETE` email + optimistic update
- 09-mark-unread
  * Add button and existing delete button to "status" element + CSS class
- 10-styling
  * app layout
  * conditional class names with `classnames` lib