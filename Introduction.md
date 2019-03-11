# SOEN 321

## Intoduction
The Internet of Things (IoT) is a ubiquitous trend which allows electronic devices to connect and communicate across networks. In of itself this connectivity increases the capabilities of these devices by increasing the resources it may draw from, update and maintain its internal software, as well as additional device or user specific data storage resource requirements. By the year 2020 an estimated 20 Billion devices may be communicating to each other requiring increased technology to maintain and improve the required infrastructure<sup>1</sup>. Recently, consumer electronics have leveraged this connectivity as and *added value* to the base functionality of the electronics such as; refrigerators being capable of re-ordering items exhausted within itsel, or smart televisions which connect to third party services to deliver alternative content than traditional cable/satellite subscription services.

With the current capabilities of Natural Language Processing and cloud computing *Smart Speakers* such as Amazon Echo or Google Home aim to act as a hub for these IoT devices. Primarily, the devices function through voice commands and are capable of controlling third party services or even other devices entirely through natural (ie. conversational) language<sup>2</sup>. This creates a incredibly intuitive and user-friendly interface which is becoming increasingly attractive to mainstream consumers.

Computer security has a particular stake in the realm of IoT but the specific nuances of Smart Speakers raise particular concerns as well. Many of these devices are a *black-box* of functionality which obfuscates the user data namely; how it's generated, what the data is, where it stored or is transmitted to, when the data is moved/created, and who are the stakeholders of the data.

Following are topics within the security of Smart Speakers which we will continue to explore and report:
1. The functionality of Smart Speakers and privacy concerns
2. Storage, ownership, privacy of user data
3. Legal and commercial consequences of Smart Speaker data leaks and company responses
4. Inferable user behavior from Smart Speaker network communication
5. Securing user privacy and associated middleware technologies
6. Future concerns, slippery slopes, and consumer protections

##Legal consequences of Smart Speakers

There is growing concern that the data collected by smart speakers could be used to the detriment of the user. Smart speaker producers have reassured customers that their data is only collected when they prompt the smart speaker to listen for a command. Furthermore, they have assured the public that their personal information is stored confidentially and that their personal information is secure. There have been multiple events in recent years that directly contradict these statements and prove that users should be more concerned about owning smart speakers.

Despite the fact that companies claim to secure user information, there is evidence to suggest that the choice might not always be in their hands. For example, in December 2015, Amazon was asked 
to hand over user data to investigators to help solve a murder case. Amazon defended the user’s right to privacy but ultimately handed over the information when the defendant’s consent. While Amazon did fight for their user in this case, the only reason why they were able to do so was because of the first amendment. If they didn’t have a law on their side, they would’ve had to hand over the data to authorities immediately. User information is only secure as long as the courts of law don’t require companies to hand it over. 

In an even more startling development, the CIA may have developed a tool to hack Samsung smart TVs. The tool was developed to turn TVs into listening devices and Samsung may have been cooperating with the government during it’s development. The entire affair was brought to light by WikiLeaks but as of this day there has been no concrete evidence that the tool actually existed. This still raises major concerns for smart speakers as they are designed to be always listening. Samsung currently has the Bixby smart speaker on the market. Federal law enforcement could use these devices to spy on their own citizens. Civilians would have to censor themselves even in the privacy of their own homes.

This all leads to the fact that if the government is capable of accessing this information, so could other nefarious parties. Information collected by smart speakers could be used to blackmail individuals, steal their identities or potentially worse. There is already evidence that smart speakers are not as secure as they seem. Virtually all smart speakers on the market use some sort of encryption to transport audio files. Smart speakers are incapable of processing audio themselves so it needs to be sent to data centres for processing. The data is then sent back to the speakers themselves so they can respond appropriately. Unfortunately, it seems like hackers can garner information from the encrypted code without ever having to decrypt it. 

## Moodle Explorations
7. Recent Attacks: 
  - (https://arxiv.org/pdf/1901.04879.pdf)[https://arxiv.org/pdf/1901.04879.pdf]
  - (http://www2.eet.unsw.edu.au/~vijay/pubs/jrnl/18tsm.pdf)[http://www2.eet.unsw.edu.au/~vijay/pubs/jrnl/18tsm.pdf]
  - (https://scholar.princeton.edu/sites/default/files/apthorpe/files/SpyingOnTheSmartHome_arXiv.pdf)[https://scholar.princeton.edu/sites/default/files/apthorpe/files/SpyingOnTheSmartHome_arXiv.pdf]

8. Mainstream perception
  - (https://bdtechtalks.com/2018/06/05/google-home-amazon-echo-privacy-security-risks/)[https://bdtechtalks.com/2018/06/05/google-home-amazon-echo-privacy-security-risks/]
  - (https://venturebeat.com/2018/05/30/smart-home-speakers-are-vulnerable-to-a-variety-of-attacks/)[https://venturebeat.com/2018/05/30/smart-home-speakers-are-vulnerable-to-a-variety-of-attacks/]
  - (https://www.nytimes.com/2018/05/10/technology/alexa-siri-hidden-command-audio-attacks.html)[https://www.nytimes.com/2018/05/10/technology/alexa-siri-hidden-command-audio-attacks.html]

9. Companion applications:
  - (Apple Siri)[https://www.siriuserguide.com/how-to-use-siri]
  - (Amazon Alexa)[https://www.amazon.com/b?node=17934671011]
  - (Google Assistant)[https://assistant.google.com/]

10. Speaker Tests

## Resources
1. Shancang Li, Li Da Xu, Shanshan Zhao, <em>5G Internet of Things: A Survey, Journal of Industrial Information Integration (2018)</em>, doi: 10.1016/j.jii.2018.01.005

2. "*(Smart) Speaking My Language: Despite Their Vast Capabilities, Smart Speakers Are All About the Music*", Nielsen, 15 February, 2019, <a href="https://www.nielsen.com/us/en/insights/news/2018/smart-speaking-my-language-despite-their-vast-capabilities-smart-speakers-all-about-the-music.html">ttps://www.nielsen.com/us/en/insights/news/2018/smart-speaking-my-language-despite-their-vast-capabilities-smart-speakers-all-about-the-music.html</a>
