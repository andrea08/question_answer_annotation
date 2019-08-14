# Toward Dialogue Modeling: A Semantic Annotation Scheme for Questions and Answers

This repository contains the annotation guidelines and the annotated corpus described in the paper "Toward Dialogue Modeling: A Semantic Annotation Scheme for Questions and Answers" and is structured as follows:

- The annotation guidelines in folder guidelines
- Annotated corpus in folder corpus:
-- ELAN format in folder eaf:
```
.
├── amy_andrea.eaf
├── amy_aria.eaf
├── amy.eaf
├── amy_gosse.eaf
├── Dutch
│   ├── CGN
│   │   ├── fn008000.eaf
│   │   ├── fn008001.eaf
│   │   └── fn008003.eaf
│   └── VanKampen
│       └── Sarah
│           └── 040011.eaf
├── mary.eaf
└── Spanish
    ├── 2034h.eaf
    ├── 2034h.pfsx
    ├── 2128h.eaf
    ├── 2128h.pfsx
    ├── 4053h.eaf
    └── 4053h.pfsx
``` 
-- JSON format in folder json:
```
.
├── 2034h_cleaned.json
├── 2128h_cleaned.json
├── 4053h_cleaned.json
├── amy_all.json
├── amy_andrea.json
├── amy_aria.json
├── amy_gosse.json
├── fn008000_cleaned.json
├── fn008000.json
├── fn008001_cleaned.json
├── fn008001.json
├── fn008003_cleaned.json
├── fn008003.json
└── mary.json
```

If you use our work please cite the paper:

"Toward Dialogue Modeling: A Semantic Annotation Scheme for Questions and Answers". María Andrea Cruz Blandón, Gosse Minnema, Aria Nourbakhsh, Maria Bortichev, Maxime Amblard. In Proceedings of the 13th Linguistic Annotation Workshop, pages 230–235,  Florence, Italy. Association for Computational Linguistics.

Bibtex:

```
@inproceedings{cruz-blandon-etal-2019-toward,
    title = "Toward Dialogue Modeling: A Semantic Annotation Scheme for Questions and Answers",
    author = "Cruz Bland{\'o}n, Mar{\'\i}a Andrea  and
      Minnema, Gosse  and
      Nourbakhsh, Aria  and
      Boritchev, Maria  and
      Amblard, Maxime",
    booktitle = "Proceedings of the 13th Linguistic Annotation Workshop",
    month = aug,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W19-4027",
    pages = "230--235",
    abstract = "The present study proposes an annotation scheme for classifying the content and discourse contribution of question-answer pairs. We propose detailed guidelines for using the scheme and apply them to dialogues in English, Spanish, and Dutch. Finally, we report on initial machine learning experiments for automatic annotation.",
}
```



