# Japanese-to-English Discourse Translation Test Set
This repository includes the dataset described in "[A Test Set for
Discourse Translation from Japanese to English](https://www.aclweb.org/anthology/2020.lrec-1.457)" published at LREC
2020.

## Data Format
We used JSON. Here is an example.

```
[
  {
    "1": {
      "type": "coreference",
      "examples": [
        {
          "src": [
            "あの彼女、今度うちの学校に来るらしいよ。",
            "けど、いつ来るか、わからない。"
          ],
          "trg": {
            "correct": [
              "That girl seems to come to our school soon.",
              "But I don't know when she comes."
            ],
            "incorrect": [
              "That girl seems to come to our school soon.",
              "But I don't know when you come."
            ]
          }
        }
      ]
    },
    ...
```

## Reference

```
@inproceedings{nagata-morishita-2020-test,
    title = "A Test Set for Discourse Translation from {J}apanese to {E}nglish",
    author = "Nagata, Masaaki and Morishita, Makoto",
    booktitle = "Proceedings of the 12th Language Resources and Evaluation Conference",
    month = may,
    year = "2020",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://www.aclweb.org/anthology/2020.lrec-1.457",
    pages = "3704--3709",
    language = "English",
    ISBN = "979-10-95546-34-4",
}
```

## LICENSE

This data is released under the NTT License, see `LICENSE.txt`.
