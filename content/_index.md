---
sections:
  - block: biography
    id: about
    content:
      username: me
    design:
      biography: 
        style: "font-size: 1rem; line-height: 1.55;"

  - block: markdown
    id: research-interests
    content:
      title: Research Interests
      text: |
        Computer Science Education, Interest Development, Belonging in CS, Broadening participation in Computer Science, Human-Computer Interaction, Human-centered AI, Collaborative learning, Informal and Formal Learning Environments

  - block: markdown
    id: research-methods
    content:
      title: Research Methods
      text: |
        Mixed-Methods, Interviews, Observations, Surveys, Interaction Analysis, Artifact Analysis

  - block: collection
    id: papers
    content:
      title: "Selected Publications"
      filters:
        folders:
          - publications
      count: 5
    design:
      view: citation
---