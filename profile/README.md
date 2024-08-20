<img  align="left" src="kresil-logo.png" alt="Kresil" width="150"> 

### Kresil

[Kresil](https://github.com/kresil/kresil) is a [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html) library for fault-tolerance,
inspired by [Resilience4j](https://resilience4j.readme.io/docs/getting-started) for Java and [Polly](https://github.com/App-vNext/Polly) for .NET. The library offers methods to enhance operations with resilience mechanisms in a functional style, using higher-order functions (decorators) while providing a concise API.
Additionally, Kresil offers extensions for [Ktor](https://ktor.io/) as plugins.

### Resilience Mechanisms ⚙️

Some of the intended resilience mechanisms are:
- 🔄 **Retry**: Repeats failed executions;
- ⛔ **Circuit Breaker**: Temporarily blocks possible failures;
- ⏳ **Rate Limiter**: Limits executions per period;
- ⏱️ **Time Limiter**: Limits duration of execution;
- 🚧 **Bulkhead**: Limits concurrent executions;
- 💾 **Cache**: Memorizes a successful result;
- 🛟 **Fallback**: Defines an alternative value to be returned or action to be executed on failure.

### Resilience Types 🔖

The resilience mechanisms can be divided in two categories, based on where they execute:
- ⚡**Reactive**: Mitigates impact from failures (after);
- 🛡️**Proactive**: Prevents failures from happening (before).

> [!NOTE]  
> This project began as a BSc degree thesis and is supported by detailed academic documentation. The project's design and implementation were guided by extensive research and formal proposals. You can explore the [report](https://github.com/kresil/project-documentation/blob/main/project-report/out/main.pdf) or browse all related documents [here](https://github.com/kresil/project-documentation?tab=readme-ov-file#documents).

