Usage
```python
uv sync
source .venv/bin/activate
jupyter-lab
```

The report is captured in `project.ipynb`.

AI tool usage:
 - chatgpt and claude desktop

Future work 
- Caption analysis to map captions to certain features of captions themes and check if there is any high performing cluster
- Caption feature could include aspects like caption length, whether it has  CTAs or not etc.
- Better NLP tools like LLMs to better understand the sentiments of the comments instead of `textblob`, which is a bit
limited in its capabilities.  
- A key missing information is the analysis so far is the content of the post. It is very likely that the 
actual content of the post plays a dominant role in driving engagement. The information themes can be extracted through
image/video analysis of post content to understand if there are common themes that drive engagement.
