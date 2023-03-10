# Automatic Pavement Crack Detection for Japan, Czech Republic and India

Step 1: Download the complete repository 

Step 2: Install all the dependencies from requirements.txt
</br>
$ pip install -r requirements.txt

Step 3: Download 3 different models one each for every country [HERE](https://drive.google.com/drive/folders/1__WPNp2PFkZf0pbGwnCValb58Mc4DKYD)

Step 4: Create a new folder within the parent directory and place each of those models in it for testing.

# Testing

The train, test1 and test2 datasets can be downloaded from [HERE](https://github.com/sekilab/RoadDamageDetector).

Since, you already downloaded the models in Step 3. Proceed to Step 5-6 for Testing those models on test1 and test2 datasets.

# test1

Step 5: Run the following python files separately by passing individual models (downloaded from Step 3) and by inserting the correct path of the models within these files:

trial.py: jpvl54.pt
</br>

trial_Czech.py:  jc66.pt
</br>

trial_india.py: last_india_new.pt
</br>

After running these files, an output .txt file would be generated with the name: tttt3_new.txt. It contains the results for test1. 
</br>

Note: Pass the appropriate model weights path in line 31 and the appropriate test datasets filenames/path in line 160.

# test2

Step 6: Now, you will need to pass different models into the following files to test on 'test2' dataset. Here are the following files and you will need to change the models as per the information detailed below:

trial2.py: jc66.pt
</br>

trial_Czech2.py:  jpvl54.pt
</br>

trial_india2.py: last_india_new.pt
</br>

After running these files, an output .txt file would be generated with the name: ttt3_test2.txt. It contains the results for test2.
</br>

Note: Pass the appropriate model weights path in line 31 and the appropriate test datasets filenames/path in line 160.

# Citation

The methods and the applicability of this research is further explained in our [PAPER](https://arxiv.org/abs/2010.10681) 
</br>

If you find this project useful for your research, please use the following BibTeX entry to cite our work:
</br>

@article{mandal2020deep,
  title={Deep Learning Frameworks for Pavement Distress Classification: A Comparative Analysis},
  author={Mandal, Vishal and Mussah, Abdul Rashid and Adu-Gyamfi, Yaw},
  journal={arXiv preprint arXiv:2010.10681},
  year={2020}
}
 
# Contact

For general inquiries, contact either Vishal Mandal (vmghv@mail.missouri.edu) or, Yaw Adu-Gyamfi (adugyamfiy@missouri.edu)


