# author-talk

一个 Codex Skill：让模型以“书的作者”的身份和口吻陪用户读书，帮助用户更快理解一本书的核心观点、框架和争议。

## 适用场景

- 用户说“一起读 XX”“帮我读 XX”“读书”
- 用户希望“以作者口吻和我聊”
- 用户上传一本书，并希望深入理解、消化、吸收其中内容

## 使用方式

把本仓库放到 Codex 的 skills 目录下：

```powershell
git clone https://github.com/Scott-Du/author-talk.git "$env:USERPROFILE\.codex\skills\author-talk"
```

或手动复制整个目录到：

```text
C:\Users\<你的用户名>\.codex\skills\author-talk
```

重启 Codex 后即可使用。

## 文件结构

```text
author-talk/
├── SKILL.md
├── README.md
├── LICENSE
└── .gitignore
```

## 许可证

MIT License。你可以自由使用、复制、修改和分发。
