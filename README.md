# Active-BrainNet
'Active-BrainNet : An Efficient Active Learning Paradigm For Brain Tumor Classification' paper suggests an innovative approach to brain tumor classification that leverages a human-in-the-loop active learning strategy.


Accurate brain tumour classification from medical imaging is crucial for early diagnosis and successful treatment strategies. Recent advancements in deep learning methods and computer vision algorithms have shown significant improvement in the field. However, the best-performing supervised learning-based approaches require a huge amount of labelled data, a task that is laborious and challenging, especially in critical domains like medicine. Further, human expertise is also not efficiently utilized in current AI systems, posing a semantic gap in the use of AI systems in the wild. The challenges of processing large-scale unlabeled data and the need for Responsible AI practices which emphasize transparency and human oversight, are not adequately addressed in existing approaches. To this end, we propose a novel Active Learning strategy viz. "Active-BrainNet", which utilizes a human-in-the-loop paradigm and requires minimal annotated data for training the model. The key contributions of the paper are threefold: First, the use of two uncertainty estimation techniques i.e., informativeness and representativeness, to choose suitable samples for annotation by the medical expert (Oracle) within the Active Learning framework. Second, the proposal of a novel 'Dynamic Thresholding' technique to determine the optimal number of sample selections for labeling in the Active Learning cycle. Third, optimization of the active learning cycles through a Self-Breaking mechanism via a weighted averages method. Extensive experiments are carried out on two benchmarking datasets: a custom-made collective dataset of Figshare, SARTAJ & Br35H datasets and T1-weighted CE MRI Dataset. Results show the superior performance of Active-BrainNet model achieving 94.85% accuracy using only 20.74% of labeled data (with an initial 3% labeled data and 25 Active learning cycles) on our custom-made dataset.









