This project implements a branched chain reactor from the Paper "Homogeneous branched-chain explosion: Initiation to completion".  
This small system of ODEs models the variables of temperature, and two chemical species.  
The first chemical species is a precursor which is not exothermic, so you don't expect the temperature to go up as the combustion of this group proceeds.  
The second fuel derived from the precursor is highly exothermic, and this is what will drive the temperature variable up over time.
#################################################
 /$$$$$$$$              /$$$$$$$                 
|__  $$__/             | $$__  $$                
   | $$  /$$$$$$       | $$  \ $$  /$$$$$$       
   | $$ /$$__  $$      | $$  | $$ /$$__  $$      
   | $$| $$  \ $$      | $$  | $$| $$  \ $$      
   | $$| $$  | $$      | $$  | $$| $$  | $$      
   | $$|  $$$$$$/      | $$$$$$$/|  $$$$$$/      
   |__/ \______/       |_______/  \______/      
##################################################
Your goal is to make a simulink simulation of the branched chain explosion.  Feel free to use MATLAB code blocks if you are familiar.
The stiffness 'e' will have consequences on the behavior of the integrator.  
Try a few difference values and see what that means and what the variable implies for the system (Remember the reaction rate Omega, depends on this parameter)
