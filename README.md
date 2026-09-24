# ask-jevs

ask-jevs is a JavaScript package that calls [Jev](https://openrouter.ai/docs/guides/community/jev) through OpenRouter. Jev is TypeSafe's decision model. You send it application state and typed questions. It returns typed answers with probabilities, not generated text.

A call tries the free endpoint first. If that call does not succeed, the package sends the same request with a configured OpenRouter API key.

The package has no dependencies and no build step. It exports functions, written in vanilla JavaScript, so you can import it from any runtime that loads a package from npm.
