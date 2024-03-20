---
title: Updates and Migrations
# description: todo
displayed_sidebar: devDocsSidebar
pagination_prev: dev-docs/plugins
---

import InstallCommand from '/docs/snippets/install-npm-yarn.md'
import BuildCommand from '/docs/snippets/build-npm-yarn.md'
import DevelopCommand from '/docs/snippets/develop-npm-yarn.md'

# Upgrades

Strapi periodically releases code improvements through new versions. New Strapi versions are announced in both the terminal and in the administration panel, and [GitHub release notes](https://github.com/strapi/strapi/releases) list what is new with each new version.

The [upgrade tool](/dev-docs/upgrade-tool) documentation should help migrating to a new Strapi version.

:::danger
It is currently strongly advised that you refrain from migrating from Strapi v4 to Strapi 5, especially in a production environment.

The beta version of Strapi 5 is not meant to be used in production yet.
:::
<!-- <CustomDocCardsWrapper>
<CustomDocCard emoji="⟳" title="Updates guide" description="Read a generic update guide. Useful when there is no breaking change." link="/dev-docs/update-version" />
<CustomDocCard emoji="🤖" title="Upgrade tool" description="Learn how to use Strapi's CLI upgrade tool to automatically handle updates & migrations." link="/dev-docs/upgrade-tool" />
<CustomDocCard emoji="⬆️" title="v5.x migration guides" description="Read specific guides to handle breaking changes while migrating from Strapi v5.x to Strapi v5.y." link="/dev-docs/migration-guides" />
<CustomDocCard emoji="⤴️" title="v4 to v5 migration guides" description="Read specific guides to handle breaking changes while migrating from Strapi v4 to Strapi v5." link="/dev-docs/migration/v4-to-v5/introduction" />
</CustomDocCardsWrapper> -->