# Requirements Document


### 1. User Requirements


##### 1.1 User Characteristics
*Main users of the application will be doctors, medical students, professors, academic staff.*
*They are very familiar (or at least want to be familiar) with Medical Domain.*
*However, their technological background vary from person to person.*

##### 1.2 System's Functionality
*The project aims to provide a system (application) that concerns extracting information from scientific documents in Medical Domain.*
*Scientific documents from PubMed database shall be able to be searched and tagged depending on significant terms such as amygdala.*
*Users shall be able to create semantic tags, where articles will be associated with URL from Wikidata.*

##### 1.3 User Interfaces
*Interfaces will be built as web application. Users will face login, search, document detail and account pages.*

### 2. System Requirements

##### 2.1 Questions to Understand Requirements Better
- *What kind of words do you need to search?*
- *Which database will be searched?*
- *Do you need to add tags for examining scientific documents?*
- *Which constraints do you have with current examining scientific documents?*
- *Do you need to find specific words in documents in Medical Domain?*
- *Why do you need to search more than one word?*

##### 2.2 Functional Requirements
- *The users shall be able to search documents with specific concepts that relate to anatomy, disease and patients.*
- *The application shall make enable users to search and tag scientific documents from PubMed.*
- *The system shall be able to give results for multiple word terms.*
- *The application shall work on a set of documents with title, abstract, authors, and keywords which are provided by PubMed.*
- *The system shall have a login page for each specific user.*
- *The system shall have a search page that includes input box and search button.*
- *The system shall take data from PubMed.*
- *The user shall be able to create semantic tags, where articles will be associated with URL from WikiData.*
- *The user shall be able to see and manage all semantic tags.*
- *The users shall be able to see search and activity history.*
- *The users shall be able to save the documents they found on their account.*
- *The system shall give notification when a new document added to PubMed database related to previous searches of the user.*

#####2.3 Non-Functional Requirements
- *The application shall need a disc space less than 1 gb.*
- *The response time for a search shall be less than 10 seconds.*
- *The application shall be available on the cloud for 7/24 service.*

