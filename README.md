# plant_resistance_gene_logistic_regressor
plant resistance gene logistic regressor: applying a logistic regressor specific for the training on the plant resistance genes. This applies the logistic regession based on the sequence characteristics of the plant disease resistance genes and the corresponding expression profile. A normalized log transformed expression methods can be used.@fasta_file: file containing the plant disease resistance genes, @expression_file: file containing the expression profile for those genes. it also takes a prediction motif profile which defines the presence and the absence of the resistance genes and makes a probability index. The function returns a accuracy score and writed the model to an output file. You can put a meshgrid to  enable the visualization of the model using the np.array. You can change the save to a pickle file for the model
```
resistancegeneLogisticRegressor(fasta_file, \
                                       expression_file, \
                                             prediction_motif, \
                                             prediction_size, \
                                                      output_file)
```
Gaurav Sablok \
Frontiers: https://loop.frontiersin.org/people/33293/overview \
ORCID: https://orcid.org/0000-0002-4157-9405 \
WOS: https://www.webofscience.com/wos/author/record/C-5940-2014 \
Github:https://github.com/sablokgaurav \
Linkedin: https://www.linkedin.com/in/sablokgaurav/ 
