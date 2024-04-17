## 🤐MUTE: A First Open Source Bengali Hateful Memes Dataset


📢 **Paper ALERT**

**MUTE: A Multimodal Dataset for Detecting Hateful Memes** (AACL-SRW 2022)    <br>
[Eftekhar Hossain*](https://eftekhar-hossain.github.io/), [Omar Sharif*](https://omar-sharif03.github.io/), [Mohammed Moshiul Hoque](https://scholar.google.com/citations?user=srYxYhcAAAAJ&hl=en)

👉 [[Paper](https://aclanthology.org/2022.aacl-srw.5/)] [[Dataset](https://drive.google.com/file/d/1ozTFUM7q27g7uckhPWUiQFwhROCiEUAc/view?usp=sharing)]


### Download the MUTE Dataset
   
```python
import gdown
# Replace 'YOUR_FILE_ID' with the actual file ID from the Google Drive link.
gdown.download("https://drive.google.com/uc?export=download&id=1ozTFUM7q27g7uckhPWUiQFwhROCiEUAc", "file.zip", quiet=False)
```
After running the cell, the dataset will be downloaded as **file.zip**

### Unzip the file.zip

```python
import zipfile
zip_ref = zipfile.ZipFile("file.zip", 'r')
zip_ref.extractall()
zip_ref.close()
```
  After unzipping the file, the **MUTE** dataset will be shown in the current directory. In the **MUTE** folder, you can see   three Excel files and one meme folder.


 ## 🐧Related Papers
- **Deciphering Hate: Identifying Hateful Memes and Their Targets** (arxiv) [[Paper](https://arxiv.org/abs/2403.10829)] [[Code]()]
- **A Multimodal Framework to Detect Target Aware Aggression in Memes** (*EACL'24*) [[Paper](https://aclanthology.org/2024.eacl-long.153/)] [[Code]()]
- **Align before Attend: Aligning Visual and Textual Features for Multimodal Hateful Content Detection** (*EACL-SRW'24*) [[Paper](https://arxiv.org/abs/2402.09738)] [[Code](https://github.com/eftekhar-hossain/Bengali-Hateful-Memes/tree/main/Align-Before-Attend%40EACL)]
- **MemoSen: A Multimodal Dataset for Sentiment Analysis of Memes** (*LREC'22*) [[Paper](https://aclanthology.org/2022.lrec-1.165/)] [[Code](https://github.com/eftekhar-hossain/MemoSen-LREC2022)]


## Citation

If you find our works useful for your research and applications, please cite using this BibTeX:
```bibtex


@inproceedings{hossain2022mute,
  title={Mute: A multimodal dataset for detecting hateful memes},
  author={Hossain, Eftekhar and Sharif, Omar and Hoque, Mohammed Moshiul},
  booktitle={Proceedings of the 2nd conference of the asia-pacific chapter of the association for computational linguistics and the 12th international joint conference on natural language processing: student research workshop},
  pages={32--39},
  year={2022}
}

@article{hossain2024deciphering,
  title={Deciphering Hate: Identifying Hateful Memes and Their Targets},
  author={Hossain, Eftekhar and Sharif, Omar and Hoque, Mohammed Moshiul and Preum, Sarah M},
  journal={arXiv preprint arXiv:2403.10829},
  year={2024}
}

@article{hossain2024align,
  title={Align before Attend: Aligning Visual and Textual Features for Multimodal Hateful Content Detection},
  author={Hossain, Eftekhar and Sharif, Omar and Hoque, Mohammed Moshiul and Preum, Sarah M},
  journal={arXiv preprint arXiv:2402.09738},
  year={2024}
}

@inproceedings{ahsan2024multimodal,
  title={A Multimodal Framework to Detect Target Aware Aggression in Memes},
  author={Ahsan, Shawly and Hossain, Eftekhar and Sharif, Omar and Das, Avishek and Hoque, Mohammed Moshiul and Dewan, M},
  booktitle={Proceedings of the 18th Conference of the European Chapter of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages={2487--2500},
  year={2024}
}

@inproceedings{hossain2022memosen,
  title={Memosen: A multimodal dataset for sentiment analysis of memes},
  author={Hossain, Eftekhar and Sharif, Omar and Hoque, Mohammed Moshiul},
  booktitle={Proceedings of the Thirteenth Language Resources and Evaluation Conference},
  pages={1542--1554},
  year={2022}
}

```
