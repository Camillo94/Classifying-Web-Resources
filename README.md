# Classifying-Web-Resources
The project’s objective is to train the current resources on their labels to successfully classify new resources. The hereby best-performing algorithm turned out to be support vector machines (SVMs) as they perform well on text-data.

## Introduction
One of the project members is currently developing a platform called radixlibrary1.
Shortly, the platform is supporting its users in learning various topics fields by
presenting a learning path that navigates through educational web-resources.
Currently, radixlibrary entails ~2000 labeled resources which are categorized into ~300
topics. To incentivize a steady growth of resources, the platform allows its users to add
a new resource by entering a URL-link. To ease the process of adding new resources,
methods are needed that automatically label and categorize a resource.
The project’s objective is to train the current resources on their labels to successfully
classify new resources. The hereby best-performing algorithm turned out to be support
vector machines (SVMs) as they perform well on text-data.

## Goal
By allowing users to add a new resource the platform is able to grow. To amplify the
growth, it is vital to minimize the act of adding a resource to simply pasting an URL-link
into a HTML form. In this way the barrier to share a resource is lowered. To accomplish
the goal, the newly added resources should be automatically labelled.
An additional motivation of the project deals with the manually created taxonomy of
radixlibrary. This taxonomy represents a hierarchy of semantically similar topic fields.
The goal is to refine the taxonomy by considering the number of topics inside the
taxonomy. By means of topic modelling the web-resources are clustered. The method of
negative matrix factorization (NMF) finds a fixed number topics that represent each
resource. At the same time, the choice of labels can be reconsidered.
