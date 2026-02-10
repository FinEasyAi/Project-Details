MomoTech

# SPONSOR TRACK & HOTFOOT Ai CHALLENGE
## We Have Used BackBoard Api for the chatbot preperation as they were the sponsor!

We team MomoTech have built **FinEasy**.**FinEasy** is a financial analyzer project developed as part of DevSoc26, where we participated in the Hotfoot AI Challenge and successfully implemented both assigned tasks. The project focuses on building a modular, scalable AI-driven system with clear separation between frontend interfaces, backend services, audio processing, and data handling.


The primary objective of the project is to analyze financial data through multiple interaction modes, including audio and text, while maintaining a robust pipeline that can be extended for real-world use cases. The architecture emphasizes clarity, independent service deployment, and smooth user flow from landing to analysis.

**Basic Figma Link:-** (https://www.figma.com/design/L1ORHknis2mOVSe22XZ8IA/Untitled?node-id=23-2&t=R2ZHdZi56TXe4cLK-1)

**Task 1** of the challenge was centered around an audio-based workflow. This includes an audio challenge interface where users can authenticate, submit audio inputs, and receive processed outputs through an AI-powered pipeline. The system handles audio ingestion, processing, and storage efficiently while keeping the user experience minimal and responsive.

Repo Link :- mvpAnalyzer(https://github.com/FinEasyAi/mvpAnalyzer)

**Task 2** of the challenge was around an Finanical-documets to summarizer. This includes the financial data we feed into our own personalized chat bots and ai agents that would assists and tell more about the docuemntation and explain the financial flow in depth.

Repo Link :- mvpLanding(https://github.com/FinEasyAi/mvplanding)

Overall, MomoTech demonstrates a complete end-to-end AI application workflow, from user interaction to backend processing and data management. The project reflects our approach to building production-oriented systems with clean architecture, clear service boundaries, and scalability in mind.

To run them we need speical Localhostport to be used they are:-

landing page **5173**
audio and login mvp **5177**
text mvp **5175** 
audio pipeline (Ml) **5567** 
Database **5432** 
Backend Server **8002** 
landing_basic_functiionality **3000**

Also we have kept all of them into one **Combinedrepo** for easier usecase. So the repo link for it is:-
combinedFrontend (https://github.com/FinEasyAi/combinedFrontend)

-----------------------------------------------------------------------------------------------------------
How to Run the Project?
-----------------------------------------------------------------------------------------------------------

To run the project you can use the **Docker**.
First, clone the repository and move into the project directory.

git clone https://github.com/FinEasyAi/combinedFrontend.git
cd combinedFrontend


Build all Docker images defined in the project.

docker compose build


Start all services in detached mode.

docker compose up -d


Check the status of all running containers.

docker compose ps


View logs for all services.

docker compose logs -f


View logs for a specific service.

docker compose logs -f <service_name>


Stop all running services.

docker compose down


Stop services and remove volumes, networks, and containers for a clean reset.

docker compose down -v


After the services start successfully, the application will be available on localhost ports 5173, 5177, 5175, 5567, 8002, 5432, and 3000.
