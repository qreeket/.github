# <strong>Qreeket</strong> (pronounced "cricket")

###### A mobile application platform for tertiary students to communicate, collaborate and share ideas with each other.

[//]: # (https://dribbble.com/shots/19523910-Bee-logo/attachments/14653757?mode=media)

As the world continues to embrace technology, the education sector has also seen a significant transformation in recent
years. Gone are the days when students had to rely solely on classroom lectures and printed materials. Nowadays,
students have access to a plethora of digital resources that make learning more engaging and interactive. However, there
is still room for improvement, particularly in terms of communication and collaboration.

To address this need, I am building a mobile application platform that will enable tertiary students to communicate,
collaborate and share ideas with each other. The platform will work like Discord, a popular communication platform among
gamers, but tailored to the needs of tertiary students. It will leverage the power of grpc and microservices to provide
a seamless user experience.

The platform will be developed using Golang and Rust, two programming languages known for their performance and
reliability. These languages are also well-suited for building microservices, which will enable the platform to scale as
the user base grows.

One of the key features of the platform is its ability to help department heads disseminate information to the various
student groups. This will help ensure that all students are up-to-date with the latest developments in their respective
departments. Additionally, students from multiple campuses offering the same course can create a community to have
discussions and share ideas. This will enhance collaboration and facilitate knowledge sharing among students.

The platform will also allow students to create channels for polling on topics of interest. This will enable them to
gather feedback from their peers and make informed decisions. Students can also invite other students to join groups,
creating a vibrant community of like-minded individuals.

In summary, the mobile application platform I am building will revolutionize communication and collaboration among
tertiary students. It will provide a seamless user experience and enable students to learn from each other, collaborate
on projects, and build a strong sense of community.

## Introduction

`Qreeket` is a communication and collaboration platform designed to meet the
needs of students in tertiary institutions. The platform is built using grpc and microservices, written in Golang and
Rust, and designed to function like Discord. The platform offers a range of features that will enhance communication,
collaboration and information sharing among students.

## Functionalities

### Group Creation

- The platform allows students to create groups and invite others to join.
- The groups can be formed based on shared interests or courses.
- Students can create channels within the group for specific discussions, such as assignments or projects.
- Students can customize the group settings and set the visibility to public or private.

### Department Information Dissemination

- Department heads can use the platform to disseminate information to their students.
- Important announcements can be made using the announcement feature to ensure that all students are aware of important
  developments in their respective departments.

### Polling on Topics of Interest

- Students can create polls to gather opinions from their peers on topics of interest.
- Polls can be used to inform decision-making or to get feedback on projects and assignments.

### Community Building

- Students from multiple campuses offering the same course can create a community to have discussions and share ideas.
- The platform enables students to connect with like-minded individuals, build relationships and collaborate on
  projects.

### Direct Messaging

- The platform provides direct messaging functionality, enabling students to send messages to other students or groups
  of students.
- Students can use this feature to ask questions, share ideas or collaborate on assignments.

### Resource Sharing

- Students can use the platform to share resources with their peers.
- Resources can include notes, books, videos, and other digital content.
- Students can upload and download resources within their groups.

## Architecture

The platform is built using grpc and microservices, written in Golang and Rust. The platform consists of the following
components:

- `Gateway`: The gateway is responsible for routing requests to the appropriate microservice. It also handles
  authentication and authorization.
- `Auth Service`: The user service is responsible for managing user accounts and authentication.
- `Group Service`: The group service is responsible for managing groups and channels.
- `Poll Service`: The poll service is responsible for managing polls.
- `Media Service`: The resource service is responsible for managing resources.
- `Announcement Service`: The announcement service is responsible for managing announcements.
- `Messaging Service`: The messaging service is responsible for managing direct messages between users.
- `Community Service`: The community service is responsible for managing communities.
- `Notification Service`: The notification service is responsible for sending notifications to users.
- `Search Service`: The search service is responsible for searching for users, groups, channels, polls, resources,
  announcements, and communities.
- `Analytics Service`: The analytics service is responsible for collecting and analyzing data about user behavior.
- `Recommendation Service`: The recommendation service is responsible for recommending content to users based on their
  interests and preferences.
- `Payment Service`: The payment service is responsible for processing payments for premium features.
- `Billing Service`: The billing service is responsible for managing subscriptions and billing information.
- `Email Service`: The email service is responsible for sending emails to users.
- `SMS Service`: The SMS service is responsible for sending SMS messages to users.
- `Push Notification Service`: The push notification service is responsible for sending push notifications to users.
- `Alerting Service`: The alerting service is responsible for sending alerts to users when there is an issue with the
  system. This is handled by Sentry.
- `Tracing Service`: The tracing service is responsible for tracing requests as they move through the system

## Group Creation

The group creation functionality is a central feature of the `Qreeket`. With
this feature, students can create groups, invite others to join, and collaborate on projects and assignments. Here are
some additional details:

### Implementation

The group creation functionality is implemented using microservices architecture and grpc. This architecture provides a
scalable, high-performance solution for handling a large number of users and groups. The group creation functionality is
written in Golang and Rust, two languages known for their performance and reliability. These languages are also
well-suited for building microservices.

### User Interface

Students can easily create a new group, add a description and invite others to join. The user interface also provides
options for customizing the group settings, such as setting the visibility to public or private.

## Department Information Dissemination

The department information dissemination functionality is a key feature of the `Qreeket`. With this feature, department
heads can communicate important information to their students in a timely and efficient manner. Here are some additional
details:

### Implementation

The department information dissemination functionality is implemented using microservices architecture and grpc. The
feature is written in Golang and Rust, and uses a publish-subscribe model to notify students of important announcements.

### User Interface

Department heads can easily create announcements and share them with their students. The user interface also provides
options for customizing the visibility of the announcement, such as setting it to be visible to all students or a
specific group of students.

## Polling on Topics of Interest

The polling on topics of interest functionality is a key feature of the `Qreeket`. With this feature, students can
create polls and surveys on topics that interest them and get feedback from
their peers. Here are some additional details:

### Implementation

The polling on topics of interest functionality is implemented using microservices architecture and grpc. The feature is
written in Golang and Rust, and uses a real-time messaging model to notify students of new polls and survey responses.

### User Interface

The user interface for polling on topics of interest is designed to be simple and intuitive. Students can easily create
polls and surveys, and share them with their peers. The user interface also provides options for customizing the
visibility of the poll, such as setting it to be visible to all students or a specific group of students.

## Community Building

The community building functionality is a core feature of the `Qreeket`. With this feature, students can create
communities and channels to connect with other students and share information. Here are some additional details:

### Implementation

The community building functionality is implemented using microservices architecture and grpc. The feature is written in
Golang and Rust, and uses a real-time messaging model to notify students of new community and channel activities.

### User Interface

The user interface for community building is designed to be user-friendly and flexible. Students can easily create
communities and channels, and invite other students to join them. The user interface also provides options for
customizing the visibility of the community or channel, such as setting it to be visible to all students or a specific
group of students.

## Direct Messaging

The direct messaging feature is an essential aspect of the `Qreeket`. This functionality allows students to send and
receive private messages from each other, making it easy for them to communicate one-on-one.

### Implementation

The direct messaging feature is implemented using gRPC and microservices architecture. It is written in Golang and Rust,
making it highly performant and reliable. The feature also utilizes end-to-end encryption to ensure that the messages
exchanged between students are secure and private.

### User Interface

The user interface for the direct messaging functionality is designed to be intuitive and straightforward. Students can
easily initiate private conversations with their friends or other students and exchange messages in real-time.

### Benefits

The direct messaging functionality offers several benefits to students, including:

- Private Communication: Students can send and receive private messages without worrying about their conversations being
  visible to others.

- One-on-One Communication: Students can communicate with each other one-on-one, making it easier to share sensitive
  information and have personal conversations.

- Efficient Communication: Direct messaging provides a fast and efficient way for students to communicate, saving time
  and streamlining the communication process.

Overall, the direct messaging feature is an essential aspect of the `Qreeket`, allowing students to communicate
privately and efficiently with each other.

## Resource Sharing

The Resource Sharing feature is designed to allow students to share resources with each other. This includes class
notes, study materials, and other educational resources. Here are some additional details:

### Implementation

The Resource Sharing feature is implemented using microservices architecture and grpc. The feature is written in Golang
and Rust, and uses a real-time messaging model to notify students of new shared resources.

### User Interface

Students can easily share resources with their peers and access shared resources that are relevant to their courses. The
user interface also provides options for customizing the visibility of shared resources, such as setting them to be
visible to all students or a specific group of students.

### Features

The Resource Sharing feature offers the following functionality:

- Uploading and sharing files: Students can upload and share files such as class notes, study materials, and other
  educational resources.
- Customizable resource visibility: Students can choose who can see their shared resources, such as making them visible
  to all students or a specific group of students.
- Resource search: Students can search for shared resources based on keywords, course codes, or other relevant criteria.
- Resource rating and commenting: Students can rate and comment on shared resources, providing valuable feedback to
  their peers and helping to improve the quality of shared resources.

## Relevant Resources

- [Publish-subscribe model](https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern) is a messaging pattern used
  in software systems to notify multiple recipients of an event or message. The`Qreeket` uses a publish-subscribe model
  to notify students of important announcements.
- [Golang](https://golang.org/) is an open-source programming language known for its performance, reliability and ease
  of use. The `Qreeket` uses Golang for implementing the department information
  dissemination functionality.
- [Rust](https://www.rust-lang.org/) is a systems programming language known for its speed, memory safety and
  concurrency. The `Qreeket` uses Rust for implementing the department
  information dissemination functionality.
- [Microservices Architecture](https://microservices.io/) is a design pattern used to develop complex software systems
  consisting of small, independent services that communicate with each other. The `Qreeket` uses microservices
  architecture to provide a scalable solution for handling a large number of users
  and announcements.
- [PostgreSQL](https://www.postgresql.org/) is an open-source relational database management system known for its
  scalability and reliability. The `Qreeket` uses PostgreSQL as its database
  management system.
- [Object-relational mapping (ORM)](https://en.wikipedia.org/wiki/Object-relational_mapping) is a programming technique
  that allows developers to interact with a database using an object-oriented programming language. `Qreeket` uses an
  ORM to simplify the process of working with the database.
- [Microservices Architecture](https://microservices.io/) is a design pattern used to develop complex software systems
  consisting of small, independent services that communicate with each other. The `Qreeket` uses microservices
  architecture to provide a scalable solution for handling a large number of users
  and groups.
- [grpc](https://grpc.io/) is a high-performance, open-source framework for building remote procedure call (RPC)
  applications. The `Qreeket` uses grpc for its microservices architecture.
- [Real-time messaging model](https://pusher.com/what-is-realtime-messaging) is a messaging pattern used in software
  systems to enable real-time communication between multiple recipients. The`Qreeket` uses a real-time messaging model
  to notify students of new polls and survey responses.

