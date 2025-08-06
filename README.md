# AI Development Prompts & Rules Library

<p align="center">
  <a href="https://www.npmjs.com/package/prompts" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/prompts.svg">
  </a>
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

> A comprehensive collection of AI prompts, development rules, and best practices for modern software development with AI coding assistants.

## 📚 Overview

This repository serves as a curated library of prompts, rules, and instructions for enhancing AI-assisted development workflows. It includes framework-specific guidelines, AI safety best practices, and project configuration templates for various technology stacks.

## 📁 Repository Structure

```
prompts/
├── .windsurf/rules/           # Framework-specific development rules
├── .github/                   # GitHub-specific configurations
│   ├── instructions/          # AI safety and prompt engineering guides
│   └── chatmodes/             # AI chat mode configurations
├── claude/                    # Claude AI specific prompts
├── universal-app/             # Universal app development templates
└── README.md                  # This file
```

## 🛠️ Development Rules

### Framework-Specific Guidelines

Comprehensive development rules and best practices for different technology stacks:

#### **[Angular Fullstack](.windsurf/rules/angular_fullstack_rules.md)**
- Angular frontend standards with TypeScript
- State management with NgRx
- HTTP & API integration patterns
- Backend architecture best practices
- Security implementation guidelines
- Testing strategies (unit, integration, E2E)
- Performance optimization techniques

#### **[React/Next.js](.windsurf/rules/react_nextjs_rules.md)**
- React/Next.js modern development patterns
- State management with Zustand/Redux Toolkit
- API integration with React Query/TanStack Query
- Server components and data fetching strategies
- Authentication & authorization flows
- Styling with Tailwind CSS and CSS-in-JS

#### **[Data Science](.windsurf/rules/data_science_rules.md)**
- Python environment setup and management
- Data processing & analysis pipelines
- Machine learning with Scikit-learn
- Deep learning with TensorFlow/PyTorch
- Model evaluation and validation
- Project structure and reproducibility

#### **[Monorepo with Tamagui](.windsurf/rules/monorepo-tamagui.md)**
- Monorepo management with Turbo
- Cross-platform UI with Tamagui (React Native + Web)
- State management with Zustand
- Data fetching with TanStack Query
- Internationalization (i18n) setup
- Stripe payment integration

## 🎯 AI Safety & Prompt Engineering

### **[AI Prompt Engineering & Safety Best Practices](.github/instructions/ai-prompt-engineering-safety-best-practices.instructions.md)**
A comprehensive guide covering:
- Prompt engineering fundamentals
- Clarity, context, and constraints in prompts
- Safety frameworks and bias mitigation
- Responsible AI usage guidelines
- Security considerations for AI systems
- Testing and validation methodologies
- Documentation standards

### **[GPT 4.1 Beast Mode](.github/chatmodes/4.1-Beast.chatmode.md)**
Advanced chat mode configuration for autonomous problem-solving:
- Agent-based approach for complex tasks
- Internet research integration
- Step-by-step workflow automation
- Comprehensive testing and validation

## 📋 Project Templates

### **[Universal App Configuration](universal-app/)**

#### **[CLAUDE.md](universal-app/CLAUDE.md)**
Claude Code specific configuration for monorepo projects:
- Development command reference
- Build and deployment scripts
- Testing and quality assurance commands
- Database management (Supabase)
- Storybook integration
- Code generation utilities

#### **[Project Instructions](universal-app/project_instructions.md)**
Comprehensive development guidelines featuring:
- TypeScript best practices
- React/React Native patterns
- Cross-platform development with Expo and Next.js
- Tamagui UI system integration
- State management with Zustand
- Data fetching with TanStack Query
- Internationalization setup
- Stripe payment processing
- Performance optimization techniques
- Error handling and validation patterns

### **[Claude Prompts](claude/)**

#### **[Create Prompt Template](claude/create_prompt.md)**
Template for creating structured prompts for LLM interactions.

## 🚀 Usage

These rules and prompts are designed to be used with AI coding assistants:

### Integration with AI Tools

1. **Cursor/Windsurf**: Place rules in `.windsurf/rules/` directory
2. **GitHub Copilot**: Use `.github/instructions/` for workspace instructions
3. **Claude**: Reference `CLAUDE.md` files for project-specific guidance
4. **Custom AI Tools**: Adapt templates to your specific workflow

### Getting Started

1. Clone this repository
2. Copy relevant rule files to your project
3. Customize rules based on your tech stack
4. Configure your AI assistant to use these rules

### Best Practices

- Keep rules updated with latest framework versions
- Customize guidelines for your team's coding standards
- Regularly review and refine prompts based on output quality
- Document project-specific modifications

## 🔧 Customization

Each rule file can be customized to match your specific needs:

1. **Technology Stack**: Modify framework versions and libraries
2. **Coding Standards**: Adjust style guides and conventions
3. **Testing Requirements**: Set coverage thresholds and testing strategies
4. **Performance Metrics**: Define specific performance targets
5. **Security Policies**: Implement organization-specific security requirements

## 👨‍💻 Author

**Sai Naveen Nimmagadda**

- 🌐 Website: [s11a.com](https://s11a.com)
- 💻 GitHub: [@funsaized](https://github.com/funsaized)

## 🤝 Contributing

Contributions, issues and feature requests are welcome! 

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-prompt`)
3. Commit your changes (`git commit -m 'Add amazing prompt'`)
4. Push to the branch (`git push origin feature/amazing-prompt`)
5. Open a Pull Request

### Contribution Guidelines

- Follow existing file structure and naming conventions
- Include examples in your prompts/rules
- Test prompts with multiple AI assistants when possible
- Document any specific requirements or dependencies

## 📝 License

This project is [MIT](LICENSE) licensed.

## 🌟 Show your support

Give a ⭐️ if this project helped you!

---

*This repository is actively maintained and regularly updated with new prompts and best practices for AI-assisted development.*