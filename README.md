# COVID-19-and-Pneumonia-Classification
Classification of COVID-19 and Pneumonia from Chest X-Ray Images (Done as a course project for CIS 520, UPenn during the Fall 2021 semester)

## Project Description

SARS-CoV-2, the virus that causes the respiratory disease COVID-19, has infected hundreds of millions of people
worldwide and caused millions of deaths. Early detection of COVID-19 through testing is critical, as prolonged
infection without treatment and quarantine can result in serious illness and spread of the disease to other individuals.
However, many standard COVID-19 tests, including the SARS-CoV-2 RT-PCR test, are in short supply in many
rural areas. Also, some tests suffer from a relatively low sensitivity. Due to these shortcomings of molecular COVID19 tests, a machine learning algorithm that can be used to accurately classify COVID-19 positive patients without
standard testing is desirable. Here we train multiple machine learning models for the classification of COVID-19
patients using only chest X-ray imaging data. We utilized baseline models (logistic regression, decision trees, random
forest, and bagging), neural networks (feed forward and CNNs), and transfer-learning-based methods. Our transfer
learning model, consisting of the pre-trained Inception V3 network connected to a feed forward network, reported
a sensitivity of 0.994 and AUC of 0.973. In addition to classifying patients as COVID-19 positive or negative, since
pneumonia is a common symptom of COVID-19, we also trained each of our models to predict whether or not a
patient has pneumonia using chest X-rays. The same transfer learning model described above attained a sensitivity
of 0.915 and AUC of 0.989 when trained for pneumonia classification. In addition, our models are computationally
fast, and since X-rays can be obtained within minutes, a COVID-19 diagnosis can be made far more quickly than if
using a RT-PCR test. Given the impressive performance and computational efficiency of our models, we anticipate
that they will become useful alternatives to molecular COVID-19 testing.
