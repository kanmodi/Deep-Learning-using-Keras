# Deep-Learning-using-Keras
This repository explains using Keras and Tensorflow 

Step 1: Create a model 

        model = keras.models.Sequential()
        

Step 2: Add layers 

        model.add(keras.layers.Dense())
        

Step 3: Compile the model

        model.compile(loss=, optimizer=)
        
        
Step 4: Training Phase 

        model.fit(training_data_file, expected_output_file)
        
        
Step 5: Testing Phase

        error_rate = model.evaluate(testing_data, expected_output_file)
        
        
Step 6: Evaluation Phase

        prediction = model.predict(new_data)
