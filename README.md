# ci-test

![Alt text](https://g.gravizo.com/svg?
  digraph G {
    app -> shuffle [label="+rand"];
    test -> shuffle [label="+rand_mock"]
    {rank=same; app; shuffle;}
  }
)
