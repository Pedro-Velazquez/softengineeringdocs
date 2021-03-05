# Introduction

## Model
Models represents some aspects of reality or and idea that is of interest. It's a simplification. It's a representation of reality that abstracts the aspects relevant to solving the problem at hands and ignore extraneous details.

## Domain
Every software program relates to some activity or interest of its users. That subject area to which the user applies the program is the domain of the software

## Domain model
A domain model isn't a particular diagram, it's the idea that the diagram is intended to covey. It's not just the knowledge in a domain expert's head. It's a rigorously organized and selective abstraction of that knowledge.

The choice of a model is determined by three basic uses:
- The model and the heart of the design shape each other. It is the intimate link between the model and the implementation that makes the model relevant and ensures that the analysis that went into it applies to the final product, a running program. This binding of model and implementation also helps during maintenance and continuing development, because the code can be interpreted based on understanding the model.
- The model is the backbone of a language used by all team members. Because of the binding of model and implementation, developers can talk about the program in this language. They can communicate with domain experts without translation. And because the language is based on the model, our natural linguistic abilities can be turned to refining the model itself.
- The model is distilled knowledge. The model is the team's agreed-upon way of structuring domain knowledge and distinguishing the elements of most interest. A model captures how we choose to think about the domain as we select terms, break down concepts, and relate them. The shared language allows developers and domain experts to collaborate effectively as they wrestle information into this form. The binding of model and implementation makes experience with early versions of the software applicable as feed-back into the modeling process.

## Crunching knowledge
Ingredients of effective modeling:
- Binding the model and the implementation.
- Cultivating a language based on the model.
- Developing a knowledge-rich model.
- Distilling the model.
- Brainstorming and experimenting.

Effective domain modelers are knowledge crunchers. They take a torrent of information and probe for the relevant trickle. They try one organizing idea after another, searching for the simple view that makes sense of the mass. Many models are tried and rejected or transformed. Success comes in an emerging set of abstract concepts that makes sense of all the detail. This distillation is a rigorous expression of the particular knowledge that has been found most relevant.

## Ubiquitous language
A project faces serious problems when its language is fractured. Domain experts use their jargon while technical team members have their own language tuned for discussing the domain in terms of design. The terminology of day-to-day discussions is disconnected from the terminology embedded in the code. And even the same person uses different language in speech and in writing, so that the
most incisive expressions of the domain often emerge in a transient form that is never captured in the code or even in writing.

With a conscious effort by the team, the domain model can provide the backbone for a common language that is more robust than the lowest common denominator, while connecting team communication to the software implementation. That language can be ubiquitous in the team's work. The vocabulary of that _UBIQUITOUS_ _LANGUAGE_ includes the names of classes and prominent
operations. The LANGUAGE includes terms to discuss rules that have been made explicit in the
model. It is supplemented with terms from high-level organizing principles imposed on the model.

Use the model as the backbone of a language. Commit the team to exercising that language relentlessly in all communication within the team and in the code. Use the same language in diagrams, writing, and especially speech. Iron out difficulties by experimenting with alternative expressions, which reflect alternative models. Then refactor the code, renaming classes, methods, and modules to conform to the new model. Resolve confusion over terms in conversation, in just the
way we come to agree on the meaning of ordinary words.

## Binding Model and Implementation
Domain-driven design calls for a model that doesn't just aid early analysis but is the very foundation of the design. This approach has some important implications for the code. What is less obvious is that domain-driven design requires a different approach to modeling. If the design, or some central part of it, does not map to the domain model, that model is of little value, and the correctness of the software is suspect. At the same time, complex mappings between models and design functions are difficult to understand and, in practice, impossible to maintain as the design changes. A deadly divide opens between analysis and design so that insight gained in each of those activities does not feed into the other.

Design a portion of the software system to reflect the domain model in a very literal way, so that mapping is obvious. Revisit the model and modify it to be implemented more naturally in software, even as you seek to make it reflect deeper insight into the domain. Demand a single model that serves both purposes well, in addition to supporting a robust **UBIQUITOUS LANGUAGE**.

If the people who write the code do not feel responsible for the model, or don't understand how to make the model work for an application, then the model has nothing to do with the software. If developers don't realize that changing code changes the model, then their refactoring will weaken the model rather than strengthen it. Meanwhile, when a modeler is separated from the implementation process, he or she never acquires, or quickly loses, a feel for the constraints of implementation. The basic constraint of MODEL-DRIVEN DESIGN—that the model supports an effective implementation and abstracts key domain knowledge—is half-gone, and the resulting models will be impractical. Finally, the knowledge and skills of experienced designers won't be transferred to other developers if the division of labor prevents the kind of collaboration that conveys the subtleties of coding a MODEL-DRIVEN DESIGN.

Any technical person contributing to the model must spend some time touching the code, whatever primary role he or she plays on the project. Anyone responsible for changing code must  learn to express a model through the code. Every developer must be involved in some level of discussion about the model and have contact with domain experts. Those who contribute in different ways must consciously engage those who touch the code in a dynamic exchange of model ideas through the UBIQUITOUS LANGUAGE.