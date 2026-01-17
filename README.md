# EMPOWER-KARE
This repository contains the dataset and code for our paper titled [EMPOWER-KARE: Deep Prompt Learning for Knowledge-aware Response Generation in Clinical Counseling and Legal Support Conversations](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10910093)

## KARE Dataset ##

The sample dataset is available in the 'EMPOWER-KARE/dataset/KARE-Sample.json'. The dataset contains the following information:

* dialogue_id: denotes a unique conversation number.

* utterance_no: denotes the utterance number in an ongoing conversation.	

* author_role: can take either of the two roles: agent/victim.
	** agent - the conversational agent acting as a counselor to help the victim.
	** victim - a user who is a victim of some crime.	
	** bot - the conversational agent acting as a counselor to help the victim.
	** user - a user who is a victim of some crime.	

* utterance: the text stated by the agent/victim.

* knowledge: Knowledge associated with the dialogue.

## Key Highlights of the KARE Dataset

- **Synthetic Data**  
  The dataset is entirely synthetic and anonymized. While it draws inspiration from real-world scenarios, it is not extracted directly from real-life conversations.

- **Ethical Compliance**  
  The dataset adheres to strict privacy laws and ethical guidelines, ensuring that no real individuals can be identified or harmed.

- **Anonymization Assurance**  
  The entire dataset is anonymized following the same principles applied to the sample dataset provided here.

  To request full data access, fill out the agreement form [linked here](https://docs.google.com/forms/d/e/1FAIpQLSd8vAwz_HB1uIyrRo4oA71aWzAf8GjRE1cKtYW5R4RpEolz1w/viewform?usp=dialog).

# EMPOWER Framework

The code for the EMPOWER framework can be found in the folder 'EMPOWER-KARE/EMPOWER-MODEL/'.

## Citations

If you are using this work or the dataset, cite the paper.

@article{priya2025empower,
  title={EMPOWER-KARE: Deep Prompt Learning for Knowledge-aware Response Generation in Clinical Counseling and Legal Support Conversations},
  author={Priya, Priyanshu and Tripathi, Armita Mani and Varshney, Deeksha and Firdaus, Mauajama and Ekbal, Asif},
  journal={IEEE Transactions on Artificial Intelligence},
  year={2025},
  publisher={IEEE}
}

