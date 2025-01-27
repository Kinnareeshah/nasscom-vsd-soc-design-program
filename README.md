I'll be adding the content according to the sessions of each day. I've done the lab for day 1 already on the 24th of January, give me some time to frame the description and add images.

This is the content of the Day-1 SKY130_D1_SK3)Getting familiar with openlane.

the directory to change it to the latest date directory, it will further give a list of directories included in it like reports, results, tmp, logs and files like config.tcl .
![Image](https://github.com/user-attachments/assets/9129308a-620f-4cbf-90ad-8da17c2844e0)

Now, change the directory to results and analyse what all results are present in this section, once the changes are made and again the whole process is run then the changes in this report and results and synthesis files can be observed in which the results specifically contains the results of floorplanning, routing, placement, synthesis, layout, cts and lvs and cvc, as shown in the figure. also as shown in the below figure the synthesis directory further includes the merged_unpadded.lef file which is a collection of the information of libs.lef and libs.tech file and its other file is of verilog file named picorv32a.synthesis.v and it has synthesizable rtl code. 
![image](https://github.com/user-attachments/assets/99769103-7af6-44ef-8f05-ea7eddcec7b1)

now once the docker is run as well as syntesis is run then the chngaes can be seen in reports file, and that too in synthesis if we go further it will giev a detailed report of statistical report, mi-max timing, slew, timing and all those, as shown in below figure.
![image](https://github.com/user-attachments/assets/1caddd3a-55ef-48c4-aff2-17db8c6955bc)





