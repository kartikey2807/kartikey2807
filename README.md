## About me   
***Kartikey Sharma***   
Personal Email: [kartikey2807@gmail.com](mailto:kartikey2807@gmail.com)   
LinkedIn: [kartikey2807](https://www.linkedin.com/in/kartikey2807)

<div align="justify">
I recently completed my master's in data science, specializing in machine learning and statistics, from Uppsala University, and have hands-on experience in generative modeling (LLMs, GANs, VAEs, etc.), privacy-based ML, and distributed learning in edge networks. I did my master's thesis at Scania, where I implemented a <i>transformer-based variational autoencoder</i> to identify anomalies in truck components for predictive maintenance and trained the model using online and federated learning to improve generalizability and communication efficiency while satisfying memory constraints. I also collaborated with researchers from Uppsala University to build robustness into FL training by using a <i>distributed WGAN</i> model to detect and filter malicious clients (with data or gradient poisoning) during aggregation. Aside from this, I have worked with AI Sweden to develop a novel <i>privacy-preserving model</i> using the exponential mechanism and empirically compared it against state-of-the-art DPSGD in terms of performance and privacy leakage to membership inference attacks. Before my master's, I was working as a data analyst in the US healthcare space. Tools and languages I work with -->
</div>
<br>

**Languages/Libraries**: Python, C++, PyTorch, Scikit-learn, Pandas, NumPy, SciPy, Matplotlib, Transformers, FEDn, Flower, and LangChain   
**Cloud Services**: AWS S3 buckets, Data Migration Service (DMS), EC2, and SageMaker    
**Database Query Languages**: SQL  
**DBMS**: PostgreSQL, Snowflake, Elastic DB, and AWS Redshift  
**Visualization Tools**: Microsoft Power BI  
**Version Control**: Git  
**Orchestration Tools**: Apache Kafka, Apache Airflow, Docker, Ansible, and Kubernetes

|Project|Skills|
|:------|:-----|
|[Online and Federated Learning for Predictive Maintenance](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A2083501&dswid=5960)|`federated learning` `online learning` `transformers` `autoencoder`|
|[Privacy-Preserving ML with Exponential Mechanism](https://github.com/kartikey2807/EXPM_NF-MIMIC3-Results)|`differential privacy` `exponential mechanism` `normalizing flows`|
|[Byzantine-Robust Federated Learning with WCGAN](https://github.com/kartikey2807/robust-federated-learning)|`conditional GANs` `federated learning` `MNIST` `PyTorch`|
|[LLM ChatBot with Retrieval Augmented Generation](https://github.com/kartikey2807/Uppsala-events-guide-Bot)|`Gemini API` `LangChain` `RAG` `Elastic DB` `Gradio` `chatbots` `LLMs`|


**Publications**

```
@inproceedings{sharma2022wasserstein,
  title={Wasserstein GANs-Enabled Spectral Normalization on Credit Card Fraud Detection},
  author={Sharma, Kartikey and Sharma, Abhishek and Bansal, Sulabh},
  booktitle={International Conference on Innovations in Computational Intelligence and Computer Vision},
  pages={155--166},
  year={2022},
  organization={Springer}
}
```

## Experience

<div align="justify">
Near the end of my master's, I interned with the R&D team at Scania, where I further improved on the work from my thesis <i>Online and Federated Learning for Predictive Maintenance in Heavy-Duty Vehicles</i>. I generated new sensor data streams (modeled as bounded random walks) from a <a href="https://www.causalchamber.ai/">Causal Chamber</a> wind tunnel device. And added stochastic degradation artifacts to roughly mimic the wear and tear of a mechanical truck component. I referred to the existing <a href="https://github.com/mohyunho/N-CMAPSS_DL">N-CMAPSS</a> remaining useful life (RUL) dataset. Then I developed a deployable, lightweight federated learning framework to train multiple models collaboratively to estimate the health index, improving generalizability without exposing the underlying data. I used a cumulative sum (CUSUM) statistical test to evaluate model performance in tracking the health index. I have also worked as a data analyst for over 2 years in the US healthcare space, collaborating with hospitals and insurance providers. I built Python workflows to integrate medical, claims, and pharmacy data into a unified data model, and used AWS S3, DMS, and Snowflake to streamline data ingestion and cloud warehousing. I was responsible for maintaining the ETL scripts on Redshift and making changes based on customer requirements. I also developed PostgreSQL validation scripts to ensure consistency between the database schema and flag KPI deviations, and automated the ingestion and validation processes, reducing data update time by 35%. Lastly, I developed Power BI dashboards to track medication expenditures and rank care providers based on readmission rates and operating costs. I delivered insights to help our clients reduce drug expenses by 8% and improve patient care.
</div>
</div>
