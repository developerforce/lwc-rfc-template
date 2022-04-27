---
title: Short Title
champion: <Author> <email@example.com>
status: DRAFTED
created_at: YYYY-MM-DD
updated_at: YYYY-MM-DD
pr: (leave this empty until the PR is created)
---

## Component Description/Overview

Brief explanation of the feature. Specification for `<c-cmp-name>`

## Basic example

```html
<c-cmp attribute="value"> .... </c-cmp>
```

## Readiness

| Team            | Info on when your component will be released |
| --------------- | -------------------------------------------- |
| Developing Team | TBD                                          |

## Detailed design

This is the bulk of the RFC. Explain the design in enough detail for somebody
familiar with your existing set of components to understand, and for somebody familiar with the
implementation to implement. This should get into specifics and corner-cases,
and include examples of how the feature is used. Any new terminology should be
defined here.

## Styling/UX Resources

Link to any mocks, existing blue print, etc.

## Classification

| Category                          | Supported Enviroments and targets |
| --------------------------------- | --------------------------------- |
| `Layout/Visualization/Navigation` | LEX, Exp Cloud, Mobile etc.       |

## Attributes (Public Properties)

Please list out known attributes the component should be aware of.

| Attribute | Type   | Default Value | Description                          |
| --------- | ------ | ------------- | ------------------------------------ |
| `checked` | `bool` | `false`       | Concise description of the attribute |

## Public Methods

| Name    | Arguments | Return Value | Description                       |
| ------- | --------- | ------------ | --------------------------------- |
| `focus` | `N/A`     | `N/A`        | Concise description of the method |

## Public Events

Please list out known events the component should be aware of or react to. Does not need to be exhaustive as the implementor will require `CustomEvent`

| Event Name | Type | Bubbles | Composed | Cancellable | Dispatch Behavior                       |
| ---------- | ---- | ------- | -------- | ----------- | --------------------------------------- |
| `clicked`  | none | `true`  | `true`   | `false`     | Concise description when event is fired |

## Accessibility Requirements

Add any necessary accessibility requirements this component _must_ meet. This can include but not limited to WCAG 2.1, keyboard interactions, focus trapping, ARIA roles and how they react when interacted with, expected experience for individuals that may be impaired of any sorts.

## Data/Metadata Requirements

Highlight any data/metadata requirements(if any).

## Public Styling Requirements

Please add any known CSS custom properties, that allow a customer to change the rendered visuals of the component.

## Internationalization

- List features that require translations
- List features that require locale support
- Does it require right-to-left support? What is the expected behavior when translated to another language?

## Performance

Define performance requirements.

## Testing

Define testing requirements such as:

- Unit tests
- UTAM objects
- Performance tests

## Open Questions

Optional, but suggested for first drafts. What parts of the design are still un-resolved, need spikes, etc.
