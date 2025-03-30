# Pokemon
Used machine learning to classify each Pokémon as either a Mega Evolution or a Regular Pokémon, without using the Pokémon name as a feature

Your task is to determine whether a Pokémon is a Mega Evolution or not using the dataset available at the following Kaggle link: Dataset.
Objective
The goal is to use machine learning to classify each Pokémon as either a Mega Evolution or a Regular Pokémon, without using the Pokémon name as a feature. The model should rely only on statistical attributes (e.g., HP, Attack, Defense, etc.) for the classification. Additionally, you should evaluate the model’s performance by plotting metrics such as:
Confusion matrix


ROC curve


Precision-recall curve
The final output should be saved in CSV format with two columns:
Pokemon: The name of the Pokémon (for identification purposes only in the output).


Mega_Evolution: Yes if the Pokémon is a Mega Evolution, No otherwise.


Example Output (CSV format)
Pokemon,Mega_Evolution  
Charizard,No  
Mega Charizard X,Yes  
Blastoise,No  
Mega Blastoise,Yes  
Gengar,No  
Mega Gengar,Yes  
Pikachu,No  
Lucario,No  
Mega Lucario,Yes 

