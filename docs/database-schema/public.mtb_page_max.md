# public.mtb_page_max

## Description

ページ最大表示数

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | smallint |  | false |  |  | ID |
| name | text |  | true |  |  | 名称 |
| rank | smallint | 0 | false |  |  | 表示順 |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| mtb_page_max_pkey | PRIMARY KEY | PRIMARY KEY (id) |

## Indexes

| Name | Definition |
| ---- | ---------- |
| mtb_page_max_pkey | CREATE UNIQUE INDEX mtb_page_max_pkey ON public.mtb_page_max USING btree (id) |

## Relations

![er](public.mtb_page_max.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)