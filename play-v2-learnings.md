\# V2 Learnings — Media Integrated / No Collision / More Ordered

\#\# Best Practices

\- Maintain a clear separation between Webflow structure, CSS rendering rules, and JavaScript layout behavior.  
\- Webflow Designer should define the semantic structure of the system.  
\- CSS should define portable visual/rendering rules.  
\- JavaScript should control engine behavior, placement logic, and runtime negotiation.  
\- Selectors belong to CSS.  
\- Listeners belong to JavaScript.  
\- Designer adjustments are useful for fast visual discovery, but stable system rules should be migrated into CSS.  
\- Avoid one-off CMS edits to fix visual anomalies. Tune governing rules instead.  
\- A deterministic layout system should be adjusted by changing constraints, not by manually forcing individual outcomes.

\#\# Key System Insight

The system became more stable when media rendering, metadata positioning, and placement logic were treated as separate layers.

\`\`\`text  
Structure \= Webflow  
Render \= CSS  
Behavior \= JS  
Content \= CMS  
