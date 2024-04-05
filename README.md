# Malicious Web Content Detection using Machine Learning

### Problem Statement - 
#### Naive web browser users are vulnerable to online threats such as phishing scams and malware downloads because they lack awareness of the website's back-end functionalities. This can lead to them unknowingly giving away personal information or downloading malicious content.  Exhaustively identifying and blocking all harmful content is impossible due to its constant evolution.


### Solution -
This project proposes a Chrome extension that acts as a middleware between users and websites. The extension utilizes machine learning to:

Mitigate risks from malicious websites: The extension will identify and block potential threats like phishing attempts and malware downloads.
Adapt to evolving threats: By employing machine learning, the extension will be able to categorize new and unseen content, enabling it to take appropriate actions against emerging threats.
This approach aims to empower users by providing an additional layer of protection against online dangers, even when encountering previously unknown malicious content.


#### Abstract -
* Naive users using a browser have no idea about the back-end of the page. The users might be tricked into giving away their credentials or downloading malicious data.
* Our aim is to create an extension for Chrome which will act as middleware between the users and the malicious websites, and mitigate the risk of users succumbing to such websites.
* Further, all harmful content cannot be exhaustively collected as even that is bound to continuous development. To counter this we are using machine learning - to train the tool and categorize the new content it sees every time into the particular categories so that corresponding action can be taken.



A few snapshots of our system being run on different webpages -


![drive_phishing](https://user-images.githubusercontent.com/18022447/35985366-81a9c5b8-0cc4-11e8-887d-7f427ffa8a8e.png)
_**Fig 1.** A phishing website which looks just like Google Drive._

![dropbox_phishing](https://user-images.githubusercontent.com/18022447/35985373-84056c86-0cc4-11e8-8751-cf511d5b8aa0.png)
_**Fig 2.** A phishing website which looks just like Dropbox_





