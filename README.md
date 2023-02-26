<h2 align="center">
    Master's degree thesis
    <br/>
    Domain-Oriented Microservices Gateway Monitoring Using Big Data Techniques
</h2>

---

This Repository contains the master's thesis of Cristian Abrante, to obtain the Master's Degree in ICT Innovation with a Major in Data Science, awarded by Aalto University and Technical University of Madrid.

---

## Abstract

Over the last decade, many companies and organizations have adopted microservices as the software architecture pattern to organize their software system. When the number of those microservices increases dramatically, there are some problems associated with tracing errors and managing common responsibilities. In that sense, many companies adopted a Domain-Oriented Microservices architecture pattern, where the microservices of a different business domain are separated and can be accessed only through a single gateway.The errors that are handled at the gateway level are interesting for other teams depending on it, but maybe they do not have direct visibility on them. This thesis has two outcomes; on the one hand, it introduces an extensible format for defining the high-level responsibilities that the gateway has to handle and the associated errors with those. On the other hand, it also describes the data pipeline introduced for gathering those errors at the gateway level and storing them efficiently to be visualized conveniently afterward.This tool is tested in the context of a multinational company on a gateway that handles thousands of requests per second. Apart from that, a comparison has been established with the most common open-source gateway technologies, showing that they do not provide by default enough cross-team visibility on the events that we are trying to gather.

## Structure

The structure of this repository is the following:

- `src/`: contains the LaTex source code for the following documents:
  - `internship-report/`: Internship report document, recognized by EIT Digital.
  - `presentation/`: Master's thesis presentation slide deck.
  - `proposal/`: Master's thesis proposal document.
  - `thesis/`: Master's thesis document both in Aalto and UPM template format.
- `compiled/`: Contains the compiled documents in PDF format.

## Links

Relevant links:

- [Aalto Repository](https://aaltodoc.aalto.fi/handle/123456789/113714): Link of the thesis in the Aalto University Learning Center Repository.
- [Technical University of Madrid](https://oa.upm.es/70461/): Link of the thesis in the Technical University of Madrid Digital Archive.

## Authors

- **Cristian Manuel Abrante Dorta** ([CristianAbrante](https://github.com/CristianAbrante)) - cristian@abrante.me - **Autor**
- **Hong-Linh Truong** ([linhsolar](https://github.com/linhsolar)) - linh.truong@aalto.fi - **Supervising professor**
- **Teemu Sidoroff** ([tsido](https://github.com/tsido)) - teemu.sidoroff@unity3d.com - **Thesis advisor**
