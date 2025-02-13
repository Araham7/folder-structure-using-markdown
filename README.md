`Markdown Cheat Sheet`

# 1. Headings
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

# 2. Text Formatting
**Bold Text** or __Bold Text__
*Italic Text* or _Italic Text_
~~Strikethrough Text~~

# 3. Lists

## Unordered List:
- Item 1
- Item 2
  - Sub-item 2.1

## Ordered List:
1. First item
2. Second item
   1. Sub-item 2.1

# 4.  Links and Images
## Link:
[Google](https://www.google.com)

## Image:
![Alt Text](https://example.com/image.png)

# 5. Code
## Inline Code:
Use `print("Hello World")` in Python.

## Code Block:
```python
def hello():
    print("Hello, Markdown!")
```

# 6. Blockquotes

> This is a blockquote.
> It can span multiple lines.

# 7. Horizontal Rule(`---`)
---

# 8. Tables

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |

# 9. Task Lists
- [x] Task 1 (completed)
- [ ] Task 2 (pending)


# 10. Escaping Characters

Use \* to display an asterisk.

# 11. file structure

```
my-express-socketio-server/
│
├── node_modules/               # Node.js modules (auto-generated by npm)
├── public/                     # Static files (CSS, JS, images, etc.)
│   ├── css/
│   ├── js/
│   └── images/
│
├── src/                        # Source code
│   ├── config/                 # Configuration files
│   │   └── index.js            # Configuration settings (e.g., environment variables)
│   │
│   ├── controllers/            # Controllers for handling routes
│   │   └── chatController.js   # Example controller for chat routes
│   │
│   ├── models/                 # Database models (if using a database)
│   │   └── User.js             # Example User model
│   │
│   ├── routes/                 # Route definitions
│   │   └── index.js            # Main route definitions
│   │
│   ├── services/               # Business logic and services
│   │   └── chatService.js      # Example service for chat logic
│   │
│   ├── sockets/                # Socket.IO event handlers
│   │   └── chatSocket.js       # Example socket handler for chat events
│   │
│   ├── utils/                  # Utility functions and helpers
│   │   └── helpers.js          # Example utility functions
│   │
│   ├── app.js                  # Main Express application setup
│   └── server.js               # Server entry point (starts the server)
│
├── .env                        # Environment variables
├── .gitignore                  # Files and folders to ignore in Git
├── package.json                # Project dependencies and scripts
└── README.md                   # Project documentation
```
