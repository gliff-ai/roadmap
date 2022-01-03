# gliff.ai ROADMAP

👋 **Welcome in!**
👋
This repository contains the ROADMAP for [gliff.ai](https://gliff.ai)’s MLOps platform.

Our ROADMAP details the [gliff.ai](https://gliff.ai)’s product framework and our teams’ development plan and progress (current and future) along with behind the scenes discussions and directional thinking. Please check out this repositories project board to see our current raised issues, their progress, development stage and expected product deployment location. This repository will be updated during sprint planning and retrospectives as well as key company milestones by the [gliff.ai team](https://gliff.ai/about/). **Next update is expected early 2022.**

❌ **This repository does not currently accept contributions unfortunately!** ❌

## Table of Contents

Looking for something specific? 🔍

- [Repository Introduction](#gliffai-annotate)
- [Mission](#demo-preview)
- [Products](#table-of-contents)
- [Guide](#installation)
- [Contribute](#contribute)
- [Contact](#contact)

## Mission

[{{back to navigation}}](#table-of-contents)

gliff.ai believes that Artificial Intelligence (AI) can improve the lives of people across the Earth. However, AI must be properly designed by domain and data experts collaborating together and the development fully documented in order to achieve regulatory compliance to be able to make a positive impact on our world.

gliff.ai is a privacy-preserving MLOps (Machine Learning Operations) platform which is revolutionising the development of trustworthy AI - built by data scientists, for everybody. Our user-friendly browser software brings together our team's expertise in medical imaging, data analysis and AI with human-centered design and open-source coding practises.

gliff.ai aims to become _the_ productivity frame for developing high-quality and auditable datasets that satisfy any relevant regulatory frameworks and produce impactful imaging AI.

## Products

[{{back to navigation}}](#table-of-contents)

Our team split the gliff.ai platform into a series of ‘products’ - open-source software focusing on a core set of tasks. These are:

- [**ANNOTATE**](https://github.com/gliff-ai/annotate) – enabling users to easily and efficiently annotate multidimensional imaging data with a range of tools including paintbrushes and splines, all built with our flexible annotation labelling system throughout.
- [**CURATE**](https://github.com/gliff-ai/curate) – enabling users to curate (selectively organise and sort) their datasets by adding imagery data to projects, downloading annotated datasets and assigning users annotation tasks.
- [**MANAGE**](https://github.com/gliff-ai/manage) – enabling users to manage their team, projects and plugins within the gliff.ai platform.
- [**AUDIT**](https://github.com/gliff-ai/audit) – enabling users, and regulatory bodies, to easily explore a fully documented audit of every single action that has occurred during the development of an annotated dataset and AI model.

Our products are also supported by a closed source deployment ecosystem that combines the power of our open-source software with a highly secure backend that uses end-to-end encryption (based on [etebase](https://www.etebase.com)) to ALWAYS ensure user data remains private for their eyes only. 

_^ All gliff.ai products are stylised in **BLOCK CAPITALS**._

This repository contains the Open Source code for gliff.ai’s UPLOAD repository (gliff.ai’s component for uploading multidimensional images). 

UPLOAD aims to allow users to easily upload a variety of image files, including multidimensional TIFFs, for the purposes of developing imaging AI products. When the full gliff.ai platform is used, UPLOAD provides just one step in developing high-quality and auditable datasets that satisfy any relevant regulatory frameworks which enables our users to build world-changing and trustworthy AI models and products. 

These products are supported by a series of supporting libraries. These are:

- [**UPLOAD**](https://github.com/gliff-ai/upload) – gliff.ai’s component allowing for the upload of a variety of image files, including multidimensional TIFFs, into the gliff.ai platform.
- [**STYLE**](https://github.com/gliff-ai/style) – gliff.ai’s user-interface pattern gallery to establish consistency across our products, underpinned by gliff.ai branding.
- [**DOCUMENT**](https://github.com/gliff-ai/document) – gliff.ai’s platform user documentation to support users engaging with our platform for curating, annotation and collaborating with imaging datasets for the purposes of developing imaging AI products.

We also have released a plugin that has been developed during this process, which is:

- [**geolocation-map**](https://github.com/gliff-ai/geolocation-map) – enabling users to have access to a visual interactive map using heat mapping to demonstrate the origin location of images within their dataset in one click. 

## Guide

[{{back to navigation}}](#table-of-contents)

Our ROADMAP is documented through a github project board attached to this repository.

The board is organised into **4 columns** to communicate development progress/status along with giving a sense of time scale on how far out each item is on the horizon. These are:

- **released** – feature is already released.
- **working** – feature is expected to be introduced within 6 months time.
- **future** – feature is expected to be introduced after 6 months time.
- **exploration** – fearure has been requested/proposed but no engineering has yet occured.

Every item on the board is then categorised through **3 label groups** to communicate product location development, item priority and item complexity. These are:

**Product**  (gliff.ai green – #02FFAD)
- [ANNOTATE](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AANNNOTATE+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [CURATE](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3ACURATE+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [MANAGE](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3MANAGE+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [AUDIT](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AAUDIT+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [STYLE](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3ASTYLE+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [REGISTER](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AREGISTER+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [UPLOAD](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AUPLOAD+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [DOCUMENT](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3ADOCUMENT+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)

**Priority**  (gliff.ai purple – #AE79FF)
- [Highest](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AHighest+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [High](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AHigh+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [Medium](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AMedium+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [Low](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3ALow+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)
- [Lowest](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3ALowest+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=)

**Complexity**  (gliff.ai cyan – #00DBFF)
- [XXL](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AXXL+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=) – Extra extra large task.
- [XL](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AXL+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=) – Extra large task.
- [L](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AL+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=) – Large task.
- [M](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AM+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=) – Medium task.
- [S](https://github.com/search?q=user%3Agliff-ai+repo%3Aroadmap+label%3AS+is%3Aopen++repo%3Aroadmap&type=Repositories&ref=advsearch&l=&l=) – Small task.

## Contribute

[{{back to navigation}}](#table-of-contents)

This repository **does not accept contributions** unfortunately as content has been developed with specific gliff.ai team practises and preferences in mind.

However, we do have several repositories within the gliff.ai github space that we welcome all contributors and any contributions on. These will be marked with the topic tag **contributors-welcome** meaning we welcome contributions on this repository! Search for them [here](https://github.com/search?q=topic%3Acontributors-welcome+org%3Agliff-ai&type=Repositories)!

Check out the [gliff.ai Contribution Guide](https://github.com/gliff-ai/.github/blob/main/CONTRIBUTING.md) 👋 to learn more!
