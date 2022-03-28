# VSD_FPGA_Workshop
Vivado / Open FPGA
<br />Day 1
<br />FPGA Introduction
<br />FPGA Design Flow
<br />![Flow](https://user-images.githubusercontent.com/66528639/160340462-c8fb2332-94ba-4d32-a058-ab0c17c4a76a.jpg)
<br />Design of a 4-bit counter through Vivado on Basys3 FPGA
<br />![Basys3 board](https://user-images.githubusercontent.com/66528639/160339995-d4d26a73-4d6c-455c-b6c7-0a32253f30b8.jpg)
<br />Basys 3 Board for Implementation of Design
<br />Use of Virtual Input/Output (VIO)
<br />Flow of VIO
<br />![VIO](https://user-images.githubusercontent.com/66528639/160340698-ad977e99-27ad-488d-a6f2-9c5cc0c70a63.jpg)
<br />![Day1_Simulations](https://user-images.githubusercontent.com/66528639/160282778-d771cc05-7530-4151-8c40-32c98df31747.jpg)
<br />Simulation results of 4 bit counter on vivado Basys FPGA
<br />![Day1_Timing analysis](https://user-images.githubusercontent.com/66528639/160282830-a1e8969f-2f33-4026-93f8-87be6c7b3495.jpg)
<br /><br />Timing analysis of 4 bit counter for 10MHz clock
<br />![Day1_all_constraints](https://user-images.githubusercontent.com/66528639/160282860-c9b3e2ee-d6d5-4102-89a4-5562c088601c.jpg)
<br />Post Implementation results of 4 bit counter with constraints
<br />![Day_1_SDC](https://user-images.githubusercontent.com/66528639/160282875-4e80d501-8cf8-463b-ad27-0cbd7f230629.jpg)
<br />SDC File for the timing analysis
<br />![Day1_Utilization report](https://user-images.githubusercontent.com/66528639/160282891-f16e457c-5e47-42ae-bdf5-ad9ab5997732.jpg)
<br />Utilization report of 4 bit counter wuth respect to area and power
<br />Vivado / Open FPGA
<br />Day 2
<br />OpenFPGA Introduction
<br />VTR Flow Process
<br />![FPGA_Fabric](https://user-images.githubusercontent.com/66528639/160341232-86438df9-f5b8-4628-af09-462c1fdb3497.jpg)
<br />Demos
<br />VPR flow: tseng on Earch
<br />VTR flow: 4 bit counter on Earch
<br />Timing, area, power and post implementation simulation
<br />Basys3 vs VTR results
<br />![Day2_OpenFPGA_Flow](https://user-images.githubusercontent.com/66528639/160283257-831c5f71-ffef-414d-b525-ecfc80b0abe8.jpg)
OpenFPGA Flow Diagram
<br />
<br />![Day2_VPR_Results](https://user-images.githubusercontent.com/66528639/160283453-99ea1de2-25a1-4140-875c-87c56bb0c5ad.jpg)
<br />VPR Results with Slack
<br />
<br />![VTR_1](https://user-images.githubusercontent.com/66528639/160283546-dad8c3a9-ebe4-49ad-aba9-2a504a3bdfbf.jpg)
<br />Placement of CLBs and other cells
<br />![VTR_1_Net](https://user-images.githubusercontent.com/66528639/160283571-ef663d21-6e49-45c8-a98f-84655f8c31c3.jpg)
<br />Results after NET toggle
<br />![VTR_2_Input_Toggle](https://user-images.githubusercontent.com/66528639/160283607-160d1aad-e238-4f92-85ce-9d503046da60.jpg)
<br />Reults after Input toggle
<br />![VTR_3_Critical_Path](https://user-images.githubusercontent.com/66528639/160283623-cbad093f-a9b3-4ffa-9c9c-6684f7c1d781.jpg)
<br />Results for Critical Path in design
<br />![VTR_4_Toggle_congestion](https://user-images.githubusercontent.com/66528639/160283643-c75c8d91-371c-4236-92f7-ca6c6b2ffba1.jpg)
<br />Results for congestion toggle
<br />![VTR_5_Positive_Slack_SDC](https://user-images.githubusercontent.com/66528639/160283671-3124eb3c-47a8-4050-b190-9649f7c5bf7d.jpg)
<br />Results for positive slack of design @ 10MHz
<br />![Day2_VTR_Place and route](https://user-images.githubusercontent.com/66528639/160283910-fc6a2cc5-97d4-4425-b91f-e9d3fd203228.jpg)
<br /> VTR Place and Route for the design
<br />VTR Flow
<br />![VTR_Flow](https://user-images.githubusercontent.com/66528639/160341662-95acd3d2-b5e0-41b1-8157-7d6687547237.jpg)
<br />![Day2_VTR_analysis](https://user-images.githubusercontent.com/66528639/160284078-da99ddbc-af94-4943-aacb-a2b104ea86db.jpg)
<br />Analysis result of VTR 
<br />![Day2_Post_results](https://user-images.githubusercontent.com/66528639/160284333-aedcef95-6f1e-40eb-ab42-dc9d00e6a61f.jpg)
<br />Results of Post Implementation
![Day2_Simulation](https://user-images.githubusercontent.com/66528639/160284446-415a13b7-24f3-484b-94bb-8bfc4520ba50.jpg)
<br />Results of Simulation
<br />![Day2_results1](https://user-images.githubusercontent.com/66528639/160284623-e99208e8-7ffd-47d9-98e7-e07d229bf126.jpg)
<br />Result analysis of arae and timing
<br />
<br />Day 3
<br />Explain RISC-V RVMyth processor code
<br />Run it till bitstream on Basys3
<br />
<br />![Day3_setup](https://user-images.githubusercontent.com/66528639/160284970-63fc0020-ad9d-488c-9db0-8e253e5d50c1.jpg)
<br />Setting up of vivado environment
<br />![Day3_Simulation](https://user-images.githubusercontent.com/66528639/160285002-d9117489-df41-4e39-b60d-84ca385d49bc.jpg)
<br />Simulation results on vivado
<br />![Day3_Synthesis](https://user-images.githubusercontent.com/66528639/160285038-7874c315-5c2d-4823-a7d1-2d9b3604f0d0.jpg)
<br />Synthesis results on vivado
<br />![Day3_Utilization_report](https://user-images.githubusercontent.com/66528639/160285125-001c37c1-b9c4-4e3d-970f-e89477eaff33.jpg)
<br />Utilization report of design
<br />![Day3_Implementation](https://user-images.githubusercontent.com/66528639/160285186-dabb78ce-45fc-4864-b3bf-eb6ee6183c32.jpg)
<br />Implementation results of design
<br />![Day3_Implementation_results](https://user-images.githubusercontent.com/66528639/160285287-bf417dfc-ea56-4c84-b19e-bc3b75d688d7.jpg)
<br />Analysis of implemented design
<br />
<br />Day 4
<br />
<br />Module 4:
<br />Skywater OpenSource FPGA (SOFA): 4-bit counter on SOFA
<br />Area, timing and post implementation
<br />![Introduction_SOFA](https://user-images.githubusercontent.com/66528639/160285556-58c0aa6c-1446-4983-a10e-ca885e7dfac9.png)
<br />Introdction to SOFA
<br />![Day4_SOFA_Circuit_statistics](https://user-images.githubusercontent.com/66528639/160285653-a5ee962d-7e85-4b2e-85a9-8c8eedf716d9.png)
<br />Circuit Statistics of counter
<br />![Day4_SOFA_Circuit_statistics_PB](https://user-images.githubusercontent.com/66528639/160285699-6430f28f-b351-4c49-ab18-61a4b87a623c.png)
<br />SOFA Circuit Statistics
<br />![Day4_SOFA_Area](https://user-images.githubusercontent.com/66528639/160285748-7b2d5c1e-2640-4e05-844d-0349d62bdbe7.png)
<br />Area analysis of SOFA
<br />![Day4_Timing_report](https://user-images.githubusercontent.com/66528639/160285861-39b69d10-6c7a-4611-9384-4ab12b83565d.jpg)
<br /> Timing Analysis of SOFA
<br />![Day4_Post_Netlist](https://user-images.githubusercontent.com/66528639/160285953-234e93d4-fe08-4714-b313-a78df0c6161e.jpg)
<br />Post Synthesis Netlist
<br />![Day4_Simulation](https://user-images.githubusercontent.com/66528639/160286084-47c6d2f1-15fc-468e-9271-cc372ae52bc4.jpg)
<br />Simulation result of Post Synthesis
<br />
<br />Day 5
<br />Module 5:
<br />Skywater OpenSource FPGA (SOFA): RVMyth on SOFA
<br />Area, timing and post implementation
<br />
<br />
![Day_5_Core_run](https://user-images.githubusercontent.com/66528639/160334657-38487d72-22fd-4781-af74-b8177aa55962.jpg)
<br />Setting Environment of SOFA RVMyth core 
<br />![SDC_analysis](https://user-images.githubusercontent.com/66528639/160335231-950243c0-af7e-452e-b6c2-b360bcc06d18.jpg)
<br />SDC Analysis of SOFA RVMyth core 
<br />![Circuit_Statsistics](https://user-images.githubusercontent.com/66528639/160335622-29955663-1c49-4477-a376-8f310a2f641c.jpg)
<br />Circuit Stastistics of SOFA RVMyth core 
<br />![Timing Constraints](https://user-images.githubusercontent.com/66528639/160335968-72c9d6b3-072a-4129-99ea-6826b6ebb826.jpg)
<br />Timing Constraints of SOFA RVMyth core
<br />![Timing Analysis](https://user-images.githubusercontent.com/66528639/160336473-6b98f581-af40-46d8-9eae-926a8ff58a76.jpg)
<br />Setup and Hold Analysis of SOFA RVMyth core
<br />![Netlist](https://user-images.githubusercontent.com/66528639/160336924-b394afb8-551a-4db1-9964-b1621ea72a91.jpg)
<br />Netlist of SOFA RVMyth core
<br />![Post_Simulation](https://user-images.githubusercontent.com/66528639/160337214-b8ac16bb-da18-4bdb-9f24-98758d66abab.jpg)
<br />Post Simulation of SOFA RVMyth core

