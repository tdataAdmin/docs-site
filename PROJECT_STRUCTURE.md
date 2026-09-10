# docs-site 폴더 구조

## 트리 뷰

```
docs-site/
├── PROJECT_STRUCTURE.md
├── mkdocs.yml
└── docs/
    ├── index.md
    ├── api/
    │   ├── payment.md
    │   └── refund.md
    └── guide/
        ├── deploy.md
        └── setup.md
```

## 트리 뷰 (JSON 형식)

```json
{
  "name": "docs-site",
  "type": "directory",
  "children": [
    {
      "name": "PROJECT_STRUCTURE.md",
      "type": "file"
    },
    {
      "name": "docs",
      "type": "directory",
      "children": [
        {
          "name": "api",
          "type": "directory",
          "children": [
            { "name": "payment.md", "type": "file" },
            { "name": "refund.md", "type": "file" }
          ]
        },
        {
          "name": "guide",
          "type": "directory",
          "children": [
            { "name": "deploy.md", "type": "file" },
            { "name": "setup.md", "type": "file" }
          ]
        },
        { "name": "index.md", "type": "file" }
      ]
    },
    { "name": "mkdocs.yml", "type": "file" }
  ]
}
```

## 파일 목록 요약

- **루트 파일**
  - `PROJECT_STRUCTURE.md` (이 파일)
  - `mkdocs.yml`
- **docs/**
  - `index.md`
  - `api/payment.md`
  - `api/refund.md`
  - `guide/deploy.md`
  - `guide/setup.md`
