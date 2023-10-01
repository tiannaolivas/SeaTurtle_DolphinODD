# SeaTurtle_DolphinODD
### Overview - purpose
The main objective of this agent-based model is to explore and understand the willingness of stakeholders to change their behavior towards common bottlenose dolphins (Tursiops truncatus) and Gulf of Mexico sea turtles (e.g. Loggerhead (Caretta caretta), Kemp’s Ridley (Lepidochelys kempii), and Green Sea Turtles (Chelonia mydas)) as predicted by indicators such as demographics (race, gender, education), general attitudes of marine wildlife, motivations of coming to the coast, and willingness to abide by laws.
This model seeks to answer:
Who do the stakeholders tend to be that are more willing to change their behavior to reduce negative interactions with dolphins and sea turtles, as predicted by demographics (race, gender, education), general attitudes of marine wildlife, basic knowledge of the laws, and species’ biology, and motivations of coming to the coast?

### Overview - entities, state variables, and scales
1. Entities: The model simulates individual people as the agents, these are individuals who go to the coast of Alabama with intentions of recreating, where the demographics of such people are predicted to change in some way (the average age is increasing/decreasing, a larger percent of one race over others, etc.). 
2. State variables: Each individual person will have a range of demographics (race: white/ non-white, gender: male/ female, education: less educated/ more educated), knowledge of wildlife laws and behavior/ ecology of wildlife (less knowledgable/ more knowledgable), and motivations for coming to the beach.) 
3. Scales: The model operates on a temporal scale. Temporally, it simulates that as time passes and variables of the individual change, their willingness to change certain behaviors also changes.
### Overview - processes
Individuals may vary in their willingness to change certain behaviors predicted by their demographics, 
### Design concepts
1. Basic Principles: The model is based on an analysis of human-wildlife interactions with social science through surveys.
2. Emergence: The model aims to reduce human-wildlife interactions occurring on the coast of Alabama between sea turtles, dolphins, and coastal tourists.
3. Adaptation: Agents (individuals) and their willingness to change certain behaviors and how that will develop over time as demographics change.
4. Objectives: The primary objective of the individuals is for a transition to certain behaviors that can contribute to the reduction of human-wildlife interactions between people who come to the coast of Alabama to recreate and Gulf sea turtles/dolphins.
### Details - 
1. Initialization: The simulation begins with a defined number of individuals with random demographics and characteristics regarding recreational activities in coastal Alabama. 
2. Input data: As time progresses, demographics are projected to change in a specific way that is related to current demographic data (e.g. younger people are going to the coast, more educated people are going to the coast, etc.)
3. Submodels: There will be submodels for projected demographic change.
4. Parameters: Model parameters include various demographics for individuals, various behavioral responses, and a projected change in demographics.
5. Observations: Stakeholders demographics and: 
    1. Basic knowledge/attitudes
    2. Behavior
    3. Information Sources
Will have a quantified relationship
6. Initialization and termination: The simulation begins at time step one and can continue for 50 steps.
7. Stochasticity: Can this type of model have stochastic elements?
