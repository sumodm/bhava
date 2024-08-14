
# Bhava: tool & library for analysing, synthesis & visualizing of Indian Music

Bhava is an open source library designed to process Indian Music, especially those with prominent melodic elements. The intricate mathematical structures found in Indian music offer an interesting opportunity for software exploration. We want build a software tool and a library that accomplish the following:
- To analyze music by identifying elements such as notes/swaras, ragas, rhythms and more.
- To synthesize Indian music from musical notations.
- To offer visualizations of music data, specifically Indian music, to enhance human detection of patterns and understanding.
- To achieve these goals, have first class objects for Indian musical representations, such as swaras, ragas and prescriptive and descriptive notation systems.

## Music Analysis
Open source tools like Audacity and Sonic Visualizer offer capabilities for processing audio data, including viewing spectrograms and Melographs. However, these tools are generally limited to low-level audio processing. Libraries such as librosa, aubio, praat, and essentia provide medium-level music processing, handling tasks like pitch extraction, onset detection etc. However, they fall short when addressing higher-level questions such as "Which parts of these two pieces of music are melodically similar?" or "Which songs adhere to a specific rhythm?" While some of these questions remain open research problems, there is ongoing work by various groups such as Hema Murthy's (IIT Madras), Preethi Rao's group (IIT Bombay), and Xavier Serra's group (UPF). We believe that a library tailored to Indian music, incorporating specific structures such as swaras, ragas, and talas, could significantly accelerate research progress in this area.

## Music Synthesis
In Computer Vision, it is easy to annotate on top of images to debug and test the accuracy of systems. But with audio, the ability to annotate is limited. Therefore in music, music analysis and music synthesis, goes more hand in hand. To this end, we are building the tool with the capability to synthesize Indian Music as well. There have been few attempts at synthesizing Indian Music from notation. One of the first was by M. Subramanian using the tool named Gaayaka. This synthesizes from prescriptive notation but raga is limited to few raga's whose descriptive notation have been hard coded by the author. Another attempt was by Srihari Sriraman with the library, Ragavardhini, a clojure based library for music synthesis. Different from these two attempts, which were more general purpose but limited in aesthetic quality, Srikumar K. Subramanian, in his Ph.D thesis attempted to synthesize with high fidelity using Veena, one keerthana in the raga Sahana.

## Visualize Music
An essential feature of such a tool should be the ability to visualize auditory patterns in a graphical format. This capability helps humans to detect patterns more effectively, similar to how spectrograms are widely used. When algorithm designers work with audio or video, they often need to make minor adjustments to the audio to verify the stability of the detected patterns. A visual representation is crucial for this purpose, as it enables users to make precise modifications to the audio and observe their impact on the detected patterns. Additionally, these tools could significantly enhance the sharing and learning of auditory patterns through visual representations, making Indian Classical Music more accessible and understandable to those who have not yet developed a keen auditory sense for these patterns.

## References
1. [Indian Art Music, Preethi Rao, Hema A. Murthy and S.R.M Prasanna](https://play.google.com/store/books/details/Indian_Art_Music_A_Computational_Perspective?id=g-2rEAAAQBAJ&hl=en_US&gl=US)
2. [Xavier Serra et al](https://www.upf.edu/web/mtg/publications-ppc)
3. [Gayaka, M. Subramanian](https://carnatic2000.tripod.com/gaayaka.htm)
4. [PASR, Srikumar Subramanian et al](https://sriku.org/thesis/)
5. [Ragavardhini, Srihari Sriraman](https://github.com/ssrihari/ragavardhini)
6. [Ragawise, Sankalp Gulati et al](https://github.com/sankalpg/Ragawise)
7. [Essentia, Xavier Serra et al](https://github.com/MTG/essentia)
8. [librosa, Brian McFee et al](https://github.com/librosa/)
9. [aubio, Paul Brossier et al](https://github.com/aubio/aubio)
10. [praat, Paul Boersma et al](https://github.com/praat/praat)
