# Power BI Measure Cleanup Tool 

**A lightweight solution for managing measures in Power BI Live Connection models**

## The Problem

Working with large Power BI live connection models often leads to:
- **Hundreds of measures** scattered across tables (especially without proper best practices)
- **No clear organization** or documentation
- **Complex measure dependencies** that make deletions risky
- **Existing tools** like Tabular Editor work best with Import models and may have unnecessary complexity

## The Challenge

Safely cleaning measures isn't simple because:
-  **Dependency risks**: Measures might be referenced by other measures or visuals
-  **No undo functionality**: Critical measure removal can break reports irreversibly
-  **Limitations in free tools** for live connections

## The Solution

A browser-based tool designed specifically for Power BI measure management:

✔ **Works with PBIX files** (Live Connection)  
✔ **Zero installation** – runs entirely in your browser  
✔ **Comprehensive dependency analysis** to identify unused measures  
✔ **Visual relationship mapping** between measures  
✔ **100% client-side** – your data never leaves your computer  

## Key Features

- **Usage Indicators**: Flags unused measures with dependency validation
- **Dependency Tree**: Clear visualization of measure relationships
- **Safe Deletion Guide**: Highlights measures with no dependencies
- **Export Capabilities**: Generate documentation for your team

## Why This Matters

🏢 **Enterprise models**: Safely clean up legacy measures  
⚡ **Performance**: Reduce overhead from unused calculations  
🤝 **Collaboration**: Document complex dependencies for your team  

## Disclaimer
This tool is provided "as-is" without warranty of any kind. Users assume all risk associated with its use. The author disclaims all liability for any damages or issues arising from the use of this.

