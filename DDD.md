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