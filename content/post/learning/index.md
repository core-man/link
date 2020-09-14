---
title: "Learning"
date: 2020-05-13
lastmod: 2020-05-13
author: core-man
draft: false
categories: ["Learning"]
slug: Learning
---


## Seismology

### Scientists’ notes

- [CPS](http://www.eas.slu.edu/eqc/eqccps.html): [Documentation](http://www.eas.slu.edu/eqc/eqc_cps/CPS/CPS330.html) | [Tutorials](http://www.eas.slu.edu/eqc/eqc_cps/TUTORIAL) | [Questions and Responses](http://www.eas.slu.edu/eqc/eqc_cps/Questions) | [Notes](http://www.eas.slu.edu/eqc/eqc_cps/workshop.html)
- [Lupei Zhu’s research notes](https://docplayer.net/62058516-Synthetic-seismograms-and-seismic-waveform-modeling-lupei-zhu-saint-louis-university.html)
- [Charles J. Ammon's research notes](http://eqseis.geosc.psu.edu/cammon/index.html)
- [Emile A. Okal’s notes](https://www.earth.northwestern.edu/individ/emile/462.Spring16)
- [William Menke’s research notes 1977-present](https://www.ldeo.columbia.edu/users/menke/research_notes/index.html)
- [格震至源](#格震至源): Prof. [Hongfeng Yang](https://www.cuhk.edu.hk/sci/essc/people/yang_hf.html)'s WeChat blog


### 地震学物理量

- 地震学中的坐标系
    - [地震学中的坐标系](https://blog.seisman.info/coordinate-systems-in-seismology): [SAC's rotate](https://seisman.github.io/SAC_Docs_zh/commands/rotate/) | [IRIS's rotation](https://service.iris.edu/irisws/rotation/docs/1/help/)
    - [SurfaceWaveMFA](http://eqseis.geosc.psu.edu/cammon/index.html): Moment-Tensor Conventions
    - [地震学断层的定义](https://blog.seisman.info/faults-in-seismology)
- Focal mechanism
    - [Focal Mechanisms Explained: What are those “beach balls”?](https://www.youtube.com/watch?v=MomVOkyDdLo): A 6-minute video explaining beachballs for non-seismologists and beginners.
    - [震源机制解的格式 (GMT5 psmeca)](https://docs.gmt-china.org/5.4/module/psmeca) | [GMT6 meca](https://docs.gmt-china.org/latest/module/meca/)


### 计算地震学

- Focal mechanism
    - [辐射花样的计算与震源球的绘制](https://blog.seisman.info/radiation-pattern-and-beach-ball)
    - [由矩张量计算双力偶断层参数](https://blog.seisman.info/moment-tensor-to-double-couple)
- 走时
    - [走时计算](https://blog.seisman.info/tags/%E8%B5%B0%E6%97%B6)


### 地震学数据

- 数据格式
    - [地震波形数据格式](https://blog.seisman.info/seismic-data-formats) | [Data Formats](https://ds.iris.edu/ds/nodes/dmc/data/formats/) | [Modern File Formats for Seismology](http://seismic-data.org/)
    - [ObsPy Supported Formats](https://docs.obspy.org/packages/autogen/obspy.core.stream.read.html#obspy.core.stream.read)
    - [SEED Channel Naming](https://ds.iris.edu/ds/nodes/dmc/data/formats/seed-channel-naming/) | [Time Series Data Channels](http://ds.iris.edu/ds/nodes/dmc/tools/data_channels/#???)
- 地震学仪器
    - tranditional instrument
        - [Instrumentation for Observational Seismology](https://www.iris.edu/hq/webinar/2020/04/instrumentation_for_observational_seismology__where_our_wiggles_come_from): Adam Ringler's talk
        - [Three Types of Noise Sources Recorded on Seismometers](https://www.youtube.com/watch?v=Eyi5Qoy3Iek&list=PLU4ZnBGMN1qjh1qjOmh3uvgzpciFF-xu3&index=16&t=3446s): Robert Anthony's talk
    - [Ocean Bottom Seismology](https://www.iris.edu/hq/webinar/2013/03/under_the_sea__ocean_bottom_seismology_for_landlubbers): Doug Wiens's talk
    - Rotational seismology
        - [International Working Group on Rotational Seismology](http://www.rotational-seismology.org/) | [Jupyter Notebooks](http://www.seismo-live.org/)
        - [Rotational Motions - a new observable for Seismology (2018)](https://www.youtube.com/watch?v=oUcVbZKRQfk): Heiner Igel's talk begins on `2:22:30`
    - Fiber-optic Seismology
        - [Review of DAS applications in geophysics](https://doi.org/10.1785/0220190112)
        - [Distributed Acoustic Sensing Virtual Workshop and Tutorial (2020)](https://www.iris.edu/hq/event/2020_DAS_Workshop)
        - [Fiber-optic Seismology in Theory and Practice (2020)](https://www.iris.edu/hq/webinar/2020/01/fiberoptic_seismology_in_theory_and_practice)
        - [Distributed Fiber-Optic Seismology in Theory and in Practice (2018)](https://www.youtube.com/watch?v=LAcQ44YRMuM)
- 仪器效应
    - [仪器响应](https://blog.seisman.info/tags/%E4%BB%AA%E5%99%A8%E5%93%8D%E5%BA%94) | [仪器响应](https://seisman.github.io/SAC_Docs_zh/appendix/resp/) | [Instrument Response](https://krischer.github.io/seismo_live_build/html/General%20Seismology/instrument_response_wrapper.html)
    - [去仪器响应](https://seisman.github.io/SAC_Docs_zh/data-process/instrument-response/)
    - [IRIS DMC Library of Nominal Responses for Seismic Instruments](http://ds.iris.edu/NRL/)
- SAC技巧
    - [SAC不同格式间的转换](https://blog.seisman.info/conversion-of-different-sac-formats)
    - [SAC技巧](https://blog.seisman.info/tags/SAC%E6%8A%80%E5%B7%A7) | [SAC 技巧与陷阱](https://seisman.github.io/SAC_Docs_zh/tricks-and-traps/)
    - [调用SAC进行Hilbert变换](https://blog.seisman.info/trash/sac-hilbert-transform)
- [New Manual of Seismological Observatory Practice](http://bib.telegrafenberg.de/en/publishing/distribution/nmsop/)
    - [CHAPTER 4: Seismic Signals and Noise](http://ebooks.gfz-potsdam.de/pubman/item/escidoc:124248)
    - [CHAPTER 5: Seismic Sensors and their Calibration](http://ebooks.gfz-potsdam.de/pubman/item/escidoc:56076)
    - [CHAPTER 6: Seismic Data Acquisition Systems](http://ebooks.gfz-potsdam.de/pubman/item/escidoc:4021)
    - [CHAPTER 7: Site Selection, Preparation and Installation of Seismic Stations](http://ebooks.gfz-potsdam.de/pubman/item/escidoc:43206)
    - [CHAPTER 10: Seismic Data Formats, Archival and Exchange](http://ebooks.gfz-potsdam.de/pubman/item/escidoc:43216)
- [Modern Approaches in Geophysics](https://www.springer.com/series/6248)
    - [Instrumentation in Earthquake Seismology](https://www.springer.com/gp/book/9789401751131)
    - [Of Poles and Zeros - Fundamentals of Digital Seismology](https://www.springer.com/gp/book/9780792368342)

### Deep Earthquakes

- [汪清7.2级深震——源于地球深部的跳动](https://mp.weixin.qq.com/s/mjQFAYmgFWQJv0vWKSJl_A)


### 格震至源

- Seismic Data
    - [屠龙宝刀生玄光：全球地震台网GSN](https://mp.weixin.qq.com/s/Hewceg1_rN32hxVgsoenfw)
    - [倚天长剑飞寒芒：地震学中的利器](https://mp.weixin.qq.com/s/vSbm6_cMxV0f8tiwIRe3EQ): 密集台阵
- Seismicity
    - [7月12日唐山5.1级地震是余震吗？](https://mp.weixin.qq.com/s/dsG-Km5Qhd1BKCAYileKjQ)
    - [擒龙功：神乎其技的地震远程触发](https://mp.weixin.qq.com/s/vBHiCvuhK6pjC41pMfWtbQ)
    - [诱发地震的“气剑”之争](https://mp.weixin.qq.com/s/JUrvmr0iCVVCK001CC8-2Q)
- Early Warning
    - [后发先至：跑赢时间的地震预警](https://mp.weixin.qq.com/s/SsrtTjMSpvf6EdqsKMxAoQ)
- Source Physics
    - [原来地震是这么回事儿](https://mp.weixin.qq.com/s/DyiVrw1S127VUl41_R7bGg)
    - [地震的能量都去哪儿了？](https://mp.weixin.qq.com/s/GKUisIX8yM9lhLyvghL3bw)
    - [仞丈之差——近断层位移对滑移弱化距离的近似](https://mp.weixin.qq.com/s/bEyNFuke5jDgXTxqXMWAyA)
    - [“举重若轻”的地震断层](https://mp.weixin.qq.com/s/FNkB_9_ThBiyWlrTX5DTLQ)
    - [断层辟了邪，破裂超剪切](https://mp.weixin.qq.com/s/z-zejXadexCIJRoF_E60xg)
    - [温润岫岩玉，奇妙蛇纹岩](https://mp.weixin.qq.com/s/fGkGvc-EM8Z6PBVfinrXKQ)
    - [小龙女跳崖：深渊之下有奇迹](https://mp.weixin.qq.com/s/2nqKGs8cIeLMUVAVdLbJBQ)
    - [潜入马里亚纳海沟-人类极限挑战](https://mp.weixin.qq.com/s/OhOX3nXq5vls9Y95DG6Erg)
- Tectonics
    - [大洋中脊核杂岩](https://mp.weixin.qq.com/s/oIN9s2pHOOrZucbehg-m0Q)

### 参考手册

- [IRIS DMC](http://ds.iris.edu/ds/nodes/dmc/)'s [manuals](http://ds.iris.edu/ds/nodes/dmc/manuals/) and [tutorials](http://ds.iris.edu/ds/nodes/dmc/tutorials/)


## Geodesy

- 震中距、方位角、反方位角: [计算](https://blog.seisman.info/calculate-dist-az-baz/) | [计算](https://zhaozhiyuan.org/post/distaz/) | [计算](https://seisman.github.io/SAC_Docs_zh/fileformat/header-variables/) | [SAC's distaz](https://seisman.github.io/SAC_Docs_zh/libs/libsacio/#distaz)
- [计算某点离海岸线的距离](https://blog.seisman.info/calculate-distance-to-coast)
- [Pacific Northwest Earth Science Animations](https://www.youtube.com/playlist?list=PLngDHXr1w29SVVyip5E9bYnuCcEeL-CGw): 俯冲带变形过程的卡通描述


## Geology

- [Geology Cafe](http://geologycafe.com/)


## 连续介质力学

- 卡通解释
    - [Malleable And Ductile](https://www.youtube.com/watch?v=99DQdM29ib8)
    - [Behaviour of Springs and Materials](https://www.youtube.com/playlist?list=PLlDtVvefFYT8h1s5owifl85J92_9ulwYg)
    - [Mechanics of Materials](https://www.youtube.com/channel/UCXAS_Ekkq0iFJ9dSUIkcAkw/playlists)


## Physics

- [Error Analysis in Experimental Physical Science](https://faraday.physics.utoronto.ca/PVB/Harrison/ErrorAnalysis/Propagation.html)


## Math

- [Autocorrelation analysis](https://emcee.readthedocs.io/en/stable/tutorials/autocorr/)
- [Seismic Tomography Using Variational Inference Methods](https://www.youtube.com/watch?v=OgAd82txLbM): Andrew Curtis's talk in 2020
- [狄拉克和他的δ 函数](https://www.ee.cityu.edu.hk/~gchen/pdf/Dirac_Delta.pdf)
- [关于正态分布，你不知道它诞生之路是多么“变态”](https://mp.weixin.qq.com/s/o6Yy-hIutAMBaabGiCIs7A)
- [正态分布的前世今生](http://www.medicine.mcgill.ca/epidemiology/hanley/bios601/Mean-Quantile/intro-normal-distribution-2.pdf)


## Data Analysis

### Machine Learning

- [Pattern Recognition and Machine Learning](https://www.springer.com/gp/book/9780387310732): [gen.lib.rus.ec](http://gen.lib.rus.ec/search.php?req=Pattern+Recognition+and+Machine+Learning&lg_topic=libgen&open=0&view=simple&res=25&phrase=1&column=def) | [知乎](https://www.zhihu.com/question/20970802)
- [Machine Learning](https://www.coursera.org/learn/machine-learning): Andrew Ng, Staford University | [youtube](https://www.youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN)
- [Machine Learning Plus](https://www.machinelearningplus.com/)
    - [Data Manipulation](https://www.machinelearningplus.com/category/data-manipulation/)
    - [Plots](https://www.machinelearningplus.com/category/plots/)
    - [Time Series](https://www.machinelearningplus.com/category/time-series/)
    - [Principal Components Analysis (PCA)](https://www.machinelearningplus.com/machine-learning/principal-components-analysis-pca-better-explained/)


## Signal

### Course

- [Signal and Systems: an introduction to analog and digital signal processing](https://ocw.mit.edu/resources/res-6-007-signals-and-systems-spring-2011/): Alan V. Oppenheim, MIT, 1987 | [youtube](https://www.youtube.com/watch?v=KJnAy6hzetw&list=PL41692B571DD0AF9B) | [网易公开课](http://open.163.com/newview/movie/courseintro?newurl=%2Fspecial%2Fopencourse%2Fsignals.html)
- [Discrete-Time Signal Processing](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-341-discrete-time-signal-processing-fall-2005/): Alan V. Oppenheim, MIT, 2005
- [Digital Signal Processing](https://ocw.mit.edu/resources/res-6-008-digital-signal-processing-spring-2011/): Alan V. Oppenheim, MIT, 1975 | [youtube](https://www.youtube.com/watch?v=rkvEM5Y3N60&list=PL8157CA8884571BA2)
- [Signal Processing: Continuous and Discrete](https://ocw.mit.edu/courses/mechanical-engineering/2-161-signal-processing-continuous-and-discrete-fall-2008/index.htm): Derek Rowell, MIT, 2008 | Level: Graduate
- [数字信号处理](https://web.xidian.edu.cn/kywang/teach.html): 本科生

### Fourier Transforms

- [An Interactive Introduction to Fourier Transforms](http://www.jezzamon.com/fourier/index.html) | [中文版](http://www.jezzamon.com/fourier/zh-cn.html)


## Computer

### Linux

- [46个Linux面试常见问题](https://cloud.tencent.com/developer/article/1527665)


## Programming

### Skills

- [这一团糟的代码，真的是我写的？！](https://developer.aliyun.com/article/718155)

### Algorithms

- [The Algorithms](https://thealgorithms.github.io/website/): Open Source resource for learning Data Structures & Algorithms and their implementation in any Programming Language | [GitHub](https://github.com/TheAlgorithms)
    - [C](https://github.com/TheAlgorithms/C)
    - [Python](https://github.com/TheAlgorithms/Python): [Chinese introduction](https://mp.weixin.qq.com/s/ZQGiqxoOGbTPO1c86mV9Tg)
    - [MATLAB/Octave](https://github.com/TheAlgorithms/MATLAB-Octave)
- [闰年的判断](https://blog.seisman.info/leap-year/)
- [判断字节序的多种方法](https://blog.seisman.info/linux-endian)

### Python

- Python Libraries
    - [SciPy](https://www.scipy.org/): a Python-based ecosystem of open-source software for mathematics, science, and engineering
        - [Getting started](https://www.scipy.org/getting-started.html)
        - [DOC](https://www.scipy.org/docs.html)
        - [Cookbook](https://scipy-cookbook.readthedocs.io/)
        - [Lecture Notes](http://scipy-lectures.org/): Getting started | Advanced topics | Packages and applications
    - [ObsPy](https://github.com/obspy/obspy): A Python Toolbox for seismology/seismological observatories | [DOC](https://docs.obspy.org/contents.html) | [Tutorial](https://docs.obspy.org/tutorial/index.html) & [Chinese tutorial](https://docs.obspy.org/archive/)
        - [Library Reference](https://docs.obspy.org/packages/index.html)
            - General Packages
                - [Core classes](https://docs.obspy.org/packages/obspy.core.html#module-obspy.core): common methods and classes for ObsPy, including the [Stream](https://docs.obspy.org/packages/autogen/obspy.core.stream.Stream.html#obspy.core.stream.Stream), [Trace](https://docs.obspy.org/packages/autogen/obspy.core.trace.Trace.html#obspy.core.trace.Trace), [UTCDateTime](https://docs.obspy.org/packages/autogen/obspy.core.utcdatetime.UTCDateTime.html#obspy.core.utcdatetime.UTCDateTime), [Stats](https://docs.obspy.org/packages/autogen/obspy.core.trace.Stats.html#obspy.core.trace.Stats) classes and methods for [reading](https://docs.obspy.org/packages/autogen/obspy.core.stream.read.html#obspy.core.stream.read) seismogram files
                - [Signal processing routines](https://docs.obspy.org/packages/obspy.signal.html#module-obspy.signa)
                - [Ray theoretical travel times and paths](https://docs.obspy.org/packages/obspy.taup.html#module-obspy.taup)
            - Scripts
            - Database or Web Service Access Clients
            - Waveform Import/Export Plug-ins
            - Event Data Import/Export Plug-ins
            - Inventory Data Import/Export Plug-ins
        - [ROSES: ObsPy](https://www.iris.edu/hq/inclass/course/roses): Remote Online Sessions for Emerging Seismologists
        - [Live Jupyter Notebooks for Seismology](http://www.seismo-live.org/): Ambient Seismic Noise | Data Visualization | General Seismology | ObsPy | Signal Processing | Workshops
        - [ObsPy Teaching Material](https://github.com/obspy/docs): Workshops / Posters / Presentations
- [NumPy](https://numpy.org/): The fundamental package for scientific computing with Python | [Documentation](https://numpy.org/doc/)
    - [Web](https://numpy.org/doc/stable/): stable version manual | [contents](https://numpy.org/doc/stable/contents.html#numpy-docs-mainpage)
        - [Numpy API Reference](https://numpy.org/doc/stable/reference/index.html): automatically generated reference documentation
            - [Routines](https://numpy.org/doc/stable/reference/routines.html): routine docstrings
                - [Statistics](https://numpy.org/doc/stable/reference/routines.statistics.html)
                - [Discrete Fourier Transform](https://numpy.org/doc/stable/reference/routines.fft.html)
    - [Latest (development) documentation](https://numpy.org/devdocs/): development version manual
    - Other learning sources
        - [Scipy leture notes](http://scipy-lectures.org/intro/numpy/index.html)
        - [A Visual Intro to NumPy and Data Representation](https://jalammar.github.io/visual-numpy/)
- [SciPy](https://scipy.org/scipylib/): [SciPy Documentation](https://docs.scipy.org/doc/)
    - [SciPy Reference Guide](https://docs.scipy.org/doc/scipy/reference/)
        - [SciPy API](https://docs.scipy.org/doc/scipy/reference/api.html)
        - [Tutorial](https://docs.scipy.org/doc/scipy/reference/)
        - API Reference
            - [Clustering package (scipy.cluster)](http://scipy.github.io/devdocs/cluster.html)
            - [Discrete Fourier transforms (scipy.fft)](http://scipy.github.io/devdocs/fft.html)
            - [Interpolation (scipy.interpolate)](http://scipy.github.io/devdocs/interpolate.html)
            - [Linear algebra (scipy.linalg)](http://scipy.github.io/devdocs/linalg.html)
            - [Statistical functions (scipy.stats)](http://scipy.github.io/devdocs/stats.html)
    - Other learning sources
        - [Scipy lecture notes](http://scipy-lectures.org/intro/scipy.html)
- [matplotlib](https://matplotlib.org/): a comprehensive library for creating static, animated, and interactive visualizations in Python
    - [Documentation](https://matplotlib.org/contents.html)
    - [Examples](https://matplotlib.org/gallery/index.html)
    - [Tutorials](https://matplotlib.org/tutorials/index.html)
    - Other learning sources
        - [Scipy lecture notes](http://scipy-lectures.org/intro/matplotlib/index.html)


###  Perl

- [时间加法](https://blog.seisman.info/perl-timespan)
- [单引号字符直接量](https://blog.seisman.info/perl-single-quoted-string-literals)
- [如何找出两个数组的交集、并集](https://blog.seisman.info/find-intersection-and-difference-of-two-arrays)


## Plot

- [GMT gallery](https://docs.generic-mapping-tools.org/6.0/gallery.html): [GMT-China gallery](https://gmt-china.org/gallery)
- [GMT-China blog](https://gmt-china.org/blog)
- [ml-visuals](https://github.com/dair-ai/ml-visuals): figures and templates used in Machine Learning | [Chinese introduction](http://www.python88.com/topic/63529)


## Lectures & Resources

### Collections

- [IRIS Webinars](https://www.iris.edu/hq/webinar/)
- [CIDER Lecture Collection](http://seismo.berkeley.edu/wiki_cider/CIDER_Lecture_Collection)
- [Earth Data Science](https://www.earthdatascience.org/): [Tutorials](https://www.earthdatascience.org/tutorials/) | [Courses & Textbooks](https://www.earthdatascience.org/courses/) | [Workshops](https://www.earthdatascience.org/workshops/)
- [Live Jupyter Notebooks for Seismology](http://www.seismo-live.org/): Some python scripts used in seismology
- [Community Online Resource for Statistical Seismicity Analysis](http://www.corssa.org/en/home/)

### Course & Workshop

- [Computers, Waves, Simulations: A Practical Introduction to Numerical Methods using Python](https://www.coursera.org/learn/computers-waves-simulations)
- [2020 Remote Online Sessions for Emerging Seismologists](https://www.iris.edu/hq/inclass/course/roses): a very good seismological course for Ph.D. students
- [2020 USTC seismological algorithms training](http://seismo.training.ustc.edu.cn/index.php): [bilibili vedio](https://www.bilibili.com/video/av841708479/) | [linkresearcher](https://www.linkresearcher.com/trainings/d65fe2ef-3cc8-4eef-9821-261e3d49a9ae)
- [2019 Southern University of Science and Technology Workshop (password: SUSTech2019)](https://owncloud.sustc.edu.cn/s/aF4ZK5C5SoLcejj)
- [2016 Subduction Zone Observatory Workshop](https://www.iris.edu/hq/workshops/2016/09/szo_16)


## Study and Research

- [Twenty things I wish I’d known when I started my PhD](https://www.nature.com/articles/d41586-018-07332-x): [中文版](https://hansonclinicalresearch.org/blog/f/%E7%BB%99%E5%8D%9A%E5%A3%AB%E7%94%9F%E7%9A%8420%E6%9D%A1%E5%BB%BA%E8%AE%AE)
- [10 easy ways to fail a Ph.D.](http://matt.might.net/articles/ways-to-fail-a-phd/): [中文版](https://mp.weixin.qq.com/s/Veil7ARFJXtAXMDfyNLcxQ)


## Misc

- [Essential Image Optimization](https://images.guide/)


## Revision history

- 2019-12-25: commit to seisman
- 2019-12-24: initial draft

