# CreditRisk-Analysis
 ds
This is based on USA data collected after the 2009 recession. This module helps in detecting whether the customer deserves to hold the credit or not.As it is one of the sensitive issue which played major role in past recession,So this is the module that will work based on the data collected from customer history,and categorizing them in bad and good credit.This will help the bank in deciding whether customer deserves the loan or not.
How to run?
Initially we need to clean the data so run credit risk analysis.-Initally run with #df_inputs_prepr = load_ds_input_train
#df_targets_prepr = load_ds_targets_train on 200th line.this will create two file related to train data.Then replace these two line with df_inputs_prepr = load_ds_input_test
df_targets_prepr = load_ds_targets_test.This will help in creating ds realted to test.
After creating 4 file we will move to pd(probablity of default) model.
Initilally run pdmodel monitoring file.this is similar to credit risk analysis.ipnyb file but here we use the the file creted  earlier in this model.and we will preporcess the required attributes as we did in credit risk analysis.
Following this we will move to pd model to create the score card file.
Then we will run LGD(loss given default) AND EAD(Exposure at default) model.
As I didnt seprated the file because it already consumed large space so I run the final output in the same file i.e LGD AND ED.impynb.
using the algorithm for credit risk analysis which is calculated using Expected Loss=PD*LGD*EAD
