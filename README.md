# e-phishGen
Official Repository of "E-PhishGen: Unlocking Novel Research in Phishing Email Detection", presented at CCS AISec 2025. 

This repository is currently under construction, and it will be available by October 10th 2025, when the paper will be presented.
```
  @article{pajola2025phishgen,
    title={E-PhishGen: Unlocking Novel Research in Phishing Email Detection},
    author={Pajola, Luca and Caripoti, Eugenio and Pizzi, Simeone and Conti, Mauro and Banzer, Stefan and Apruzzese, Giovanni},
    journal={arXiv preprint arXiv:2509.01791},
    year={2025}
  }
```
### E-PhishLLM Dataset

In this repo, you can find *ephishLLM.json*, our dataset containing phishing emails generated in both English and Italian. 
The dataset is organized as a list of dictionaries. Each entry contains:

  - Subject of the email
  - Body of the email
  - Class type, 0 for legitimate emails, 1 for phishing
  - Language of the email

Below is an example of two ephishLLM entries:
{
        "Subject": "Exciting Sustainable Project Collaboration",
        "Body": "Hi Nina,\n\nI hope you’re doing well! I’m thrilled to reach out regarding our upcoming collaboration focused on sustainable practices. There’s so much buzz on our end about working together with Elysium Cosmetics!\n\nCould you please provide some insights on the formulation timelines for this project? This will help us align our plans and ensure a smooth process on both sides.\n\nLooking forward to your feedback and excited about the journey ahead.\n\nBest regards,\n\nGiovanni Ferrari\nBrand Partnerships Associate",
        "type": 0,
        "Language": "en"
    },
    {
        "Subject": "Urgent: Immediate Action Required - Password Change Needed",
        "Body": "Dear User,\n\nWe have detected unusual activity in your account that requires your immediate attention. To ensure your account's security, please reset your password using the provided link within the next 24 hours.\n\nFailure to do so may result in temporary suspension of your account. Kindly use the following link to proceed: <<link>>\n\nThank you for your immediate attention to this matter.\n\nSincerely,\nIT Support Team",
        "type": 1,
        "Language": "en"
    },
