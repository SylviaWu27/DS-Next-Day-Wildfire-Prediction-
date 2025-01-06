# Abstract

This report outlines the development and outcomes of a capstone project aimed at predicting next-day wildfire occurrences in Los Angeles using advanced deep learning techniques. The project's primary goal was to harness the capabilities of a Transformer-based model to provide accurate and timely predictions, enhancing wildfire management and preparedness strategies.

The methodology involved comprehensive data collection from multiple sources, followed by rigorous preprocessing to ensure data quality and consistency. A significant emphasis was placed on data visualization using Kepler.gl, an open-source geospatial analysis tool, which facilitated an in-depth understanding of the spatial distribution of fire occurrences and aided in identifying risk hotspots. The project adopted a multi-faceted approach to model development, incorporating basic model frameworks and advanced Transformer architectures, fine-tuned to address the challenges presented by highly imbalanced wildfire data.

Key project activities included the implementation of a robust data engineering pipeline to streamline processes from data ingestion to model training and the use of sophisticated data visualization techniques to communicate complex data insights effectively. The analysis highlighted the critical role of environmental variables in wildfire prediction and underscored the importance of advanced feature engineering and model optimization strategies.

Ultimately, the project demonstrated the potential of deep learning technologies in environmental risk assessment and provided a scalable model adaptable for broader applications. Future recommendations focus on integrating real-time data feeds to enhance the model’s responsiveness and applying the model to other wildfire-prone regions, contributing to global efforts in disaster prevention and management.

---

## Contribution

- Conducted extensive literature reviews to identify advanced methodologies in wildfire prediction.
- Developed the basic framework and initial phases of the Transformer model.
- Created visual representations of the data using diverse tools and platforms to enhance analytical understanding.
- Employed data visualization techniques to improve predictive strategies and model accuracy.

---

## Roles & Responsibilities

**Xinzhou Wu**  
- Role: Model Developer and Visualization Analyst  
- Contributions:
  - Conducted in-depth literature reviews on wildfire prediction methods.
  - Developed the initial framework for the Transformer-based model and a baseline model.
  - Utilized various data visualization tools and platforms to explore the dataset and extract actionable insights, improving the model’s predictive accuracy.

---

## Project Aims & Objectives

### Project Aims
To develop a deep learning model that effectively assesses and predicts the risk of wildfires in Los Angeles for the next day. This model aims to enhance decision-making for fire prevention agencies and local governments by providing timely and accurate predictions. Long-term benefits include improved emergency preparedness, optimized resource allocation, and scalability to other regions or similar environmental monitoring applications.

### Project Objectives
- **Data Collection & Preprocessing:** Collect and preprocess data from weather stations, NASA, and fire protection organizations to create a unified semantic data structure supporting simultaneous region predictions and streaming data integration.
- **Model Development:** 
  - Develop a Transformer-based model targeting over 70% accuracy for high-risk wildfire incidences in the short term and 65% in the long term.
  - Transition the model infrastructure from TensorFlow to PyTorch for better alignment with the client’s requirements.
- **Visualization:** Present prediction results through static visualizations and develop interactive maps for real-time data display.
- **MLOps Practices:** Implement code modularization and a publish/subscribe-based streaming data architecture for real-time data handling.
- **Advanced Goals:** Predict the direction and size of wildfire spread post-initial assessment and integrate real-time data feeds to enhance model responsiveness.

---

## Metrics for Success & Long-Term Impact

- **Accuracy Targets:** Maintain over 70% accuracy for high-risk wildfire predictions in the short term and 65% in the long term.
- **User Interface Functionality:** Ensure an intuitive, actionable visualization interface.
- **Broader Goals:** Align with environmental and public safety objectives, offering scalable solutions adaptable to various regions and scenarios. Serve as a benchmark for advancing technological capabilities in disaster preparedness and environmental management.

---

## Project Questions

- **Central Question:** Can deep learning models reliably predict next-day wildfires in Los Angeles?  
- **Challenges:**
  - **Technical:** Developing a streamlined data pipeline and a deep learning model capable of handling non-linear patterns in highly imbalanced data.
  - **Non-Technical:** Addressing incomplete or outdated data through comprehensive literature review and experimentation to refine data collection and model training.

---

## Project Scope

- **Data Handling:**  
  - Ingest datasets from weather stations, NASA, and fire departments.  
  - Preprocess and clean data for model training.  
  - Use H3 Hexagonal Spatial Index for spatial standardization.

- **Model Development:**  
  - Implement feature engineering using techniques like PCA.  
  - Develop a baseline regression model and a Transformer-based architecture in PyTorch.  
  - Optimize model performance through iterative experimentation adhering to MLOps best practices.

- **Visualization & Reporting:**  
  - Create interactive maps to highlight wildfire risks.  
  - Develop a risk management report to address potential data inaccuracies or technical limitations.

- **Flexibility:** Adjust project scope based on client feedback and data availability, ensuring a tailored and robust solution.

---

## Technical & Operational Challenges

1. **Data Pipeline Design:** Streamline processes from ingestion to visualization.
2. **Model Accuracy:** Optimize performance for temporal-spatial data.
3. **Data Limitations:** Address incomplete or insufficient data through exploration and feature refinement.

---

This project showcases the transformative potential of deep learning in environmental risk management, paving the way for advanced predictive tools in public safety and disaster preparedness.
