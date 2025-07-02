# Todo2 - AI-Powered Task Management for VS Code

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/Todo2.todo2?style=flat-square&logo=visual-studio-code)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/Todo2.todo2?style=flat-square)
![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/Todo2.todo2?style=flat-square)

**Transform your development workflow with AI-native task management.** Todo2 seamlessly integrates with Cursor AI through Model Context Protocol (MCP) for natural language todo management.

![Todo2 Demo](todo2-demo.gif)

> 📹 **Demo GIF:** The demonstration above shows the complete Todo2 workflow including setup and dashboard features. *Hosted in public repository.*

## 🚀 Quick Start

### Installation & Setup
1. **Install** Todo2 from VS Code Marketplace
2. **Open** your project workspace in VS Code  
3. **Run** `Todo2: Initialize Workspace` (Ctrl+Shift+P)
4. **Restart** Cursor to load MCP integration
5. **Switch** to Agent mode in Cursor

### Start Managing Tasks with AI
```
Ask AI: "Show me my current todos"
Ask AI: "Create a todo for implementing user authentication"  
Ask AI: "Mark todo T-1 as in progress"
Ask AI: "What should I work on next?"
```

## ✨ Why Todo2?

### 🤖 **AI-Native Design**
Unlike traditional task managers, Todo2 is built for **natural language interaction** with AI assistants. No clicking through menus - just tell your AI what you need.

### ⚡ **One-Click Setup**  
Single command automatically configures Cursor MCP integration. No complex setup, no configuration files to edit manually.

### 🏠 **Workspace-Focused**
Each project gets its own isolated todo list. Switch between projects, switch between todo contexts automatically.

### 💾 **Simple & Transparent**
Tasks stored in readable JSON files (`.todo2/state.todo2.json`). Version control friendly, human readable, no proprietary formats.

## 🎯 Perfect AI Workflow

**Traditional todo apps** force you to context-switch between your code and a separate interface.

**Todo2** keeps you in your AI conversation flow:

```
You: "Help me plan my React project"
AI: I'll create project tasks for you.
✅ Created 5 tasks: Setup, Components, API, Testing, Deployment

You: "What should I start with?"  
AI: I recommend T-2: "Create component structure" - it's foundational.

You: "Start that task"
AI: ✅ Marked T-2 as "In Progress". Ready to code!
```

## 🛠️ Rich Task Management

### Professional Markdown Editor
- **Rich formatting** with live preview
- **Syntax highlighting** for code snippets  
- **Auto-save** and theme integration
- **Full-screen editing** for detailed planning

### Smart Comment System
- **📝 Notes**: Progress tracking and observations
- **🔬 Research**: Links and investigation findings  
- **⚙️ Setup**: Step-by-step configuration instructions
- **✅ Results**: Completion outcomes and lessons learned

### Modern Interface
- **Beautiful UI** matching your VS Code theme
- **Statistics dashboard** showing progress metrics
- **Filter & search** for easy task discovery
- **Responsive design** for all screen sizes

## 🔧 Available Tools (Cursor Agent Mode)

| Tool | What It Does |
|------|-------------|
| **`list_todos`** | Show all tasks with optional status filtering |
| **`create_todo`** | Create new tasks with rich descriptions |
| **`update_todo_status`** | Move tasks through workflow (Todo → In Progress → Done) |
| **`get_todo_details`** | Get full task info including comments |
| **`delete_todo`** | Remove completed or obsolete tasks |
| **`get_statistics`** | Progress overview and completion metrics |

## ⚙️ Configuration

Customize in VS Code Settings (`Ctrl+,`):

| Setting | Default | Description |
|---------|---------|-------------|
| `todo2.autoConfigureMcp` | `true` | Auto-setup Cursor MCP integration |
| `todo2.dataLocation` | `"workspace"` | Store todos per-workspace vs globally |

## 🔍 Troubleshooting

**Tools not appearing in Cursor?**
1. Restart Cursor after running "Initialize Workspace"
2. Verify Agent mode is active (Cmd+I or Ctrl+I)
3. Check `.cursor/mcp.json` contains todo2 server

**Tasks not saving?**
1. Ensure workspace folder is writable
2. Check `.todo2/state.todo2.json` file permissions
3. Verify VS Code has file system access

**Need to reset?**
1. Delete `~/.cursor/mcp.json` 
2. Re-run "Initialize Workspace"
3. Restart both VS Code and Cursor

## 📊 Todo2 vs Traditional Extensions

| Feature | Todo2 | Traditional |
|---------|-------|-------------|
| **AI Integration** | ✅ Native, natural language | ❌ Manual commands only |
| **Setup** | ✅ One command | ❌ Complex configuration |
| **Context** | ✅ Per-workspace | ❌ Global or manual |
| **Storage** | ✅ Simple JSON | ❌ Complex databases |
| **Workflow** | ✅ AI conversation | ❌ UI clicking |

## 🎨 Screenshots

*Coming soon - AI agent integration, rich task editor, and modern interface*

## 🤝 Support & Contributing

- **🐛 Issues**: Report through VS Code extension management
- **💡 Feedback**: Share ideas via marketplace reviews

## 📄 License

See [LICENSE](LICENSE) for details.

---

**🚀 Ready to transform your development workflow?**

*Install Todo2 and experience AI-powered task management today!*

## ✨ The Ultimate Developer Task Manager for VS Code

**Todo2** is not just another todo list. It's an intelligent task management system powered by the **MCP (Multi-Contextual Prompts) Client**, designed to live right inside your favorite editor. It helps you manage complex development workflows with AI-powered task generation, state management, and seamless integration with your coding environment.
