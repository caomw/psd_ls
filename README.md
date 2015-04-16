#Positive Definte Least Squares Problem 
      
      min_X  a*trace(X'*X) - trace(Y'*X)
      subject to X is positive (semi)-definite matrix
      X,Y are symmetric n-by-n matrices
    
      using Accelerated Projected Gradient(APG) algorithm


      @author: Junhao Hua
      @email:  huajh7@gmail.com
      Latest update: 2015/4/16
