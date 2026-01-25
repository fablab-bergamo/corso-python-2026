# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is an educational Python course repository for "Python in Pratica" (Python in Practice) organized by FabLab Bergamo in 2026. It contains teaching materials for a 4-lesson beginner Python course focused on practical applications and real-world projects.

## Repository Structure

The repository follows a lesson-based organization:

- **Jupyter Notebooks**: `Python_Lezione[1-3].ipynb` - Interactive lessons with code examples and exercises
- **Slide Materials**: `Slides-Lezione[1-3].pdf` - Presentation materials for each lesson
- **Documentation**: `README.md` - Course overview and instructions in Italian

## Course Architecture and Progression

### Educational Philosophy
The course follows Python's "Zen" philosophy emphasizing readability, simplicity, and practical application. The pedagogical approach progresses from basic concepts to real-world libraries and applications.

### Lesson Structure and Dependencies
1. **Lezione 1** (Fundamentals): Python basics, variables, data types, control structures, lists, dictionaries
2. **Lezione 2** (Libraries & Web): Functions, external libraries (requests, Pillow, trimesh), API interactions
3. **Lezione 3** (Data Analysis): Advanced data manipulation with Pandas, visualization with Matplotlib
4. **Lezione 4** (Planned): Large Language Models and AI APIs

### Key Teaching Patterns
- **Conceptual Bridging**: Each lesson connects new concepts to previously learned material (e.g., dictionaries → Pandas DataFrames)
- **Hands-on Examples**: Real-world APIs (weather, cat images), practical exercises
- **Italian Language**: All content, comments, and examples are in Italian for Italian learners
- **Google Colab Focus**: Materials designed for browser-based Python environment

## Development Guidelines

### Working with Notebook Content
- When modifying notebooks, preserve the educational flow and Italian language
- Maintain the progression from simple concepts to complex applications
- Keep examples practical and relatable (weather data, student grades, etc.)
- Preserve the connection between mathematical concepts and Python implementation

### Library Dependencies
The course introduces libraries progressively:
- **Core Python**: Built-in functions and data structures
- **External Libraries**: requests, Pillow, pandas, matplotlib, trimesh
- **Installation Pattern**: Uses `!pip install` commands within notebooks for Colab compatibility

### Code Style
- **Beginner-Friendly**: Simple, readable code with extensive comments in Italian
- **Practical Examples**: Real-world scenarios (rubrica telefonica, voti scolastici)
- **Interactive**: Designed for step-by-step execution in notebook environments
- **No Advanced Patterns**: Avoids complex Python features to maintain accessibility

### Documentation Standards
- All documentation should be in Italian
- Course materials should include practical exercises and real-world examples
- Links to Google Colab should be maintained for easy student access
- External resources and API endpoints should be verified for functionality

## Common Development Tasks

### Adding New Content
When adding new lessons or modifying existing ones:
1. Follow the established naming pattern: `Python_Lezione[N].ipynb`
2. Include corresponding slide materials: `Slides-Lezione[N].pdf`
3. Update README.md with new content descriptions
4. Ensure Google Colab compatibility with proper pip install commands

### Maintaining External Dependencies
- Verify API endpoints remain functional (weather API, cat image API)
- Update library versions if compatibility issues arise
- Test notebook execution in Google Colab environment
- Maintain working download links for CSV example files

### Content Localization
All materials are designed for Italian learners:
- Variable names in Italian (e.g., `voti`, `studente`, `materia`)
- Comments and explanations in Italian
- Examples using Italian cultural context
- Error messages and output in Italian where possible

## Educational Context

This repository serves students with no prior programming experience. The teaching methodology emphasizes:
- **Immediate Practical Application**: Students create working programs from lesson 1
- **Conceptual Connections**: Links abstract programming concepts to familiar real-world scenarios
- **Progressive Complexity**: Each lesson builds naturally on previous knowledge
- **Interactive Learning**: Designed for live coding sessions and student experimentation

The course concludes with AI/LLM integration, preparing students for modern Python applications while maintaining focus on fundamental programming principles.