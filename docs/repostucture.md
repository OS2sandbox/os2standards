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
        Standard
        Standard+Custom expansion1
        Standard+Custom expansion2
    deploy["DEPLOYMENTS
    Templates to deploy the product to different platforms"]
     Base
     Variants
     Environments