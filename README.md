# Todo2 - AI-Powered Task Management for Cursor

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/Todo2.todo2?style=flat-square&logo=visual-studio-code)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/Todo2.todo2?style=flat-square)
![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/Todo2.todo2?style=flat-square)

**Transform your development workflow with AI-native task management.** Todo2 seamlessly integrates with Cursor AI through Model Context Protocol (MCP) for natural language todo management.

![Todo2 Demo](todo2-demo.gif)

> 📹 **Demo GIF:** The demonstration above shows the complete Todo2 workflow including setup and dashboard features.

## 🚀 Quick Start

### Installation & Setup
1. **Install** Todo2 from Cursor Marketplace
2. **Open** your project workspace in Cursor  
3. **Click** the "Todo2 Dashboard" button in the status bar (bottom left)
4. **Automatic Setup** - MCP integration configures itself on first UI open, just allow MCP in left bottom corner
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

### ⚡ **Zero Setup**  
Install and go! MCP integration configures automatically when you first open the dashboard. No manual configuration needed.

### 🏠 **Workspace-Focused**
Each project gets its own isolated todo list. Switch between projects, switch between todo contexts automatically.

### 💾 **Simple & Transparent**
Tasks stored in readable JSON files (`.todo2/state.todo2.json`). Version control friendly, human readable, no proprietary formats.

### 📊 **Status Bar Integration**
Quick access to your todo dashboard with a dedicated status bar button. One click to open, no command palette needed.

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
- **Beautiful UI** matching your Cursor theme
- **Statistics dashboard** showing progress metrics
- **Filter & search** for easy task discovery
- **Responsive design** for all screen sizes
- **Instant loading** - no delays or loading screens

## 🔧 Available Tools (Cursor Agent Mode)

| Tool | What It Does |
|------|-------------|
| **`list_todos`** | Show all tasks with optional status filtering |
| **`create_todo`** | Create new tasks with rich descriptions |
| **`update_todo_status`** | Move tasks through workflow (Todo → In Progress → Done) |
| **`get_todo_details`** | Get full task info including comments |
| **`delete_todo`** | Remove completed or obsolete tasks |
| **`get_statistics`** | Progress overview and completion metrics |

## 🎮 Commands

| Command | Description | Access |
|---------|-------------|--------|
| **`Todo2: Open Todo UI`** | Open the todo dashboard | Status bar button or Command Palette |

## 🔍 Troubleshooting

**Tools not appearing in Cursor?**
1. Open Todo2 dashboard once to trigger automatic MCP setup
2. Restart Cursor to load the MCP integration
3. Verify Agent mode is active (Cmd+I or Ctrl+I)
4. Check `.cursor/mcp.json` contains todo2 server entry

**Tasks not saving?**
1. Ensure workspace folder is writable
2. Check `.todo2/state.todo2.json` file permissions
3. Verify Cursor has file system access

**Status bar button not visible?**
1. Check if status bar is enabled in Cursor (View → Appearance → Status Bar)
2. Look for "Todo2 Dashboard" button on the left side of the status bar
3. Restart Cursor if the button doesn't appear after installation

**Need to reset MCP integration?**
1. Delete `.cursor/mcp.json` from your home directory
2. Open Todo2 dashboard to trigger automatic reconfiguration
3. Restart Cursor to reload the integration

## 📊 Todo2 vs Traditional Extensions

| Feature | Todo2 | Traditional |
|---------|-------|-------------|
| **AI Integration** | ✅ Native, natural language | ❌ Manual commands only |
| **Setup** | ✅ Automatic, zero config | ❌ Complex configuration |
| **Context** | ✅ Per-workspace | ❌ Global or manual |
| **Storage** | ✅ Simple JSON | ❌ Complex databases |
| **Workflow** | ✅ AI conversation | ❌ UI clicking |
| **Access** | ✅ Status bar button | ❌ Command palette only |

## 🤝 Support & Contributing

- **🐛 Issues**: Report through Cursor extension management
- **💡 Feedback**: Share ideas via marketplace reviews

## 📄 License

See [LICENSE](LICENSE) for details.

## Need more info?
For more information please visit https://todo2.pro/ or write at info+todo2@theadamlabs.com

---

**🚀 Ready to transform your development workflow?**

*Install Todo2 and experience AI-powered task management today!*

## ✨ The Ultimate Developer Task Manager for Cursor

**Todo2** is not just another todo list. It's an intelligent task management system powered by the **MCP (Model Context Protocol)**, designed to live right inside your favorite editor. It helps you manage complex development workflows with AI-powered task generation, state management, and seamless integration with your coding environment.
