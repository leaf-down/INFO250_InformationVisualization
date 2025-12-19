## Causes of death among women aged 65 years or over in the European Union, 2012–2022.

**Original chart analysis**: I began by briefly dissecting the structure of the Eurostat static chart, clarifying the time axis (2012–2022) and the index baseline (2012 = 100). The focus was on relative changes in causes of death over a decade, while noting limitations in interactivity and visual guidance for readers.

**Reproduction phase**: Using ECharts (HTML output via pyecharts), I recreated the chart with high fidelity, ensuring consistent indicators, accurate values, and identical trend directions. This step established a reliable foundation without introducing statistical distortion.

**Enhancement and storytelling phase**: Building on this foundation, the focus shifted from simply *showing data* to *helping readers understand the story behind the changes*. Several key improvements were introduced:

- Added **end labels** to each line so readers can immediately see which causes are rising and which are declining  
- Used **color, line width, and symbols** to highlight major trends (e.g. the sustained increase in dementia and lung cancer)  
- Introduced a **baseline reference line (2012 = 100)** to provide an intuitive benchmark for increases and decreases  
- Enabled **interactive tooltips**, allowing users to trace each cause of death year by year along the timeline  

**Outcome**: The final chart moves beyond a dense collection of lines and tells a clear narrative. Among women aged 65 and over in the EU, the structure of mortality has shifted markedly over the past decade: deaths related to dementia and lung cancer have risen steadily, while ischaemic heart and cerebrovascular diseases have declined. These patterns reflect both medical progress and the growing importance of chronic and neurodegenerative conditions in an ageing society.