# Auto-GPT
Command get_text_summary returned: Error: [E088]

i have a problem, please help me for fix it thx 


Command get_text_summary returned: Error: [E088] Text of length 6539507 exceeds maximum of 1000000. The parser and NER models require roughly 1GB of temporary memory per 100,000 characters in the input. This means long texts may cause memory allocation errors. If you're not using the parser or NER, it's probably safe to increase the `nlp.max_length` limit. The limit is in number of characters, so you can check whether your inputs are too long by checking `len(text)`.
