# jQuery Agent Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Repo Size](https://img.shields.io/github/repo-size/btafoya/jquery-agent-skill)](https://github.com/btafoya/jquery-agent-skill)
[![GitHub Issues](https://img.shields.io/github/issues/btafoya/jquery-agent-skill)](https://github.com/btafoya/jquery-agent-skill/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/btafoya/jquery-agent-skill)](https://github.com/btafoya/jquery-agent-skill/pulls)
[![GitHub Language](https://img.shields.io/github/languages/top/btafoya/jquery-agent-skill)](https://github.com/btafoya/jquery-agent-skill)

> A comprehensive jQuery development assistant for all compatible AI tools

This skill augments AI coding assistants with expert jQuery knowledge for DOM manipulation, event handling, AJAX, animations, and plugin development. Compatible with any tool that supports the standard skill format.

## Features

- **Complete jQuery Reference** - Comprehensive documentation with code examples
- **DOM Manipulation** - Content getting/setting, element creation, and modification
- **Event Handling** - Binding, delegation, and event object utilities
- **AJAX/HTTP Requests** - Basic requests, shorthand methods, and configuration
- **Animations** - Built-in effects, custom animations, and animation control
- **Utilities** - Array/object helpers, string utilities, and type checking
- **Plugin Development** - Basic patterns and widget factory patterns
- **Best Practices** - Performance optimization and safety patterns
- **Common Patterns** - Form validation, infinite scroll, modals, and tabs
- **Migration Guide** - jQuery to vanilla JavaScript equivalents
- **Debugging Tips** - Troubleshooting jQuery code

## Installation

### Using the Skills CLI (Recommended)

The [Vercel Labs Skills CLI](https://github.com/vercel-labs/skills) provides an easy way to install and manage skills across compatible AI tools:

```bash
# Install to current project
npx skills add btafoya/jquery-agent-skill

# Install globally (available to all projects)
npx skills add -g btafoya/jquery-agent-skill

# List installed skills
npx skills list

# Update skills
npx skills update
```

The Skills CLI supports installing from GitHub repositories, GitLab URLs, any git URL, or local paths.

### Manual Installation

Place the `jquery.skill` file in your AI tool's skills/plugins directory. The skill will activate automatically when working with jQuery.

### Known Compatible Tools

- Claude Code
- Any tool supporting the standard skill format

Check your tool's documentation for the specific skills directory location.

## Usage

This skill activates automatically when you:

- Mention jQuery, `$`, or jQuery syntax patterns
- Work with DOM selectors like `$('#id')` or `$('.class')`
- Use event handlers like `.on()`, `.click()`, `.submit()`
- Make AJAX requests with `$.ajax()`, `$.get()`, `$.post()`
- Add animations like `.fadeIn()`, `.slideUp()`, `.animate()`
- Ask about jQuery plugins or extending `$.fn`
- Need to debug or refactor jQuery code
- Want to migrate jQuery to vanilla JavaScript

## Example

```
User: How do I fade out an element with jQuery?

Assistant: You can use the .fadeOut() method:

$('#myElement').fadeOut();           // Default speed
$('#myElement').fadeOut(500);        // 500ms duration
$('#myElement').fadeOut('slow');     // Preset speed

You can also chain callbacks:

$('#myElement').fadeOut(300, function() {
    console.log('Fade complete!');
});
```

## Topics Covered

- Selectors (ID, class, element, attribute, hierarchy, form)
- DOM Traversal and Manipulation
- Event Binding and Delegation
- AJAX Configuration and Global Events
- Custom Animations
- Deferred/Promise Patterns
- Plugin Development Patterns
- Performance Optimization
- Namespacing and Safety Patterns

## License

MIT License - see [LICENSE](LICENSE) for details.

## Resources

- [Official jQuery Documentation](https://api.jquery.com/)
- [jQuery Download](https://jquery.com/download/)
- [Browser Support](https://jquery.com/browser-support/)