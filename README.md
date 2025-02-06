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
![image](https://github.com/user-attachments/assets/d4090665-23bf-43bb-a1b1-5734714557fb)
![image](https://github.com/user-attachments/assets/e21385e2-f951-4b60-ac29-40b086d72b4d)
Changing the properties of the inverter like its pitch and width and checking all the respective changes.
![image](https://github.com/user-attachments/assets/3745e04f-b485-4f00-af3c-6e770072cef2)
![image](https://github.com/user-attachments/assets/178bc880-90bf-4904-8352-6116949080eb)
![image](https://github.com/user-attachments/assets/f5f1f8f7-5885-40a5-a903-6383c65266e3)
![image](https://github.com/user-attachments/assets/30525c65-f2bf-4f51-bff5-dc0298dd27a3)
![image](https://github.com/user-attachments/assets/7ee816ba-6505-4d31-9a7c-c3069c8ec451)
![image](https://github.com/user-attachments/assets/5ec08dfa-8314-4514-bce7-aa2b0cd6bcec)
checking the lef file that has been generated of this layout
![image](https://github.com/user-attachments/assets/d806ff99-cff8-496a-9718-a39f34dd6b54)
![image](https://github.com/user-attachments/assets/56241c73-03fc-475c-b752-8e6fe76896a5)
![image](https://github.com/user-attachments/assets/ad3cfb86-7f95-40d5-8a79-0ee05833a337)
![image](https://github.com/user-attachments/assets/d36a2409-2f5c-4f34-a425-319e654a2666)
![image](https://github.com/user-attachments/assets/0f99d798-8c65-41c1-ac58-4f2a6187c56c)
![image](https://github.com/user-attachments/assets/1a488b35-ed5d-47c2-87cd-ac0362e780aa)
now in this next image it can be seen that has increased
![image](https://github.com/user-attachments/assets/de3eff83-db79-4b88-b31e-bff65880d712)
![image](https://github.com/user-attachments/assets/e8c72dff-7f2b-4a6c-b930-295539070b71)
check the newly created lef file of updated inverted in vsdcelldesign- sky130_vsdinv.lef and check for your specific inv who's property were changed,
![image](https://github.com/user-attachments/assets/9a5a3044-f0ff-4c81-861c-c2fae07bd04b)
![image](https://github.com/user-attachments/assets/d6e64700-1c1d-4710-bb29-48efbf855180)
![image](https://github.com/user-attachments/assets/6073258f-647f-4104-b527-8f97b08db2d8)
![image](https://github.com/user-attachments/assets/08ce9235-9d54-4b2e-93ab-6b053f00c554)
![image](https://github.com/user-attachments/assets/89af08ca-a453-4fc6-adb4-0bb052d98064)
![image](https://github.com/user-attachments/assets/73e421b3-5ce8-4e66-8dbd-f215f67b113e)
![image](https://github.com/user-attachments/assets/792ce7d6-59ea-441f-9fd6-a2996dcd3051)
config.tcl and base.sdc to create on your own
![image](https://github.com/user-attachments/assets/e8eeb931-ecbd-4b87-931b-9122a798346f)
![image](https://github.com/user-attachments/assets/d4823e92-78f9-49d3-824e-8e014e769ece)
![image](https://github.com/user-attachments/assets/e07f0b58-98da-40ab-82a4-c6065ba2e187)
![image](https://github.com/user-attachments/assets/aaf1da1e-ee96-4d09-952d-e39323e600f5)
![image](https://github.com/user-attachments/assets/03598df5-2547-4e3d-996b-c5ee8e4dee57)
![image](https://github.com/user-attachments/assets/3a24cd0c-10a7-4304-a669-2b444f7bfba7)
![image](https://github.com/user-attachments/assets/0d9e8428-a3ee-4448-b33d-56f6717fab8d)
![image](https://github.com/user-attachments/assets/e97bd4db-807a-4715-bf62-9f73aa0a7d15)
![image](https://github.com/user-attachments/assets/d3411054-d822-4113-8148-ef52a63b8690)
![image](https://github.com/user-attachments/assets/d6933d69-6fe3-4a6a-9e21-1ab6b851c37d)
![image](https://github.com/user-attachments/assets/f56a13e9-c041-4d16-9e11-41ed8ad155e9)
![image](https://github.com/user-attachments/assets/9faf1948-c2ca-47b7-9b72-c579e935e005)
![image](https://github.com/user-attachments/assets/69ea9b08-8604-46d7-9822-01a68bc91c6b)
![image](https://github.com/user-attachments/assets/5c1685b2-0732-487f-9fed-829a9249dc8f)
![image](https://github.com/user-attachments/assets/b68790fb-41a2-4ae8-b94b-5995fc6f18d2)
![image](https://github.com/user-attachments/assets/4ecdfa7a-3ab8-4ae1-adf3-7309736ebdfc)
![image](https://github.com/user-attachments/assets/9de1c235-6abe-4949-b152-48d1e0617740)
![image](https://github.com/user-attachments/assets/41108b89-b635-4516-8551-421c5dd9ad92)
![image](https://github.com/user-attachments/assets/cb4fedb5-24a4-4c85-8f70-dc25e672c565)
![image](https://github.com/user-attachments/assets/250fc2e8-bb5b-4b23-a6b1-20ac002db50a)
![image](https://github.com/user-attachments/assets/374face5-5729-4ecc-8f8f-ae01337b096a)
![image](https://github.com/user-attachments/assets/f5d2ed6a-1680-49e1-a400-ceb4fa459bc1)
![image](https://github.com/user-attachments/assets/bcc96b4e-a27c-4e9b-a1e9-3b33c3d736e1)
![image](https://github.com/user-attachments/assets/249d7247-d4d1-4a4c-8bea-4bb9290266b8)
![image](https://github.com/user-attachments/assets/e76b3d0a-dcb2-4dcb-8fbb-d563562116a3)
![image](https://github.com/user-attachments/assets/7b2c9eb0-e8f5-400b-9140-b0bc9659ce18)
![image](https://github.com/user-attachments/assets/1e08aa00-2e77-47ae-ab2f-3c3106819a05)
![image](https://github.com/user-attachments/assets/f96d1d87-4f07-46a6-ad1a-4e5ca1bf9907)














































