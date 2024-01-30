# Fictioneer Taxonomy Project

The Fictioneer Taxonomy Project is an attempt to make taxonomies for web fictions more conform. This may prove useful to services or tools which offer searchable lists aggregated from different sites.

This is part of the [Fictioneer](https://github.com/Tetrakern/fictioneer) theme for WordPress.

## Genres

Genres are immediately understandable categories of stories in regards to content, technique, tone, or sometimes length (e.g. short stories). They are broad in the sense that no one story ever needs to be alike, allowing an infinite number of variations and combinations of tropes — although they usually follow trends.

### How to properly use genres

Genres should describe a story conceptually and whole, not just single occurrences within. For example, the "Military" genre revolves around the armed forces including their organizations, operations, politics, history, and so forth. Or the opposition thereof. If your "Fantasy" story features a single war but is otherwise about hunting monsters, you should opt for a tag instead or leave it out.

## Tags

Tags are keywords associated with commonly agreed upon trappings and tropes. They help describing, browsing, and searching stories. Not to be confused with _genres_, such as "Science Fiction" meant for broad categorization, or _fandoms_ which situate a story within a particular intellectual property, such as "Stargate".

This list is incomplete and always will be incomplete, serving as vocabulary templates for your own.

### How to properly use tags

Tags should be chosen based on relevance and weighted presence, not added in bulk just to account for every reference or possibility. The "Smartphone" tag is superfluous for modern stories, but may be justified if the protagonist retains a working device after being transported into a medieval world. If you end up with half a page of tags or more, better reevaluate. Redundancy should be avoided as well, so when you got "High Fantasy" you do not need "Fantasy" on top.

### Wait, where is all the smut?

Most adult tags have been deliberately left out because there are just _too many of them_. Half the list would be nothing but fetishes, kinks, and practices. And let’s be real, do you really need assistance to describe your smut? After years on the Internet, you cannot tell?

## Data Node Example

```json
"siblingRivalry": {
  "aliasOf": "",
  "association": ["Siblings", "Family", "Brother", "Sister", "Twin", "Heirs"],
  "category": ["Family"],
  "name": "Sibling Rivalry",
  "parent": "Rivalry",
  "description": "Competition or animosity among siblings, regardless of blood-relation. Reasons may include preferential treatment, the order of succession or inheritance, literal enforced competition, or just petty jealousy."
}
```
