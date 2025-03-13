# Multi-Threaded-File-Searcher
Project idea   This project is a **search engine within text files using Multi-Threading**. It aims to improve search performance by running multiple threads running in parallel, which makes search faster compared to traditional implementation.

How to implement the project  
### 🔹 **1. Define requirements**  
- The program will search for **word or sentence** within a group of text files.  
- A large number of files will be handled to ensure performance testing.  
- Search should be **fast and efficient** using **multi-threading**.
-2. Divide tasks**  
- **Data Entry**: Allow the user to choose **The folder containing the text files**.  
- **Threads Management**:  
  - A **Thread Pool** will be created so that the files are distributed among several threads running in parallel.  
  - Each thread will search within a specific set of files.  
- **Collecting results**: After the search is finished, the names of the files that contain the desired word will be displayed along with the line numbers in which they appeared.
- 3. Expected output**  
- When running the program, the user **enters the folder and the word to search for**.  
- The search is carried out in parallel within the files, then the results are displayed on the screen.  

### 🔹 **4. Future improvements**  
- **Add support for other file types** (e.g. JSON, XML, CSV).  
- **Improved search** to include searching for regular expressions.  
- **Adding a user interface** for ease of use instead of running it through the Terminal.

- What are the next steps?  
1. **Designing the project structure**: Determine how to divide the codes and organize the files.  
2. **Getting started**: Create basic components such as thread management and file reading.  
3. **Performance testing**: Ensuring that the research is carried out quickly and efficiently.  
4. **Improve the project and add additional features
