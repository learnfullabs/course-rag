# CourseRAG
CourseRAG is a package for performing high-accuracy retrieval augmented generation (RAG) on PDFs, Common Cartridge LMS Exports (IMSCC), PPTX, DOCX, lecture recordings, quizzes, assignments, or text files, with a focus on the teaching and learning.

## Quickstart
In this example we take a folder containing a PDF textbook and an IMSCC export of a course from an LMS, extract their metadata, parse and vectorize their contents, and finally answer the user question with an LLM agent using the context of the materials.

```
pip install course-rag
cd my_course
crag ask 'What are the topics I should study for the midterm?'
```

### Example Output
Question: ---

Answer: ---
