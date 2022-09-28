The *-train.txt files were created using https://github.com/det-lab/SNOWMASS-paper-collector.  These files contained a lot of reports focused on machine learning and unrelated entries were removed by hand.``

The unique-train.txt file was created with

```
cat cef-train.txt compf-train.txt rf-train.txt af-train.txt cf-train.txt ef-train.txt if-train.txt nf-train.txt  tf-train.txt uf-train.txt | sort -u
```
