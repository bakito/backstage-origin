# @backstage/plugin-events-backend-module-gitlab

## 0.1.8

### Patch Changes

- 807416a9ed39: fix Installation documentation
- Updated dependencies
  - @backstage/backend-plugin-api@0.5.3
  - @backstage/config@1.0.8
  - @backstage/plugin-events-node@0.2.7

## 0.1.8-next.2

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.5.3-next.2
  - @backstage/config@1.0.7
  - @backstage/plugin-events-node@0.2.7-next.2

## 0.1.8-next.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.5.3-next.1
  - @backstage/plugin-events-node@0.2.7-next.1
  - @backstage/config@1.0.7

## 0.1.8-next.0

### Patch Changes

- Updated dependencies
  - @backstage/config@1.0.7
  - @backstage/backend-plugin-api@0.5.3-next.0
  - @backstage/plugin-events-node@0.2.7-next.0

## 0.1.7

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.5.2
  - @backstage/config@1.0.7
  - @backstage/plugin-events-node@0.2.6

## 0.1.7-next.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.5.2-next.1
  - @backstage/config@1.0.7
  - @backstage/plugin-events-node@0.2.6-next.1

## 0.1.7-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.5.2-next.0
  - @backstage/config@1.0.7
  - @backstage/plugin-events-node@0.2.6-next.0

## 0.1.6

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.5.1
  - @backstage/config@1.0.7
  - @backstage/plugin-events-node@0.2.5

## 0.1.6-next.2

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.5.1-next.2
  - @backstage/config@1.0.7
  - @backstage/plugin-events-node@0.2.5-next.2

## 0.1.6-next.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.5.1-next.1
  - @backstage/config@1.0.7
  - @backstage/plugin-events-node@0.2.5-next.1

## 0.1.6-next.0

### Patch Changes

- Updated dependencies
  - @backstage/config@1.0.7
  - @backstage/backend-plugin-api@0.5.1-next.0
  - @backstage/plugin-events-node@0.2.5-next.0

## 0.1.5

### Patch Changes

- a5de745ac17: Renamed `gitlabEventRouterEventsModule` to `eventsModuleGitlabEventRouter` and `gitlabWebhookEventsModule` to `eventsModuleGitlabWebhook` to match the [recommended naming patterns](https://backstage.io/docs/backend-system/architecture/naming-patterns).
- 928a12a9b3e: Internal refactor of `/alpha` exports.
- Updated dependencies
  - @backstage/backend-plugin-api@0.5.0
  - @backstage/plugin-events-node@0.2.4
  - @backstage/config@1.0.7

## 0.1.5-next.2

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.4.1-next.2
  - @backstage/plugin-events-node@0.2.4-next.2
  - @backstage/config@1.0.7-next.0

## 0.1.5-next.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.4.1-next.1
  - @backstage/config@1.0.7-next.0
  - @backstage/plugin-events-node@0.2.4-next.1

## 0.1.5-next.0

### Patch Changes

- 928a12a9b3: Internal refactor of `/alpha` exports.
- Updated dependencies
  - @backstage/backend-plugin-api@0.4.1-next.0
  - @backstage/plugin-events-node@0.2.4-next.0
  - @backstage/config@1.0.6

## 0.1.4

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.4.0
  - @backstage/plugin-events-node@0.2.3
  - @backstage/config@1.0.6

## 0.1.4-next.2

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.4.0-next.2
  - @backstage/plugin-events-node@0.2.3-next.2
  - @backstage/config@1.0.6

## 0.1.4-next.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.3.2-next.1
  - @backstage/config@1.0.6
  - @backstage/plugin-events-node@0.2.3-next.1

## 0.1.4-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.3.2-next.0
  - @backstage/plugin-events-node@0.2.3-next.0

## 0.1.2

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.3.0
  - @backstage/config@1.0.6
  - @backstage/plugin-events-node@0.2.1

## 0.1.2-next.1

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.3.0-next.1
  - @backstage/plugin-events-node@0.2.1-next.1
  - @backstage/config@1.0.6-next.0

## 0.1.2-next.0

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.2.1-next.0
  - @backstage/config@1.0.6-next.0
  - @backstage/plugin-events-node@0.2.1-next.0

## 0.1.1

### Patch Changes

- 884d749b14: Refactored to use `coreServices` from `@backstage/backend-plugin-api`.
- 31fe8f256a: Add `createGitlabTokenValidator(config)` which can be used
  to create a validator used at an ingress for topic `gitlab`.

  On top, there is a new `gitlabWebhookEventsModule` for the new backend plugin API
  which auto-registers the `HttpPostIngress` for topic `gitlab` incl. the validator.

  Please find more information at
  https://github.com/backstage/backstage/tree/master/plugins/events-backend-module-gitlab/README.md.

- Updated dependencies
  - @backstage/backend-plugin-api@0.2.0
  - @backstage/plugin-events-node@0.2.0
  - @backstage/config@1.0.5

## 0.1.1-next.3

### Patch Changes

- Updated dependencies
  - @backstage/backend-plugin-api@0.2.0-next.3
  - @backstage/config@1.0.5-next.1
  - @backstage/plugin-events-node@0.2.0-next.3

## 0.1.1-next.2

### Patch Changes

- 884d749b14: Refactored to use `coreServices` from `@backstage/backend-plugin-api`.
- Updated dependencies
  - @backstage/backend-plugin-api@0.2.0-next.2
  - @backstage/config@1.0.5-next.1
  - @backstage/plugin-events-node@0.2.0-next.2

## 0.1.1-next.1

### Patch Changes

- 31fe8f256a: Add `createGitlabTokenValidator(config)` which can be used
  to create a validator used at an ingress for topic `gitlab`.

  On top, there is a new `gitlabWebhookEventsModule` for the new backend plugin API
  which auto-registers the `HttpPostIngress` for topic `gitlab` incl. the validator.

  Please find more information at
  https://github.com/backstage/backstage/tree/master/plugins/events-backend-module-gitlab/README.md.

- Updated dependencies
  - @backstage/backend-plugin-api@0.1.5-next.1
  - @backstage/config@1.0.5-next.1
  - @backstage/plugin-events-node@0.2.0-next.1

## 0.1.1-next.0

### Patch Changes

- Updated dependencies
  - @backstage/plugin-events-node@0.2.0-next.0
  - @backstage/backend-plugin-api@0.1.5-next.0

## 0.1.0

### Minor Changes

- 63f7983398: Adds a new module `gitlab` to plugin-events-backend.

  The module adds a new event router `GitlabEventRouter`.

  The event router will re-publish events received at topic `gitlab`
  under a more specific topic depending on their `$.event_name` value
  (e.g., `gitlab.push`).

  Please find more information at
  https://github.com/backstage/backstage/tree/master/plugins/events-backend-module-gitlab/README.md.

### Patch Changes

- Updated dependencies
  - @backstage/plugin-events-node@0.1.0
  - @backstage/backend-plugin-api@0.1.4
