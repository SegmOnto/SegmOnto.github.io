# `GraphicZone`

## 1. Definition

**GraphicZone** is a zone containing any type of graphic element, from purely ornamental information to information consubstantial to the text (e.g. full-page paintings, line-fillers, marginal drawings, figures, etc.). Captions, if there are any, is part of this zone, and its text line is labelled `HeadingLine`. If an image contains text, it is possible to label the lines as `DefaultLine`.

⚠️ Drop capitals are excluded from this category.

## 2. Subtypes

Suggested values include:

* `GraphicZone:illustration`
* `GraphicZone:ornamentation`
* `GraphicZone:figure`

If necessary, it is possible to be more precise (and therefore less generic):

* `GraphicZone:headpiece`
* `GraphicZone:tailpiece`
* `GraphicZone:illumination`
* `GraphicZone:fillings`

## 3. Examples

| Type | Exemple |
|------|---------|
| `GraphicZone:illustration` <br/> (or `GraphicZone:illumination`) | <img src="btv1b84259980_f466.jpg" width="200px">  |
| `GraphicZone:illustration` <br/> (or `GraphicZone:engraving`) | <img src="bpt6k15120824_f7.jpg" width="200px">  |
| `GraphicZone:ornamentation` <br/> (or `GraphicZone:headpiece`) | <img src="btv1b86070385_f65.jpg" width="200px">  |
| `GraphicZone:figure` | <img src="Latin_7295A__btv1b10027322j_23.jpg" width="200px">  |
| `GraphicZone:figure` | <img src="btv1b8601519p_f219.jpg" width="200px">  |

## 4. Problems and challenges

- How should we deal with line fillers?