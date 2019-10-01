Annotated evidence sentences for 500 questions from the dev set of the RACE-Middle dataset described in the paper *[Evidence Sentence Extraction for Machine Reading Comprehension](https://arxiv.org/abs/1902.08852v2)*. We provide the annotations of two annotators. 


If you find this resource useful, please cite the following paper.
```
@inproceedings{wang2019evidence,
  title={Evidence Sentence Extraction for Machine Reading Comprehension},
  author={Wang, Hai and Yu, Dian and Sun, Kai and Chen, Jianshu and Yu, Dong and McAllester, David and Roth, Dan},
  booktitle={Proceedings of the CoNLL},
  address={Hong Kong, China},
  url={https://arxiv.org/abs/1902.08852v2},
  year={2019}
}
```

The format of these files are as follows.
```
{
 docid: [
  evidence sentences for the 1st question,
  evidence sentences for the 2nd question,
  ...
 ], 
 ...
}
```

Note that for some questions, annotators cannot find appropriate evidence sentences. For these cases, we leave the evidence sentence list empty.
