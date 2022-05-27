# "Colored" inversion
Seismic exploration is a branch of exploration geophysics based on recording artificially excited elastic waves and extracting useful geological and geophysical information from them. One of the final steps in extracting useful information is deterministic seismic inversion. The "colored" inversion method is the main representative of operator-based seismic inversion algorithms.

# What the program does?
Filters seismic data with a transfer filter. After convolved with the wavefield allows the transition from amplitude values to an acoustic impedance distribution.

# How the program works
1. Parsing seismic data from a SEGy file
2. Parsing log data from las-file
3. Logging Spectrum Calculation
4. Seismic Data Spectrum Calculation
5. Operator evaluation
6. Convolution of operator and seismic data

# Befor
![изображение](https://user-images.githubusercontent.com/62353818/170700642-fb561e4f-2535-4b5f-8c75-5baa6ee842f8.png)
# After
![изображение](https://user-images.githubusercontent.com/62353818/170700784-5d4795f9-6637-42d4-9caf-1eeedd1bc66f.png)

# To Run
The program is written in Python on a Juputer Notebook.
To run you need to install Juputer Notebook and download the download SEGy to the data folder (it's too big for git) - https://drive.google.com/file/d/1taNxIQGS1_U5al_LUoDQwIqIwz_1xIp3/view?usp=sharing
