I'll be adding the content according to the sessions of each day. I've done the lab for day 1 already on the 24th of January, give me some time to frame the description and add images.

This is the content of the Day-1 SKY130_D1_SK3)Getting familiar with openlane.

[NOTE: run Docker and this synthesis reports in two different terminals.] 

starting and working on Docker.

The directory to change it to the latest date directory, it will further give a list of directories included in it like reports, results, tmp, logs and files like config.tcl .
![Image](https://github.com/user-attachments/assets/9129308a-620f-4cbf-90ad-8da17c2844e0)

Now, change the directory to results and analyse what all results are present in this section, once the changes are made and again the whole process is run then the changes in this report and results and synthesis files can be observed in which the results specifically contains the results of floorplanning, routing, placement, synthesis, layout, cts and lvs and cvc, as shown in the figure. also as shown in the below figure the synthesis directory further includes the merged_unpadded.lef file which is a collection of the information of libs.lef and libs.tech file and its other file is of verilog file named picorv32a.synthesis.v and it has synthesizable rtl code. 
![image](https://github.com/user-attachments/assets/99769103-7af6-44ef-8f05-ea7eddcec7b1)

now once the docker is run as well as synthesis is run then the changes can be seen in the reports file, and that too in synthesis if we go further it will giev a detailed report of statistical report, mi-max timing, slew, timing and all those, as shown in below figure.

![image](https://github.com/user-attachments/assets/1caddd3a-55ef-48c4-aff2-17db8c6955bc)
![image](https://github.com/user-attachments/assets/056bcee8-18a8-48f2-a743-c867d815ed14)
![image](https://github.com/user-attachments/assets/41926281-8941-48f1-aabf-28f5db8db9ff)
![image](https://github.com/user-attachments/assets/57ae1a93-4e0f-48cb-83ff-233cedc2d2da)
![image](https://github.com/user-attachments/assets/ddadd7f6-0e51-4611-a1e7-9a7e9351a904)
![image](https://github.com/user-attachments/assets/cd6e8cae-153e-4dee-8dc0-bfe87d3ea406)
![image](https://github.com/user-attachments/assets/d92b8857-5c51-434d-99d5-79cb825310c2)
![image](https://github.com/user-attachments/assets/7f300e8e-5a9a-4602-bd80-726aa4e245de)
![image](https://github.com/user-attachments/assets/bb7a5911-7bec-4757-9c2f-90c1f777720b)
![image](https://github.com/user-attachments/assets/00cc5bc9-602f-4066-b53d-c484f69e8ec4)
![image](https://github.com/user-attachments/assets/3d2b6332-d671-4f10-af9e-89532cb097a8)
![image](https://github.com/user-attachments/assets/b34a477d-7ae9-46ec-a75d-f71822d1ca50)
![image](https://github.com/user-attachments/assets/fe3559a4-7465-4345-8d6a-5e125d53ea3d)
![image](https://github.com/user-attachments/assets/56d39b71-98d0-4eb7-bdcc-06838fe84879)
![image](https://github.com/user-attachments/assets/378fea88-c485-4fe0-9af9-fdbdef272a30)
![image](https://github.com/user-attachments/assets/1caf06db-29ed-442b-9fca-aee2cc4a6aa1)
![image](https://github.com/user-attachments/assets/7b37d6ea-c3c7-4365-81cf-91108b4282ba)
![image](https://github.com/user-attachments/assets/d950c6cd-0317-494f-be5b-8d06d12a3309)
![image](https://github.com/user-attachments/assets/79762558-ba97-413d-a156-7751fa8811ca)
![image](https://github.com/user-attachments/assets/b828f20c-41e0-4a38-9de2-fafc0ecf7e4f)
![image](https://github.com/user-attachments/assets/a0a83d6b-274f-4773-a5a9-8eb13670b232)
![image](https://github.com/user-attachments/assets/2b714da7-90e3-4eef-a6a1-bfc2b0e65311)
![image](https://github.com/user-attachments/assets/59a438de-1dce-4486-981e-9006a6117cbd)
![image](https://github.com/user-attachments/assets/52e9c724-f2fc-474b-855b-2c15593aaf88)
![image](https://github.com/user-attachments/assets/528ff3de-57e3-4160-8137-03d404298948)
![image](https://github.com/user-attachments/assets/7311a23d-eb59-4b16-ac9b-2b8cdf5c83cf)
![image](https://github.com/user-attachments/assets/cdaae9b3-c9a4-494c-b469-6be30ea516c1)
![image](https://github.com/user-attachments/assets/4189e070-c523-467b-8c1c-e092a810ab66)
![image](https://github.com/user-attachments/assets/228a59be-735d-4360-96f6-748ad689a8a9)
![image](https://github.com/user-attachments/assets/a7928f5d-f852-4d07-97cb-90f88b3632e4)
![image](https://github.com/user-attachments/assets/9268ff35-2319-4a84-8612-9b945475e642)
![image](https://github.com/user-attachments/assets/0e37dcd6-a3e6-4ed2-b617-956cf325aab7)
![image](https://github.com/user-attachments/assets/965adeee-5cbd-4db0-a5ac-e2d7f0b2b237)
![image](https://github.com/user-attachments/assets/fa2262c9-9650-4ef9-b7de-7ead107cd013)
![image](https://github.com/user-attachments/assets/148c20da-dd58-4e22-93ec-471464f414db)
![image](https://github.com/user-attachments/assets/980333c8-8056-4c8d-ab54-0398eae7c3b1)
![image](https://github.com/user-attachments/assets/03710ac2-bc90-4426-817b-8e9b95e3b95f)
![image](https://github.com/user-attachments/assets/1a95650c-cade-4066-bd61-1a7f0a027ac4)
[image](https://github.com/user-attachments/assets/8eb52dd2-e6b2-4cb8-81e2-176ad5e526e5)
![image](https://github.com/user-attachments/assets/cb436052-09f2-4092-9c88-1566239b8205)
![image](https://github.com/user-attachments/assets/e21385e2-f951-4b60-ac29-40b086d72b4d)
![image](https://github.com/user-attachments/assets/d4090665-23bf-43bb-a1b1-5734714557fb)
![image](https://github.com/user-attachments/assets/a20525bd-c22d-44c4-aa9b-dcd592e947eb)
![image](https://github.com/user-attachments/assets/0e9ffe27-eb99-4c0f-9205-62a07e062217)
![image](https://github.com/user-attachments/assets/904f786a-69ff-4b32-a143-196bb0727dc3)
![image](https://github.com/user-attachments/assets/fefbf1b9-b1fc-43ec-87ec-935b30e7cce1)
![image](https://github.com/user-attachments/assets/34d09aaf-1c1e-4604-9db0-4512deebbe5e)
![image](https://github.com/user-attachments/assets/74237050-1a4e-4f1f-a667-3e59c67cf957)
![image](https://github.com/user-attachments/assets/fe230844-41c7-42be-8e9a-d41cea74b5a2)
![image](https://github.com/user-attachments/assets/cb7dbbd4-0f69-4b62-9bf7-340b6e2b14b3)
![image](https://github.com/user-attachments/assets/e8eeb931-ecbd-4b87-931b-9122a798346f)
![image](https://github.com/user-attachments/assets/f391cb4c-228f-441e-a353-bb6752d7946b)
![image](https://github.com/user-attachments/assets/4a723019-5e95-4e9b-b1d8-68f75f547300)
going through this error during the upscaling of the cells.
![image](https://github.com/user-attachments/assets/eb9a1b24-83dd-46f0-aa6f-2c44f09f3106)
will try to resolve it soon and update here.






































