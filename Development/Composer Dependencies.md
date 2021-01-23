# Composer Dependencies

Composer is great! While in version <code>1.0.0</code>, WikiPeep composer dependencies are the following
```
    "jamesmoss/flywheel": "dev-master"
    "georgelemon/loopless-framework": "dev-main",
```

### Powered by Loopless Micro Framework
Loopless is a micro framework that is [available on GitHub](https://github.com/georgelemon/loopless), composer ready and comes packed with Symfony HttpFoundation, Illuminate Filesystem & Support package.

WikiPeep is developed on Loopless, and comes with some extra features, like Symfony Console that can build the contents via <code>terminal</code>, a Markdown parser (a built-in version of Parsedown), while **Flywheel** is used for storing the parsed contents in a flat file repository based on JSON.