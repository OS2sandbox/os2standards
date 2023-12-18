# OS2Produkt Repository struktur

```mermaid
%%{init: {'theme': 'forest', "flowchart" : { "curve" : "basis" } } }%%

mindmap
  root((OS2Produkt))
    core["📦CORE
    Non-optional code"] 
    mods["🧩 MODULES
    Available components"]
        Module1
        Module2
        Module3
    docs["📚 DOCUMENTATION
    How to deploy, run and develop"]
    conf[" 🔧 CONFIGURATIONS
    Templates to configure the product to different scenarios"]
        Baseline
        Baseline+Variant1
        Baseline+Expansion2
    deploy["📥 DEPLOYMENTS
    Templates to deploy the product to different platforms"]
     Base
     Variants
     Environments
    shared["🔁 SHARED
    Shared user-content like forms, scripts. Easy to clone and participate for contributors"]