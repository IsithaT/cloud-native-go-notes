```
Hello anyone who is reading this,

These notes are by no means a substitute for the book, I'll be noting things that are new or relevant to me but won't make an effort to cover every element of the book. :P 
```

# Loose Coupling:

When a system's components are designed in such a way that they don't need to have much knowledge of other components. So changes to one component doesn't require changes to the other component.

# Resilience/Fault Tolerance: 

When stuff goes wrong, how well can the system handle and recover from it.
### Resilience ≠ Reliability

- **Resilience**, how well it can keep operating when faced with errors and faults. Contributes to reliability
- **Reliability**, its ability to behave as expected for a certain time interval. Contributes to dependability

# Manageability

How easily the system can be modified to keep it secure, smooth and compliant with standards.

This means designing it such that you can alter it's behavior without having to alter its code.

Eg: using Env vars instead of hardcoding database locations, being able to easily set feature flags, easily deploying upgrading and downgrading components.

### Manageability ≠ Maintainability

Maintainability is how easy it is to maintain code to change functionality (making changes on the inside). Manageability is how easy it is to make changes on the outside.

# Observability

How well you can observe its internal state from its external outputs. More than just metrics and logging. 

Will be covered more in chapter 11.