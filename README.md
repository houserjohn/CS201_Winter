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
