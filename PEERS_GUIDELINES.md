# Translated Content Peer Guidelines

## Policies for community maintenance teams

### Reviewing and issue queue

It is the responsibility of the active community maintenance team for each active locale to keep up-to-date with reviews of pull requests and handling issues filed against that locale. You can filter the relevant pull requests and issues for each locale using the relevant label — `l10n-fr`, `l10n-ja`, `l10n-ko` , `l10n-pt-br`, `l10n-ru`, `l10n-zh` and `l10n-es`.

### Requirements for keeping locales up-to-date

Active community maintenance teams are expected to keep their locales maintained and reasonably up-to-date. This means:

- Reviewing and actioning all pull requests within 2 weeks.
- Triaging and fixing all actionable issues within 1 month.
- Making reasonable progress on keeping MDN's Tier 1 content (definition TBD) synchronized with the `en-US` versions. This means some progress should be made each week, e.g. updating an article to be in sync with the English version, removing or fixing a bad quality article…

If no progress is made on a locale in these areas within 1 month, the locale will be considered inactive, and edits will stop being accepted.

### Review teams

The review teams for each locale are:

- Brazilian Portuguese (`pt-BR`) content — the [pt-br-content](https://github.com/orgs/Unity-Billal-mesloub/teams/pt-br-content) team, which consists of:
  - [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub)
- French (`fr`) content — the [fr-content](https://github.com/orgs/Unity-Billal-mesloub/teams/fr-content) team, which consists of:
  - [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub)
- Japanese (`ja`) content — the [ja-content](https://github.com/orgs/Unity-Billal-mesloub/teams/ja-content) team, which consists of:
  - [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub)
- Korea (`ko`) content — the [ko-content](https://github.com/orgs/Unity-Billal-mesloub/teams/ko-content) team, which consists of:
  - [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub)
- Russian (`ru`) content — the [ru-content](https://github.com/orgs/Unity-Billal-mesloub/teams/ru-content) team, which consists of:
  - [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub)
- Chinese (`zh-CN` and `zh-TW`) content — the [zh-content](https://github.com/orgs/Unity-Billal-mesloub/teams/zh-content) team, which consists of:
  - [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub)
- Spanish (`es`) content - the [es-content](https://github.com/orgs/Unity-Billal-mesloub/teams/es-content) team, which consists of:
  - [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub)
---

## Synchronization with the en-US document structure

Periodically we synchronize all the localized document tree structures with the `en-US` tree structure (English slugs only), to make the documentation easier to manage. When documents are removed from `en-US` it results in `orphaned` and `conflicting` documents within a sub-directory of each locale folder.

Active locale maintenance teams are invited to spend some time exploring the orphaned and conflicting documents, to see whether any of this work is worth keeping (either adding to, or merging with an existing document in, the main tree), or whether it can just be deleted.

When a synchronization occurs maintenance teams are given two weeks to decide what to do with the affected documents in their locales to keep things in sync.

See [the guide about orphaned and conflicting pages](./docs/orphaned_and_conflicting.md) for more details about how to deal with such pages.

---

## Get in touch

If you want to ask questions or talk to us about forming a new community maintenance team, see [ask for help][].

### Code of Conduct

Everyone participating in this project is expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

### License

When contributing to the content you agree to license your contributions according to [our license](LICENSE.md).

[ask for help]: https://developer.mozilla.org/docs/MDN/Community/Communication_channels
