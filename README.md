# UNTD Math Major Degree Plan

```mermaid
graph TD
    %% Phase 1: Foundation
    Start([Start: College Algebra/STEM Prep]) --> Calc1[MATH 2413: Calculus I]
    Start --> Core[University Core Curriculum - 42 Hours]
    Start --> CS1[CSCE 1030: Computer Science I]

    %% Phase 2: Sequential Core
    Calc1 --> Calc2[MATH 2414: Calculus II]
    Calc2 --> Calc3[MATH 2415: Multivariable Calculus]
    Calc2 --> Proofs[MATH 3405: Intro to Mathematical Proofs]
    CS1 --> CS2[CSCE 1040: Computer Science II]

    %% Phase 3: Transition & Support
    Calc3 --> DiffEq[MATH 3331: Differential Equations I]
    Proofs --> LinAlg[MATH 3315: Linear Algebra]
    Proofs --> Stats[MATH 3361: Applied Statistics]
    CS2 --> CS3[CSCE 2100: Computing Foundations I]
    
    %% Phase 4: Advanced Theory (Requires Proofs)
    LinAlg --> Abstract[MATH 4411: Abstract Algebra I]
    LinAlg --> Analysis[MATH 4441: Real Analysis I]
    Proofs --> Number[MATH 3311: Number Theory]
    Proofs --> Geometry[MATH 3351: Foundations of Geometry]

    %% Phase 5: Final Requirements
    Analysis --> Electives[2x Advanced Math Electives]
    Abstract --> Electives
    Core --> Grad([Graduation: 120 Total Hours])
    Electives --> Grad
    CS3 --> Grad
    DiffEq --> Grad
