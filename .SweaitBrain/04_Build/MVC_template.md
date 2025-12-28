# Active Coding Scaffold Template

Use this template when generating the **Practice Exercise** (Phase 4). The goal is to force the user to "Active Recall" the logic rather than passively copying code.

## 1. The Structure (Scaffold)
Provide the boilerplate imports, class definitions, and function signatures. This removes the friction of setup.

## 2. The Gap (Business Logic)
**CRITICAL**: You must COMMENT OUT the core business logic or implementation details.
- **Do not** leave it empty.
- **Do not** provide the solution immediately visible.
- **Do** provide a comment explaining *what* needs to be done, referencing the *Mental Model*.

## 3. The Template Format
```python
"""
EXERCISE: [Name of Concept]
Context: [Reference to Literature Note/Anchor]
Task: Uncomment and fix the logic below.
"""

# 1. Setup/Imports (Given)
import ...

# 2. The Logic Gap (The Exercise)
def critical_function():
    # [TODO]: [Explain the goal using the Metaphor]
    # Hint: [Provide a subtle hint]
    
    # ---------------------------------------------------------
    # UNCOMMENT AND FIX THE LOGIC BELOW
    # ---------------------------------------------------------
    # result = ... # (Broken or missing critical parameter)
    # return result
    
    pass

# 3. Validation (Immediate Feedback)
if __name__ == "__main__":
    # Simple check to see if the user fixed it
    try:
        critical_function()
        print("Success! Logic verified.")
    except Exception as e:
        print(f"Logic Gap Detected: {e}")
```

## Rules for "The Gap"
1.  **Complexity**: gaps should be cognitive (logic), not mechanical (syntax).
2.  **Safety**: The code should be safe to run (will just fail/print error), not destructive.
3.  **focus**: Only 10-20% of the lines should be commented out. The rest is support structure.
