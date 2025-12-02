## 分析项目依赖，识别需要升级的包（安全漏洞、过时版本、维护状态等）。

```
cd /Users/**/react-financial-charts && npm outdated 2>&1 | head -50
```

## 检查安全漏洞和过时依赖，识别需要升级的包：

```
cd /Users/**/react-financial-charts && npm audit --audit-level=moderate 2>&1 | head -100
```

