# AI Configuration and Rules repository

This repository contains AI prompts, rules, and configuration files to exchange solely inside the Kepler Team Company.

## Contents

- [AI Configuration and Rules repository](#ai-configuration-and-rules-repository)
  - [Contents](#contents)
  - [Directory Structure](#directory-structure)
  - [Documentation Standards](#documentation-standards)
    - [User Documentation Files](#user-documentation-files)
    - [Guidelines for User Documentation](#guidelines-for-user-documentation)

## Directory Structure

```text
├── README.md                    # This file - project overview
prompts/
├── {username}_prompt_name.md    # AI prompt template to use for some task
cursor_rules                     # Cursor IDE specific configurations
├── {username}.cursorrules       # Main Cursor IDE rules file
└── {username}_cursor_config.md  # User-specific Cursor rules description
windsurf_rules  
├── {username}.windsurfrules        # Main Windsurf rules file
└── {username}_windsurf_config.md   # User-specific Windsurf rules description
other
```

### Directory Descriptions

- **`cursor_rules/`** - Cursor IDE rules and configurations
- **`windsurf_rules/`** - Windsurf editor rules and configurations  
- **`prompts/`** - AI prompt templates organized by category
- **`other/`** - Other configurations and best practices which do not fit into the other directories

## Documentation Standards

### User Documentation Files

Each project should contain documentation files following this naming convention:

```text
{username}_{short_description}.md
```

**Examples:**

- `sergey_deployment_guide.md` - Deployment instructions added by Sergey
- `alexander_api_integration.md` - API integration notes by Alexander
- `marat_troubleshooting.md` - Troubleshooting guide by Marat

### Guidelines for User Documentation

1. **Username**: Use the first name from the team member's email (e.g.,
   `sergey` from `sergey.ponomarenko@kepler.team`)
2. **Short Description**: Use underscores and keep it concise (2-4 words)
3. **Content**: Include practical information like setup guides,
   troubleshooting steps, or implementation notes
4. **Location**: Place the file in the root of the relevant project directory
