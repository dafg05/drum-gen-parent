# drum-gen-parent

An entry point to the various repos that constitute my drum generation project. This project builds upon the [TransformerGrooveTap2Drum](https://github.com/marinaniet0/TransformerGrooveTap2Drum) project by incorporating a data augmentation technique that uses "seed examples" to instill a variety of afrocuban rhythms and patterns into the dataset.

## Sub-repos

* [drum-gen-learning](https://github.com/dafg05/drum-gen-learning): The main repo that houses model architecture (which is based off of the TransformerGrooveTap2Drum model), train/test loops, and evaluation procedures.
* [midiUtils](https://github.com/dafg05/midiUtils): Miscellanous midi utilities, including but not limited to 2-bar midi transformation for data augmentation, synthesis, trimming, and merging.
* [drum-gen-preprocessing](https://github.com/dafg05/drum-gen-preprocessing): Script to preprocess and augment the [groove midi dataset](https://magenta.tensorflow.org/datasets/groove).
* [hvo_sequence](https://github.com/dafg05/hvo_sequence): Main representation of data for groove transformer model. A fork of [this repo](https://github.com/behzadhaki/hvo_sequence), but contains some extra packaging setup.
* [hvo-processing](https://github.com/dafg05/hvo-processing): Contains various conversion functions between midi, hvo_seq, and [note_seq](https://github.com/magenta/note-seq/tree/main) objects. 
