## Following graphs show that:
  * SVCCA and CKA pass the sanity check of the permutation baseline (```en vs en_rand```)
  * SVCCA and CKA exhibit the interlingual pattern 
  * PWCCA and Cosine do not pass the sanity check (```en vs en_rand``` gets just as high a similarity as ```en vs other languages```)

## "Valid" metrics
Here "valid" is used in the context of the metrics passing the sanity check of telling apart random English sentence pairs vs English-other language sentence pairs

### SVCCA
![desc](abstraction_pattern_tuned_xnli_langs_svcca-1.png)
 
### CKA
![desc](abstraction_pattern_tuned_xnli_langs_cka-1.png)

## "Invalid" metrics
Here "invalid" is used in the context of the metrics passing the sanity check of telling apart random English sentence pairs vs English-other language sentence pairs

### PWCCA
![desc](abstraction_pattern_tuned_xnli_langs_pwcca-1.png)
 
### Cosine

![desc](abstraction_pattern_tuned_xnli_langs_cosine-1.png)
 
