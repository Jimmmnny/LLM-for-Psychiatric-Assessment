# LLM for Psychiatric Assessment

This project aims to develop and utilize a large language model (LLM) for enhancing the accuracy and efficiency of psychiatric assessments. By leveraging advanced NLP techniques, the model assists in diagnosing psychiatric conditions based on textual vignettes describing patient symptoms and behaviors.

## Project Structure

- `cot_all.txt`: Contains the methodology for assessing psychiatric symptoms and the diagnostic process.
- `populate_database.py`: Python script used to manage and populate the database with relevant case studies and diagnostic criteria.
- `experiment.ipynb` : Experiments, model training, and evaluation processes, with LLama3.2 and mistral (on local computer with Ollama)
- `LLama3.3.ipynb` : Experiments with LLama 3.3 on lighting AI
## Methodology

The process follows a structured diagnostic framework:
1. **Identify Key Symptoms**: Extract and assess key symptoms from clinical vignettes.
2. **Broad Symptom Analysis**: Group symptoms into potential related domains.
3. **Compare Across Diagnostic Criteria**: Map symptoms to specific diagnostic criteria for various psychiatric disorders.
4. **Differential Analysis**: Analyze symptom overlap and rule out inconsistent conditions.
5. **Functional Impact Assessment**: Evaluate the impact of symptoms on the individual’s functioning across various domains.
6. **Final Diagnosis and Summary**: Derive a potential diagnosis supported by a detailed analysis and summary.

## data

Since there is confidencial data, not all data is uploaded here.

## Usage
To run the model and perform an assessment, execute the following:

```bash
python populate_database.py
jupyter notebook experiment.ipynb
```
