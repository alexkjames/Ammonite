# Ammonite

Python package designed for conducting non-linear time series analysis of paleoclimate data. Recommended for usage in tandem with [Pyleoclim](https://github.com/LinkedEarth/Pyleoclim_util). Developed by [Alexander James](https://alexkjames.github.io/) withe [University of Southern California Climate Dynamics Lab Group](https://climdyn.usc.edu/). Currently under heavy construction.

Much of Ammonite's capability is enabled by [PyRQA](https://pypi.org/project/PyRQA/), a tool designed to conduct recurrence analysis in a massively parallel manner. Many of our functions are essentially wrappers around PyRQA functions, so we recommend checking that package out as well if you're curious about the bones of how recurrence analysis is done in Ammonite.

Things to note:

* Current releases of Ammonite are highly experimental. These are mainly done to facilitate our research, though others are welcome to use the functionality. Just be aware that the package is currently subject to constant change and will remain unstable for some time.

* Certain functionalities such as RecurrenceNetwork and the synthetic_series utilities are currently non-functional and are acting as placeholders for features that will be included in the future.

* This function has only been tested on macOS/Unix based operating systems, so if you encounter errors they may be system specific.

* Raising issues/feature requests is appreciated but there is no guarantee they'll be addressed hastily at this stage of the package's development as we are focused on building core features that are of use to our lab.