# Youness Aamiri

Software engineer from Morocco 🇲🇦. I build .NET systems where correctness and performance are requirements, not afterthoughts.

**[Projects](https://younessaamiri.dev/projects)** · **[Blog](https://younessaamiri.dev/posts)** · **[DEV](https://dev.to/younessaamiri)** · **[LinkedIn](https://linkedin.com/in/youness-aamiri)** · **[Email](mailto:youness.aamiri@pm.me)**

---

## Bijecta

`Bijecta` is the namespace for my developer tooling.

```bash
dotnet tool install --global Bijecta.BenchmarkGate.Tool
```

A bijection is a perfect one-to-one correspondence, with nothing left over. That is the standard I hold the code to: inputs map to outputs predictably, and nothing is lost along the way.

### [Bijecta.BenchmarkGate](https://github.com/Bijecta/BenchmarkGate)

A local-first performance regression gate for BenchmarkDotNet. It compares benchmark results against baselines and policies committed to your repo as plain JSON, and fails the build when performance regresses. No SaaS and no hosted database, and it runs the same locally and in CI.

*Alpha (v0.4.0) · Apache-2.0 · .NET*

---

## More projects

Engines for regulated domains, where a wrong number is a real problem. Both are being renamed.

### [CedarRecon](https://github.com/AamiriYouness/CedarRecon)

A financial reconciliation engine built like an analytical query engine: columnar execution, a cost-based planner, the ReconQL matching DSL, and an eight-phase classification cascade. Every performance number is reproducible from the committed benchmarks, including the optimizations that didn't work. Classification runs **2.1x faster** than the dictionary baseline (1,368 ms to 646 ms per million transactions).

*Active development · .NET 10 · Apache-2.0*

### [CedarRisk](https://github.com/AamiriYouness/CedarRisk)

An auto insurance premium rating engine for the Moroccan market. It calculates the full premium (RC, optional guarantees, trailers, and the whole fiscal chain) with Clean Architecture, DDD, CQRS, and Result-pattern error handling instead of exceptions.

*Active · .NET 10 · PostgreSQL*

---

## How I work

- **Measured.** Performance numbers come from benchmarks anyone can rerun.
- **Simple to reason about.** If it takes a meeting to explain, it's too complicated.
- **Trustworthy.** Finance and insurance don't forgive silent errors, so the code makes them loud.
- **Built to evolve.** Clean boundaries over rewrites.

## Writing

I write about architecture, .NET, performance, and the realities of financial and insurance software.

- [younessaamiri.dev/posts](https://younessaamiri.dev/posts)
- [dev.to/younessaamiri](https://dev.to/younessaamiri)

---

If you work on developer tooling, finance, or insurance systems, or just like talking engineering, [get in touch](mailto:youness.aamiri@pm.me).
