## (0) Project Name and Team Slack Handles
Please tell us your project's name and the Filecoin Slack handles for your teammates.

‒ Project Name: Filbox
‒ Slack Channels: can't create right now (no permission?).
‒ Team Slack handles: yongxi.liu, kimmy.w, lea, felixzhou 

## (1) Brief Project Description

‒ Encrypt your file and choose your storage miner! Filbox is an open source file storage encryption application that is designed to enable millions of users to easily encrypt their files and upload it to the distributed network. Powered by IPFS, Filbox adds an extra layer of convenience by providing the choices of storage miners to the end users so that users can choose the intended storage miners based on their preferences. 

## (2) Link to Project UI
Please include a link to your project application or UI. It does not need to be super polished or completely functional. We will be reviewing this link periodically to verify that your project is eligible for final rewards.

‒ Filbox Demo(https://filbox.keystore.com)



## (3) What does your application/UI do?
Give us a brief description of what your application/UI does and how users are intended to interact with it.



‒ Users can upload their files through the Filbox App and they will be able to choose from a list of eligible miners to store their files. Of couse, users get the choice of picking themselves as the miner as well.
‒ For users who are concerned with data privacy, we provide the encryption function to encrypt and decrypt private files.
‒ In the future, Filbox can take the role of a content sharing platform as well - users can also sell their original files in Filbox to get more Fils.

## (4) If your project is using a curated dataset, which one are you using?
You can reference the list of curated datasets in this repo. If you'd like to use a dataset that is not on that list, please nominate your chosen dataset by updating the curated datasets table in this PR. If nominating a dataset, do you own or have exclusive rights to the data you plan to use?

‒ We are not using curated dataset for this project. 
## (5) If your project is not using a curated dataset, please tell us a little bit more about your data by answering the questions below.
What sorts of data will you collect? Do you own or have exclusive rights to the data you plan to use? Is the data license available online? Does the data contain any sensitive or illegal information?

‒ We collect file that users are willing to upload, share and sell and that will be our major consideration.

## (6) How much data are you planning to store to the Filecoin network during the Slingshot competition?
Give us as realistic an estimate as you possibly can at this stage. We understand it's impossible to have perfect information before really starting your project!

‒ ~100T

## (7) How are you structuring the data?
Is this structured or unstructured data? What data formats, schemas, etc. does this dataset follow?

‒ The data uploaded will be sealed by the miner and backed up into the IPFS network. Filbox will record user info, order & payment details, etc.,

## (8) What pre-processing are you doing before ingesting the data?
How will you prepare this data for ingestion into Filecoin? What size storage deals will you be making? If this is a tabular dataset or directory structure, how will you maintain indices into the data so you can retrieve specific data as needed for your application? This is currently one of the most important steps to being successful with data storage on Filecoin. Feel free to ask for help and/or look at docs for recommendations!

‒ Depending on user preferences, the data uploaded will be either encrypted or unencrypted.

## (9) What tech stack will you use to store the data?
Either: Powergate, Hosted Powergate, Textile Hub/Buckets, lotus, or some other solution. Tell us what you're planning to use and how.

‒ We will use Powergate and lotus.

## (10) How will you retrieve the data?
Share some more information about the data retrieval plans for your application? How often does the data need to be retrieved? What is the size of each individual read? Do you need to retrieve from Filecoin (colder storage) or from an intermediate caching layer, like IPFS? How will your application/UI retrieve the necessary data and expose it/interact with it in the UI?

‒ Users can retrieve data directly from IPFS or from Filecoin miners.

## (11) Who is the intended user for your application/UI?
Who do you anticipate will use your project/dataset?

‒ Anyone who wants to use decentralised storage is our potential user. 
‒ Those who want to provide valuable data and earn Fils can also join us in the project.

## (12) Do you have any users already or plans to acquire users soon?
Yes/no. Also, please tell us a little bit about your future plans for user acquisition.

‒ Yes, we have already had some early users from some of our existing projects. However, Filbox is still under development and we expect to gain more users as the project matures. 

## (13) What challenges do you anticipate with this project?
We'd love to know what you're most worried about so we can help as much as possible. Let us know what you anticipate to be the biggest challenges with this project!

We will be keen to know:

‒ How to improve user experience, especially how to help new users to understand decentralised storage and make the most of it.
‒ Time constraints - what level of readiness do you expect the projects to be by the end of Slingshot.
‒ And of course, how to acquire users in a short time frame.
