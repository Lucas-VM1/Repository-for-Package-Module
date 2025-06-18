---
type: "project" # DON'T TOUCH THIS ! :)
date: "2025-05-20" # Date you first upload your project.
# Deep Electrode Mapper: Using Deep Learning to Localize EEG Electrodes' Coordinates

# List the names of the collaborators within the [ ]. If alone, simple put your name within []
names: [Joel P. Diaz-Fong, Lucas Vidal Murakami, Aijia Ivy Zhong]

# Your project GitHub repository URL
github_repo: https://github.com/JOEwithanL/DeepElectrodeMapper

# List +- 4 keywords that best describe your project within []. Note that the project summary also involves a number of key words. Those are listed on top of the [github repository](https://github.com/PSY6983-2021/project_template), click `manage topics`.
# Please only lowercase letters
tags: [electrode localization, deep learning, clustering, preprocessing tools]

# Summarize your project in < ~75 words. This description will appear at the top of your page and on the list page with other projects.

summary: "Accurate source localization in EEG requires electrode's coordinates. However, currently this process requires skill and experience in dealing with different methods and softwares, which can be expensive, laborious and time consuming (Tveter et al., 2024). The Deep Electrode Mapper’s objective is to solve the electrodes’ localization issue by implementing deep learning to segment the electrodes from multiple image formats and find their coordinates via clustering. Currently the project is still in progress, and its development will be share via its repository. 

References:

Tveter, M., Tveitstøl, T., Nygaard, T., Kulashekhar, S., Bruña, R., Hammer, H. L., Hatlestad-Hall, C., & Haraldsen, I. R. H. (2024). EEG electrodes and where to find them: automated localization from 3D scans. Journal of Neural Engineering, 21(5), 056022."

# If you want to add a cover image (listpage and image in the right), add it to your directory and indicate the name
# below with the extension.
image: ""
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background

When using EEG for clinical or research analysis of brain activity the problem of associating a recording to a specific brain region (i.e., source localization) needs to be addressed for meaningful analysis. Although dependent on some variables, knowing the coordinates of the electrodes (i.e., where the signal is being recorded) precisely and accurately is central for source localization (Hirth et al., 2020). However, currently getting electrodes' coordinates are either time-consuming, requiring manual labeling of each electrode, or using specilzed software that are expensive to use (Tveter et al., 2024), adding to the skills and experience required in either method. In addition, there are multiple file formats that can be used for extracting the electrodes' coordinates, for example, MRI volumes (Pinte et al., 2021), 3D scans and photogrammetry (Hirth et al., 2020). Therefore, having a a pipeline that is less labour intensive and expensive, while accounting for the multiple set-ups and file formats would be an ideal imporvement in the process of electrodes' localization.
There has been development in improving the electrodes' localization process, for example pipeline using phones as portable scanners, algorithms that predict other electrode coordinates based on a smaller subset for multiple channels' setups (Hirth et al., 2020), and even the usage of deep learning to localize the coordinates from MRI scans (Pinte et al., 2021). 
In light of such developments, this project aimed to use deep learning to perform localization of electrodes, while accounting that the pipeline is generalizable for different file formats and set-ups, so it can be used inspite of the methodology used.

References:

Everitt, A., Richards, H., Song, Y., Smith, J., Kobylarz, E., Lukovits, T., Halter, R., & Murphy, E. (2023). EEG electrode localization with 3D iPhone scanning using point-cloud electrode selection (PC-ES). Journal of Neural Engineering, 20(6), 066033.

Hirth, L. N., Stanley, C. J., Damiano, D. L., & Bulea, T. C. (2020). Algorithmic localization of high-density EEG electrode positions using motion capture. Journal of neuroscience methods, 346, 108919. https://doi.org/10.1016/j.jneumeth.2020.108919.

Pinte, C., Fleury, M., & Maurel, P. (2021). Deep learning-based localization of EEG electrodes within MRI acquisitions. Frontiers in Neurology, 12, 644278.

Tveter, M., Tveitstøl, T., Nygaard, T., Kulashekhar, S., Bruña, R., Hammer, H. L., Hatlestad-Hall, C., & Haraldsen, I. R. H. (2024). EEG electrodes and where to find them: automated localization from 3D scans. Journal of Neural Engineering, 21(5), 056022."

<iframe width="560" height="315" src="https://www.youtube.com/embed/PTYs_JFKsHI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Tools

The "project template" project will rely on the following technologies:
 * Markdown, to structure the text.
 * The Hugo website framework which is used by the BHS website. This makes it possible to easily add the markdown project description to the website.
 * Adding the project to the website relies on github, through pull requests.

### Data

Ultimately, the project template will be used by all BHS participants. Data on the different projects will be aggregareted on the [following page](https://psy6983.brainhackmtl.org/project). This will serve as an additional example gallery in the years to come for future brainhack school students. Many reports from [BHS 2020](https://github.com/brainhack-school2020) already used this template.

### Deliverables

At the end of this project, we will have:
 - The current markdown document, completed and revised.
 - A gallery of the student projects at Brainhack 2020.
 - Instructions on the website about how to submit a pull request to the [brainhack school website](https://github.com/PSY6983-2021) in order to add the project description to the website.

## Results

### Progress overview

The project was swiftly initiated by P Bellec, based on the existing template created in 2019 by Tristan Glatard and improved by different students. It was really not that hard. Community feedback is expected to lead to rapid further improvements of this first version.

### Tools I learned during this project

 * **Meta-project** P Bellec learned how to do a meta project for the first time, which is developping a framework while using it at the same time. It felt really weird, but somehow quite fun as well.
 * **Github workflow-** The successful use of this template approach will demonstrate that it is possible to incorporate dozens of students presentation on a website collaboratively over a few weeks.
 * **Project content** Through the project reports generated using the template, it is possible to learn about what exactly the brainhack school students are working on.

### Results

#### Deliverable 1: report template

You are currently reading the report template! I will let you judge whether it is useful or not. If you think there is something that could be improved, please do not hesitate to open an issue [here](https://github.com/PSY6983-2021/project_template/issues/) and let us know.

#### Deliverable 2: project gallery

You can check out the [2020 BrainHack School project gallery](https://psy6983.brainhackmtl.org/project/)

##### ECG pupilometry pipeline by Marce Kauffmann

The repository of this project can be found [here](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann). The objective was to create a processing pipeline for ECG and pupillometry data. The motivation behind this task is that Marcel's lab (MIST Lab @ Polytechnique Montreal) was conducting a Human-Robot-Interaction user study. The repo features:
 * a [video introduction](http://www.youtube.com/watch/8ZVCNeX42_A) to the project.
 * a presentation [made in a jupyter notebook](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann/blob/master/BrainHackPresentation.ipynb) on the results of the project.
 * Notebooks for all analyses.
 * Detailed requirements files, making it easy for others to replicate the environment of the notebook.
 * An overview of the results in the markdown document.

##### Other projects
Here are other good examples of repositories:
- [Learning to manipulate biosignals with python](https://github.com/mtl-brainhack-school-2019/franclespinas-biosignals) by François Lespinasse
- [Run multivariate anaylysis to relate behavioral and electropyhysiological data](https://github.com/mtl-brainhack-school-2019/PLS_PV_Behaviour)
- [PET pipeline automation and structural MRI exploration](https://github.com/mtl-brainhack-school-2019/rwickens-sMRI-PET) by Rebekah Wickens
- [Working with PSG [EEG] data from Parkinson's patients](https://github.com/mtl-brainhack-school-2019/Soraya-sleep-data-in-PD-patients) by Cryomatrix
- [Exploring Brain Functional Activation in Adolescents Who Attempted Suicide](https://github.com/mtl-brainhack-school-2019/Anthony-Gifuni-repo) by Anthony Gifuni

#### Deliverable 3: Instructions

 To be made available soon.

## Conclusion and acknowledgement

The BHS team hope you will find this template helpful in documenting your project. Developping this template was a group effort, and benefitted from the feedback and ideas of all BHS students over the years.

You can also make submit your project to neurolibre https://neurolibre.org/. It is a preprint server for interactive data analyses. It is tailored for publishing interactive neuroscience notebooks that can seamlessly integrate data, text, code and figures.The submission instructions can be found here https://docs.neurolibre.org/en/latest/index.html and the jupyter book docs there https://jupyterbook.org/intro.html.
