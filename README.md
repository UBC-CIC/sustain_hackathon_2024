# UBC Generative AI and Sustainability Hackathon 2024

## Introduction

**About Sustainability, Generative AI, and Cloud Computing** <br>
Sustainability is a broad topic and has no one singular definition. Check out the [UN Sustainable Development Goals](https://sdgs.un.org/goals) as a starting point.

Generative AI refers to a type of artificial intelligence designed to generate new content, data, or outputs that are not explicitly programmed in advance. It involves models that can create new examples or samples within a given domain, such as images, text, music, or other types of data.

Cloud Computing is the practice of using a network of remote servers hosted on the internet to store, manage, and process data, rather than a local server or a personal computer. It allows you to focus on developing, rather than having to worry about providing all the hardware. One of the biggest cloud service providers out there is AWS.

## Event Overview 😄
### General Schedule

* 8:00AM: Check in + Breakfast
* 8:30AM: Introduction
* 8:40AM: Icebreaker
* 9:10AM: Hacking commences
* 12:00PM: Lunch (provided) 
* 5:00PM: Dinner (provided)
* 6:00PM: Hacking ends
* 6:10PM: Judging starts
* 7:45PM: Closing ceremony
* 8:00PM: End of Hackathon!

### Item Checklist

#### Required
- UBC Card
- Adapters
- Laptop and charging cables

#### Suggested
- A water bottle
- Reusable coffee mug, containers, and cutlery

### Venue

Sauder Learning Labs: 6326 Agricultural Road, Vancouver, BC V6T 1Z2

It is behind the Sauder building and sandwiched between Triple O’s and the Leonard S. Klinck building. Look out for a sign that says **David Lam Learning Centre**!

### Rules

* No plagiarism
* Code must be on GitHub and open sourced
* Any private datasets used must not contain personally identifiable information
* Project design and development must start at the hackathon’s beginning, but preprocessed and structured data is allowed

### Submission Guidelines

- Total 5 minutes (3 min presentation, 2 min Q&A)
- We recommend talking about your motivation for choosing this project, and its potential impact.
- **REQUIRED**: To judge the technical details of your solution, you must include an architecture diagram (try out draw.io, or any other tool).
- **REQUIRED**: You must explain why your solution addresses an issue regarding sustainability.
- **DEADLINE**: There is a hard deadline to submit the link to your public GitHub repository in your Discord team channel by 6:00PM. Late submissions will lead to disqualification.

### Criteria

- Creativity and Originality: The innovativeness and uniqueness of the generated solution.
- Technical Implementation: The complexity and effectiveness of the AI model and its integration with the user interface. 
- User Interaction: The intuitiveness and effectiveness of the user interface in influencing the generated solution. 
- Cloud deployment: The choices and efficient deployment of cloud services for their solution.
- Sustainability: The extent to which the solution addresses an issue regarding sustainability.
- Presentation: The clarity, coherence, and persuasiveness of the final presentation. 
  
### FAQs

For frequently asked questions and tips, please visit [FAQs](https://docs.google.com/document/d/1bntohJU4VPZH4nLsNasZp23QJ1u2Kutwwwge3V7k_5k/edit?usp=sharing)

## Getting Started 🎧

In the week leading up to the event, a workshop on Amazon Bedrock will be posted.

[Getting Started With AWS Workshop Studio](https://docs.google.com/document/d/1E29Kh7kJ_z67m5JeN4q-uEkvcntl261336XTxJyeNx8/edit?usp=sharing)

## Resources ⭐️

### Gen AI Fundamentals

- [Introduction to Generative AI - Art of the Possible](https://explore.skillbuilder.aws/learn/course/external/view/elearning/17176/introduction-to-generative-ai-art-of-the-possible)
- [Planning a Generative AI Project](https://explore.skillbuilder.aws/learn/course/external/view/elearning/17256/planning-a-generative-ai-project)
- [Foundations of Prompt Engineering](https://explore.skillbuilder.aws/learn/course/external/view/elearning/17763/foundations-of-prompt-engineering)
- [Generative AI with Large Language Models](https://www.coursera.org/learn/generative-ai-with-llms)
- [Introduction to LangChain](https://python.langchain.com/docs/get_started/introduction) - LangChain is a framework for developing applications powered by language models
- [Serverless LLM apps with Amazon Bedrock](https://www.deeplearning.ai/short-courses/serverless-llm-apps-amazon-bedrock/) - (Course) Enroll for free. Learn how to deploy a large language model-based application into production using serverless technology.
- [Generative AI with Large Language Models](https://www.coursera.org/learn/generative-ai-with-llms) - (Course) Enroll for free. Excellent intro course. Gain foundational knowledge, practical skills, and a functional understanding of how generative AI works.
- [Prompt Engineering Best Practices](https://www.youtube.com/watch?v=jlqgGkh1wzY) - Prompt engineering best practices for LLMs on Amazon Bedrock.
- [General Prompt Engineering using Party Rock](https://partyrock.aws/u/js2222/zEj353AmT/Prompt-Engineering-Guide-Introduction) - Learn General Prompt Engineering using Party Rock (free to use).
- [Anthropic Claude on Party Rock](https://partyrock.aws/u/schuylr/proiDgYx9/Claude-Prompt-Engineering-Interactive-Tutorial-Chapter-1) - Learn Anthropic Claude Interactive Prompt Engineering tutorial on Party Rock (free to use).
- [Anthropic’s Official Documentation](https://docs.anthropic.com/claude/docs/guide-to-anthropics-prompt-engineering-resources) - Anthropic’s Official Prompting Documentation
- [AWS Bedrock Samples Repository](https://github.com/aws-samples/amazon-bedrock-samples) - AWS's Official GitHub Samples Repository
- [AWS GenAI Quick Starts](https://github.com/aws-samples/genai-quickstart-pocs/) - AWS's Quick Starts for GenAI Repository
- [AWS Bedrock PDF Chat](https://github.com/aws-samples/serverless-pdf-chat) - Example of PDF Chat using Amazon Bedrock

---

### Data (extending the LLM)

#### Retrieval-augmented generation (RAG)

Retrieval-augmented generation (RAG) for large language models (LLMs) aims to improve prediction quality by using an external datastore at inference time to build a richer prompt that includes some combination of context, history, and recent/relevant knowledge

- [What Is Retrieval Augmented Generation (RAG)](https://aws.amazon.com/what-is/retrieval-augmented-generation/)

- More in-depth intro [Retrieval Augmented Generation (RAG) for LLMs](https://www.promptingguide.ai/research/rag)

#### Implementing RAG applications on AWS

##### RDS / pgVector:

- [Building AI-powered search in PostgreSQL using Amazon SageMaker and pgvector (Blog post)](https://aws.amazon.com/blogs/database/building-ai-powered-search-in-postgresql-using-amazon-sagemaker-and-pgvector/)
- AWS Samples (GitHub) - [RAG with Amazon Bedrock and PGVector on Amazon RDS](https://github.com/aws-samples/rag-with-amazon-bedrock-and-pgvector)

##### Knowledge Base:

- [Knowledge Bases now delivers fully managed RAG experience in Amazon Bedrock](https://aws.amazon.com/blogs/aws/knowledge-bases-now-delivers-fully-managed-rag-experience-in-amazon-bedrock/)
- [Knowledge Base for Amazon Bedrock](https://aws.amazon.com/bedrock/knowledge-bases/) - [Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/knowledge-base.html)

##### OpenSearch:

- [Amazon OpenSearch Service’s vector database capabilities explained](https://aws.amazon.com/blogs/big-data/amazon-opensearch-services-vector-database-capabilities-explained/)
- [Build scalable and serverless RAG workflows with a vector engine for Amazon OpenSearch Serverless and Amazon Bedrock Claude models (Blog post)](https://aws.amazon.com/blogs/big-data/build-scalable-and-serverless-rag-workflows-with-a-vector-engine-for-amazon-opensearch-serverless-and-amazon-bedrock-claude-models/)

### Example Data Sets:

- [Open Government Canada](https://open.canada.ca/en)
- [ Environment and Natural Resources Canada](https://www.canada.ca/en/services/environment.html)
- [U.S. Government's Open Data](https://data.gov/)
- [Kaggle](https://www.kaggle.com)

---

### Agents for Bedrock

Enable generative AI applications to execute multistep tasks across company systems and data sources

- [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html)
- [Demo Video - Agents for Amazon Bedrock ](https://www.youtube.com/watch?v=UcehCSSOMQA)
- [Amazon Bedrock Agents Quickstart](https://github.com/build-on-aws/amazon-bedrock-agents-quickstart) - Functional code example
- [Build a foundation model (FM) powered customer service bot with agents for Amazon Bedrock](https://github.com/aws-samples/agentsforbedrock-retailagent)

### AWS Basics

- [AWS Cloud Essentials](https://aws.amazon.com/getting-started/cloud-essentials/)
- [AWS Security Essentials](https://assorted-market-2d4.notion.site/AWS-Security-Essentials-97e1020385564db4a59fe41cd0ce5929)
- [AWS Networking Essentials](https://assorted-market-2d4.notion.site/AWS-Networking-Essentials-cb0e377177eb4bfbbeebc58c8ca180cd)
- [AWS Technical Essentials](https://assorted-market-2d4.notion.site/AWS-Technical-Essentials-612efb1dde3c4ac1a8a68969b7fd8d5b)
- [Architecting on AWS - Online Course Supplement](https://explore.skillbuilder.aws/learn/course/external/view/elearning/8319/architecting-on-aws-online-course-supplement)
- [AWS Serverless Land](https://serverlessland.com/) - AWS Serverless examples, patterns, documentation and guidance.


## Examples / Ideas 🤔

Where do current tools fall short? How can you innovate using generative AI to fill those gaps? Here are some examples to get you started.

### Google Interview Warmup
A web-based tool developed by Google to help users practice answering common interview questions in a variety of fields, including tech, data, and UX. It uses speech recognition and AI feedback to analyze users' responses, helping them identify strengths and areas for improvement.

### Alternative Clothing Suggester 
This mobile app enhances online shopping by analyzing the materials and production methods of clothing items. It then suggests eco-friendly alternatives that match the user's style, offering similar articles of clothing made from sustainable materials and produced through ethical practices
