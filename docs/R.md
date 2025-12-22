# R — Systemic Ratio

**Layer**: SYF Core  
**Status**: Canonical · v0.1-docs

## 1. Definition

R is the **sole public output** of SYF Core.  
It is a **scalar invariant** derived from Flow (F) and Entropy (E) via SyFF.

R is computed by: `R = (F × E) / K`

## 2. Properties

- **No semantic meaning**: not "good", not "bad"  
- **Not a command**: cannot trigger actions  
- **Not a prediction**: reflects current state only  
- **Deterministic**: same (F,E) → same R  
- **Observable**: can be read, logged, or framed (e.g., by FrameR)  
- **Bounded domain**: R is a scalar value over a defined range

## 3. Constraints

- No governance can override R
- No external oracle is required by the core definition
- R must be computed **deterministically** from canonical inputs

## 4. Usage Note

R may be used by **downstream systems** (e.g., SEW, WMW, Applicative Layer),  
but **SYF Core never consumes or reacts to R**.

Derived systems may track additional contextual variables (e.g., Dormancy),  
but this must not change the core definition of R.

