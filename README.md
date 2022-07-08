# Book Recommendation Engine
Recommender systems is a sub-class of information filtering system that provide suggestions for items that are most pertinent to a particular user. Typically, the suggestions refer to various decision-making processes, such as what product to purchase, what music to listen to, or what online news to read. Recommender systems are particularly useful when an individual needs to choose an item from a potentially overwhelming number of items that a service may offer.

**There are two ways to build a recommendation system:-**

> **Content-based Recommendation system :**
>> One popular technique of recommendation systems is **content-based filtering**. Content here refers to the content or attributes of the products you like. So, the idea in content-based filtering is to tag products using certain keywords, understand what the user likes, look up those keywords in the database and recommend different products with the same attributes.

>> It is based on the idea of recommending the item to user K which is similar to previous item highly rated by K. Basic concept in content based filtering is TF-IDF (Term frequency — inverse document frequency), which is used to determine the importance of document/word/movie etc. Content based filtering shows transparency in recommendation but unlike collaborative filtering it can’t able to work efficiently for large data. Content-based approach requires a good amount of information of items’ own features, rather than using users’ interactions and feedbacks. For example, it can be movie attributes such as genre, year, director, actor etc., or textual content of articles that can extracted by applying Natural Language Processing.

> **Collaborative Filtering based Recommendation system:**
>> Collaborative methods for recommender systems are methods that are based solely on the past interactions recorded between users and items in order to produce new recommendations. These interactions are stored in the so-called “user-item interactions matrix”.

>> **The class of collaborative filtering algorithms is divided into two sub-categories that are generally called memory based and model based approaches.**

>> Memory based approaches directly works with values of recorded interactions, assuming no model, and are essentially based on nearest neighbours search (for example, find the closest users from a user of interest and suggest the most popular items among these neighbours). Model based approaches assume an underlying “generative” model that explains the user-item interactions and try to discover it in order to make new predictions.

>> The main advantage of collaborative approaches is that they require no information about users or items and, so, they can be used in many situations. Moreover, the more users interact with items the more new recommendations become accurate: for a fixed set of users and items, new interactions recorded over time bring new information and make the system more and more effective. However it only consider past interactions for making recommendations.

**The method I used for this project is collaborative filtering**.