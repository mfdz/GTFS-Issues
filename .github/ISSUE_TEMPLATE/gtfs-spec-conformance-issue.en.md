---
name: GTFS Spec Conformance Issue
about: Create an issue describing a violation of GTFS Specification
title: 'Agency Short Name: '
labels: Error
assignees: ''

---

**Issue description**
A clear and concise description of the error.

**SQL to reproduce (if applicable)**
In case the issue can be demonstrated, add an SQL query which demonstrates the issue you identified:

```SQL
SELECT * FROM ...
```

Note: There exist a couple of tools to import GTFS data in SQL databases and query it, see e.g. https://gtfs.org/resources/gtfs/#postgresql or https://github.com/andredarcie/awesome-gtfs.


**Reference**
Provide a link to the GTFS Spec which should is violated.
[e.g. https://developers.google.com/transit/gtfs/reference/#stopstxt]

**Last update of GTFS Feed**
[e.g. 2019-01-17]

**Hash of the GTFS Feed**
If you have the ability, please provide a hash of the whole GTFS feed, e.g. a [SHA-1](https://en.wikipedia.org/wiki/SHA-1) or [MD5](https://en.wikipedia.org/wiki/MD5) hash. This allows others to check if they're working with the exact same version of the feed.

**GTFS Feed Download Link**
[e.g. http://www.verbund.de/download/gtfs.zip]