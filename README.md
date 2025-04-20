# SAGE: Structured AI Guided Epistemology

Welcome to **SAGE**! SAGE is a framework designed to structure knowledge for both humans and AI through a set of modular scrolls. It supports both natural language and logic-based learning, and is ideal for creating AI-human collaborative knowledge systems. This guide will show you how to create, modify, and use **SAGE scrolls** effectively.

## Table of Contents

- [Introduction](#introduction)
- [Core Concepts](#core-concepts)
- [SAGE Structure](#sage-structure)
- [Creating a SAGE Scroll](#creating-a-sage-scroll)
- [Using SAGE with AI](#using-sage-with-ai)
- [Advanced Features](#advanced-features)
- [Best Practices](#best-practices)

## Introduction

SAGE stands for **Structured AI Guided Epistemology**. It’s a dynamic framework for organizing and sharing knowledge between AI and humans. SAGE scrolls are modular units of knowledge, each containing specific categories (e.g., essence, mechanics, models) and sections (e.g., metadata, core concept, example). SAGE is designed to allow AI systems to learn while ensuring human comprehensibility.

## Core Concepts

Before you start creating your first scroll, here are a few core concepts:

- **Scrolls**: The fundamental unit of knowledge in SAGE, each scroll represents a topic or concept.
- **Categories**: Scrolls are divided into categories, each representing a different aspect of the subject.
- **Sections**: Detailed subdivisions within categories. Common sections include:
  - **Metadata**: Structural information about the scroll.
  - **Core Concept**: The main idea or principle of the category.
  - **Example**: Concrete examples to help explain the concept.
  - **Story**: A narrative that provides context to the concept.
  - **Logic Map**: A machine-readable structure that outlines the relationships between different parts of the concept.
  - **Prompt Template**: A prompt that guides AI responses based on the concept.
  
Each category and section serves a specific purpose to ensure the scroll is useful for both human readers and AI systems.

## SAGE Structure

### Scroll Components:
SAGE scrolls consist of a **Category** and **Sections**. Here’s a breakdown of each:


### **Categories**

Categories are broad divisions that encapsulate different aspects of a subject. Think of categories as the main themes or elements of knowledge. Each scroll can have multiple categories, each with specific focus areas.

1. **Essence**
   - **Purpose**: Defines the core identity of the concept or subject. It encapsulates what the subject is fundamentally about.
   - **Use**: Used for establishing the primary definition, attributes, or unique essence of the subject.
   - **Example**: In a scroll about "Electricity," the essence might define what electricity is, its fundamental properties, and its role in nature.

2. **Elements**
   - **Purpose**: Breaks the subject into fundamental building blocks or components.
   - **Use**: Identifies the key elements that make up the whole subject.
   - **Example**: In a scroll about "Electricity," elements would cover components like voltage, current, and resistance.

3. **Mechanics**
   - **Purpose**: Explains how the elements work together to form a functioning system.
   - **Use**: Describes the processes, dynamics, or principles that govern the functioning of the subject.
   - **Example**: In the case of "Electricity," the mechanics might describe Ohm's Law and how voltage, current, and resistance interact.

4. **Patterns**
   - **Purpose**: Identifies common occurrences, relationships, or behaviors within the subject.
   - **Use**: Describes trends, recurring features, or observable phenomena that occur in the subject area.
   - **Example**: In "Electricity," this could include patterns like how electric current behaves under varying resistances or voltages.

5. **Models**
   - **Purpose**: Provides theoretical or practical frameworks to explain or predict aspects of the subject.
   - **Use**: Provides formal representations or simulations that allow the user to understand the subject better or apply it to new situations.
   - **Example**: In "Electricity," models could include circuit diagrams or the mathematical models that describe electric circuits.

6. **Applications**
   - **Purpose**: Describes how the subject or its components are applied in real-world scenarios.
   - **Use**: Provides context to the practical uses of the subject, showing how it’s used in various fields or industries.
   - **Example**: In "Electricity," applications would cover areas like electronics, power generation, and telecommunications.

7. **Adaptability**
   - **Purpose**: Explores how the subject can be modified, evolved, or applied in various contexts over time.
   - **Use**: Describes how the subject can evolve or be modified to suit different environments, technologies, or future scenarios.
   - **Example**: In "Electricity," adaptability could include advancements in renewable energy systems or innovations in electrical storage and transmission.

---

### **Sections**

Each category is subdivided into sections that provide specific details or formats for that aspect of knowledge.

1. **Metadata**
   - **Purpose**: Contains basic structural information, like tags, learning objectives, difficulty level, and keywords.
   - **Use**: To provide contextual information about the scroll, helping both human users and AI to understand the focus and complexity of the scroll.
   - **Example**: In the "Electricity" scroll, metadata might include learning objectives such as "Understand Ohm’s Law" and tags like "Physics, Basics, Electricity."

2. **Core Concept**
   - **Purpose**: Presents the fundamental idea or principle behind the category.
   - **Use**: To provide a clear and concise explanation of the central idea within the category.
   - **Example**: For "Electricity," the core concept might define electricity as the flow of charge through conductors.

3. **Logic Structure**
   - **Purpose**: Presents a formal, machine-readable structure of the knowledge.
   - **Use**: Provides a structure that can be understood by AI systems, often through key concepts and their relationships.
   - **Example**: A logic structure for electricity could include concepts like "current," "voltage," and "resistance," along with their relationships and equations.

4. **Example**
   - **Purpose**: Provides concrete instances or cases that illustrate the core concept.
   - **Use**: To make abstract ideas more relatable and understandable through real-life scenarios.
   - **Example**: An example in the "Electricity" scroll could show how a simple circuit with a battery, resistor, and light bulb works.

5. **Story**
   - **Purpose**: Presents the concept in a narrative form, often used for human learning.
   - **Use**: To explain the concept through a relatable, often anecdotal, context that helps people engage with the subject on a personal level.
   - **Example**: The story section might narrate how electricity was first discovered and the journey of its scientific understanding.

6. **Guidelines**
   - **Purpose**: Provides step-by-step instructions or best practices for understanding or using the concept.
   - **Use**: To offer practical advice or methodology to apply the knowledge in real-world scenarios.
   - **Example**: For "Electricity," guidelines might include safety tips for handling electrical circuits.

7. **FAQs**
   - **Purpose**: Provides answers to common questions or points of confusion.
   - **Use**: To address frequent doubts or issues that arise in the understanding of the concept.
   - **Example**: In "Electricity," FAQs might include questions like "What is the difference between AC and DC current?"

8. **Glossary**
   - **Purpose**: Defines key terms related to the subject.
   - **Use**: To provide easy-to-reference definitions for specialized terms, helping both humans and AI understand specific terminology.
   - **Example**: The glossary for "Electricity" might define terms like "ampere," "voltage," and "resistance."

---

### Example of a Scroll:

```yaml
- category: "Essence"
  sections:
    - section: "metadata"
      content:
        learning_objective: "Understand the foundational principles of the topic."
        difficulty_level: "Intermediate"
    - section: "core_concept"
      content: "The essence of the topic lies in its core principle: ..."
    - section: "example"
      content: "For instance, ... illustrates the core principle."
    - section: "story"
      content: "Once upon a time, this principle led to ..."
    - section: "logic_map"
      content: "{ 'node': 'core_principle', 'relations': [] }"
```

## Creating a SAGE Scroll

### 1. Define Your Category

Start by defining the **category** you’re working on. Categories are broad and define the type of knowledge being shared.

Example:  
```yaml
category: "Mechanics"
```

### 2. Add Sections

Each category is subdivided into **sections**. Common sections are:
- **metadata**
- **core_concept**
- **example**
- **story**
- **logic_map**

You can use these sections as templates to define how to express your knowledge.

Example:
```yaml
section: "core_concept"
content: "The core concept of the topic is based on..."
```

### 3. Add Metadata

Metadata provides essential contextual information that will help both humans and AI navigate the knowledge structure effectively.

Example:
```yaml
section: "metadata"
content:
  learning_objective: "Gain a foundational understanding of..."
  difficulty_level: "Beginner"
  transfer_type: "Conceptual Knowledge"
```

### 4. Add Dual Expression

Provide both a **human-readable narrative** (for ease of understanding) and a **machine-readable logic map** (for AI processing).

Example:
```yaml
section: "story"
content: "In ancient times, this principle was discovered..."
```

```yaml
section: "logic_map"
content: "{ 'node': 'principle', 'connections': ['concept1', 'concept2'] }"
```

## Using SAGE with AI

SAGE scrolls are designed for use with AI systems like ChatGPT. AI can interpret and interact with the **logic maps** and **prompt templates** in each scroll.

1. **AI-Prompt Synergy**: Use the `prompt_template` section to guide AI in generating responses or carrying out tasks.
2. **Learning from SAGE Scrolls**: AI can use the `logic_map` to learn relationships between concepts and build upon them.

### Example:
```yaml
section: "prompt_template"
content: "Generate a question about [core_concept]."
```

## Advanced Features

### 1. Contextual Layering
You can define how each section is contextually relevant and in what scenarios it applies. Use metadata tags like `contextual_tags` to define when and where the knowledge applies.

### 2. Relationship Maps
Define how different scrolls or sections relate to each other, providing a clear semantic map for the AI.

Example:
```yaml
ragmap:
  - source: "mechanics"
    target: "patterns"
    relation: "builds upon"
```

## Best Practices

1. **Clear Categorization**: Keep your categories distinct and meaningful to maintain the organization of knowledge.
2. **Dual Expression**: Ensure that both human-readable narratives and logic maps are included to bridge AI and human understanding.
3. **Metadata Awareness**: Always include clear metadata for learning objectives, difficulty levels, and AI prompts.
4. **Version Control**: Regularly update scrolls and use versioning to track changes in the knowledge base.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### How to Use This Guide

This **README.md** is designed to teach users how to create, use, and interact with SAGE scrolls, starting from the basics and expanding into advanced features like **relationship maps** and **AI-prompt synergy**. It helps structure knowledge for both human learning and AI training.
