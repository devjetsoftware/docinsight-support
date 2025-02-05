# DocInsight 2025 Roadmap

> [!NOTE] Disclaimer
> This roadmap is for informational purposes only and is subject to change without notice. It does not constitute a commitment to deliver any specific features within a given timeframe.

## Modernization

### New Responsive and Theme-Aware Template

Introduce a modern and adaptable template that seamlessly aligns with different UI themes.

### Instant Search in HTML Output

Provide real-time filtering and search to quickly locate relevant documentation.

### Support Delphi IDE Theming

Ensure extension and documentation styling remains consistent with Delphi IDE themes (Light/Dark).

### New WebView2-Based Doc Editor

Retire IE based doc editor. Enhance editing stability and performance using the latest web technologies.

### Stay Current with the Latest Delphi Releases

Maintain compatibility and leverage new features from upcoming Delphi versions.

## Help Authoring

### Markdown-Based Authoring

Create concise, developer-friendly documentation using a lightweight markup language that’s easy to write, review, and version-control.

- Link to API elements in Markdown files.
- Link to topics in XML doc comments (`<see xref="topicId"/>`).

### New DocInsight Manifest

Centralize DocInsight project settings, metadata, and resources in a structured manifest (_json_ or _toml_).

## Cross-Platform CLI

- Windows
- macOS
- Linux

## CI/CD

### GitHub Actions

Streamline builds, checks, and deployments with automated workflows.

## Output Formats

### Markdown Output

Export API documentation to external Markdown files to simplify integration with static site generators and other help authoring software.

### PDF Output

Generate high-quality PDF documents for offline distribution.

## Exploration

### AI Assistance

Investigate automated documentation generation and more AI-driven features.

### RESTful API Documentation (Swagger/OpenAPI)

Examine extended support for web services and API documentation.

### Self-Contained CHM Generation

Generate CHM output in a cross-platform manner without depending on _HTML Help Workshop_ or requiring Windows.
