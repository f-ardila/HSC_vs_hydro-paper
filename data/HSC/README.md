Each directory contains three files corresponding to profiles in each of three bins of Mvir.  
(13.00,13.42)  
(13.42,13.83)   
(13.83,14.25)  

Each file is a numpy structured array which can be opened with `np.load()`

# delta_sigma
Each numpy structured array contains three entries:  
`r_mpc` : radial bins in physical units [Mpc]  
`dsigma_lr`: delta sigma signal [M_sun / pc^2]  
`dsigma_err_1`: delta sigma error [M_sun / pc^2]  


# mu
Each numpy structured array contains three entries:  
`r_mpc` : radial bins in physical units [Mpc^0.25]  
`median_mu`: median surface stellar mass density [log(M_sun / kpc^2)]  
`std_mu`: standard deviation in surface stellar mass density [log(M_sun / kpc^2)]  
