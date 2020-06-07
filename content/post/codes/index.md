---
title: "Codes"
date: 2020-03-15
lastmod: 2020-03-15
author: core-man
draft: false
categories: ["Geoscience code"]
slug: codes
---

## Seismic Data Downloading and Processing

### Data Request Tools

- [SOD](http://www.seis.sc.edu/sod): The best seismic data request tool | [Tutorial (in Chinese)](https://blog.seisman.info/sod-notes) | [Recipes](https://github.com/seisman/SODrecipes)
- [ObsPy](https://github.com/obspy/obspy): Data download, processing and visulization software written in Python
    - [ObsPy docs](https://github.com/obspy/docs): Some teaching materials including data request
    - Some obspy scripts
        - [fetch_Events](https://github.com/jbrussell/fetch_EVENTS): Download event data from IRIS-DMC
        - [fetch_NOISE](https://github.com/jbrussell/fetch_NOISE): Download daily seismograms from the IRIS-DMC
- [HinetPy](https://seisman.github.io/HinetPy): Request data from Hi-net server, written in Python | [Hinet notes](https://blog.seisman.info/hinet)
- [FDSN Web Services](http://www.fdsn.org/webservices) | [Chinese note](https://blog.seisman.info/web-service-clients)
- [IRIS DMC Web Services](http://service.iris.edu)
    - [Web Service Fetch scripts](https://seiscode.iris.washington.edu/projects/ws-fetch-scripts): Data request scripts written in Perl | [Chinese note](https://blog.seisman.info/web-service-fetch-scripts)
- [ROVER](https://iris-edu.github.io/rover): A command line tool to robustly retrieve geophysical timeseries data from data centers
- [BREQ_FAST](http://ds.iris.edu/ds/nodes/dmc/manuals/breq_fast): Seismic data request by sending email | [Chinese note](https://blog.seisman.info/tags/breq_fast)
- [IRIS Wilber 3](http://ds.iris.edu/wilber3/find_event): A web GUI to request waveform data of individual seismic events | [Chinese note](https://blog.seisman.info/wilber3)
- [jweed](http://ds.iris.edu/ds/nodes/dmc/software/downloads/jweed): Data request client written in Java
- [StrongMotion Fetch](https://www.usgs.gov/software/strongmotion-fetch): download and/or process strong motion data from various networks



### Seismic Data Format Conversion

- [rdseed](https://github.com/iris-edu-legacy/rdseed): Convert seismic data from SEED format to other common format, e.g., SAC
    - Data extraction has some problems with the sources. We have to use the binary instead, which can be found in [IRIS](http://ds.iris.edu/pub/programs). | [Chinese install manual](https://blog.seisman.info/rdseed-install) | [Chinese note](https://blog.seisman.info/tags/SEED)
- [sac2mseed](https://seiscode.iris.washington.edu/projects/sac2mseed): Convert SAC format to minniSEED format
- [mseed2sac](https://github.com/iris-edu/mseed2sac): Convert miniSEED format to SAC format
- [win32tools](http://www.hinet.bosai.go.jp/REGS/manual/dlDialogue.php?r=win32tools): Convert WIN32 format used by Hi-net, to SAC format
- [dataselect](https://seiscode.iris.washington.edu/projects/dataselect): Selection and sorting for data in miniSEED format
- [msmod](https://seiscode.iris.washington.edu/projects/msmod): A small program to modify miniSEED header values
- [ObsPy](https://github.com/obspy/obspy): Data download, processing and visulization software written in Python



### Seismic Data Processing

- [SAC](http://ds.iris.edu/ds/nodes/dmc/forms/sac): The most commonly used seismic data processing software | [Chinese manual](https://seisman.github.io/SAC_Docs_zh)
- [ObsPy](https://github.com/obspy/obspy): Data download, processing and visulization software written in Python
- [GISMO](http://geoscience-community-codes.github.io/GISMO): Data download, processing and visulization software written in Matlab
- [SeisIO.jl](https://github.com/jpjones76/SeisIO.jl): Data download, processing and visulization software written in Julia
- [Geopsy](http://www.geopsy.org/download.php): An open source software for geophysical research and application written in C++



--------------------
## Plot

- [GMT](https://www.generic-mapping-tools.org): The most popular mapping tools in Earth Science
    - [GMT中文图库](https://gmt-china.org/gallery) | [GMT gallery](https://docs.generic-mapping-tools.org/6.0/gallery.html)
    - [GMT China](https://gmt-china.org/#) | [GMT Chinese Manual](https://docs.gmt-china.org/6.0)
- [PyGMT](https://www.pygmt.org/dev/index.html): A Python interface for GMT (in the early stages of design and implementation)
- [ObsPy](https://github.com/obspy/obspy): Data download, processing and visulization software written in Python
- [JPlotResp](http://www.isti2.com/JPlotResp): Plot amplitude and phase of instrumental responses in RESP format | [Chinese note](https://blog.seisman.info/jplotresp)
- [MoPad](http://www.larskrieger.de/mopad): Analysis and visulization of seismic moment tensor, focal mechanism | [Chinese note](https://blog.seisman.info/mopad)
- [obspy-mopad](https://docs.obspy.org/packages/autogen/obspy.imaging.scripts.mopad.html): similar to MoPad, provided by ObsPy
- [pssac](http://www.eas.slu.edu/People/LZhu/home.html): GMT-style SAC trace plotting for GMT4 | [pssac notes](https://blog.seisman.info/tags/pssac) | [pssac2 notes](https://blog.seisman.info/tags/pssac2)
- [EMC visualization tools](http://ds.iris.edu/dms/products/emc/horizontalSlice.html)
- [EMC-ParaView](https://github.com/iris-edu/EMC-ParaView): A set of Python programmable filters/sources to allow ParaView open-source, multi-platform data analysis and visualization application to display EMC netCDF/GeoCSV models along with other auxiliary Earth data.
- [3D Focal Mechanisms](https://www.usgs.gov/software/3d-focal-mechanisms): View earthquake focal mechanism symbols three dimensionally
- [SeisTomoPy](https://seiscode.iris.washington.edu/projects/seistomopy): Visulization of 3D tomography models and calculate traveltime in 3D model
- [SubMachine](https://www.earth.ox.ac.uk/~smachine/cgi/index.php): Web-Based Tools for Exploring Seismic Tomography and Other Models of Earth’s Deep Interior
- [Tomoeye](http://www.iearth.org.au/codes/Tomoeye): a set of programs for tomographic model visualization written in MatLab 6.1 script



---------------------------
## Traveltime Calculation/Ray Tracing

- [TauP](http://www.seis.sc.edu/TauP): Calculate travel times, ray paths, pierce and turning points etc. | [Chinese introduction](https://blog.seisman.info/tags/TauP)
- [obspy.taup](http://docs.obspy.org/packages/obspy.taup.html): TauP, rewritten in Python
- iaspei-tau traveltime table package
    - Arthur Snoke's version: Traveltime calculator for iasp91 and AK135 models | [IASPEI](http://www.iaspei.org/downloads) | [IRIS code](https://seiscode.iris.washington.edu/projects/iaspei-tau)
    - [B.L.N. Kennett and Ray Buland's version](http://rses.anu.edu.au/seismology/soft/ttsoft.html): Calculation of travel times and ellipticity corrections for iasp91 and AK135 models | [Some revisions to compile the codes](https://github.com/seisman/TravelTimeEllipcityCorrection)
    - [George Helffrich's version](https://members.elsi.jp/~george/sac-bugs.html#ttimes): Traveltime calculator for iasp91, AK135, PREM etc.
- [Cake](https://pyrocko.org): Traveltime calculation software, written in Python.
- [ANISOtime](http://www-solid.eps.s.u-tokyo.ac.jp/~dsm/anisotime.html): Traveltime calculation for transversely isotropic (TI) spherically symmetric models
- [FM3D](http://rses.anu.edu.au/seismology/soft/fmmcode): 3D traveltime calculation using Fast Marching Method
- [pySeismicFMM](https://github.com/gozwei/pySeismicFMM): 3D traveltime calculation using Fast Marching Method, C codes with a Python interface
- [Surface Wave Ray Tracing with Azimuthal Anisotropy](http://www.spice-rtn.org/library/software/traceswani/softwarerelease.2006-11-16.2126060784.html): Surface Wave Ray Tracing with Azimuthal Anisotropy


## Synthetic Seismograms

### 1D methods in a layered earth

#### Ray theory

- [aser](http://www.eas.slu.edu/People/LZhu/home.html): Calculate synthetic seismograms based on Generalized Ray Theory
- [Ray theory](http://www.spice-rtn.org/library/software/Raytheory.html): Ray-theoretical approach to the calculation of synthetic seismograms in global Earth models
- [Generalized ray in CPS330](http://www.eas.slu.edu/eqc/eqccps.html): Collection of programs for calculating theorectical seismogram, receiver function, surface wave dispersion curve et al. | [Chinese install introduction](https://blog.seisman.info/cps330-install) and [Chinese introdution](https://blog.seisman.info/cps330)
- [Asymptotic ray theory in CPS330](http://www.eas.slu.edu/eqc/eqccps.html): Collection of programs for calculating theorectical seismogram, receiver function, surface wave dispersion curve et al. | [Chinese install introduction](https://blog.seisman.info/cps330-install) and [Chinese introdution](https://blog.seisman.info/cps330)
- [WKBJ method in seisan](http://seisan.info): [Seismology at GEUS](http://seis.geus.net)


#### Reflectivity method

- [fk](http://www.eas.slu.edu/People/LZhu/home.html): Calculate synthetic seismograms in layered isotropic models, using frequency-wavenumber method | [Chinese introduction](https://blog.seisman.info/fk-notes) | [Intall fk](https://blog.seisman.info/fk-install)
- [QSEIS](https://www.gfz-potsdam.de/en/section/physics-of-earthquakes-and-volcanoes/infrastructure/tool-development-lab/): Calculating synthetic seismograms based on a layered viscoelastic half-space earth model
- [Reflectivity method](http://www.spice-rtn.org/library/software/ERZSOL3.html): Calculating the response of a layered uniform solid layers to excitation by a point moment tensor source using the reflectivity method


#### Wavenumber integration (Another name is discrete wavenumber?)

- [Wavenumber integration method in CPS330](http://www.eas.slu.edu/eqc/eqccps.html): Collection of programs for calculating theorectical seismogram, receiver function, surface wave dispersion curve et al. | [Chinese install introduction](https://blog.seisman.info/cps330-install) and [Chinese introdution](https://blog.seisman.info/cps330)
- [Discrete wavenumber method in seisan](http://seisan.info): [Seismology at GEUS](http://seis.geus.net)



#### Modal Summation

- [Modal Summation in CPS330](http://www.eas.slu.edu/eqc/eqccps.html): Collection of programs for calculating theorectical seismogram, receiver function, surface wave dispersion curve et al. | [Chinese install introduction](https://blog.seisman.info/cps330-install) and [Chinese introdution](https://blog.seisman.info/cps330)



### 1D methods in a spherical earth

#### Reflectivity method

- [yaseis](https://seiscode.iris.washington.edu/projects/yaseis): Calculate synthetic seismograms in spherically layered isotropic models, using frequency-wavenumber method

#### Normal modes

- [CIG's Mineos](https://github.com/geodynamics/mineos): Computes synthetic seismograms in a spherically symmetric non-rotating Earth by summing normal modes
- [Colleen Dalton's Mineos](https://github.com/jbrussell/MINEOS): All the tools one should need to compile and run the MINEOS program, including MATLAB driver scripts.
    - [Matlab to MINEOS](https://github.com/jbrussell/matlab_to_mineos): Wrapper scripts for running MINEOS through MATLAB.
    - [MINEOS_synthetics](https://github.com/jbrussell/MINEOS_synthetics): Calculate dispersion tables and synthetic seismograms for layered models using MINEOS and idagrn6 housed within MATLAB wrappers
- [Generalized Eigenproblem Spectral Collocation](https://github.com/mdenolle/gesc)
- [Normal modes](http://www.spice-rtn.org/library/software/Normal%20Modes.html): Normal-mode based computation of seismograms for spherically symmetric Earth models
- [QSSP](https://www.gfz-potsdam.de/en/section/physics-of-earthquakes-and-volcanoes/infrastructure/tool-development-lab/): Calculating complete synthetic seismograms of a spherical earth using the normal mode theory
- DISPER80: Calculation of normal modes, which is a very old fortran code. You have to ask for it from someone who conducts surface-wave studies.


#### Direct solution method

- [DSM](http://www-solid.eps.s.u-tokyo.ac.jp/~dsm/software/software.htm): Computing synthetic seismograms in spherically symmetric transversely isotropic (TI) media using the Direct Solution Method | [updated version](http://www.eri.u-tokyo.ac.jp/people/takeuchi/)
- [GEMINI](http://www.spice-rtn.org/library/software/GEMINI.html): Calculation of synthetic seismograms for global, spherically symmetric media based in direct evaluation of Green's functions (The files seem wrong)
- [DGRFN](https://www.usgs.gov/software/direct-greens-function-synthetic-seismograms): Calculate synthetic seismograms on a radially stratified model



### Finite Difference Methods

- [SOFI2D](https://git.scc.kit.edu/GPIAG-Software/SOFI2D): 2D finite-difference seismic P-SV simulation | [Chinese note](https://blog.seisman.info/sofi2d-notes)
- [SOFI2D_sh](https://git.scc.kit.edu/GPIAG-Software/SOFI2D_sh): 2D finite-difference seismic SH-wave simulation
- [SOFI3D](https://git.scc.kit.edu/GPIAG-Software/SOFI3D): 3D finite-difference seismic wave simulation
- [FD2D](http://www.spice-rtn.org/library/software/Fd2d.html): A very simple training code for 2D finite difference
- [FD3S](http://www.spice-rtn.org/library/software/FD3S.html): 3D finite-difference seismic wave simulation in a spherical section
- [FD1D](http://www.nuquake.eu/Computer_Codes/1dfd.htm)
    - [1DFD_DS](http://www.spice-rtn.org/library/software/1DFDDS.html): 1D finite-difference seismic simulation using the displacement-stress staggered-grid
    - [1DFD_DVS](http://www.spice-rtn.org/library/software/1DFDDVS.html): 1D finite-difference seismic simulation using the displacement-velocity-stress staggered-grid
    - [1DFD_VS](http://www.spice-rtn.org/library/software/1DFDVS.html): 1D finite-difference seismic simulation using the velocity-stress staggered-grid
- [2DFD_DVS](http://www.nuquake.eu/Computer_Codes/2dfd.htm): Computation of seismic wavefields in 2D heterogeneous structures with planar free surface due to linear double-couple source or linear single force or plane-wave incidence
- [FDSim3D](http://www.nuquake.eu/Computer_Codes/3dfd.htm): Computation of seismic wavefields in 3D heterogeneous surface geological structures with planar free surface due to surface and near-surface point double couple sources or by a vertically incident plane wave.
- [SEISMIC_CPML](https://github.com/geodynamics/seismic_cpml): 2D/3D Finite-Difference Seismic Wave Simulation + CPML
- [SW4](https://github.com/geodynamics/sw4): 3D Finite-Difference Seismic Wave Simulation (4th order)
- [OpenSWPC](https://github.com/tktmyd/OpenSWPC): 2D/3D Finite-Difference Seismic Wave Simulation




### Finite Element Methods

- [3DFE_GSM](http://www.nuquake.eu/Computer_Codes/request.htm)
- [3DFE_REF](http://www.nuquake.eu/Computer_Codes/request.htm)


### Pseudo-Spectral Methods

- [Ps2D](http://www.spice-rtn.org/library/software/Ps2d.html): A very simple code for elastic wave simulation in 2D using a Pseudo-Spectral Fourier method



### Spectral Element Methods

- [SPECFEM1D](https://github.com/geodynamics/specfem1d): A small code that allows users to learn how a spectral-element program is written
- [SPECFEM2D](https://github.com/geodynamics/specfem2d): Simulates seismic wave propagation in a 2D heterogeneous medium, using spectral element method (spherical coordinate system)
    - FK-2DSEM can be requested from Ping Tong. Is the 2D SEM in spherical coordinate?
- [SPECFEM3D](https://github.com/geodynamics/specfem3d): Simulates seismic wave propagation in a 3D heterogeneous medium, using spectral element method (Cartesian coordinate system)
    - DSM-SEM & AxiSEM-SEM can be found in `EXTERNAL_PACKAGES_coupled_with_SPECFEM3D`
    - FK is not an external code, it is now called internally
    - The coulping can be found in `specfem3D/couple_with_injection.f90`
- [SPECFEM3D_GLOBE](https://github.com/geodynamics/specfem3d_globe): Simulates seismic wave propagation in a 3D heterogeneous medium, using spectral element method (spherical coordinate system)
- [SEM_DSM_hybrid](https://github.com/wenbowu-geo/SEM_DSM_hybrid): A hybrid method to efficiently compute teleseismic synthetics with 3D seismic strucure at source side (SEM) and 1D strucure outside the source region (DSM).
- [RegSEM](http://www.quest-itn.org/library/software/regsem.html): Simulates seismic wave propagation in a 3D heterogeneous media, using spectral element method at the regional scale. Regional scale means distances ranging from about 1 km (local scale) to 90 degree (continental scale).
- [AxiSEM](https://github.com/geodynamics/axisem): A parallel spectral-element method to solve 3D wave propagation in a sphere with axisymmetric or spherically symmetric visco-elastic, acoustic, anisotropic structures.
- [Instaseis](http://instaseis.net): The Python interface of AxiSEM
- [AxiSEM3D](https://github.com/kuangdai/AxiSEM3D)
- [NEXD](http://www.gmg.ruhr-uni-bochum.de/geophysik/seismology/nexd.html): Nodal Discontinuous Galerkin Method | [1D](https://github.com/seismology-RUB/NEXD-1D) | [2D](https://github.com/seismology-RUB/NEXD-2D) | [3D](https://github.com/seismology-RUB/NEXD-3D)
- [2DSPEC](http://www.spice-rtn.org/library/software/2DSPEC.html): A parallel/serial 2d spectral element code for wave propagation and rupture dynamics
- [sem2dpack](http://www.spice-rtn.org/library/software/sem2dpack.html): A spectral element package for 2D wave propagation and earthquake rupture dynamics


### Discontinuous Galerkin Method

- [SeisSol](https://github.com/SeisSol/SeisSol): a scientific software for the numerical simulation of seismic wave phenomena and earthquake dynamics



### Surface waves in 3D structures

- [Couplage](http://www.quest-itn.org/library/software/couplage): Modelling of propagation of surface waves in 3D structures by mode coupling method


### Hybrid method

- [PSV Hybrid](http://geophysics.geo.sunysb.edu/wen/resource/index.html): Calculating synthetic seismograms involving two-dimensional localized hetergeneous structures based on GRT-FD hybrid method.


---------------
## Seismic Source

### Earthquake Detection

- [REAL](https://github.com/Dal-mzhang/REAL): Rapid Earthquake Association and Location
- [Match&Locate](https://github.com/Dal-mzhang/MatchLocate2): Template detecting and locating of small earthquakes
- [GPU-MatchLocate1.0](https://github.com/MinLiu19/GPU-MatchLocate1.0): A GPU version of Match&Locate
- [FastMatchedFilter](https://github.com/beridel/fast_matched_filter): An efficient seismic matched-filter search for both CPU and GPU architectures.
- [EQcorrscan](https://github.com/eqcorrscan/EQcorrscan): A python package for the detection and analysis of repeating and near-repeating earthquakes
- [REDPy](https://github.com/ahotovec/REDPy): Repeating Earthquake Detector, written in Python


### Earthquake Location

- [GrowClust](https://github.com/dttrugman/GrowClust): Relative relocation for earthquake hypocenters
- [HypoDD](https://www.ldeo.columbia.edu/~felixw/hypoDD.html): Double-difference earthquake location
- [HypoRelocate](https://github.com/sun1022/hypoRelocate): High-resolution earthquake relocation method
- [HYPOINVERSE2000](https://www.usgs.gov/software/hypoinverse-earthquake-location): Locate earthquakes and determine magnitudes in a local or regional seismic network
- [NonLinLoc](https://seiscode.iris.washington.edu/projects/nonlinloc): Probabilistic, Non-Linear, Global-Search Earthquake Location in 3D Media.
- [REAL](https://github.com/Dal-mzhang/REAL): Rapid Earthquake Association and Location
- [Velest](https://seg.ethz.ch/software/velest.html): 1-D inversion of velocities and hypocenter locations
    - This code is modified to be used in [REAL](https://github.com/Dal-mzhang/REAL)



### Focal Mechanism

- [gCAP](http://www.eas.slu.edu/People/LZhu/home.html): Focal mechanism inversion using cut and paste method | [Chinese note](https://blog.seisman.info/gcap-install)
- [CPS330](http://www.eas.slu.edu/eqc/eqccps.html): Collection of programs for calculating theorectical seismogram, receiver function, surface wave dispersion curve et al. | [Chinese install introduction](https://blog.seisman.info/cps330-install) and [Chinese introdution](https://blog.seisman.info/cps330)
- [W Phase](http://eost.u-strasbg.fr/wphase): Moment tensor inversion using W phase
- [focmec](https://seiscode.iris.washington.edu/projects/focmec): Package for determining and displaying double-couple earthquake focal mechanisms based on polarities and amplitude ratios
- [HASH](https://earthquake.usgs.gov/research/software/#HASH): Determine double-couple earthquake focal mechanisms based on P-wave polarity and S/P amplitude ratios
- [FPFIT](https://www.usgs.gov/software/fpfit-fpplot-and-fppage): Calculate and plot fault-plane solutions from first-motion data
- [ISOLA](http://www.spice-rtn.org/library/software/ISOLA.html): Retrieve isolated asperities from regional or local waveforms based on multiple-point source representation and iterative deconvolution
- [MTfit](https://github.com/djpugh/MTfit): Bayesian Moment Tensor Fitting
- [pyTDMT](https://github.com/fabriziobernardi/pydmt): time-domain focal mechanism inversion, written in Python
- [hybridMT](https://www.induced.pl/software): MATLAB package for moment tensor inversion and refinement
    - [fociMT](https://www.induced.pl/software): A stand-alone command line application for seismic moment tensor inversion, which is an integral part of hybridMT package
- [FOCI](https://www.induced.pl/software): A stand-alone Windows GUI application for performing the seismic moment tensor inversion and source parameters assessment
- [RPGEN](https://www.induced.pl/software/radiation-of-psshsv-waves-from-shear-tensile-source-model): Radiation of P/S/SH/SV waves from shear-tensile source model
- [MT_DECOMPOSITION](https://www.ig.cas.cz/mt-decomposition): A Matlab software package for the moment tensor decomposition
- [PCA-DECOMPOSITION](https://www.ig.cas.cz/en/pca-decomposition): A Matlab software package for the Principal Component Decomposition of seismic traces for extracting the common wavelet


### Seismicity

- [CLUSTER2000](https://www.usgs.gov/software/cluster2000): Identify clusters (e.g., aftershocks) in an earthquake catalog
- [ZMAP](http://www.seismo.ethz.ch/en/research-and-teaching/products-software/software/ZMAP): A software package to analyze seismicity


### Stress

- [Coulomb 3](https://www.usgs.gov/software/coulomb-3): Investigate Coulomb stress changes on mapped faults and earthquake nodal planes
- [SATSI](https://www.usgs.gov/software/satsi): Spatially and/or temporally varying stress field from focal mechanisms
- [MSATSI](https://www.induced.pl/software): MATLAB package for stress tensor inversion
- [STRESSINVERSE](https://www.ig.cas.cz/en/stress-inverse): A Matlab or Python software package for an iterative joint inversion for stress and fault orientations from focal mechanisms


### Source Spectrum

- [Multitaper Spectrum Estimation Library](https://www.gaprieto.com/software)


---------------------------
## Seismic Imaging

### Body-wave tomography

- [Nick Rawlinson's softwares](http://rses.anu.edu.au/~nick)
    - [FMTOMO](http://rses.anu.edu.au/~nick/fmtomo.html): 3-D traveltime tomography based on fast marching method | [FMTOMO at iEarth](http://www.iearth.org.au/codes/FMTOMO)
    - [FMTT](http://rses.anu.edu.au/~nick/teletomo.html): Teleseismic tomography based on fast marching method | [FMTT at iEarth](http://www.iearth.org.au/codes/FMTT)
- [SIMUL2000](https://www.usgs.gov/software/3d-velocity-modeling): Traveltime tomography


### Surface-wave tomography

#### Teleseismic surface-wave tomography

- [Huajian Yao's Lab](http://yaolab.ustc.edu.cn/resources.php?i=28)
    - Surface-wave two-station dispersion analysis GUI software in Matlab (What's the tomography method?)
- [ASWMS](https://ds.iris.edu/ds/products/aswms): Automated Surface Wave Phase Velocity Measuring System, measuring two-station phase delay and then 2D phase velocity maps at each period using Eikonal and Helmhotza tomography | [code in GitHub](https://github.com/jinwar/matgsdf)
- Two-plane wave with 2D sensitivity kernel ([Yang & Forsythn, 2006, GJI](https://doi.org/10.1111/j.1365-246X.2006.02972.x); [Yang & Forsythn, 2006, JGR](https://doi.org/10.1029/2005JB004180))


#### Ambient noise surface-wave tomography

- Data pre-processing and measuring phase velocity (traveltime difference) between station pair
    - [Research Products from CU-Boulder](http://ciei.colorado.edu/Products)
        - [ancc](http://ciei.colorado.edu/Products/ancc-1.0-1.src.tgz): Ambient noise data processing code and database for processing: available from the CU, in C
        - [AFTAN](http://ciei.colorado.edu/Products/aftan-1.1.tgz): Automatic frequency-time analysis, in C and Fortran
    - [Huajian Yao's Lab](http://yaolab.ustc.edu.cn/resources.php?i=28)
        - Ambient noise cross-correlation codes for daily long SAC format data in Matlab
        - Dispersion Analysis GUI software for ambient noise cross-correlation functions in Matalb
    - [NoisePy](https://github.com/mdenolle/noisepy): Fast and easy computation of ambient noise cross-correlation functions written in Python, with noise monitoring and surface wave dispersion analysis
    - [SeisNoise](https://github.com/tclements/SeisNoise.jl): Fast and easy ambient noise cross-correlation in Julia, with noise monitoring and surface wave dispersion analysis
    - [MATnoise](https://github.com/jbrussell/MATnoise): Calculate ambient noise cross-correlations, measure phase velocities, and invert for phase velocity maps in MATLAB.

- Inverting phase/group velocity maps
    - [tomo_sp_cu_s](http://ciei.colorado.edu/Products/tomo_sp_cu_s-v1.1.tgz): Surface wave tomography based on ray theory | [Research Products from CU-Boulder](http://ciei.colorado.edu/Products)
    - [FMST](http://rses.anu.edu.au/~nick/surftomo.html): traveltime tomography code in 2-D spherical shell coordinates based on fast marching method | [FMST at iEarth](http://www.iearth.org.au/codes/FMST)
    - [rj-TOMO](http://www.iearth.org.au/codes/rj-TOMO): 2-D transdimensional travel time tomography based on Reversible jump Markov chain Monte Carlo algorithm
    - [MATnoise](https://github.com/jbrussell/MATnoise): Calculate ambient noise cross-correlations, measure phase velocities, and invert for phase velocity maps in MATLAB.


#### Other method to measure surface-wave dispersion

- [mat-LRTdisp](https://github.com/jbrussell/mat-LRTdisp): Measuring multi-mode surface wave dispersion using the Linear Radon Transform (LRT) written in Matlab


#### Surface-wave dispersion inversion

- [CPS330](http://www.eas.slu.edu/eqc/eqccps.html): Collection of programs for calculating theorectical seismogram, receiver function, surface wave dispersion curve et al. | [Chinese install introduction](https://blog.seisman.info/cps330-install) and [Chinese introdution](https://blog.seisman.info/cps330)
- [dispinversion](https://github.com/jinwar/dispinversion): Surface wave dispersion inversion code written in Matlab


#### Surface-wave dispersion inversion

- [DSurfTomo](https://github.com/HongjianFang/DSurfTomo): Direct inversion of 3-D Vs structure from dispersion data based on period-dependent ray tracing in Fortran
- [3D Monte Carlo Direct Inversion](https://www.geos.ed.ac.uk/eip/codes.html): 3D Monte Carlo tomography using both body and surface wave data


#### Surface-wave dispersion forward calculation

- [CPS330](http://www.eas.slu.edu/eqc/eqccps.html): Collection of programs for calculating theorectical seismogram, receiver function, surface wave dispersion curve et al. | [Chinese install introduction](https://blog.seisman.info/cps330-install) and [Chinese introdution](https://blog.seisman.info/cps330)
- [Geopsy](http://www.geopsy.org/download.php): An open source software for geophysical research and application written in C++
- [senskernel](http://ciei.colorado.edu/Products/senskernel-1.0.tgz): Calculate sensitivity kernal of group velocity and phase velocity
- [Vphase](http://www.spice-rtn.org/library/software/vphase.html): A training code to calculation of phase velocity dispersion curves


### Rayleigh-wave HV

- `TBA`


### Noise HVSR

- [Geopsy](http://www.geopsy.org/download.php): An open source software for geophysical research and application written in C++
- [IRIS HVSR](https://github.com/iris-edu/HVSR): A set of Python scripts to compute and plot HVSR curves using MUSTANG PDF-PSD web service from IRIS | [IRIS website](https://ds.iris.edu/ds/products/hvsr)
- [H/V Toolbox](https://github.com/krischer/HtoV-Toolbox): A toolbox to calculate surface-wave HVSR
- [HV-Inv](https://w3.ual.es/GruposInv/hv-inv): Inversion of HVSR and SW dispersion
- [OpenHVSR](https://www.samuelbignardi.com/en/openhvsr-project): Measure and Inversion of HVSR written in Matlab
- [HV-TEST](https://zenodo.org/record/260131#.XhMFYxczY1J): A tool for the verification of the reliability and clarity of the H/V peak according to the SESAME criteria
- [HVResPy](https://www.researchgate.net/publication/283085984_HVResPy_an_open-source_Python_tool_for_Geopsy_HVSR_post-processing?channel=doi&linkId=5629ff6308ae518e347ef829&showFulltext=true): An open-source Python tool for Geopsy HVSR post-processing



### Ambient Noise Inversion

- [MSNoise](http://www.msnoise.org): A Python Package for Monitoring seismic velocity changes using ambient seismic noise
- [seismic-noise-tomography](https://github.com/bgoutorbe/seismic-noise-tomography): Python framework for seismic noise tomography


### Receiver Function

#### Synthetic RF

- [hk](http://www.eas.slu.edu/People/LZhu/home.html): Receiver function package (synthetic RF, deconvolution, and H-k stacking) | [Chinese note](https://blog.seisman.info/hk-install)
- [RAYSUM](https://home.cc.umanitoba.ca/~frederik/Software): Ray-theoretical modelling of teleseismic waves in dipping, anisotropic structures
- [CPS330](http://www.eas.slu.edu/eqc/eqccps.html): Collection of programs for calculating theorectical seismogram, receiver function, surface wave dispersion curve et al. | [Chinese install introduction](https://blog.seisman.info/cps330-install) and [Chinese introdution](https://blog.seisman.info/cps330)
- [RF software](https://seiscode.iris.washington.edu/projects/rfsyn): Computes a receiver-function for a stack of anisotropic layers over an isotropic halfspace, via a reflectivity algorithm, assuming a plane wave incident from below | [Manual](https://www.ldeo.columbia.edu/~vadim/RF/RF-manual.html) | [Some updates at JParkCodes](http://jparkcodes.blogspot.com)
- [RFtool](https://members.elsi.jp/~george/rftool.html): An interactive, GUI-based tool to simulate P or S receiver functions
- [PSV Hybrid RF](http://geophysics.geo.sunysb.edu/wen/resource/index.html): Calculating synthetic RF in two-dimensional localized hetergeneous structures based on PSV Hybrid method (GRT-FD).



#### RF Measurements and Inversion

- [hk](http://www.eas.slu.edu/People/LZhu/home.html): Receiver function package (deconvolution and H-k stacking) | [Chinese note](https://blog.seisman.info/hk-install)
- [RF software](https://seiscode.iris.washington.edu/projects/rfsyn): Computes a receiver-function for a stack of anisotropic layers over an isotropic halfspace, via a reflectivity algorithm, assuming a plane wave incident from below | [Manual](https://www.ldeo.columbia.edu/~vadim/RF/RF-manual.html) | [Some updates at JParkCodes](http://jparkcodes.blogspot.com)
- [CCP](http://www.eas.slu.edu/People/LZhu/home.html): Common-Conversion-Point (CCP) stacking of receiver functions | [Chinses note](https://blog.seisman.info/ccp-install)
- [rj-RF](http://www.iearth.org.au/codes/rj-RF): Inversion of Receiver Functions using Reversible jump Markov chain Monte Carlo algorithm
- [IRFFM](http://rses.anu.edu.au/~hrvoje/IRFFMv1.1.html): An interactive Java program for joint interactive forward modelling of teleseismic receiver functions and surface wave dispersion
- [CrazySeismic](http://web.gps.caltech.edu/~yucq/software.html): A MATLAB GUI-based package to process single channel seismic data (picking, McCC, PCA, Deconvolution)
- [FuncLab](https://seiscode.iris.washington.edu/projects/funclab): a Matlab based GUI for handling receiver functions (link does work) | [revised FuncLab](https://seiscode.iris.washington.edu/projects/funclab-revised)
- [processRFmatlab](https://github.com/iwbailey/processRFmatlab): matlab functions and scripts for working with receiver functions
- [rf](https://github.com/trichter/rf): Receiver function calculation in seismology, written in Python
- [SplitRFLab](https://github.com/xumi1993/SplitRFLab): A Matlab toolbox of processing receiver functions and shear wave spliting modified from [Splitlab](http://splitting.gm.univ-montp2.fr) and [processRFmatlab](https://github.com/iwbailey/processRFmatlab)
- [Some group codes for RF analysis](https://github.com/rmartinshort/RecieverFunctions): Ammon's & Cheng's codes



### Joint Inversion of Seismological Data

- [LitMod_seis](https://www.juanafonso.com/software): A joint inversion code for inverting Vs and anisotropy data (Rayleigh and Love phase and/or group velocities, ellipticity (Z/H ratio) and receiver functions) with a Markov Chain Monte Carlo method. (Released soon)
- [Huajiang Yao's Lab](http://yaolab.ustc.edu.cn/resources.php?i=28): Inversion of Vs, Vp/Vs, and interface depth using (multimode, Rayleigh and/or Love, phase and/or) dispersion data and Rayleigh wave fundamental mode ZH data (ellipticity) based on the Neighborhood Algorithm in Fortran



### Multi-observable Modelling of Geophysical Data

- [LitMod](https://www.juanafonso.com/software): Multi-observable modelling of geophysical data
    - [LitMod_2D](https://www.juanafonso.com/software): An interactive software to perform multi-observable modelling of geophysical data for 2D whole lithospheric structure of the Earth and/or other terrestrial planets
    - [LitMod_T](https://www.juanafonso.com/software): the "transient" equivalent of LitMod_2D
    - [LitMod_3D](https://www.juanafonso.com/software): A 3D version LitMod | [Github code](https://github.com/javfurchu/litmod)
    - [LitMod_4INV](https://www.juanafonso.com/software): A fully nonlinear probabilistic inversion code(s) in spherical coordinates for the compositional and thermal structure of the lithosphere and upper mantle, simultaneously inverting gravity gradients, gravity anomalies, geoid height, surface heat flow, magnetotelluric data, receiver functions, surface-wave data, absolute elevation (including both static and dynamic effects) and body-wave data, together with petrological information.



### Full Waveform Inversion

- [TOY2DAC](https://seiscope2.osug.fr/TOY2DAC,82?lang=fr): 2D Acoustic frequency-domain Full Waveform modeling and inversion code
- [ASKI](http://www.gmg.ruhr-uni-bochum.de/geophysik/seismology/aski.html): Modularized program suite for sensitivity analysis and iterative full waveform inversion
- [FWI.jl](https://github.com/JuliaInv/FWI.jl): 2D/3D acoustic FWI in Julia
- [IFOS2D](https://git.scc.kit.edu/GPIAG-Software/IFOS2D): 2D elastic full waveform inversion
- [IFOS3D](https://git.scc.kit.edu/GPIAG-Software/IFOS3D): 3D elastic full waveform inversion
- [DENISE-SH](https://github.com/daniel-koehn/DENISE-SH): 2D SH-wave full waveform modeling and inversion
- [DENISE](https://github.com/daniel-koehn/DENISE-Black-Edition): 2D PSV-wave full waveform modeling and inversion
- [GERMAINE](https://github.com/daniel-koehn/GERMAINE): 2D Acoustic frequency-domain Full Waveform modeling and inversion code.
- [SAVA](https://github.com/daniel-koehn/SAVA): 3D seismic modelling, FWI and RTM code for wave propagation in isotropic (visco)-acoustic/elastic and anisotropic orthorhombic/triclinic elastic media
- [SES3D](https://cos.ethz.ch/software/production/ses3d.html): Simulation of elastic wave propagation and waveform inversion in a spherical section
- [LASIF](http://www.lasif.net): Framework for large scale full waveform inversion
- [seisDD](https://github.com/yanhuay/seisDD): Double-difference adjoint seismic tomography
- [Salvus](https://salvus.io): Full waveform modelling and inversion


### Other Imaging Methods

#### Shear Wave Splitting

- [SplitLab](http://splitting.gm.univ-montp2.fr): Shear-wave birefringence analysis code, written in Matlab | [An updated version](https://robporritt.wordpress.com/software)
- [MFAST](http://mfast-package.geo.vuw.ac.nz): Multiple Filter Automatic Splitting Technique written in Fortran
- [multisplit](https://github.com/ftilmann/multisplit): Shear-wave birefringence analysis code
- [SHEBA](https://github.com/jwookey/sheba): Shear-wave birefringence analysis code
- [SplitRacer](http://www.geophysik.uni-frankfurt.de/64002762/Software): Shear-wave splitting analysis written in Matlab


#### Imaging of Earth interior

- [PKPprecursor](http://geophysics.geo.sunysb.edu/wen/resource/index.html): Locating seismic scatterers in the lower mantle, using PKP precursor onsets


----------------------
## Seismic Data Analysis

### Phase Picking

- [Adaptive Stacking](http://rses.anu.edu.au/seismology/soft/astack/index.html): Adaptive stacking to estimating traveltime residual patterns across a network of seismic stations | [Adaptive stacking at iEarth](http://www.iearth.edu.au/codes/AdaptiveStacking)
- [AIMBAT](https://seiscode.iris.washington.edu/projects/pysmo-aimbat): A Python/Matplotlib Tool for Measuring Teleseismic Arrival Times
- [CrazySeismic](http://web.gps.caltech.edu/~yucq/software.html): A MATLAB GUI-based package to process single channel seismic data (picking, McCC, PCA, Deconvolution)
- [CrazyTremor](http://web.gps.caltech.edu/~yucq/software.html): A MATLAB GUI-based package to display and picking multi-channel seismic data
- [mccc](https://github.com/xumi1993/mccc): Determines optimum relative delay times for seismograms by multi-channel cross-correlation
- [PhasePApy](https://github.com/austinholland/PhasePApy): Seismic Phase Picker and Associator, written in Python
- [P-Phase Picker](https://www.usgs.gov/software/p-phase-picker): Detecting P-phase onset written in Java and Matlab


### Single Station Signal Analysis

- [MUSTANG](http://service.iris.edu/mustang): A quality assurance system at the IRIS DMC that provides metrics pertaining to seismic data quality | [Tutorial](https://ds.iris.edu/ds/nodes/dmc/tutorials/getting-started-with-mustang)
- [IRIS DMC Noise Toolkit Products](http://ds.iris.edu/ds/products/noise-toolkit)
    - [Noise Toolkit](https://seiscode.iris.washington.edu/projects/iris-dmc-noise-toolkit)
        - [PDF-PSD](https://seiscode.iris.washington.edu/projects/noise-toolkit-pdf-psd-bundle): Computing Power Spectral Densities (PSD) of waveform data
        - [microseism energy](https://seiscode.iris.washington.edu/projects/noise-toolkit-microseism-energy-me-bundle): Performing microseism energy computations from PSDs
        - [Polarization attributes](https://seiscode.iris.washington.edu/projects/noise-toolkit-polarization-attributes-bundle): Performing frequency dependent polarization analysis of seismograms
- [PQLX](https://www.usgs.gov/software/pqlx-a-software-tool-evaluate-seismic-station-performance): An open-source software system for evaluating seismic station performance and data quality
- [Station Analysis Tools](https://robporritt.wordpress.com/software): A set of c routines for computation of power spectral densities, coherence, probability density functions, and a handful of other tools for monitoring the health of a station | [iris code site](https://seiscode.iris.washington.edu/projects/station-analysis-tools)
- [Est_noise](https://www.usgs.gov/software/estnoise): Analyze time-series data to quantify temporal correlations and simultaneously estimate rates, offsets, and other functional dependencies.
- Time-frequency analysis
    - [TF-SIGNAL](http://www.nuquake.eu/Computer_Codes/tfsig.htm): Computation and visualization of time-frequency representations of time signals using one or more of seven alternative methods of time-frequency analysis
- [BCseis](http://www.ceri.memphis.edu/people/clangstn/software.html): a MatLab GUI and set of inline functions for performing various non-linear thresholding operations using the Continuous Wavelet Transform


### Array Seismology

- [ObsPy](https://github.com/obspy/obspy): Data download, processing and visulization software written in Python
- [Geopsy](http://www.geopsy.org/download.php): An open source software for geophysical research and application written in C++


### Seismic data digitization

- [DigitSeis](http://www.seismology.harvard.edu/research/DigitSeis.html): A Digitization Software for Analog Seismograms, written in Matlab


### Seismic data problem detection and correction

- [CWPAR](https://seiscode.iris.washington.edu/projects/cwpar-clipped-waveform-pickup-and-restoration): Clipped Waveform Pickup and Restoration
- [ATacR](https://github.com/helenjanisz/ATaCR): Automated Tilt and Compliance Removal (for ocean bottoms seismometers)
- [DLOPy](https://github.com/jbrussell/DLOPy_v1.0): Calculate OBS horizontal orientations based on Raleigh-wave arrival angle


### Cross-correlation

- [SEC_C](https://github.com/Naderss/SEC_C): Super-Efficient Cross-Correlation


---------------------
## Geosciences

### Tectonics

- [GPlates](https://www.earthbyte.org/category/gplates): A desktop software for the interactive visualisation of plate-tectonics


### Geodecy

- [Moho inversion](https://github.com/pinga-lab/paper-moho-inversion-tesseroids): Fast non-linear gravity inversion in spherical coordinates with application to the South American Moho.
- [Gravity modelling and inversion in 2D](https://www.juanafonso.com/software): A very simple matlab code to illustrate the basics of gravity modelling and inversion
- [SDM](https://www.gfz-potsdam.de/en/section/physics-of-earthquakes-and-volcanoes/infrastructure/tool-development-lab/): Geodetic finite-fault slip inversion based on co-seismic surface deformation data (GPS, InSAR, etc.)


### Geophysics

- [distaz](http://www.seis.sc.edu/software/distaz): Classic codes to calculate distance, azimuth and back-azimuth of any two points at the Earth's surface | [Chinese note](https://blog.seisman.info/calculate-dist-az-baz)
- [AFAT](http://cpc.cs.qub.ac.uk/summaries/AFAT_v1_0.html): Solving the Christoffel equation: phase and group velocities



---------------
## Software Library

### Mathmatical Library

- [SHTOOLS](https://github.com/SHTOOLS/SHTOOLS): Spherical Harmonic Tools
- [Shansyn](http://www.spice-rtn.org/library/software/shansyn): Spherical Harmonic ANalysis and SYNthesis
- [SEISCOPE TOOLBOX](https://seiscope2.osug.fr/SEISCOPE-OPTIMIZATION-TOOLBOX?lang=fr): Seiscope optimization toolbox
- [Parameter Estimation and Inverse Problems Example Code and Associated Subroutines](https://seiscode.iris.washington.edu/projects/peipcode): a compilation of inverse and parameter estimation code that accompanies the second edition of the textbook "Parameter Estimation and Inverse Problems"
- [The Computational Geometry Algorithms Library](https://www.cgal.org/index.html)
- [Delayed Rejection Adaptive Metropolis (DRAM) in Fortran](https://www.juanafonso.com/software): A simple teaching code in Fortran of the DRAM method
- [rj-MCMC](http://www.iearth.org.au/codes/rj-MCMC): A library providing routines for running Reversible Jump Monte-Carlo Markov chains for 1-D and 2-D spatial regression problems
- [Malcolm Sambridge's softwares](http://rses.anu.edu.au/~malcolm/_pages/Research)
    - [Neighbourhood Algorithm](http://rses.anu.edu.au/~malcolm/na/na.html) | [Neighbourhood Algorithm at iEarth](http://www.iearth.org.au/codes/NA)
    - [Natural Neighbours](http://rses.anu.edu.au/geodynamics/nn/nn.html)


### Seismic Library

- [William Menke's codes](https://www.ldeo.columbia.edu/users/menke/software.html)
- [libmseed](https://github.com/iris-edu/libmseed): A miniSEED library that provides a framework for manipulation of SEED data records


### Matlab Library

- [CREWES Matlab Toolbox](https://www.crewes.org/ResearchLinks/FreeSoftware)



### Other Library

- [Free Intel® Software Development Tools](https://software.intel.com/en-us/qualify-for-free-software) | [Chinese introduction](https://blog.seisman.info/intel-non-commercial-software) and [How to uninstall](https://blog.seisman.info/uninstall-intel-parallel-studio-completely)
    - [Educator](https://software.intel.com/en-us/qualify-for-free-software/educator) | [Open Source Contributor](https://software.intel.com/en-us/qualify-for-free-software/opensourcecontributor) | [Student](https://software.intel.com/en-us/qualify-for-free-software/student)


----------------------
## Software Centers

- [IRIS SeisCode](https://seiscode.iris.washington.edu)
- [CIG Software](https://geodynamics.org/cig/software)
- [USGS Software](https://www.usgs.gov/natural-hazards/earthquake-hazards/software) | [Old website](https://earthquake.usgs.gov/research/software)
- [SPICE Software](http://www.spice-rtn.org/library/software/softwarefolder_view.html)
- [QUEST Software](http://www.quest-itn.org/library/software)
- [NuQuake Software](http://www.nuquake.eu/Computer_Codes)
- [iEarth](http://www.iearth.edu.au)
- [Seismology & Mathematical Geophysics Research Group Software](http://rses.anu.edu.au/seismology/index.php?p=software) (In the Australian National University)
- [USC Software](http://www.seis.sc.edu/software.html)
- [ETH Seismology and Geodynamics](https://seg.ethz.ch/software.html)
- [GPIAG-Software](https://git.scc.kit.edu/GPIAG-Software)
- [GFZ software](https://www.gfz-potsdam.de/en/section/physics-of-earthquakes-and-volcanoes/data-products-services/downloads-software)
- [EarthByte software](https://www.earthbyte.org/category/resources/software-workflows)



## Revision history

- 2019-12-25: update some links，commit to  SeisMan
- 2019-11-07: initial draft, reference to [SeisMan's links](https://link.seisman.info)

