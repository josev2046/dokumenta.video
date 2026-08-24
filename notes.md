
# Presentation Outline: Case Studies for Digital Humanities Research

## Slide 1: Title Slide

## Slide 2: Theme 1 - The Evolving Information Ecosystem

**Title:** Problematic Interventions and the New Archival Paradigm
**Bullet Points:**

* The archivist's role is evolving from passive guardianship to active contextualisation.


* Digital interventions can distort historical truth, altering collective memory.


* Example: The digital alteration of Khmer Rouge victim portraits (adding smiles) highlights the ethical dangers of manipulating historical records.


* Archivists must critically assess digital ephemerality and the authenticity of visual heritage.



**Speaker Notes:**

* Refer to the Vice article regarding the Khmer Rouge photographs to illustrate how digital restoration can cross the line into historical manipulation.


* Discuss the "Restoring Mona Lisa" concept—adding contemporary overlays (like a Netflix logo) changes the intrinsic meaning of the artifact.



## Slide 3: Theme 2 - Fundamentals of Digitisation

**Title:** Why Digitise? The Preservation Imperative
**Bullet Points:**

* **Deterioration:** Analogue carriers undergo inevitable physical degradation.


* **Obsolescence:** The hardware and skills required to play legacy media are rapidly disappearing.


* **Access:** There is a growing demand for rapid, simultaneous digital access to archives.


* **Digitisation vs. Preservation:** Digitisation is a single event; preservation is a continuous process of maintaining accessibility.



**Speaker Notes:**

* Digitisation is not a final solution, but merely one step in a continuous audiovisual preservation workflow.


* We digitise to transform vulnerable physical media (like VHS, Betacam, U-matic) into sustainable, file-based formats.



## Slide 4: Theme 2 - Storage Infrastructure for the Archive

**Title:** Scaling Archival Storage
**Bullet Points:**

* **Magnetic Tape (LTO):** Highly cost-effective for deep, offline storage (up to 12TB uncompressed per LTO-8 cartridge).


* **Disk Storage & RAID:** Provides fast, random access for "online" or "nearline" work-in-progress, but comes with practical scalability limitations.


* **Object Storage:** Scales geographically by storing unstructured data as objects rather than hierarchical files, using erasure coding for redundancy.


* **Cloud Architecture:** Shifts infrastructure from capital expenditure to operational expenditure (Public, Private, or Hybrid).



**Speaker Notes:**

* Tape (LTO) consumes no power when offline and natively supports Write Once Read Many (WORM) to prevent data loss.


* "The cloud is just someone else's computer." Be aware of egress costs when retrieving large archival datasets from public cloud providers.



## Slide 5: Theme 3 - Workflows and Standards

**Title:** The OAIS Reference Model
**Bullet Points:**

* Open Archival Information System (OAIS) provides the structural framework for digital repositories.


* **Ingest:** Packaging Submission Information Packages (SIP).


* **Archival Storage:** Managing Archival Information Packages (AIP).


* **Access:** Delivering Dissemination Information Packages (DIP) to end-users.



**Speaker Notes:**

* OAIS ensures digital assets remain accessible and usable for as long as necessary.


* It clearly separates the technology used to store data from the logical processes required to preserve it.



## Slide 6: Theme 3 - Codecs, Wrappers, and Open Standards

**Title:** Selecting the Right File Formats
**Bullet Points:**

* **Digitisation Master:** The raw output from the analogue-to-digital converter.


* **Archive Master:** The stored file, kept as close to the analogue original as possible.


* **Mezzanine & Browse:** Lighter copies utilised for production and online access.


* **Open Standards:** FFV1 (codec) and Matroska (container) offer a robust, lossless, and open-source solution for film and video preservation.



**Speaker Notes:**

* Avoid cascading compression/decompression cycles which degrade quality.


* FFV1 and Matroska are emerging standards championed by the PREFORMA project and the IETF, specifically designed by archivists for archivists.



## Slide 7: Theme 3 - Metadata Architecture

**Title:** Structuring Data About Data
**Bullet Points:**

* **Descriptive:** Aids discovery (Title, Author).


* **Structural:** Defines how an object is assembled.


* **Administrative/Technical:** Governs preservation and rights (e.g., PREMIS standard).


* **Storage Methods:** Metadata can be embedded within the file, stored in a sidecar file (XML/XMP), or hosted in an external database.



**Speaker Notes:**

* Good metadata must be Findable, Accessible, Interoperable, and Reusable (FAIR).


* Tools like Exiftool allow archivists to automatically extract or embed technical metadata directly into digital objects.



## Slide 8: Theme 4 - Applied AI and Cognitive Computing

**Title:** Overcoming the Archival Bottleneck with AI
**Bullet Points:**

* Manual cataloguing cannot keep pace with the increasing volumes of archive content.


* **Natural Language Processing (NLP):** Extracts concepts, entities, and sentiment from text.


* **Computer Vision:** Enables deep object detection, scene segmentation, and quality control.


* **Speech Recognition:** Automates transcription, audio segmentation, and speaker diarisation.



**Speaker Notes:**

* Only a small percentage of traditional archives are enriched with detailed metadata due to time and resource constraints.


* AI automation shifts the archivist's focus from data entry to metadata quality control.



## Slide 9: Theme 4 - Algorithmic Ethics and Limitations

**Title:** Is AI a Silver Bullet?
**Bullet Points:**

* Machine learning models are only as reliable as their training data.


* Algorithms struggle with visual ambiguity and context (e.g., distinguishing a Chihuahua from a muffin, or a sheepdog from a mop).


* Archivists must audit AI for systemic biases and false positives.



**Speaker Notes:**

* AI is highly efficient but lacks human nuance. The visual examples of animals vs. food highlight how computer vision can easily misinterpret scenes without human oversight.



## Slide 10: Theme 5 - Real-World Case Studies

**Title:** BFI National Archive Infrastructure
**Bullet Points:**

* **High-Volume Scanning:** Utilising DFT Scanity for high-fidelity (2K) continuous motion film scanning.


* **Instant Access Storage:** 700TB Isilon spinning disk clusters for work-in-progress and web-browser playback.


* **Deep Archive:** Geographically separated Spectra Logic tape libraries (LTO-6 and IBM TS1150) for resilient preservation.


* **Media Asset Management:** Imagen MAM used to integrate workflows, transcode files, and serve viewing copies.



**Speaker Notes:**

* The BFI case study demonstrates a successful end-to-end infrastructure, seamlessly linking physical film scanning to deep tape storage via a REST API.



## Slide 11: Theme 5 - Real-World Case Studies

**Title:** Watson Media Enrichment at the BBC
**Bullet Points:**

* **The Challenge:** Harvesting a massive broadcast archive where finding specific content manually takes hours.


* **The Solution:** Deploying IBM Watson’s Tone Analyzer and Natural Language Understanding APIs.


* **The Outcome:** Automated curation of playlists, extraction of underlying concepts, and new faceted navigation for researchers.



**Speaker Notes:**

* The BBC's "Blue Room" innovation hub utilised AI to generate deeply enriched, second-to-second metadata, re-awakening long-form legacy content for immediate re-use.



## Slide 12: Conclusion

**Title:** Conclusion & Professional Networks
**Bullet Points:**

* AV digitisation is highly complex; there is no "one-size-fits-all" solution.


* Solutions must be tailored to an organisation's specific mission, resources, and ethical guidelines.


* **Collaborate and share knowledge via:**
* FIAT/IFTA (Television Archives)


* IASA (Sound and Audiovisual Archives)


* CCAAA (Coordinating Council of Audiovisual Archives Associations)





**Speaker Notes:**

* Always seek advice and collaborate. Engaging with international networks ensures adherence to global best practices in preserving our collective memory.
