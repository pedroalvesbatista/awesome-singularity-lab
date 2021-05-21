# awesome-singularity-lab
Singularity container runtime use cases and applications.

## ECP (Exascale Computing Project) Apps

Quoting the Executive Summary from [Science Prospects and Benefits
with Exascale Computing, December 2007](https://www.webcitation.org/67OhjP9os?url=http://www.nccs.gov/wp-content/media/nccs_reports/Science%20Case%20_012808%20v3__final.pdf) :

> Scientific computation has come into its own as a mature technology in all fields of science.
Never before have we been able to accurately anticipate, analyze, and plan for complex events that
have not yet occurred—from the operation of a reactor running at 100 million degrees centigrade to
the changing climate a century down the road. Combined with the more traditional approaches of
theory and experiment, scientific computation provides a profound tool for insight and solution as we
look at complex systems containing billions of components. Nevertheless, it cannot yet do all we
would like. Much of scientific computation’s potential remains untapped—in areas such as materials
science, Earth science, energy assurance, fundamental science, biology and medicine, engineering
design, and national security—because the scientific challenges are far too enormous and complex for
the computational resources at hand. Many of these challenges are of immediate global importance.
These challenges can be overcome by a revolution in computing that promises real advancement
at a greatly accelerated pace. Planned petascale systems (capable of a petaflop, or 1015 floating point
operations per second) in the next 3 years and exascale systems (capable of an exaflop, or 1018
floating point operations per second) in the next decade will provide an unprecedented opportunity to
attack these global challenges through modeling and simulation. Exascale computers, with a
processing capability similar to that of the human brain, will enable the unraveling of longstanding
scientific mysteries and present new opportunities.

The Exascale Computing Project aims to fullfil the future demands concerning exaflops computing capacity, setting coordinated strategies regarding hardware and software, providing advanced research & development capacities to retake America's innovation in HPC field.


In this lab repository, Singularity and Warewulf, both from the [HPCng](https://www.hpcng.org) project, will be used to demonstrate Exascale Apps from ECP and prepare the ground to reach out this and putting a way down to modern hyperscale pipelines and workflow for variated kind of analytics workloads.

## ECP Apps

[Exascale Proxy Applications](https://proxyapps.exascaleproject.org/)

[CoPA Cabana - The Exascale Co-Design Center for Particle Applications Toolkit](https://github.com/ECP-copa/Cabana/)

[Project Cinema/E4S](http://pantheonscience.org/e4s/)


## Research Materials

A good starting point to understand how ECP ecosystem works is the [SPACK: THE DEPLOYMENT TOOL FOR ECP’S SOFTWARE STACK](https://www.exascaleproject.org/spack-the-deployment-tool-for-ecps-software-stack/) where [Todd Gamblin](https://github.com/tgamblin) talks about it in great details.

For understanding the [Extreme-Scale Scientific Software Stack](https://oaciss.uoregon.edu/ecp/), this is a good guide, along with [E4S: Extreme-Scale Scientific Software Stack](https://ecpannualmeeting.com/poster-interface23894732314e23hreu823rd/pdfs/E4S_Poster_2020.pdf).

The xSDK: Extreme-scale Scientific Software Development Kit plays a essential role in ECP Software Stack too, and you can check the [Ecosystem State-of-the-Art](http://xsdk.info/xsdk-home-page/ecosystem-elements/), as :

> The vision of the xSDK is to provide infrastructure for and interoperability of a collection of related and complementary software elements—developed by diverse, independent teams throughout the high-performance computing (HPC) community—that provide the building blocks, tools, models, processes, and related artifacts for rapid and efficient development of high-quality applications.
