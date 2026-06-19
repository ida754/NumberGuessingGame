# NumberGuessingGame (C# Console Architecture)
An interactive, text-based algorithmic console game built using C# and .NET framework.This application transitions standard baseline syntax into practical programming control flows, showcasing data serialization, complex conditional loops, and real-time state preservation.

## Core Features
*  **Persistent Application Lifecycle**:Utilizes an outer 'do-while' control architecture to manage continuous application execution and clean engine state resets per match.
*  **Absolut Proximity Tracking**:Employs mathematical distance evaluation ('Math.Abs') to deliver context-aware,localized feedbackmetrics ("almost there" vs "too far") instead of generic boundary pointers.
*  **Localized Resource Budgeting**:Implements a strict execution capping player lifecycle thresholds  at exactly  5 guessing cycles.
*  **UX Optimization**:Synthesizes screen flushes('Console.Clear') and defensive user input normalization('ToLower().Trim()')to handle game reset validation securely.

## Concepts and Engineering Principles Practised
* **Multi-Tiered Loop Nesting**:Orchestrating an absolute application execution cycle  wrapping a conditional processing engine ('while' emedded inside 'do-while').
* **Relational Boolean Evaluation**:Utiling multi-conditional evaluation sequence using short-circuit logical operators(&&,||).
* **Data Transformation**intercepting  standard user input strems('Console.Readline')and handling memory formatting tasks cleanly via ('int.TryParse').
* **Memory Scope isolation**:strategic placement of instance allocations to prevent cross-session variable leakage across separate game matches.

## Tech Stack
* **language**: C#
* **Runtime Environment**: .NET Console 
* **Development IDE**: Visual Studio 2026

## How To Run The Application
1. Clone this repository locally or download the source code files.
2. Launch the project solution file('.sln') inside **Visual Studio**.
3. Press **F5** or click the green **Start/Play** icon at the top of the interface.


  
