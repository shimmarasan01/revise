# ReVise

[Demo](https://www.youtube.com/watch?v=b_e31lw-K6o&ab_channel=Shimmarasan01)

Status: Incomplete<br><br>
Remaining tasks: 
  * Store/retrieve workspaces in/from Firebase
  * UI/UX
  * Bugs
  * Exception handling

<p align="justify">A Flutter application that empowers students to effectively structure their notes and optimize their studying experience. The application offers a range of features designed to enhance note-taking and revision processes:</p>

* Intuitive Note-Taking Interface: 
  * <p align="justify">The application provides a streamlined interface for students to create workspaces and structure notes in 3 different categories (header, main point, and supporting points).</p>

* NLP-Generated Questions: 
  * <p align="justify">Leveraging the power of NLP models, the application automatically generates questions from the notes. These questions prompt students to test their understanding and recall key information. By engaging in active recall, students reinforce their knowledge and identify areas that require further revision.</p>

* Answer Validation: 
  * <p align="justify">When students attempt to answer the generated questions, the application checks the semantic similarity between their answer with the actual answers derived from the notes. This immediate feedback mechanism allows students to gauge their comprehension and identify areas for improvement.</p>

* Multimedia Conversion: 
  * <p align="justify">The application incorporates audio, video, and YouTube content conversion to text. Students can upload or link multimedia files, and the application transcribes the content into textual format, making it easier to integrate with their notes and revise effectively.</p>

* HuggingFace Spaces Integration: 
  * <p align="justify">The NLP model and other Python functions, responsible for generating questions and performing other language processing tasks, are hosted within HuggingFace Spaces. This explains the speed of the question generation and multimedia conversion processes as HuggingFace Spaces (Free) only provides 2 CPUs with no GPU support.</p>

* Firebase Database: 
  * <p align="justify">The application utilizes Firebase to manage the database, facilitating seamless synchronization of notes and user data across devices. Firebase offers real-time data synchronization, ensuring that students can access their notes from any device and never lose their progress.</p>
