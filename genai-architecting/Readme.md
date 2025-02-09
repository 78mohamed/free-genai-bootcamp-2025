## Technical Considerations

This is a high-level diagram that is used to communicate to key stakeholders the business solution we are implementing.

![genai-architeching](genai-architeching.png)

## Architectural/Design Considerations

- **Requirements, Risks, Assumptions, & Constraints**:
    - **Requirements**: Using GenAi to create a language learning app to learn Arabic.
    - **Risks**: The user might not get the expected outcome they want from the model or a fully correct answer.
    - **Constraints**: The system and the tools used need to be in the free tier and open source due to a tight budget.

- **Data Strategy**: Data will be collected from books and audio that our organization owns to avoid any copyright issues. We will also scrape any resources that are free for public use on the internet.

- **Model Selection and Development**: We will use Llama 3 because Llama 3 is an open-source model, and Meta made the model's code and weights publicly available, allowing developers to access and build upon the technology.

- **Infrastructure Design**: We will use self-hosted servers, as after doing some calculations, this will be much cheaper than using a cloud provider. Additionally, we don't expect a lot of traffic, so we won't need high availability.

## Business Considerations

- **Use Cases**:
    This model will be used to help students learn the Arabic language on the language portal by interacting with them through various activities, like:
    - Sentence constructions
    - Vocabulary flashcards practice
    - Daily grammar challenges

- **Complexity**: Adding a GenAI model will add complexity in the following areas:
    - We will need to invest in our infrastructure.
    - The app will need to know how to interact with the model.
    - Feedback and monitoring of the model's prompts is necessary to fine-tune it and improve its efficiency.

- **Key Levers of Cost**:
    - We will need to have an AI expert to help us fine-tune our model.
    - We will need to invest in our infrastructure to host the model locally.
