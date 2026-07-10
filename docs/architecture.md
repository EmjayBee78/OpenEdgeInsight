```mermaid
classDiagram

Project "1" --> "*" SourceFile

AnalysisResult --> Project
AnalysisResult --> Issue

Rule --> Issue

Report --> AnalysisResult
```