# Why Zilp-Zalp?

 Contact tracing should not be a business model. Contact tracing
software with personal data should be designed for the **common good** and operated **without commercial interests**. It should also be strictly assessed in advance whether such contact tracing is necessary at all or whether completely anonymous solutions are preferable.

Zilp-Zalp is an **open source**, **free-to-use** software system for **digital-analog** contact tracing. It was designed according to **Privacy By Design** principles and systematically minimizes privacy & security risks for users of the system. The software also protects operators of localities and technically prevents the data collected for pure contact tracking from being used elsewhere. 

Zilp-Zalp can very easily be operated in a **decentralized** manner, data can be stored **fail-safe** and **redundantly** in a **federated infrastructure**. Zilp-Zalp is also the only contact tracking system to implement **strong cryptographic earmarking of** data.
With Zilp-Zalp, it is not possible to decrypt the data without a reason; the control over the data lies solely with the persons concerned^1.
In addition, Zilp-Zalp systematically minimizes opportunities to collect and analyze meta-data, which also poses a significant privacy risk in contact tracking systems in addition to the actual data collected. We believe that Zilp-Zalp is the **most privacy-friendly contact tracking software system** available. It also meets all legal requirements for contact tracking and should therefore be preferred over commercially operated systems.

## Further information

Have a look at [our documentation]({% if lang == 'en'%}/en/docs{% else %}/doku{%endif%}) and our [Github page](https://github.com/zilp-zalp) to learn more about using Zilp-Zalp. Or just [contact us](mailto:kontakt@zilpzalp.eu) !

[^1] : Zilp-Zalp can optionally implement an ombuds process that puts control over data in the hands of three (or more) independent controllers for exceptional cases. This allows data to be decrypted in specific cases (e.g. if a user loses a key). The ombuds process can be disabled.
