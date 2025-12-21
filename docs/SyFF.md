# Systemic Fire Formula (SyFF)

SyFF defines the core signal **R** of SYF Core.

> `R = (F × E) / K`

where:
- **F** = Flow (conceptual input)
- **E** = Entropy (conceptual input)
- **K** = internal damping / normalization constant (implementation-defined but deterministic)
- **R** = Systemic ratio (core state output)

## Dormancy (D)

**Dormancy (D) is not part of the core SyFF equation.**

Dormancy may exist as a conceptual variable in **derived systems** for contextual analysis,  
but **SYF Core computes R solely from Flow (F) and Entropy (E), normalized by K**.

## Determinism requirement

For identical canonical inputs, independent implementations must produce  
**deterministic-equivalent R**.

(Strict mode, optional for implementations: produce **bit-identical R** for identical canonical inputs.)
