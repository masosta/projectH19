# projectH19
Two models was implemented for this project, the LSTM and CNN model. The sound files was .wav files, and was listed in .csv file, train.csv with the ID of the sound in the clip. In this case, the ID was either Jack snipe, Chaffinch or wind. In total there was 300 wav-files. 

The trained models was saved as hdf5. load_raw.ipynb is the code used to make 4 seconds sound clips out of a raw audio data file. This was saved as chunk.npy. The loaded LSTM model was used on the raw data by using the predict function. It can be seen in LSTM_model.ipynb in the three last "windows".
