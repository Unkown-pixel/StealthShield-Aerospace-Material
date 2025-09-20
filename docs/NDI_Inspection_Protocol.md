# NON-DESTRUCTIVE INSPECTION (NDI) PROTOCOL — STEALTHSHIELD-MID

## 1. PURPOSE
Ensure structural integrity, FSS electrical continuity, and interleaf uniformity.

## 2. METHODS
### A. Phased Array Ultrasonic Testing (PAUT)
- **Frequency**: 5 MHz  
- **Coverage**: 100% scan, 5mm raster  
- **Acceptance**: No delamination > 3mm diameter

### B. Time-Domain Reflectometry (TDR)
- **Purpose**: Verify FSS pattern continuity  
- **Setup**: 50Ω impedance, 1ns pulse  
- **Acceptance**: Reflection < -20 dB at all FSS segments

### C. Infrared Thermography (IRT)
- **Purpose**: Detect interleaf agglomeration or voids  
- **Setup**: Flash heating (2°C/s), 640×480 IR cam  
- **Acceptance**: ΔT < 1.5°C across panel

## 3. FREQUENCY
- Pre-cure: IRT only  
- Post-cure: PAUT + TDR + IRT

## 4. DOCUMENTATION
- Save .csv TDR traces  
- Annotate PAUT C-scans  
- Archive IR thermograms

---
© 2025 Unknown-pixel + Qwen
