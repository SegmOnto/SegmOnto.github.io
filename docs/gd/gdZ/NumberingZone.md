# `NumberingZone`

## 1. Definition

**NumberingZone:** is a zone containing the page, the folio, or the document number, with no regard for the mark's origin (scribe, curator, etc). The zone usually is at the top of the page.

⚠️ Letters/numbers denoting a folio's order within a quire are annotated differently with a special zone: `QuireMarksZone`.

## 2. Subtypes

Suggested values include:

* `NumberingZone:page`
* `NumberingZone:folio`
* `NumberingZone:item`

## 3. Examples

| Type | Example |
|------|---------|
| `NumberingZone:folio` | <img src="btv1b84192440_f45.jpg" width="200px">  |
| `NumberingZone:page` | <img src="btv1b86070385_f135_p.jpg" width="200px">  |

⚠️ A single folio can bear two `NumberingZone` (here `NumberingZone:item` on the left in blue and `NumberingZone:folio` on the right in red):

<img src="Sorbonne_MSVC_lettre 65_001.jpg" width="400px">

## 4. Problems and challenges

∅