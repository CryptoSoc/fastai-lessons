# Fastai Course Notebooks

This repo contains different versions of the [fastai course notebooks](https://github.com/fastai/course-v3). These can be used to practice after watching the [lectures](https://course.fast.ai/).

## Notebooks

Over the course you can go through the notebook for that week. Find them in the corresponding folder or open them in [Colab](https://colab.research.google.com/) from here.

In each week's folder, there are 3 other folders:

- `original`: The original notebooks from this weeks lesson.
- `guided_nbs`: Notebooks that guide you through the entire process of recreating the lesson.
- `hinted_nbs`: Notebooks that force you to learn more by just hinting what should be done.

### Week 1: Intro to Vision



## FAQ

### What workflow should I use?

My recommendation is to watch the lecture and just take some notes. After watching the lectures, go through the notebooks that Jeremy works through. Those can be found in the XXX folder. Get involved in the code in this step - use the tab completion, look at the docs, change some numbers and see what happens. Make sure you understand more or less whats going on.

After this, depending on your level of comfort with the course, you can reimplement the notebook.

- If you're feeling unsure about the code and can't remember too much, look at the XXX folder. This notebook will guide you through recreating the lesson's results and why we do it.
- If you are more confident but want some guidance, look in the XXX folder for the week. This notebook will lead you through the lesson with some hints and places to look.
- If you're confident, implement the lesson from a blank notebook. Import `fastai` and go through the week's application using either your own data or data from the library as best as you can.

### How should I get set up with a GPU?

There are several different options you can use and different providers offer different machine configurations and different user interfaces. The other meaningful difference is pricing. We suggest to go with the one you find easier to use (if you already have an account) or set-up (if not). Try Colab if you're just warming up and then try another.

Whatever provider you choose, you should make sure **from the first day** that you can set up and running a GPU-enabled Jupyter Notebook fairly quickly. Deep Learning is a tiresome endeavor and your development setup cannot be an obstacle. If there is any problem you cannot solve in your own, the [forums](forums.fast.ai) are your best friend, especially the [Install Issues Thread](https://forums.fast.ai/t/fastai-v1-install-issues-thread/24111/87).

#### Ready to run: "One-click" Jupyter

These are the easiest to use; they've got all the software, data, and lessons preinstalled for you. They're a little less flexible than "full servers" (below), but are the simplest way to get started.

- [Colab](https://course.fast.ai/start_colab.html); (instant approval, requires minimal installation, free)
- [Crestle](https://course.fast.ai/start_crestle.html); (instant approval, no installation required, $0.30 an hour)
- [Paperspace Gradient](https://course.fast.ai/start_gradient.html); (instant approval, no installation required, $0.59 an hour; $10 free credit)
- [Kaggle Kernels](https://course.fast.ai/start_kaggle.html); (Instant Launch, No setup required, Free)
- [Floydhub](https://course.fast.ai/start_floydhub.html); (instant approval, no installation required, $1.20/hour + $9.00/month (100GB storage), 2 hours free credit)
- [Salamander](https://course.fast.ai/start_salamander.html) (instant approval; no installation required; includes full terminal access; $0.38 an hour; $75 free credit for students)

#### Ready to run: Full servers

- [Google Compute Platform](https://course.fast.ai/start_gcp.html) ($0.38 an hour + storage, $300 free credit)
- [Azure](https://course.fast.ai/start_azure.html); (instant approval; no installation required; $0.90 an hour + storage for a VM OR $0.18 an hour + storage for [low priority preemptable instances](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-use-low-priority))

#### Some installation required

We also have instructions for using these platforms, but they don't have everything preinstalled yet:

- [SageMaker](https://course.fast.ai/start_sagemaker.html); (requires some installation, and wait for approval, $1.26 an hour + storage)
- [Amazon Web Services EC2](https://course.fast.ai/start_aws.html) ($0.9 an hour + storage)

**For those starting out, we highly recommend a Jupyter Notebooks platform (Option 1)**

* Notebooks are the easiest way to start writing python code and experimenting with deep learning.
* Renting a Cloud Server (Option 2) requires environment configuration and setup.
* Building a PC requires environment setup and more up-front money.
