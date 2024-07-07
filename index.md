pr=4
for c in 1 2 3; do echo "change by bkleinen $pr.$c" >> index.md ; git add . ; git commit -m "change by bkleinen $pr.$c" ; done

pr=5
for c in 1 2 3; do echo "change by drblinken $pr.$c" >> index.md ; git add . ; git commit -m "change by drblinken $pr.$c" ; done


change 1.1
change 1.2
change 1.3

change 2.1
change 2.2
change 2.3

change by bkleinen 3.1
change by bkleinen 3.2
change by bkleinen 3.3
change by bkleinen 4.1
change by bkleinen 4.2
change by bkleinen 4.3

change by drblinken 5.1
change by drblinken 5.2
change by drblinken 5.3
