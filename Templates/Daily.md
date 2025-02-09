
<%*
const year = tp.date.now("YYYY")
const month = tp.date.now("MM")
const targetDir = `0_Daily/${year}/${month}`
await tp.file.move(`${targetDir}/${tp.file.title}`)
-%>
---
created: <% tp.date.now("YYYY-MM-DD") %>
type: daily
---
# 📅 <% tp.date.now("YYYY년 MM월 DD일") %>

## 🎯 오늘의 목표

## 📝 오늘의 노트

## ✅ 완료한 일

## 📊 회고
- 좋았던 점:
- 개선할 점:
- 내일 할 일: