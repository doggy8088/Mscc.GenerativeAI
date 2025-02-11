# Changelog (Release Notes)

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) (SemVer).

## [Unreleased]

### Added

- Feature suggestion: Retry mechanism ([#2](https://github.com/mscraftsman/generative-ai/issues/2))
- Feature suggestion: Add logs with LogLevel using the Standard logging in .NET ([#6](https://github.com/mscraftsman/generative-ai/issues/6))
- implement Automatic Function Call (AFC)

### Changed
### Fixed

## 0.9.2

### Added

- models of Gemini 1.5 and Gemini 1.0 Ultra
- tests for Gemini 1.5 and Gemini 1.0 Ultra

## 0.9.1

### Added

- add interface IGenerativeAI
- simplify image/media handling in requests
- extend generateAnswer feature
- more tests for Gemini Pro Vision model
- add exceptions from API reference

### Changed

- improve creation of generative model in Google AI class
- SafetySettings can be easier and less error-prone. ([#8](https://github.com/mscraftsman/generative-ai/issues/8))
- remove _useHeaderApiKey ([#10](https://github.com/mscraftsman/generative-ai/issues/10]))

## 0.9.0

### Added

- compatibility methods for PaLM models

### Changed
### Fixed

## 0.8.4

### Added

- missing comments and better explanations
- add GoogleAI type ([#3](https://github.com/mscraftsman/generative-ai/issues/3))
- read environment variables in GoogleAI and VertexAI

## 0.8.3

### Added

- simplify creation of tuned model

### Fixed

- check of model for Tuning, Answering and Embedding

## 0.8.2

### Added
 
- ability to rewind chat history
- access text of content response easier

### Changed

- improve handling of chat history (streaming)

## 0.8.1

### Changed

- access modifier to avoid ambiguous type reference (ClientSecrets)

## 0.8.0

### Added

- implement tuned model patching (.NET 6 and higher only)
- implement transfer of ownership of tuned model
- implement batched Embeddings
- query string parameters to list models (pagination and filter support)
- type documentation
- generate a grounded answer
- constants for method names/endpoints
- enumeration of state of created tuned model

### Changed

- text prompts have `user` role assigned
- improve Embeddings
- refactor types according to API reference 
- extend type documentation
- improve .NET targetting of source code

## 0.7.2

### Added

- delete tuned model

### Changed

- method to list models supports both - regular and tuned - model types

## 0.7.1

### Added

- implement model tuning (works with stable models only)
  - text-bison-001
  - gemini-1.0-pro-001
- tests for model tuning
 
### Changed

- improved authentication regarding API key or OAuth/ADC
- added scope https://www.googleapis.com/auth/generative-language.tuning
- harmonized version among NuGet packages
- provide empty response on Safety stop
- merged regular and tuned ModelResponse

## 0.7.0

### Added

- use Environment Variables for default values (parameterless constructor)
- support of .env file

### Changed

- improve Function Calling
- improve Chat streaming
- improve Embeddings

## 0.6.1

### Added

- implement Function Calling

## 0.6.0

### Added

- implement streaming of content
- support of HTTP/3 protocol
- specify JSON order of properties

### Changed

- improve handling of config and settings

## 0.5.4

### Added

- implement Embeddings
- brief sanity check on model selection

### Changed

- refactor handling of parts
- ⛳ allow configuration, safety settings and tools for Chat

## 0.5.3

### Added

- Implement Chat

## 0.5.2

### Added

- Use of enumerations

### Changed

- Correct JSON conversion of SafetySettings

## 0.5.1

### Added

- Handle GenerationConfig, SafetySeetings and Tools

### Changed

- Append streamGenerateContent

## 0.5.0

### Added

- Add NuGet package Mscc.GenerativeAI.Web for use with ASP.NET Core.

### Changed

- Refactor folder structure

## 0.4.5

### Changed

- Extend methods

## 0.4.4

### Added

- Automate package build process

## 0.4.3

### Added

- Add x-goog-api-key header

## 0.4.2

### Changed

- Minor correction

## 0.4.1

### Added

- Add OAuth to Google AI

## 0.3.2

### Changed

- Improve package attributes

## 0.3.1

### Added

- Add methods ListModels and GetModel

## 0.2.1

### Added

- Initial Release

## 0.1.2

### Changed

- Update README.md
