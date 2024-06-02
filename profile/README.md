<img  align="left" src="kresil-logo.png" alt="Kresil" width="150"> 

### Kresil - Kotlin Resilience

[Kresil](https://github.com/kresil/kresil) is a [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html) library for fault-tolerance,
inspired by [Resilience4j](https://resilience4j.readme.io/docs/getting-started) for Java and [Polly](https://github.com/App-vNext/Polly) for .NET.

The library provides ways to enhance operations with resilience mechanisms in a functional way, using higher-order functions (decorators).

### Mechanisms

Some of the intended resilience mechanisms are:

- **Retry**: Repeats failed executions;
- **Circuit Breaker**: Temporarily blocks possible failures;
- **Rate Limiter**: Limits executions per period;
- **Time Limiter**: Limits duration of execution;
- **Bulkhead**: Limits concurrent executions;
- **Cache**: Memorizes a successful result;
- **Fallback**: Defines an alternative value to be returned on failure.

Additionally, Kresil offers extensions for [Ktor](https://ktor.io/) as plugins.

### Repositories

- [Kresil](https://github.com/kresil/kresil): Contains the main development of the library, including the Ktor plugins;
- [Experiments](https://github.com/kresil/kresil): Contains experiments exploring the Kotlin Multiplatform development, the Ktor framework and the Resilience4j library;
- [PS](https://github.com/kresil/ps): Outlines the founding proposal and technical documentation of the project