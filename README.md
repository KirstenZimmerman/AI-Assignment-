# AI-Assignment-
Assignment  for Data Science 311

Project Overview
This notebook recreates an exploratory data analysis of credit crad fraud transcations, focusing on identifying key behavioral and transctional difference between frudulent and non fradululent purchases. The analysis includes loading and cleaning the dataset, summarizing numeric features, and visulizing trends such as how fraud correlates with chip usage, PIN entry, and online orders actitivy. The goal of this assisgnment was to recreate the analysis we went over at the start of the semeter, up to the section "can we predit if a transction is fruad?" without copying any of the code directly. 

AI (Chat-GPT 5) was used as a coding and learning assistant to improve both effiency and understanding. It helped me generate clear visulizations, cleanly structed pandas code, and formatted plots that compare fruad vs non-fraud behaviors. All results and code were verfied manually to ensure correctness and alignment with the original data set. 

Reflection
a. AI provided several practical benefits while creating this notebook. It saved time debugging erros and helped format the plots so that the comparison between fraudulent and non-fradulent transaction were easy to interpret. For example AI explained what each code block was doing, which made the process feel more like an interactive learning session. 

b. Someone who relies entirely on AI to make this notebook could miss key learning objectives. For example, AI might write technically correct code without ensuring that the analysis logically answers the question. Someone who doesn’t understand what .groupby() or .value_counts() actually does might produce graphs that look fine but interpret them incorrectly. Another danger is over-trusting AI’s default choices: it might import unnecessary libraries, apply the wrong aggregation (like a sum instead of a mean), or mislabel variables. 

c. There were several times I had to double-check AI’s work. For instance, AI repeatedly tried to import matplotlib.pyplot before every single plot, even though it was already imported at the top. I also had to correct the color consistency of the graphs, since AI often forgot which colors I had chosen for fraudulent (red) vs. non-fraudulent (green) transactions. These corrections were important because inconsistent visuals can confuse interpretation. I recognized these mistakes by reviewing the plots after each cell and noticing mismatches between expected colors, duplicate imports, or formatting differences. This process reinforced the importance of verifying AI outputs rather than assuming it’s perfect.
