# nodejs-notes-app
An app to create a note (notes.json), then add/remove/list/read that note.

---
PS C:\JavaScript\NodeJs\section-9\notes-app> node .\app.js --help
app.js [command]

Commands:
  app.js add     Add a new note
  app.js remove  Remove a note
  app.js list    List your notes
  app.js read    Read a note

Options:
  --help     Show help                                                 [boolean]
  --version  Show version number                                       [boolean]
  
---  
PS C:\JavaScript\NodeJs\section-9\notes-app> node .\app.js add
app.js add

Add a new note

Options:
  --help     Show help                                                 [boolean]
  --version  Show version number                                       [boolean]
  --title    Note title                                      [string] [required]
  --body     Note body                                       [string] [required]

Missing required arguments: title, body

---
PS C:\JavaScript\NodeJs\section-9\notes-app> node .\app.js add --title "this-is-title" --body "this-is-body"
New note added!
