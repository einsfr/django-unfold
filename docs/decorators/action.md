---
title: Action
description: Custom Unfold @action decorator.
order: 2
---

# Unfold @action decorator

Unfold also uses custom `@action` decorator, supporting 2 more parameters in comparison to base `@action` decorator:

- `url_path`: Action path name, used to override the path under which the action will be available
  (if not provided, URL path will be generated by Unfold)
- `attrs`: Dictionary of the additional attributes added to the `<a>` element, used for e.g. opening action in new tab (`{"target": "_blank"}`)