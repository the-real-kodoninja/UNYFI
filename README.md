# UNYFI
Developed by Aviyon, uses the UNYSL programming language to create natively compiled applications for mobile, web, and desktop from a single codebase.

**Role**: One-codebase → mobile, web, desktop  
**Syntax**: UNYSL  
**Compiler**: UNYFI → iOS/Android/Web/WASM/Desktop  
**Integration**: EvoSynUI, d30.js  
**Use Case**: Modu apps, Gizmo widgets  

```unyfi
@target(all)
component RepairBay {
  onScan(ule) => bookSlot();
}
```
