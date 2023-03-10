1	P(theta|d)

2	Start with theta_0 from posterior P(theta_c|d)

3	Choose theta_c from Proposal distribution q(theta_c, theta_0)

4	p_c = P(theta_c|d)

5	alpha = min{(P_c/P_0) q(theta_0 -> theta_c)/q(theta_c -> theta_0), 1}
		= min {P_c/P_0 , 1}
		
6	U =  Ranf(0, 1)
	accept theta_c if U < alpha
	otherwise  reject it

7	If accepted add it between	
	
	
