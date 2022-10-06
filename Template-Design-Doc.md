# [Template] Design Doc

# Design Doc

- **Metadata**
    
    **Authors:** *andrei.bulanov*
    
    **Date:** *07.10.2022*
    
    **Terminology:**
    
    - `3rd party service` — *3rd Party Payment processor*
    - `transactions service / transactions` — *payment feed*

## Background

### Context

<aside>
💡 In this document there is a list of performance improvements that can be done to increase system performance for higher load. 

</aside>

### Motivation

<aside>
💡 Explain what the motivation is for the change and why we should aim to address it.

</aside>

### Requirements

<aside>
💡 A short list of bullet points of what the scope of the change is. 
*Note: It is often helpful to state explicitly what is not expected to be in the scope.*

</aside>

## Design

*Given the background, explain the high-level idea of the solution you're proposing.*

### System Architecture

<aside>
💡 Describe the system on a high level and put it into context. Diagram usually works great — e.g. [system context diagram](https://en.wikipedia.org/wiki/System_context_diagram). Explain components and how do they relate to each other.

</aside>

### Communication

<aside>
💡 Explain how the components communicate. Diagrams with a bit of context usually work great — e.g. [data/control flow diagrams](https://lh3.googleusercontent.com/sdy9Au0Ibv3aseGZyIKNwivgqnaZ0FqF1mUgIzZY7ZIqppJeZVqUl3Iundy0qzwJLSMdFyA-oysP5YGv5pNYpI11m9A5AY0Oqdqj=s0).

</aside>

*If you already have a clear idea you can further sketch APIs and explain mechanics — e.g. Kafka/HTTP, protocol — e.g. JSON/Protobuf,  REST/gRPC — and message schema for how components communicate.*

## Data

*Think about data in your design. Start with high-level entities and drill down to how does the system work with the actual data when implemented.*

### Model

<aside>
💡 Think about key entities in your design, which system owns them and how do they relate inside or across the systems.
*Hint: Don't think about database tables just yet!*

</aside>

### Storage

<aside>
💡 Explain a bit more about any data storage considerations — databases or other storage affected, data model, formats, etc.

</aside>

## Further Considerations

### Previous Art

*Any previous attempts to solve this problem? Provide references, links or further context.*

### Open Questions

*What questions are left open and you would like to discuss with audience?*

### Next Steps

*Are you planning to call a design review meeting, starting to code prototype straight away or hoping to have a broad discussion? Clarify your plan going forward.*
