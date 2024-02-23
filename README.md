# CS201 Winter 
## 1/9/24 Week 1 Tuesday Lec 1
* Presented by Paul Eggert
* How Computer Science saves Biodiversity
* Doctor Tim Haas
* scruffy cycad
* Problems to solves
    * peer to peer secure sharing of criminal intelligence
    * reconstructioning criminal social network from censured link data
    * construct persistent, self-healing, and self-restrating IoT robots to monitor political-ecological systems
* Aimed at middle-to-senior managers for for-profit orgs
* Biodiversity is going away
    * The sixth mass extinction in the history of the planet is underway
    * Most large, wild mammals, many fish species, and many rare plants will be gone by 2060
* Cycads, sharks, and elephants
    * For instance, the cycad plant, poached as a status symbol and investment, has been on this planet for about 280 million years. Dinosaurs 245.
    * The great white shark is endangered
    * African savanna elephant was added to the IUCN Red List in 2021
* What to do
    * To curb this non-reversible destruction, wholesale killing of animals and plants need to stop, and habitat destruction needs to be curtailed
    * But achieving these two goals will require initiatives that move people away from these behaviors
    * These initiatives need to be derived from credible models of those political-ecological systems that host endangered species
* Private enterprise could save biodiversity
    * Private, for-profit firms could save biodiversity by developing and running these initiatives
    * Really, how?
    * In short, by making biodiversity conservation profitable
* Selling to biodiversity-concerned customers
    * Step 1: A firm identifies a species they want to save
    * Step 2: They launch a new product or service called a biodiversity offering that is attached to a biodiversity project.
    * Step 3: They maintain a public-facing biodiversity dashboard that contains real-time, detailed, and audited information on the project and the species being saved
* Why would this work?
    * Firms exist to make a profit. Biodiversity offerings would be priced and managed to be profitable
    * Biodiversity offerings would tap into a giant market niche of people wanting to help but feeling powerless
* Firms are resourceful and distributed
    * Firms hold most of the world's wealth and expertise. Collectively, they have the resources to solve a planet-level problem
    * Because firms are not all under a single, hierarchical control structure, a few newly-minted tyrants would not be able to shutdown all firm-level biodiversity projects.
* Building a biodiversity project
    * First, the firm builds a model of the political-ecological system that contains their species
    * Based on this model, the firm identifies a biodiversity project that will encourages species-preserving behaviors
    * Finally, the firm implements this project and an attendant monitoring program that feeds real-time data to the firm's biodiversity dashboard
* Suggested biodiversity projects (ranked by effectiveness)
    1. Improving habitat by reducing the firm's raw material demands from species-hosting countries
    2. Improving habitat by relocating/shutting operations within species-hosting countries
    3. Reducing poaching by owning and operating a production/service facility in a city that draws people away from ecological hotspots
    4. Providing expertise, data, software, and hardware to international law enforcement teams fighting wildlife trafficking
    5. Owning and operating a private wildlife reserve
    6. Owning and operating captive breeding facilities for critically-endangered species.
* Needed technology
    * To be credible, political-ecological models need to be statistically fitted to parsed streams of new articles, and streams of ecological metric observations such as species abundance
    * These fitted models need to be simulated under different biodiversity projects to find ones that work
* Modeling a political-ecological system
    * Agent-based submodels make decisions about actions that affect an at-risk species
    * Agents include poachers, kingpins, consumers, farmers, wildlife protection agencies, and governemnts.
    * An individual-based submodel of how the targeted species' abundance affects and is affected
* Computational challenge: Model assessment
    * Runs of these stochastic, many-parameter models are expensive. Hence, massive computing resources and new optimization algorithms are needed to compute
* Computational challenge: Search for the optimal ecosystem management plan
* Forecasted actions under a proposed project
    * The following is a plot of the cheetah system simulator's actions history under a proposed project
    * Lines connect action-reaction sequences
    * One frequent action sequence or episode is:
        * poaching event
        * negative ecosystem status report
* An Example: An in-country
* Create companies to employ people who would otherwise be poachers
## 1/11/24 Week 1 Thursday Lec 2
* Adaptively Caching Context Information for Fast Concurrent Access in Internet of Things
* Shakthi Weerasinghe
* 01 Context & Context Management
* Where the IoT Big Data comes from?
    * Twenty-five gigabytes: that's how much data a connected car will upload to the cloud every hour
* Context Information
    * "Any information that can be used to characterize the situation of an entity. An entity is a person, place, or object that is considered relevant to the interaction between a user and an application, including the user and applications themselves."
* Content Spaces
    * Foundation for context representation, reasoning, validation, & prediction
    * Naive Context Spaces (NCS)
    * Context Spaces leads towards a general context model to aid reasoning about and describing context, and to design operations for manipulating and utilizing context
        * Geometrical spaces metaphor
        * The state-space model [Ogata, 67]
        * Control Theory
    * Application space - UoD
* Context Spaces Model: Example
    * Context:
* Context Querying
* Context-as-a-Service
    * Enables global standardization and interworking among different context providers and consumers in IoT environments.
* Context Definition & Query Language (CDQL)
* 02 ACOCA: Challenges & Opportunities
    * Problems in caching context information
* Efficiency of Context Queries
    * Responding to context queries are time-critical
    * Context needs to be computed proactively to notify in time
    * But context is transient, and larger that data in total size
* Summary of Related Work
* Traditional Adaptive Data Caching vs ACOCA
* 03 Parameterizing ACOCA Decisions
* Strategies for Context Retrieval
* Formal Models of Context Retrieving
* NAd Retrieval
* FC Retrieval
* Re Retrieval
* Results and Discussion
* Four further problems
    1. Not paramters can be efficiently monitored of all billions of situations
    2. What parameters are more important to make the context caching decisions?
    3. What parameters are relevant to making context fresher?
    4. Parameters can have varying weights to how significant they are to make caching decisions.
* Context Freshness Monitoring System (CFMS)
* Evaluation and Results (Different Caching Algorithms)
* Estimating the Refresh Rate
* 04 Concepts for ACOCA
* Definition of Adaptive Context Caching
    * The decision about what context to cache in near real-time to achieve cost efficiency goal(s) measured by Quality of Service (QoS) and Quality of Context (QoC) parameters. These decisions should be comparable with a benchmark trained with absolute prior knowledge, while using the minimal necessary resources and ensuring minimum loss to quality of cached context (QoCaC)
* Formulating an Adaptive Context Caching Mechanism
* Context Prediction and Estimation Engine
* 05 Reactive & Proactive Context Caching
* Current Value of Returns from Context Caching
* How Long? When? to Cache
* How to Cache Context?
* Eviction Heuristics
* Experimental Hueristics
* Experimental Setup
* Results and Discussion
* Reactive Adaptive Context Caching
* Context Selection for Caching
* Making the context selection decision
* Context Query Classes and Overcoming Uncertainty
* Adpative Refreshing Rate Setting
* Time Aware Context Cache Management
* Results and Discussion (1-SLA) - Performance Efficiency
* Results and Dicussion (1-SLA) - Overall
* Results and Discussion (n-SLA)
* The missing objective is maximizing QoC
* ConCQEng
* Results and Discussions
* Proactive Context Caching
* Structural Changes & In Cache Verification
* Results and Discussion
* Future Directions
* Publications
## 1/25/24 Week 3 Thursday Lec 3
* Topic Models
    * UN
* GANs
    * kernel discriminators
    * training GANs
    * Evan Becker
* AI for Hemodynamic Analysis of Cardiovascular
    * Gary Chen
    * Hemodynamics
        * Heart rate, Flow velocity, Blood pressure
* Multi-agent Reinforcement Learning: Asynchronous Communication, Robustness and Privacy
    * Reinforcement Learning
    * Cooperative Multi-Agent Reinforcement Learning
    * Topic 1: Asynchronous Communication
* Topic 2: Robust Reinforcement Learning
    * Adversarial attack for Communication
* Topic 3: Differentially Private Reinforcement Learning
    * Multi-Agent Reinforcement Learning
* Non-Euclidean Mixture Model for Social Network Embedding
* Social Network Embedding Models
    * NMM-GNN Architecture
    * Evaluation: Classification & Link Prediction
* Situational impairments
* Chameleon: Compoisitional Reasoning with Large Language Models
    * Chain-of-Thought Prompting (CoT)
* Predicting Perinatal Depression Using Electronic Health Data
    * Perinatal depression
* Harnessing Black-Box Control to Boost Commonsense
    * Motivations -- Why?
    * Build Commonsense Scorer
* Improving the Trustworthiness and Generalization of Machine Learning Models
    * Research Overview
    * Trustworthiness
        * Evaluate and improve certified robustness against adversarial attack
    * Red Teaming Language Model Detectors with Language Models
    * Universality and Limitations of Prompt Tuning
    * Input Tuning vs. Weight Tuning
    * Absorbing format with prompt tuning
* Predicting and Interpreting Energy Barriers of Metallic Glasses with Graph Neural Networks
* Motivation: AI for Material Science Research
    * A Graph Machine Learning Formulation of Energy Barrier Prediction

## 1/30/23 Week 4 Tuesday Lec 4
* Unsupervised Learning of Segmentation
* Making sense of sensory data 
* Supervised Undifferentiated Multi-Task Learning
* Segment Anything Model
* Learning - Drilling
* Learning - Mulling
* what is a baby supposed to learn?
* What can we learn from nothing but data?
* From undivided sensation to bounded rationality?
1. Unsupervised Learning of Generic Objectives
* Challenges of Video Object Segmentation
    * Motion helps, Appearance helps
* Object Segmentation from Unlabeled Videos
    * Our work: Segmentation and Flow Decomposition
* Flow = Displacement Across Frames
* Optical Flow = Local Displacement Per Pixel
    * Concurrently Learn Segmentation and Flow Estimation
* Our Appearance Motion Decomposition Model
* Training on Youtube-VOS: 4000 Videos, 5s, 94 Categories
* Single Image to Multiple Segmentation Channels
* Objectness Emerges in a Particular Channel
* The Emergence of Objectness: Why and How?
    1. Segmentation uncertainty
    2. Reconstruction error
    3. Mask center and spread
* Zero-Shot Video Object Segmentation
* Figure-ground Segmentation Learned without Edges, Optical Flows, or Saliency but with only Instantaneous Visual Constancy
2. Unsupervised Learning of Hierarchical Semantics
* Semantics Intrinsically Has Multiple Levels of Granularity
* Segmentation: Pixel-wise Representation Learning
    * co-segmentation use features to get segmentation
    * feature learning
    * Key insight: While we don't know X or G, any good X makes G consistent!
* Feature Learning by Hierarchical Segment Grouping
    * Feature learning loss + goodness of grouping loss
* SOTA on Unsupervised Semantic Segmentation
* First Unsupervised Hierarchical Semantic Segmentation
* Contextual Visual Segment Retrieval
3. Unsupervised Learning of Visual Context
* Semantics Is Fundamentally Grouping Not Naming
* Human-Object Interaction Recognition
* Supervised Approach: Discrete Classification
* Our Approach: Discriminative Feature Learning
* Oracle: Co-occurring Semantic Statistics for Context
* Human-Object Interaction Benchmarks
* Recognize Interactions via Retrievals
4. Unsupervised Learning of Parts-and-Wholes for Recognition
* New: Recognition w/ Hierarchical Segmentation & Adaptive Tokens
* Hierarchical Segmentation By Recognition
* Hierarchical Parts-and-Wholes For Recognition
* Unsupervised Discovery of Parts-and-Wholes
* Better Semantic Segmentation
* Better Semantic Segmentation w/o & w Fine-Tuning
* Multi-faceted Inverse Learning Problem
* Unsupervised Structured Inverse Learning Problem
* Agenda: Unsupervised Learning of Mid-Level Vision
## 2/1/2024 Week 4 Thursday Lec 5
* Precision Healthcare: Guiding Anti-Cancer Therapy through Multimodal Biomedical Imaging and Machine Learning
    * Mingqi Han, Ph.D.
* Tumors: High Energy Demanding Regions in the Body
    * Growth of tumor cells requires nutrients and building blocks
* Targeting Mitochondria in Cancer
    * Mitochrondrial metabolism fuels tumor growth
    * Bioenergetics: generate ATP
    * Upregulated gylcolysis: generate building blocks ...
* Early mitochondria activation in tumorigenesis
    * Tumor cells require energy and nutrient to proliferate
    * Transformed cells upregulate mitchondrial mass
    * Pre-clinical settings achieved effective response by targeting mitochondrial vulnerability
* Targeting Mitochondria in Cancer
    * Clinical trials targeting mitochondria in tumor
* Overview
    * Spatial Mapping of Mitochondria
* Mitochondrial Bioenergetics
    * Electron passage and proton pumping
    * Electron transport chain (ETC)
    * Oxidative phosphorylation (OXPHOS)
* Folded Inner Membrane: Mitochondrial Cristae
* Mouse Models and Histology
    * Genetically Modified Mouse Models (GEMMs)
* In vivo Measure Mitochondrial by PET/CT
* Reprogrammed Glucose Metabolism in Cancer
* Stratify Tumor by Metabolic Signature
* What Dictates the Signal Difference
* Metabolic Signature, Histology, and Respiration
* Structure-Function Correlation
    * In vivo imaging: fluorescent staining unfriendly
* Problems with 2D TEM
* Analyzing Tumors with a "Google Earth" Approach
    * Extracellular matrix: neutrophils infiltration
* Vasculature and Microenvironment
    * Metabolic Signature, Vasculature, Tumor Landscape
* Distinct Mitochondrial Networks
* Mitochondrial Cristae Subtypes
* Deep Learning Based Organelle Analysis
    * Organelle Segmentation
* The Eureka! Moment
* Mitochondrial Subpopulations
    * Peri-droplet Mitochrondria (PDM)
    * Peri-nuclear Mitochondria (PNM)
* PDM associated Type I Cristae Structure
* Compartmentalized Mitochondrial Metabolism
* Nutrient Deprived Cell Growth
* Summary
    * Startify tumors based on their metabolic signature: Oxidative v.s. Glycolytic
    * Distinct mitochrondrial networks associated with different metabolic signatures
    * Oxidative tumors
* Stratify GEMMs by LKB1 Status
    * How do tumor metabolic signature change over time?
* Longitudinal PET on Bioenergetics
    * Metabolic Signature
* LKB1 Regulates Peri-droplet Mitochondria (PDM)
* Summary
    * LKB1 expression sustains or elevates the bioenergetic processes in lung tumors
    * The metabolic signature of a tumor can switch from oxidative to glycotic upon the loss LKB1
    * LKB1 moderates the iteraction and communication between mitochrondria and lipid droplets
    * The formation of PDM can alter the structure of mitochrondrial cristae to promote
* Lipid Content as a Predictive Secondary Biomarker for Therapy Response
* Structural Analysis of Chemical Compound to predict their
    * "Nutrient storage" station
    * Influence "Drug Metabolism"
* Precision Healthcare: Predict Therapy Resistance
* Correlating Imaging with Diagnosis Observations
## 2/6/2024 Week 5 Tuesday Lec 6
* Re-searching the foundations of Heuristic Search
    * Notes on five problems in connexion with graphs, heuristics, and re-expansions
* High-level overview of problems
* One of three pan-Canadian AI strategy institutes
    * 2002 -> present
    * 36 Canada CIFAR Chairs
    * 400+ trainees
* https://upperbound.ai/
    * Travel scholarships
* Traditional Games
    * Machine Learning in Games
    * Solving Games
* Search
    * Core search algorithms
    * Multi-agent pathfinding
* Games
    * Pathfinding in games
    * Puzzle entropy
    * AI assisted design
* MSc and PhD positions
* Heuristic Search and Shortest Path Problems
* Timeline of Search
    * Dijkstra's Search, A* Search, Weighted A*
    * IDA*
    * Bidirectional Search
* State Re-expansions
    * Consistent Heuristic
    * Inconsistent Heuristic
    * Many algorithms encounter worst-case behavior when re-searching through previously visited states
        * Dijkstra Algorithm
        * Bidirectional Search
        * A*
        * Weighted A*
        * IDA*
* Algorithm/Problem Recent Solutions
* Dijsktra's Algorithm (Uniform-Cost Search)
    * g(n) be the cost of best known path from start to n
    * Expand states from low to high g(n)
    * Assume c(a,b) > 0
* Unidirectional Problem
    * Start goal
* Negative Edge Costs
    * What if some c(a,b) < 0
        * Re-expand states (Johnson, 1973)
        * Exponential worst-case complexity
    * Bellman-Ford fixes this
        * Expand all states iteratively (not greedy)
        * O(V * E) -> O(V^2)
* Bidirectional Search
    * Let g_F(n) be the cost of the best known path from start to n
* Bidirectional Problem
* Negative Edge Costs
    * Same problem as Dijkstra's algorithm - not formally analyzed
* A*
    * A Formal Basis for the Heuristic Determination
    * Let g(n) be the cost of the best known path from start to n
    * Let h(n) be an estiamte of the distance from n to goal
    * Expand states from low to high f(n) = g(n) + h(n)
    * Assume either c(a,b) >= 0 or c(a,b) > \epsilon
    * Assume h(n) is both admissible and consistent
* A* inconsistent heuristics
    * Equivalent to negative edge weights in Dijsktra's algorithm
    * Exponential worst-case
    * Algorithm B (Martelli, 1977) - O(V^2)
* Bidirectional Heuristic Search
* Bidirectional Search + Heuristics
    * Dijsktra -> Bidirectional Dijkstra
* Explanation: Frontiers Miss
* Explanation: Frontiers Meet Early
* Initial Solution: Consistency
    * Consistent Heuristic:
        * Avoid frontiers crossing
        * Improve heuristics
* Problem
    * No bidirectional theory
        * Algorithms terminating late
        * Optimality of algorithms not well defined
* Unidirectional Theory
    * If f(u) < C^* then we must expand u
* Bidirectional Problem - Front to End
* New Theory
* Comparison
    * A^*: Repeatedly expand state with lowest f(n)
    * NBS: Repeated expand pair of states with lowest lb(u,v)
        * May expand the same state in each direction
        * No more than 2x minimal expansions / no algorithm can beat this
* Consistency
* New theory
* Experimental Results 24 Puzzle; 10GB Heuristic
* A* and IDA*
* Better Algorithms
    * Algorithm B (1977) does O(N^2)
    * IBEX/BGS does O(NlogC^*)
* Two Problems
    * Misleading heuristic causes ex-expansions
        * Could avoid with Dijkstra's algorithm
    * Heuristic may prune many states
        * Don't want to discard completely
* Better Algorithms
    * If we knew C^* (solution cost) we could
    * Estimate C^* using exponential search
        * Use a budget to control the cost of overestimates
        * What is maximum $f$ fully explored with K expansions
* Weighted A*
    * Heuristic search viewed as path finding in a graph
    * Let g(n) be the cost of the best known path from start to n
    * Let h(n) be an estimate of the distance from n to goal
    * Expand states from low to high f(n) = g(n) + w*h(n)
        * w is an inflation factor that bounds suboptimality
        * ...
* Weighted A^* (HPA+)
* Weighted A^*
    * Weighted A^* can do O(N^2) re-expansions of N states
    * Re-expansions are optional
* Alternate Weightings
    * Suppose we write priority function as: f(n) = \phi(h(n), g(n))
    * what properties on $\phi$ allow us to avoid reopening states
* Piecewise 
    * Suboptimality
* Weighted A^* Summary
    * Previous work didn't deeply analyze the impact of revisits
    * Rich class of improved priority functins
    * Can control where the suboptimality arises
* Open Question
    * Given a general graph without negative cost cycles:
        * Extract A^* search
## 2/13/2024 Week 6 Tuesday Lec 7
* From Haptic Illusions in Virtual Realityy to Beyond Real Interactions
* Commercialization of virtual reality (VR) headsets
* VR applications
    * Exploring, artifacts, learning
    * With limited haptic feedback
* Missing the sense of touch in VR
* Vision of swarm of drones providing haptics
* Goal: feeling textures and forces in VR
* Implementation: using a safe-to-touch drone
* Many challenges, including low position accuracy
* Haptic devices that provide the sense of touch
* All haptic devices have hardware limitations
    * Accuracy, speed, resolution
* Our perception is imperfect, so we do not need perfect hardware
* We can leverage limits of our perception to create an illusion of improved performance
* Outline
    * Illusion of realistic haptic rendering
    * Beyond-real interactions
* Using a safe-to-touch drone for haptics in VR
* People instinctively touch safe-to-touch drones
* Ideally, drone is positioned at contact point
* In practice, position accuracy is a problem
* Using retargeting illusion as a solution
* How the brain plans and controls movement
* Improving the perceived position accuracy of drones through dynamic retargeting
* Overcoming position inaccuracies with illusions
* Outline
    * Illusion of realistic haptic rendering
* Limited speed delays mobile robot's arrival time
* Touch prediction for dynamic retargeting
* Outline
* Angle redirection for improved resolution
* Detection thresholds for angle redirection
* Evaluating performance for angle redirection
* Scaling up for improved resolution
* Detection thresholds for scaling up
* Evaluating performance when scaling up
* Outline
    * Illusion of realistic haptic rendering
* We can remap users' movements in VR
* Beyond-real interactions
* Untethered headsets and walking in VR
* I'm a giant locomotion: 10x gain
* Seven-league boots locomotion: 10x gain
* Need for more systematic investigations in addition to empirical evaluations
* Understanding perception
* How the brain plans and controls movement
* VR system intercepts sensory signals
* Beyond-real designs create sensory conflict
* Framework for describing sensory conflict
* Evaluating designs from a large design space
* Open challenges and future work in VR
    * Designing usable interactions
        * Building predictive tools
        * Simulating alternatives
    * Considering individual differences
        * Capturing user behaviors
        * Adapting to individual users
* Situated Interactions Lab (\psi Lab)
* In situ intelligence augmentation
    * Adaptive interfaces
        * Minimal, Timely, Sensory modality
    * Input on-the-go
        * Uncertainty
        * Disambiguation
        * Privacy-preserving
    * Interactions w/ situated AI
        * Complexity
        * Dynamicity
* thanks to my advisors
## 2/22/24 Week 7 Thursday Lec 8
* Leveling up Next Gen Xbox User Experience with Neural Networks and Sound
* Krishna Kant Chintalapudi
* Xbox many components
* Console Gaming
* Cloud Gaming
* How Gaming Works
    * Game Engine
        * Infinite loop evolving game state continuously
    * Gamer Inputs
        * Digital Inputs
            * Button presses
        * Analogue Inputs
            * Joy sticks
    * Feedback
        * Haptic Feedback
            * Similar to an audio stream
        * Rumble Motors
            * Digital commands
    * Audio & Video
        * Game audio stream
        * Video frames at 60Hz refresh rate (16.67ms)
    * Connectivity options
        * Console gaming
        * Cloud Gaming
* To Wire or go Wireless is the Question
* Background - Data Rates in WiFi
    * Each data rate needs a certain minimum SNR
    * Lower data rate takes more time and waste Time and Energy
    * OFDM
    * If more than certain number of sub-carriers are poor - you have packet losses
* Gamer's Wireless Channel
    * During active game play
        * Up to 10-15 dB changes with 50-80ms
        * Consecutive losses are common
    * Xbox Transmits PCM audio in 8ms chunks
    * Each loss introduces a discontinuity
    * Joy stick does not respond well
        * Packet losses create discontinuities
* User Study
    * Audio experience is effected by
        * Packet loss rates
        * Consecutive losses - loss duration
        * Type of audio - racing, classical, music
* Battery Longevity
    * Controllers are battery powered 200-400 MHz ARM processors
* First Thoughts
    * There is two decades of work in Adaptive Rate Techniques
* How State-of-the-art Adaptive Rate Schemes Work
* We should be able to use Reinforcement Learning
* A Continuous Online Learning Approach
* Wireless Channel Asymmetry
    * Reverse and Forward Channels measurements are not the same
    * Tx Power differences
* ANNs Can Learn Online to Model Wireless Channels
* We implemented state-of-the-art in reinforcement learning
    * 10x reduced in packet loss using PPO clip
* ADR-X: Leverages Wireless Domain Knowledge
    * Key Insight 1: Using wireless domain knowledge, can significant learning relieve burden from the ANN
    * Key Insight 2: Use an ANN to learn to map the wireless channel into a wired channel and then make use of standard results
* ADR-X: Online Continuous Learning and Adaptation
    * Learning needs to be online and continuous
* ADR-X: The Loss Function
    * Use the instantaneous measured sample
* ADR-X: Feature Engineering for Compute and Convergence Speed
* ADR-X: Survivorship Bias and Stability
    * Initially, when the network is learning, bad actions can be taken
    * Survivorship Bias: Packets lost => CSI measurements lost
    * Guardrails
* ADR-X: Real time convergence
    * Is robust to sudden changes in interference and operating costs
* ADR-X is an ML powered adaptive data scheme that learns and adapts continuously in real time
* Tale of Two Streams
    * Accessory Stream (Game Audio + Chat) Proprietary Protocol
* The Ekho Problem - Inter-Stream Delay
    * Both streams are kept on, one for onlookers and the other for gamers
    * The gamer hears two audio game streams at the same time - screen stream & accessory stream
    * Server to ear latency for these paths are differentt
    * Gives perception of Echo
* User Study - How Much IDF Echo is Perceptible?
    * 15 most popular Xbox games
    * 3555 ratings in accordance with ITU-T P.808
* Inter-Stream Delays
* The Inter-Stream Delay Measurement Challenge
    * No control over some end-points hinders measurements
    * RTT/2 incurs errors due to latency asymmetry
    * Sound propagation delay is not measureable without participation of both devices
* Ekho's Solution
    * Key Idea: Correlate the overhead sound from the screen and one recieved at the headphones to estimate the inter-streeam delay
    * Server embeds inaudible acoustic PN sequences in the game audio
    * The headphone/controller time stamps sample numbers and conveys them to server
    * The microphone at the headset records the overhead sound from the screen, including the embedded PN sequences
    * Server estimates delay difference by correlating the PN sequence
* The Challenges
    * The screen speakers and the headphone microphones distort the overheard game audio - needs to work in the cheapest qualtiy devices
    * The PN sequences embedded in game audio that are already designed to be inaudible
* Synchronizing the Streams
    * Inject Empty Samples in faster route
* Ekho allows for sub-millisecond synchronization of streaming media