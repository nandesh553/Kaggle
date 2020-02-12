## Random Forest (Decision Tree Approach)

### With Label Encoded Data
* **MADE A MISTAKE HERE:** ACCIDENTALLY TRAINED MODEL WITH 'ID' AS FEATURE)
* **Surprisingly** it gave **0.77990** accuracy
    
### With Label Encoded Data and removed 'ID' from features
* **0.7081** accuracy
* also Built functional pipeline
        
### Grid Search Cross Validation with LabelEncoded Values
* **0.74162** accuracy
    
### One hot encoded categorical variables with Random Forest - GridSearch Cross Validation.
* **0.75598** accuracy
* One hot encoded variables should make no sense in decision trees. Splitting startegy depends on info gain
* But due to minor change in input data (X) outputs vary highly in decision trees.
