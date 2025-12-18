# Portfolio

## LensCull — Image Similarity Checker

**Repository:** [https://github.com/simon9834/LensCull](https://github.com/simon9834/LensCull)

### Overview

LensCull is a Python-based application for computing visual similarity between images. It is designed to identify near-duplicates and assess image quality across datasets using perceptual techniques and statistical comparisons. The project emphasizes clean architecture, testability, and performance.

### Core Capabilities

* Image similarity detection using perceptual hashing (pHash)
* Histogram-based comparison for visual analysis
* Parallel processing for scalable workloads
* Quality assessment utilities
* Web-based interface for interaction
* Structured logging and configuration management

### Technology

* Python 3.8+
* NumPy
* Pillow (PIL)
* Parallel execution
* Unit testing framework

### Architecture Summary

The project follows a modular structure with clear separation of concerns:

* **Processing layer:** image loading, quality analysis, similarity computation
* **Exception handling:** custom, domain-specific errors
* **Testing suite:** unit tests covering core functionality
* **Web layer:** lightweight server and HTML interface

This organization supports maintainability, extensibility, and reliable testing.

### Execution

Dependencies are managed via `requirements.txt`. Images are placed in the designated data directory and processed through the main application entry point.

### Purpose and Outcome

LensCull demonstrates practical application of image processing concepts, parallel computation, and software engineering best practices. It reflects an approach focused on clarity, correctness, and real-world usability.
