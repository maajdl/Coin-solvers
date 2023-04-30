# Finding solvers for Pyomo
Ipopt is the one I use the most from Pyomo.     
The coin solvers that I wish to keep "in a safe" are: Bonmin, Cbc, Couenne and Ipopt.     
Below are some links where the binaries were available in May 2023.
   
**Pyomo documentation**:     
http://www.pyomo.org/     
https://pyomo.readthedocs.io/en/latest/index.html      
- **Using conda it is possible to install both Pyomo and the solvers ipopt and Glpk:**    
conda install -c conda-forge pyomo     
conda install -c conda-forge ipopt glpk 
- **Using pip only Pyomo can be installed:**    
pip install pyomo     
the solvers need to be copied to an ad-hoc folder from where it is accessible to Pyomo         


## Finding solvers for Pyomo   


**Coin-OR binaries on main site**:     
https://www.coin-or.org/download/binary/     
https://www.coin-or.org/download/binary/Ipopt/      
https://www.coin-or.org/download/binary/Bonmin/     
https://www.coin-or.org/download/binary/Cbc/     
https://www.coin-or.org/download/binary/Couenne/     
https://www.coin-or.org/download/binary/CoinAll/     

**Coin-OR binaries on Github**:      
https://github.com/coin-or/Ipopt/releases      
https://github.com/coin-or/Cbc/releases

    
**Ipopt binaries provided for use in Julia**:     
https://github.com/JuliaBinaryWrappers/Ipopt_jll.jl/releases/tag/Ipopt-v3.13.2%2B0       
        
**Coin-OR binaries provided by AMPL on Github**       
https://github.com/ampl/coin/releases        
https://github.com/ampl/coin/releases/download/v20191215/coin-linux32.tar.gz      
https://github.com/ampl/coin/releases/download/v20191215/coin-linux64.tar.gz      
https://github.com/ampl/coin/releases/download/v20191215/coin-osx.tar.gz      
https://github.com/ampl/coin/releases/download/v20191215/coin-win64.zip      
        
**Coin-OR binaries provided by AMPL on the AMPL portal**     
https://portal.ampl.com/user/ampl/download/list?legacy      
https://portal.ampl.com/download/coin.linux-intel32.20230221.tgz      
https://portal.ampl.com/download/coin.linux-intel64.20230221.tgz      
https://portal.ampl.com/download/coin.macos64.20211124.tgz      
https://portal.ampl.com/download/coin.mswin32.20230221.zip      
https://portal.ampl.com/download/coin.mswin64.20230221.zip      
