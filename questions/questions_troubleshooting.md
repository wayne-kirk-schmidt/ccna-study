# Troubleshooting Thinking

⬅️ Back to [Questions README](README.md)

## How to Think About Failures
1. Identify the **last thing that works**
2. Map that to an **OSI layer**
3. Identify the **next dependency upward**
4. Choose a **minimal verification step**

## Scenarios
- You can ping an IP but not a hostname  
  → What dependency comes next after IP reachability?

- An application is slow only at peak times  
  → Which layers are sensitive to load?
