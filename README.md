
# 📊 README for Heap Sort Visualization using Streamlit

## 🚀 Project Overview
This Streamlit web application offers a **creative heap sort visualization**, showcasing two methods of heap sorting: **Top-Down Heap Sort** and **Bottom-Up Heap Sort**. The application allows users to upload or generate an array, visualize the sorting process step-by-step using Graphviz, and interactively explore how heap sort works.

Additionally, users can **insert** or **delete** elements from the array, view the sorting process with detailed steps, and even download the sorted array. 🎉

## 🌟 Features
- 📂 **Upload or generate random arrays**: Users can upload a text file containing an array or generate a random array of a specified size.
- 🏗️ **Top-Down Heap Sort and Bottom-Up Heap Sort**: Both sorting methods are implemented and visualized.
- 👁️ **Interactive visualization**: The sorting process is visualized step-by-step using Graphviz diagrams, with highlighted nodes for each step.
- ➕ **Insert and Delete elements**: Users can insert new elements into the array or delete specific elements.
- 🎚️ **Step-by-step slider**: A slider allows users to control and observe each step of the sorting process.
- 🌀 **Heap Sort Animation**: Users can watch an animated version of the entire sorting process.
- 💾 **Download sorted array**: The sorted array can be downloaded as a text file.

## 🛠️ How to Run the Project
### ⚙️ Prerequisites
1. **Python 3.7+** installed on your system.
2. Install the required dependencies by running:
   ```bash
   pip install streamlit numpy graphviz pillow
   ```

### ▶️ Running the Application
1. Clone the repository or download the code.
2. Run the application with the following command:
   ```bash
   streamlit run <file_name>.py
   ```
3. The application will open in your default web browser. You can now upload or generate an array and interact with the sorting visualizations.

## 🔍 Code Explanation

### 📂 File Structure
1. **image_to_base64**: Helper function to convert an image to a base64 string for embedding.
2. **set_app_style**: Defines custom styles for the app’s UI, setting background images, text colors, and sidebar styles.
3. **Heap Sort Functions**:
   - `topDownHeapSort`, `bottomUpHeapSort`: These functions implement the heap sort using top-down and bottom-up approaches.
   - `sift_up`, `sift_down`, `heapify`: Support functions to maintain heap property during sorting.
4. **visualize_heap**: Generates a Graphviz graph to visually represent the heap at each step.
5. **highlight_array**: Highlights sorted portions of the array in green. 
6. **Streamlit Main App**: Handles user input (file upload, random array generation, insertion, deletion), manages the interactive UI, and displays the sorting steps and visualizations.

### 💻 Additional Sorting Algorithms
The script also includes implementations for:
- 🔀 **Merge Sort**
- ⚡ **Quick Sort**

These can be expanded or integrated into the main interface for additional sorting visualizations.

## 🔮 Future Improvements
- **Visualize other sorting algorithms** like Merge Sort and Quick Sort.
- **Enhance UI/UX** by adding more interactive features such as speed control for the sorting animations or customizing color themes.
- **Save visualizations** as images or videos for educational purposes. 🎥

## 🏁 Conclusion
This application serves as both an educational tool and an interactive experience to help users understand the heap sort algorithm through visualization. Users can dynamically interact with arrays, modify data, and visualize the heap sorting process with ease. 💡
