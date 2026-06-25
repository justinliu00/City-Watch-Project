# City-Watch-Project
## About City Watch

City Watch is an AI-powered urban hazard reporting platform designed to help residents identify and document public infrastructure and safety issues more quickly. The application allows a user to upload a photograph of a hazard, provide its location, add an optional description, and report when the problem began.

Once submitted, City Watch uses a locally hosted vision-language model to analyze the image and generate a structured hazard assessment. The system identifies the likely issue, evaluates its danger level, assigns a priority score, estimates its confidence, and explains the visible evidence used in its decision. It also provides safety guidance for residents, recommends the appropriate city department, suggests a municipal response, and generates a professional service report.

City Watch was created to address a common weakness in traditional city-reporting systems: residents may not know how serious a problem is, which department is responsible, or how to describe the issue clearly. Reports can therefore be incomplete, delayed, or sent to the wrong authority. City Watch simplifies this process by transforming a resident’s photo and basic information into a clear, organized, and actionable report.

The project is built with Python, Streamlit, Pillow, Ollama, and the `qwen2.5vl:3b` vision-language model. Image processing is performed locally, and uploaded photos are resized and compressed before analysis to improve performance. The AI model is also kept loaded temporarily between requests to reduce repeated startup time.

City Watch is currently a prototype and is not intended to replace emergency services or official city inspections. Its purpose is to demonstrate how multimodal AI can improve communication between residents and local governments by making hazard reports faster, more consistent, and easier to prioritize.
