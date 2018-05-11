# PerfCal  
              Retrieves Performance Measures
                              confusianMatrix .................2 X 2 matrix
                              measurement..................TruePositiveRate, Presicion, FMeasure,
                                      Specificity, Accuracy
# Explanatiom
               This function calculates detailed accuracy by class from confusion matrix binary classes.
               Please, also see crosstab function in MATLAB library
               confusion matrix can be calculated using built-in crosstab function 
               confusionMatrix=crosstab(label_index_expected, label_index_actual);

# Usage
                X=[22, 2; 23, 1]
                measures=perfCal(X)
 
 
                                  Authored by , Apdullah Yayık 2015
