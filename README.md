# mlfs-book
O'Reilly book - Building Machine Learning Systems with a feature store: batch, real-time, and LLMs

# This Lab
Link to github pages dashbord:
https://sagalgit.github.io/mlfs-book/air-quality/

- We changed the wrong order of:
batch_data = batch_data.sort_values(by=['date']) # changed order of this
batch_data['days_before_forecast_day'] = range(1, len(batch_data)+1) 

## ML System Examples


[Dashboards for Example ML Systems](https://featurestorebook.github.io/mlfs-book/)

## Course Comparison

| Course                         | MLOps | LLLMs             | Feature/Training/Inference | Working AI Systems | Focus |
|--------------------------------|-------|----------------------------|--------------------|------------------|
| Building AI Systems (O'Reilly) | Yes   | Fine-Tuning & RAG | Yes                        | High               | Project-based, Software Engineering, Fundamentals    |
| [Made With ML](https://madewithml.com/)                   | No          | Yes   | No                         | No                 | Software Engineering, Model Training   |
| [7 Steps MLOps](https://www.pauliusztin.me/courses/the-full-stack-7-steps-mlops-framework)            | Yes   | Separate Course    | Yes                        | Low                | Learning Tools and Project    |
