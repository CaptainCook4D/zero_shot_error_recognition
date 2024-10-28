# ZERO SHOT ERROR RECOGNITION

To perform Zero Shot Error Recognition, we cast the problem as a Video Question Answering task. 

We developed two variants for the task: 
- Variant 1
  -  Use video and a question (a generic prompt corresponding to the error recognition task) as input to VLMs
- Variant 2
  -  Engineered prompts that take both video context and the error description.
  -  Use these error-specific engineered prompts along with Videos as input to VLMs
