# [gliff.ai](https://gliff.ai) product roadmap

<a href="https://gliff.ai"><img src="https://user-images.githubusercontent.com/7795189/124492005-cd649800-ddab-11eb-9000-f3c0831338b7.png" align="right" height="150"></a>

In this repository, you can find the details of [gliff.ai](https://gliff.ai)'s product framework, including a roadmap for future development.
This repository is a pulic-facing document where we discuss what features we are planning to develop, which we are currently working on, what stage they are in, and when we expect to deploy them to our products.
Have any questions or comments about products or items on the roadmap - begin a discussion on the related Issue.
This repository will be updated during sprint planning and sprint retrospectives by the gliff.ai team.

## Mission

gliff.ai believes that Artificial Intelligence (AI) can improve the lives of people worldwide.
But AI needs to be properly designed by domain and data experts working together.
At gliff.ai we help teams come together to build and deploy world-changing AI, all in one platform.

gliff.ai is a privacy-preserving machine learning operations (MLOps) platform revolutionising the development of trustworthy AI - built by data scientists, for everybody.
Our software brings together our expertise in medical imaging, data analysis and artificial intelligence (AI) with human design and open-source coding practices.

gliff.ai aims to become *the* productivity framework for generating high-quality, auditable imaging AI.

## Product definitions

We split the gliff.ai platform into a series of 'products' - open-source user interfaces focussed on a core set of tasks.
These products are:
- [CURATE](https://github.com/gliff-ai/curate): enabling users to curate their datasets, i.e. create projects, add data to projects, update data or projects, etc.
- [ANNOTATE](https://github.com/gliff-ai/annotate): enabling users to annotate multi-dimensional imaging data with paintbrushes, splines and other annotation tool, all built with our flexible annotation labelling system throughout
- [MANAGE](https://github.com/gliff-ai/manage): enabling users to manage their team and projects within the gliff.ai platform
- [AUDIT](https://github.com/gliff-ai/audit) (due mid 2021): enabling users, and regulatory bodies, to audit all the actions that have been taken to develop a dataset, annotations and AI models
- [REGISTER](https://github.com/gliff-ai/register) (due late 2021): allowing teams to register their AI experiments within the gliff.ai platform with a high-quality, human-readable audit trail

Products are always tagged in block capitals.

Our products are also supported by a closed source deployment ecosystem that combines the power of our open-source user interfaces with a highly secure backend that uses end-to-end encryption (based on [etebase](https://github.com/etesync)) to ensure user data stays private.

Plug-ins:
- Watch this space...

Supporting libraries:
- [UPLOAD](https://github.com/gliff-ai/upload): gliff.ai's wrapper for loading a range of multidimensional data into gliff.ai products
- [STYLE](https://github.com/gliff-ai/style): gliff.ai's Material UI theme for consistent branding of gliff.ai products

## Guide to the roadmap

Every item on the roadmap is a GitHub Issue, with a group of labels as described below.

### Roadmap labels

- A **product** (see the list above) that indicates within which product(s) the feature will be deployed within the wider gliff.ai framework.
- A **priority**, one of *highest*, *high*, *medium*, *low* or *lowest*.
- A **complexity**, one of *S*, *M*, *L*, *XL* or *XXL*.

### Roadmap stages

The roadmap is arranged on a project board to give a sense for how far out each item is on the horizon.
Every feature is added to a particular project board column according to the its progress.

- If a feature is already release, it will be in the **released** column.
- If a feature is expected to be introduced in the next 6 month's time, it will be in the **working** column.
- If a feature is expected to be introduced in 6 month's time, it will be in the **future** column.
- If a feature has been requested or proposed but no engineering has yet gone in to it, it will be in the**exploration** column.
