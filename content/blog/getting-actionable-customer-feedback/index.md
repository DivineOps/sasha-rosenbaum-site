---
title: "Getting Actionable Customer Feedback"
subtitle: "What does actionable feedback look like, and how to get it from your customers"
date: 2021-07-10T00:00:00-05:00
draft: false
summary: "Customer feedback is absolutely crucial to product success. The worst sin a company can commit is not listening to their customers. Yet product teams, especially at large companies, get inundated with hundreds of customer requests and escalations. How do you make sure that the requests you are relaying are useful, non-redundant, and detailed enough to be actionable? "

summaryImage: "images/feedback.webp"
listImage: "getting-actionable-customer-feedback/images/feedback.webp"
hideLastModified: false
---

<img src="images/feedback.webp" alt="feedback"  />

If you are a technical seller, you are the connecting link between your company’s customers, and your product team, and you are frequently required to bring feedback from your customer to the product team, and bring their responses back to the customer. 

Customer feedback is absolutely crucial to product success. The worst sin a company can commit is not listening to their customers. Yet product teams, especially at large companies, get inundated with hundreds of customer requests and escalations. How do you make sure that the requests you are relaying are useful, non-redundant, and detailed enough to be actionable? 

Communicating actionable feedback will ensure that you get good quality responses to bring back to the customer. It will also build a productive relationship between you and the product team, which will make you more effective at your job.

# Definitions
As in my previous post on <a href="https://www.sasharosenbaum.com/blog/anatomy-of-customer-presentation/" target="_blank">The Anatomy of a Customer Presentation</a>, it is useful to start with a few of definitions to make sure we are on the same page.

***Customer*** - large enterprise company with multiple stakeholders involved.

***Account Team*** - the team responsible for selling the entire vendor's product portfolio to one or more enterprise customers. May include some or all of the following roles: Account Executive / Account Manager, Account Solution Architect, Account Technology Strategist, Technical Account Manager, Customer Success Manager, and so on.

***Technical Sales*** - sales of technology that is so complex that it requires an engineer to have a full time job explaining it.

***Product*** - the complex technology that requires technical sales. These are often platforms that involve days of setup and customization, and hours of employee training before they can be leveraged to the full extent of their capability. 

***Product Team*** - the team responsible for defining product strategy, planning the roadmap, and designing product features. Product teams work closely with engineering on feature planning and implementation. To quote <a href="https://twitter.com/martinwoodward" target="_blank">Martin Woodward</a> - product teams make sure we build the right thing at the right time.

# What does actionable feedback look like?
It can be a bit hard to explain what good feedback looks like in an abstract, so instead, I am going to use examples.

First, here is what **NOT** to do:
## 100-Level Feedback Example

*“Customer will not buy the product until feature X is added / removed”*

This is the kind of feedback you expect to get from your Account Teams and other non-technical sellers (and yes, some account teams are highly technical, but they are often stretched too thin to deep dive into a particular product). 

**Important note**: please do not get annoyed with your non-technical seller for this! They are doing their job, which is different from yours! Have you tried generating customer-specific Total Cost of Ownership (TCO) estimates, or creating yearly sales projections for the whole territory? I much prefer the easier tasks, like deploying a Kubernetes cluster...

100-level feedback is not immediately useful to the product team. To make it useful, they would need to reach out to the customer and gain an understanding of what the blocker really is. 

Now, here are a couple of examples of useful feedback:
## 400-Level Feedback Example 1
*“Customer is blocked due to lack of feature X.
The specific issue is that the product currently requires giving access to production systems directly to their development teams. Doing so puts them in violation of their current implementation of Sox compliance policy. Alternative implementation of Sox without segregation of duties has been suggested, but rejected by the enterprise security team.”*

## 400-Level Feedback Example 2 
*“Customer is blocked because of feature Y.
The specific issue is that the current minimal application cluster is a 7-node cluster deployed on large VMs using premium storage. The current on-prem architecture requires deploying a cluster per each 5-10 applications, due to both logical and permission-based separation of apps. Deploying the current architecture would require dozens of clusters, which would cost hundreds of thousands of dollars a year. Changing the current architecture to consolidate clusters would take years.”*

This kind of feedback is actionable. It can be triaged and prioritized based on how many customers are likely to experience a similar issue. Note that the response may still be “we cannot change the implementation due to XYZ architectural constraints”. The good news is that now you know exactly what the architectural constraints are. 

# How do you get actionable feedback?
Before you can communicate actionable feedback, you need to get it from the customer. What if all they are telling you is that “the security team doesn’t like feature X”?

Two things will help you get good quality feedback:

## Knowing your product
First, if the product has a roadmap, have it in your bookmarks. If you can get access to the engineering planning tools - get it. You will save yourself and the product team lots of time by finding out if similar customer requests have already been documented, triaged, and possibly planned for implementation. 

Second, it goes without saying that as a technical seller you should know what your product does and how it does it. But there’s more. You should also understand why things are the way they are. 

Sometimes a feature is missing because it didn’t occur to anyone that it was needed. Sometimes it is missing because the product and engineering teams haven’t had a chance to implement it yet. More often, things are implemented in a certain way because building platforms is hard. 

The more you understand your product’s architectural constraints, the better you will be at communicating with your customers. This kind of knowledge doesn’t come overnight. The good news is that every time you gather actionable customer feedback and address it, you will also learn more about your product.

Ideally, your company has a system for reporting and upvoting customer feedback outside of the official roadmap. Please use it! Having visibility into customer feedback is what helps product teams prioritize feature development and build the best possible product.

## Asking good questions 
Not all of the objections customers raise are true adoption blockers. Many objections can be addressed by explaining the product features, or the benefits of the new process in more detail. That is one of the most important functions of a technical seller's job. 

When it comes to true adoption blockers, even though every enterprise is a snowflake, all of them are the same. In my experience, most of the underlying causes for push-back come from the following list:

- Cost
- Compliance
- Current infrastructure constraints
- Current people / process constraints 

When you run into a true adoption blocker, don't stop after you get the first high-level explanation. Unless the underlying cause is immediately obvious, dig deeper until you find it. This is a bit like playing a detective - and who doesn't like to do that?
 
# Communicating the product team response back to the customer 
The product team response usually falls into one of the following categories
<ol>
<ul>
1. The feature already exists - congratulations, you get to immediately make your customer happy!
 </ul>
<ul>
2. The feature is on / was added to the roadmap, with the approximate delivery date of... 
 </ul>
<ul>
3. The feature is not currently a priority due to being a rare request (is your customer a real snowflake?)
 </ul>
<ul>
4. The feature is too costly to implement
 </ul>
<ul>
5. Implementing the feature doesn’t align with the product / company priorities, for instance:
    <ol>
    <ul>
   - An ask for enhanced capabilities in a feature that is planned to be sunsetted
    </ul>
    <ul>
   - A feature that leads the customer down the wrong path (for instance, encourages Waterfall rather than Agile project planning)
    </ul>
    <ul>
   - An integration with a competing product
   </ul>
    </ul>
   </ol>
</ol>


In the same way you have empathy for your customers, your customers have empathy for you. Explaining why building a certain feature is currently impossible goes a REALLY long way. Exceptions can be made even to compliance policies - if your customer understands why the exception is justified, and is convinced that that the benefits of your product outweigh the downsides.

**Bonus**: if the feedback falls into category 2-5, you get to shine as a technical seller by working with your customer to create an acceptable workaround!

That's it for today!

{{< line_break >}}
*Interested in seeing more posts like this? Please let me know on {{< new_tab_link href="https://twitter.com/DivineOps" text="Twitter" >}} or {{< new_tab_link href="https://www.linkedin.com/in/sasha-rosenbaum/" text="LinkedIn" >}}*






