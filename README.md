# Jupyter Notebook on Android using Termux

1. Install Termux  
[Download via Fdroid](https://f-droid.org/packages/com.termux/) (recommended)  
[Download via Playstore](https://play.google.com/store/apps/details?id=com.termux)  


2. To install python and other components  

        > apt install clang python fftw libzmq freetype libpng pkg-config libcrypt
  
3. To install Jupyter Notebook

        > LDFLAGS="-lm -lcompiler_rt" pip install jupyter
       
4. If you need to install any additional libs  

        > LDFLAGS="-lm -lcompiler_rt" pip install numpy matplotlib  
      
5. Start Jupyter Notebook  
       
       > jupyter notebook

