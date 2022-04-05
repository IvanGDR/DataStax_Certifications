# A study guide for preparing DataStax Certifications
(Admin, Dev and K8ssandra)
&nbsp;
#### :books: Ivan Garcia Del Risco / :calendar: Jan 2022 / :clock4: 10 min read
&nbsp;
I have recently cleared out the DataStax Certification Exams: 
- Apache Casandra Developer Associate Certification.:mortar_board:
- Apache Cassandra Administrator Associate Certification.:mortar_board:
- Apache Cassandra Operations on Kubernetes Associate Certification.:mortar_board:

In return to the community and colleagues interested in obtaining these certifications, I have decided to write this post sharing my experience and study guide that can make easier this journey.
&nbsp;
<p align="center">
  <img width="600" height="500" src="https://user-images.githubusercontent.com/67383481/161704530-e0979038-9766-4d25-be73-4d48dea7f0e7.png">
</p>


Although this guide is being elaborated with the purpose to obtain the 3 certificates currently offered by DataStax, it can be used to prepare each exam individually but as I develop this document, you will notice that there is an underlying pattern silently pointed out  by the DataSax Academy Exams that would make you realise the convenience of taking the courses offered by DataStax Academy as well as the supported resources in a convenient way as showing it here.

# Before Preparing the Exam :walking:

Before taking the exam it is important to become familiarised with the way this is going to be delivered, for this you can find information about the certifications details as well as rules and the process itself [here](https://www.datastax.com/dev/certifications) :globe_with_meridians:.

The exam is online and proctored, you will need a **Photo ID document** :ticket: as Driver License or Passport as well as access to a computer and a very quite room with a desk completly free of any material or equipment apart from your laptop only. Any telephone, mobile phone, printer or second screen must be turned off and people around is not acceptable, your exam can be voided for any of these reasons.

All the exams consist of **60 multiple choice questions** and you have **60 minutes to complete it**. The **cost of the exam is USD$145.00**.
&nbsp;
> :wave: As a member of the public, you have the chance to obtain **FREE VOUCHERS** just join the community and get access to organised workshops. All you have to do is attend them and complete the exercises. Click [here](https://www.datastax.com/workshops) to see the scheduled workshops. Furthermore, I recommend you to [subscribe](https://docs.google.com/forms/d/e/1FAIpQLSfEtzzVauuFpFJWUiepYndqchBpNsaOwm6raPJDsMt9nTvMbw/viewform) to receive workshop event notifications.

> :wave: If you are part of any of the DataStax Engineering Support Teams (EMEA, APAC, USA) and/or these certifications are part of your onboarding process, **you are likely to be entitle for exam vouchers** that can help you to cover the cost. Each voucher assigned gives you two chances for any of the exams. Please approach your coach for this.

> :wave: Test your equipment to double check you can access the exam room, do this with plenty time prior to do the exam.

# Preparing the Exam :running_man:

#### Apache Cassandra Administrator and Development Certifications :bookmark:

I particularly found out this book very handy to understand how C* works, I would recommend you to read it if you have time, this would give you a strong base to deal with the task on hands.

![84cdf1b7](https://user-images.githubusercontent.com/67383481/161704634-200b2193-d8d9-4a59-82b9-8c651feb492c.png)
&nbsp;
<p align="center">
   <img width="300" height="500" src="https://user-images.githubusercontent.com/67383481/161704634-200b2193-d8d9-4a59-82b9-8c651feb492c.png">
</p>

From this book the content of chapters 2, 5, 6, 9 are from my view highly recommended when pursuing these certificates. :book:

On the other hand the DataStax content for these two certifications can be accessed using the :globe_with_meridians: [DataStax Academy Portal](https://academy.datastax.com), **a valid email account** is neccesary in order to access the courses as well as the exams, included the K8ssandra one.
The DataStax Academy Portal is a friendly study environment that keeps your progress marked also there are plenty mock questions very similar to the ones you will deal during the real exams.


| Learning Path      | Course and Code         | Time (Hours)  |
| :----------------- |:------------------------| :------------:|
| Core (Admin + Dev) | Introduction C* (DS101) |     1         |
| Core (Admin + Dev) | Foundations C* (DS201)  |     4         |
| Admin              | Operations C* (DS210)   |     6         |
| Dev                | Data Modeling C* (DS220)|     5         |

&nbsp;
Additionally there is youtube content that necesarily need to be visited. For both Cassandra Administrator and Cassandra developer there are a couple of workshops:

:cinema: [Introduction to Apache Cassandra - YouTube](https://www.youtube.com/watch?v=uwuF9xa3Vyw)

:cinema: [Cassandra Certification Preparation - YouTube](https://www.youtube.com/watch?v=yahycROCCOg)

Also specifically for the developer certification, the youtube content that I recommend are the ones dedicated to modelling apache C*:

:cinema: [How to Create a Cassandra Data Model - YouTube](https://www.youtube.com/watch?v=4D39wJu5Too)

:cinema: [Data Modelling in Apache Cassandra - YouTube](https://www.youtube.com/watch?v=5NoixINC9l4)

For the Administrator certification, I do recommend to stick to the dataStax Academy content.

&nbsp;
> :wave: Do not get surprised that the C* Administrator exam would include "few" questions related to data modeling or Development learning path. Likewise the C* Developer exam would include "few" questions regarding the administrator learning path.
> **The takeaway here is to whatever exam you want to clear initially you should review all the learning paths content shown on the table above (core, Dev and Admin)**.

&nbsp;
#### Apache Cassandra Operations in Kubernetes - K8ssandra Certification :bookmark:


The format of this course delivered by DataStax Academy is different than the previous ones dedicated to C* admin and dev certifications. To get access to the content, please visit: :globe_with_meridians: [Cassandra Operations in Kubernetes by DataStax](https://www.datastax.com/learn/apache-cassandra-operations-in-kubernetes).

Before working on the series topic, if your experience on Docker and K8s is new for you, it would be vital to review a good book about K8s. The book I recommend for this is:

![68c79a48](https://user-images.githubusercontent.com/67383481/154661402-c2bb0b75-f0d1-45e3-b861-a9d043bab2c8.png)
&nbsp;
<p align="center">
  <img width="600" height="500" src="https://user-images.githubusercontent.com/67383481/154661402-c2bb0b75-f0d1-45e3-b861-a9d043bab2c8.png">
</p>

Within this book touch the content in Part 1: chapters 1, 2 and Part 2 chapters 3, 4, 5, 6. :book:

Along with the book recommended, I would strongly suggest to visit the official :globe_with_meridians: [K8ssandra](https://k8ssandra.io/) web page, perhaps this is the best content to equip you for the exam, review the documentation and follow the get started guide to set up a K8ssandra cluster.

From the series Topics, this is what you will get, pay attention to the KataCoda exercise commands:

&nbsp;
&nbsp;
&nbsp;

| Series Topic                                       | Time (Hours) |
|:-------------------------------------------------- |:------------:|
| K8ssandra Intro                                    |      0.4     |
| Running K8ssandra in Docker                        |      0.5     |
| Managing C* in K8s using Cass Operator             |      0.6     |
| Monitoring C* in K8s using Prometheus and Graphana |      0.4     |
| Access C* with Stargate API                        |      0.3     |
| Deploying C* in K8s with K8ssandra                 |      0.7     |
| Automating Back up and Restore with Medusa         |      0.3     |
| Automating repair with C* Reaper                   |      0.3     |


&nbsp;
Complementary to the content pointed out above in this section, there are four videos that riguroulsy you need to visit:

:cinema: [K8ssandra First Touch - YouTube](https://www.youtube.com/watch?v=qlZVLEWzJq0)

:cinema: [An Introduction to Kubernetes - YouTube](https://www.youtube.com/watch?v=fMjIqw40CvU)

:cinema: [Introducing K8ssandra - Apache Cassandra & Kubernetes - YouTube](https://www.youtube.com/watch?v=pvzr75ZYwLE)

:cinema: [Connecting Apache Cassandra™ and Kubernetes - YouTube](https://www.youtube.com/watch?v=PCA-aERrcU4)

Also this is a K8ssandra exam workshop, with the type of questions you will see during the exam:

:cinema: [K8ssandra Certification Workshop - YouTube](https://www.youtube.com/watch?v=JT1Dljbfmz8)

# Conclusions

Following this guide, being familiar with the DataStax learning paths and answering the questions confidently after each video section first within the DataStax Academy contents and then resolving the youtube video exams questions preparation and finally the mock exams provided before carrying out the real exams (before booking any exam, you will see a mock exam available within the portal), I think you will be more than ready to obtain the certifications.

Additionally you can go to UDEMY web page and adquire the following test bundle, with questions similar to the exams. Particularly I found these tests counter productive, I have not used it myself but this resource is available just in case. Remember the questions on these type of bundles are similar to the ones on the exams, do not expect copy of exams as this  is illegal :cop:. Once you start to hit 90% positive results you should be good to go.

:globe_with_meridians: [Apache Cassandra Admin, K8ssandra, Dev practice tests \| Udemy](https://www.udemy.com/course/apache-cassandra-admin-k8ssandra-dev-practice-tests/)

&nbsp;
I hope this detailed guide is useful to you as other guides were to me when I was preparing the exam. If you still have any questions, please feel free to contact me! :speaking_head:

&nbsp;
&nbsp;
:facepunch: Good luck with your exams! :rocket:
