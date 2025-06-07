# BiancaTools v3.0.0 🚀

## Total: 15 Ferramentas!

### 🌐 Puppeteer (5)
- puppeteer_navigate
- puppeteer_screenshot
- puppeteer_click
- puppeteer_type
- puppeteer_get_content

### 🐙 GitHub (6)
- github_create_issue
- github_list_issues
- github_create_pr
- github_create_repo
- github_push_files
- github_commit

### 📁 Git Local (4) - NOVO!
- git_status
- git_commit
- git_push
- git_pull

## Como usar as novas ferramentas Git:

```javascript
// Verificar status
await mcp__BiancaTools__git_status({ detailed: true });

// Fazer commit
await mcp__BiancaTools__git_commit({
  message: "feat: Minhas alterações",
  addAll: true
});

// Fazer push
await mcp__BiancaTools__git_push({ branch: "main" });
```

---

*Criado com BiancaTools - O servidor MCP mais completo!*