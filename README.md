# Knowledge

后端面试知识库 ledger。learn_agent ingest pipeline 写入。

## 结构

```
_state/
   processed_ids.json    每个已处理的 content_id 集合
   taxonomy.json         当前所有 leaf 路径的清单
tree/
   服务端技术/...        题目 markdown ledger（追加式）
   算法与数据结构/
   面试软技能/
```

## 来源

`../learn_agent/data/list_data_full.jsonl`

由 `learn_agent/tools/knowledge` ingest，详细 taxonomy 与字段约定见 `learn_agent/tools/knowledge/taxonomy.go`。
