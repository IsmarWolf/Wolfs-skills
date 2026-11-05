# Wolfs-skills

A collection of Claude skills by [IsmarWolf](https://github.com/IsmarWolf). Each set of skills lives in its own repository, with its own tests and benchmarks. This repo is the index: it links to every set and lets you install them all from one place.

![license](https://img.shields.io/badge/license-MIT-green) ![claude code](https://img.shields.io/badge/Claude%20Code-marketplace-orange)

## Collections

| Collection | What is inside | Repo |
|---|---|---|
| **Wolfs-token-toolkit** | Build, compress and A/B-test prompts to spend fewer tokens on Claude. Benchmarked against Caveman and Ponytail. | [IsmarWolf/Wolfs-token-toolkit](https://github.com/IsmarWolf/Wolfs-token-toolkit) |

More collections will be added here as they are released.

<a href="https://github.com/IsmarWolf/Wolfs-token-toolkit">
  <img src="https://raw.githubusercontent.com/IsmarWolf/Wolfs-token-toolkit/main/docs/charts/1-cost-per-case.png" alt="Cost per message by tool, from the Wolfs-token-toolkit benchmark" width="100%">
</a>

*From the [Wolfs-token-toolkit benchmark](https://github.com/IsmarWolf/Wolfs-token-toolkit#results): weighted cost per message, lower is cheaper.*

## Install

Add this repo once as a marketplace, then install the collections you want:

```
/plugin marketplace add IsmarWolf/Wolfs-skills
/plugin install wolfs-token-toolkit@wolfs-skills
```

Each collection is also a standalone plugin, so you can install it directly from its own repo; see that repo's README.

## How this repo is organized

- `.claude-plugin/marketplace.json` lists every collection and points to its repository.
- Each collection repo holds the skills (`skills/<name>/SKILL.md`), their tests, and any benchmarks.
- Adding a collection means adding one entry to the marketplace file and one row to the table above.

## License

[MIT](LICENSE).
