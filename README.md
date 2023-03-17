# LibriTTS-British

This is a subset of the [LibriTTS dataset](https://openslr.org/60/) that includes British speakers.

Speakers are sorted into `libritts-english`, `libritts-irish`, `libritts-scottish`, and `libritts-welsh` subsets.

Speakers were found using two resources, the [LibriVox Accents Table](https://wiki.librivox.org/index.php/Accents_Table) and [Ruth Golding's Blog](https://golding.wordpress.com/home/other-british-readers-on-librivox), which both compile a list of British LibriVox audiobook speakers.

Please be aware that this dataset is *likely not complete*, and *I make no promises of the regional accuracy*.

Files are in a `.tar.gz` archive, split into 1GB chunks. This is because GitHub's LFS service imposes size limits, preventing the dataset being uploaded in a single file.

## Download Mirrors

[Kaggle dataset](https://www.kaggle.com/datasets/oscarvl/libritts-british-accents)

[Kaggle direct download](https://www.kaggle.com/datasets/oscarvl/libritts-british-accents/download?datasetVersionNumber=1)

### GitHub LFS
Note: GitHub LFS requires the purchase of "data packs", so I'd advise against using it.

1. Install [git lfs](https://git-lfs.github.com/) if you do not have this installed.
2. Run `git lfs install` to set up lfs for your user account.
3. `git clone https://github.com/OscarVanL/LibriTTS-British-Accents`

## License

The [original LibriTTS dataset](https://openslr.org/60/) was published under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licensing. This gives me permission to share and adapt this dataset as long as I give attribution. You can do the same with this dataset.

This dataset is licensed with [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
