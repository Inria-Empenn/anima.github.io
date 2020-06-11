<!-- ![Anima](images/LogoAnima.png "Anima: library and python scripts for medical image processing") -->

<p align="justify"> 
Anima provides a set of software tools contributed by and coming from the research works from the [Empenn research team](https://team.inria.fr/empenn). It is a set of [ITK](http://www.itk.org) / [VTK](http://www.vtk.org) based libraries and multi-platform command line tools for medical image analysis. Among other tools, it contains software for image registration (linear and non linear block matching registration, EPI distortion correction), statistical analysis (group comparison, patient to group comparison), diffusion imaging (model estimation, tractography, etc.), quantitative MRI processing (quantitative relaxation times estimation, MR simulation), image denoising and filtering, and segmentation tools (Graph cut segmentation and multiple sclerosis lesion segmentation).
</p>

<p align="justify">
Anima core software tools are also the base for Anima scripts, a set of [python](https://www.python.org/) scripts and additional data from the [Empenn research team](https://team.inria.fr/empenn), to perform complex preprocessing and core processing tasks on medical images such as diffusion imaging, atlasing, brain extraction, relaxometry.
</p>

# Download 
{% assign release = site.github.latest_release %}
{{ release.assets[0] }}
<a href="{{ release.assets[0].browser_download_url }}">Anima latest release</a>
{% for repository in site.github.public_repositories %}
{% if repository.name == "Anima-Scripts-Public" %}
<a href="{{ repository.latest_release.assets[0].browser_download_url }}"> {{ repository.name }} latest release ({{ repository.latest_release.name }})</a>
{% endif %}
{% if repository.name == "Anima-Scripts-Data-Public" %}
<a href="{{ repository.latest_release.assets[0].browser_download_url }}"> {{ repository.name }} latest release ({{ repository.latest_release.name }})</a>
{% endif %}
{% endfor %}
