# inspec-elasticsearch Inspec Profile


To use it in your Kitchen suite add:

```
verifier:
  inspec_tests:
    - name: inspec-elasticsearch
      git: https://github.com/sbeyn/inspec-elasticsearch.git
```

To use it in your Packer suite add:

```
  "provisioners": [
    {
      "type": "inspec",
      "profile": "https://github.com/sbeyn/inspec-elasticsearch.git"
    }
  ]
```
