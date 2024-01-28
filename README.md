# Medical Chat - User Guide (WIP)

## Overview

**Medical Chat** is a conversational AI chatbot designed to provide information and lifestyle advice for promoting heart health. It leverages advanced AI techniques to offer responses based on credible medical sources, specifically the "Healthy Heart" guide by the U.S. Department of Health and Human Services and The Gale Encyclopedia of Medicine, Second Edition.

## Key Features

1. **Information Retrieval**: Draws on established medical literature to provide accurate and reliable advice.
2. **Conversational Interaction**: Users can interact in a natural, conversational manner.
3. **Heart Health Focus**: Specialized in providing advice and information related to heart health.
4. **Source Referencing**: Cites sources for the information provided, ensuring transparency and trustworthiness.

## How It Works

### User Interaction

1. **Start a Conversation**: Simply type in a question or a topic related to heart health.
2. **AI Response**: The chatbot uses its programming to retrieve relevant information and present it in an easy-to-understand format.
3. **Follow-Up Questions**: Users can ask follow-up questions for more detailed information.


### Behind the Scenes

- **Database Use**: The chatbot has a special storage area (called `FAISS`) where it keeps a lot of medical information. Think of it like a digital library where the chatbot can quickly find answers.
- **Custom Prompts**: When you ask a question, the chatbot uses a special way of figuring out what you're asking. It's like having a guidebook that helps it understand and answer your questions better.
- **Finding Answers**: The chatbot has a special method (called retrieval QA chain) to search for the best answers. It's like having a super-fast detective inside the chatbot that finds the most useful clues from the digital library.
- **Using the Right Tools**: The chatbot uses tools named HuggingFaceEmbeddings and FAISS. These tools help the chatbot search through its digital library really quickly and accurately, like a super-fast librarian.
- **Staying on Topic**: The chatbot is set to be very focused and precise (that's what we mean by a low temperature setting, 0.2). This makes sure that it sticks to the point and gives you relevant answers.


## Developer Section

Medical Chat is brought to you by:

- **Dr. Victor Ukwu, MD**: A Distinguished Family Medicine Physician and graduate of Meharry Medical College School of Medicine. [LinkedIn Profile](https://www.linkedin.com/in/victor-n-ukwu-md-9bb06552/)

- **Jamall Winn**:  Information Architect with a passion for Embedded AI. [LinkedIn Profile](https://www.linkedin.com/in/jamall-winn-994b0935/)

---

*Please note that while Medical Chat aims to provide accurate and helpful health information, it is designed to supplement, not replace, professional medical advice, diagnosis, or treatment. Users are encouraged to use this tool responsibly and safely, always considering it as a source of supplementary information. The contributors and developers of Medical Chat make every effort to ensure the reliability of the information provided, but they do not assume liability for any damages or implications arising from the use of this tool. It is important for users to consult healthcare professionals for personal health concerns and not solely rely on the advice provided by this chatbot.*
