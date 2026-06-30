# Todo List Application with Local Storage

A modern, feature-rich todo list application built with HTML, CSS, and JavaScript. All data is stored locally in your browser using localStorage, so your tasks persist even after refreshing or closing the page.

## ✨ Features

### Core Functionality
- ✅ **Add Tasks** - Create new todo items with ease
- ✅ **Mark Complete** - Check off completed tasks
- ✅ **Delete Tasks** - Remove individual tasks or all at once
- ✅ **Local Storage** - All tasks are saved locally in your browser

### Advanced Features
- 📊 **Statistics Dashboard** - View total, completed, and remaining tasks
- 🎯 **Priority Levels** - Set task priority (High, Medium, Low)
- 🔍 **Smart Filtering** - Filter by All, Active, Completed, or High Priority
- ⏰ **Timestamps** - See when each task was created
- 🧹 **Bulk Actions** - Clear all completed tasks or delete everything
- 📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile

## 🚀 How to Use

1. **Open the Application**: Open `todo-list.html` in your web browser
2. **Add a Task**: Type your task in the input field, select priority, and click "Add" or press Enter
3. **Mark Complete**: Check the checkbox to mark a task as complete
4. **Delete Task**: Click the Delete button to remove a task
5. **Filter Tasks**: Use the filter buttons to view specific tasks
6. **View Stats**: Check the statistics section to see your progress
7. **Clear Data**: Use the action buttons to clear completed or all tasks

## 💾 Local Storage

Your tasks are automatically saved to your browser's local storage. This means:
- Tasks persist when you refresh the page
- Tasks persist when you close and reopen your browser
- Each browser/device has its own separate task list
- No data is sent to any server

## 🎨 Design Features

- **Beautiful Gradient Background** - Purple gradient theme
- **Smooth Animations** - Hover effects and transitions
- **Color-Coded Priorities** - Visual indicators for task priority
- **Empty State Message** - Friendly message when no tasks exist
- **Responsive Layout** - Adapts to all screen sizes
- **Custom Scrollbar** - Styled scrollbar for the todo list

## 🔒 Security

- XSS Protection - All user input is properly escaped
- Input Validation - Tasks are validated before saving
- Character Limit - Maximum 100 characters per task
- Confirmation Dialogs - Confirm before bulk deletions

## 📊 Statistics

The app automatically tracks:
- **Total Tasks** - Total number of tasks
- **Completed** - Number of finished tasks
- **Remaining** - Number of active tasks

## 🎯 Priority Levels

- **High** - Red badge, important tasks
- **Medium** - Orange badge (default), regular tasks
- **Low** - Green badge, less important tasks

## 🔧 Technical Details

### Technologies Used
- HTML5
- CSS3 (with gradients, flexbox, animations)
- Vanilla JavaScript (no dependencies)
- Local Storage API

### Browser Compatibility
- Chrome/Edge ✅
- Firefox ✅
- Safari ✅
- Opera ✅
- IE11+ ✅

## 📝 Local Storage Data Structure

Each todo item is stored as a JavaScript object:

```javascript
{
  id: 1234567890,              // Unique timestamp ID
  text: "Task description",    // Task text
  completed: false,            // Completion status
  priority: "high",            // Priority level
  createdAt: "Jan 1, 10:30 AM" // Creation date/time
}
```

## 💡 Tips

1. Use keyboard shortcut - Press Enter to add a task quickly
2. Set priorities - Mark important tasks as high priority
3. Regular cleanup - Delete completed tasks to keep focused
4. Mobile friendly - Access your list on any device

## 🐛 Troubleshooting

### Tasks not saving?
- Check if your browser allows local storage
- Try clearing browser cache
- Check browser privacy settings

### All data disappeared?
- Local storage may have been cleared
- Browser cache was cleared
- You're using a different browser

## 📄 License

Free to use for personal and commercial projects.

## 🤝 Contributing

Feel free to fork, modify, and improve this application!

---

**Made with ❤️ for productivity**