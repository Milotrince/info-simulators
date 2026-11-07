# Physics Simulators

A comparison of physics engines and simulation platforms for robotics, robot learning, and games.
This is the data behind the tables in
[The Wonderful World of Physics Simulators and How to Choose One](https://trinityjchung.com/words/the-wonderful-world-of-physics-simulators-and-how-to-choose-one/).

| File | What's in it |
| --- | --- |
| [`engines.yaml`](engines.yaml) | Physics engines: core physics providers (MuJoCo, PhysX, Bullet, ...) |
| [`platforms.yaml`](platforms.yaml) | Simulation platforms: an engine plus tooling and ecosystem (Isaac Sim, Gazebo, Unity, ...) |
| [`glossary.yaml`](glossary.yaml) | What the acronyms in the other two files mean |

## Contributing

Found a mistake, or a simulator that's missing? Open an issue or a pull request.

- Each file starts with `fields`, which sets the table's rows and their labels.
  Every entry should have a value for each field.
- Entries appear in the order they're listed. Engines are sorted by release year.
- Values can use inline markdown links, `[MJX](https://...)`, and `~~strikethrough~~`.
- If you use a new acronym, add it to `glossary.yaml`.
- Please link a source (docs, paper, code) in your PR for anything that isn't obvious.
